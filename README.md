# Farewell, Tanu ❤️

A little book of memories, appreciation and good wishes for Tanu's next chapter.

## Website

This repository contains a responsive interactive farewell microsite with 11 personal messages collected from the team.

- Open any letter to read the full message.
- Search notes by teammate name.
- Navigate between notes or choose a random note.
- Finish with an animated send-off.

## Run locally

Open `index.html` in a browser, or run a local server from this folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## GitHub Pages

The deployment workflow in `.github/workflows/deploy-pages.yml` publishes this site from the repository root. In GitHub, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source. The workflow then deploys automatically after a push to `main`.

## Privacy

This repository is public. Contributor names and messages in `data/messages.json` are publicly accessible. Do not change the repository to public-facing if the team has not agreed to share these messages.
