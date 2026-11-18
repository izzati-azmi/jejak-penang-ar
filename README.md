# Jejak Penang AR (CBDE3103 Mini Project, Question 2)

Web-based AR prototype using **MindAR** (image tracking) and **A-Frame** (3D).
Users scan one of four marker cards and a 3D heritage model appears with Story, Old photo, Rotate, Quiz and Photo buttons.

## Files
- `index.html` : the whole app (UI, 3D models, quiz, photo, BM/EN)
- `assets/markers/marker1-4.png` : the four marker cards (print these or show them on a second screen)
- `assets/oldphotos/stop1-4.jpg` : PLACEHOLDER pictures. Replace with real public-domain / licensed photos (same file names).
- `targets.mind` : **you must make this file (Step 1 below). It is not included.**

## Step 1: make targets.mind (about 2 minutes)
1. Open the MindAR image target compiler: https://hiukim.github.io/mind-ar-js-doc/tools/compile/
2. Upload `marker1.png`, `marker2.png`, `marker3.png`, `marker4.png` **in this order** (order = stop number).
3. Press **Start**, wait, then **Download** the file. Rename it exactly `targets.mind`.
4. Put `targets.mind` in the same folder as `index.html`.

## Step 2: test on your laptop
- The camera only works on **https** or **localhost**.
- In VS Code install **Live Server**, right-click `index.html` > Open with Live Server.
- Allow the webcam, then hold your phone (showing a marker image) in front of the webcam.

## Step 3: put it online (GitHub Pages, free)
1. Make a GitHub account and a new public repository, for example `jejak-penang-ar`.
2. Upload ALL files and folders (index.html, targets.mind, assets).
3. Settings > Pages > Source: `main` branch, `/ (root)` > Save.
4. After a minute your link is `https://YOURNAME.github.io/jejak-penang-ar/`.

## Step 4: make the QR code
Paste the link into any free QR code generator, download the PNG, and test it with your phone camera.
Put this QR code and the link in your document (Section 12) and on Behance.

## Before you submit (edit in index.html)
- Replace `[YOUR NAME]` and `[YOUR MATRIC NO]` (search for them).
- Check the story facts against official sources and change the text if needed.
- Replace the placeholder old photos and credit the source on Behance.

## Troubleshooting
- Black screen / no camera: you are not on https, or camera permission was blocked.
- Model never appears: `targets.mind` missing, or markers were uploaded in the wrong order.
- Marker not detected: more light, hold steady, print bigger (at least 10 cm wide), avoid glare.
- Page does not load libraries: you need internet (A-Frame and MindAR load from a CDN).

## Credits
MindAR (MIT licence) and A-Frame (MIT licence). All 3D models are made from simple A-Frame shapes.
