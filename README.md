# beanz-portfolio

Personal portfolio site for coolbeanz. Static HTML, deployed to Netlify from this repo.

## Layout

- `output/index.html` - the whole site, one file
- `output/assets/` - profile pictures
- `netlify.toml` - Netlify config, publish directory is `output`

## Profile pictures

Drop PNGs into `output/assets/` with these exact names. Any that are missing fall back to a
letter monogram, so the page never breaks.

| File | Shows up as |
|---|---|
| `coolbeanz.png` | Main profile picture in the header |
| `database-administrator.png` | Database Administrator |
| `staff-manager.png` | Staff Manager |
| `database-guardian.png` | Database Guardian |
| `northgate-os.png` | NorthGate OS |
| `north-shield.png` | North Shield |
| `arc-os.png` | ARC.OS |
| `bsch.png` | BSCH, left avatar |
| `vortigen-support.png` | BSCH card, right avatar (what it is now) |
| `beanz-app.png` | Beanz.APP |

Square images look best. 256x256 or larger.

## Preview locally

```
py -m http.server 8000 --directory output
```

Then open http://localhost:8000
