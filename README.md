# Amritesh & Shalini — Wedding Invitation

A static invitation for GitHub Pages. The site uses `index.html`, `couple-portrait.jpeg`, `ganpati.png`, and `judi-jodi-15s.mp3` at the repository root, so it works on a GitHub project URL.

## Music

The site plays the first 15 seconds of “Judi Jodi” from Ramayana, supplied by the site owner, on a continuous loop for the whole visit. Browsers block sound before any interaction, so the song starts as soon as the guest taps the seal (or anything else) on the opening screen. A floating button in the corner lets guests pause or resume it. Confirm that you have permission to publish the recording before deploying the site. To change the song, replace the audio source and its visible credit in `index.html` with a recording you have permission to use.

## Publishing

1. Create a GitHub repository and push these files to its `main` branch.
2. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source.
3. The included workflow publishes on every push to `main`. The resulting URL appears in the workflow's deployment result.
