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
| `my-pfp.webp` | Main profile picture in the header |
| `northcore.png` | NorthCore |
| `northoperations.png` | NorthOperations |
| `northshield.webp` | North Shield |
| `site-47-modbot.png` | Database Administrator |
| `47-staff-management-bot.png` | Staff Manager |
| `site47-guardian.webp` | Database Guardian |
| `arc-32-bot-pfp.png` | ARC.OS |
| `bsch-bot-pfp.png` | BSCH, left avatar |
| `vortigern_support.png` | BSCH card, right avatar (Vortigen Support) |
| `beanz-app-pfp.png` | Beanz.APP |

Square images look best. They are resized to 256x256 on the way in, so anything larger is fine.

## Preview locally

```
py -m http.server 8000 --directory output
```

Then open http://localhost:8000
