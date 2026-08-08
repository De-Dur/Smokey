# Smokey

**Smokey** is a touch-controlled browser experiment for creating soft clouds, smoke, dust and spores directly on screen.

The app is designed primarily for mobile use and combines interactive particle effects with a live camera background.

## Features

- Cloud, Smoke, Dust and Spores modes
- Touch and drag interaction
- Adjustable brush size and particle amount
- Softness control
- Lift control
- Wind direction and wind speed
- Seed / Clear / Pause controls
- Live camera background
- Camera ON / OFF control
- Optional hand-tracking interaction
- PNG export
- 10-second video export
- Vertical mobile-first interface

## Camera access

The live camera requires a **secure browser context**.

Camera access will work when Smokey is opened through:

- **HTTPS**, for example GitHub Pages
- **localhost** during local development

Camera access usually will **not work when the HTML file is opened directly on Android as `content://`**.

## Test with GitHub Pages

1. Create a GitHub repository.
2. Upload the Smokey HTML file.
3. Rename the main file to `index.html` if needed.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/root` folder.
7. Save and wait for GitHub Pages to publish the site.
8. Open the generated HTTPS address on your phone.
9. Tap **CAMERA ON** and allow camera permission when the browser asks.

## Hand tracking

When hand tracking is enabled, the app can use the detected index fingertip as an interaction point for the particle effect.

Hand tracking may require an internet connection if its tracking library/model is loaded from an external CDN.

## Mobile use

For the best experience:

- Open Smokey in Chrome or another modern browser.
- Use the published HTTPS GitHub Pages version.
- Allow camera permission when requested.
- Use portrait orientation for the intended interface layout.

## Files

The project can run as a single HTML file, making it easy to host on GitHub Pages without a build system.

## Author

**Denisa Durica**

Interactive digital experiment / generative visual tool.
