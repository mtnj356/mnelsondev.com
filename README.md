# mnelsondev.com

Static site for mnelsondev, served by GitHub Pages at https://mnelsondev.com.

Plain HTML and one shared stylesheet (`assets/site.css`), no build step. Push to `main` to publish.

## Layout

- `/` home page
- `/<app>/` app page
- `/<app>/privacy/` app privacy policy

**Don't move or rename the privacy policy pages.** Their URLs are built into the apps and entered in
Google Play Console, so changing one means shipping an app update.

## Preview locally

```
python -m http.server 8000
```

Then open http://localhost:8000.
