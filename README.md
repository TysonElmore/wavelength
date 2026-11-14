# Wavelength: WiFi Intruder App Prototype

Wavelength is a clickable prototype of a camera-free home security app for renters, built for my MIST 5740 (Project Management) individual project at UGA.

The idea: a small hub next to your WiFi router notices movement from the WiFi signal and learns how each person in the home walks. It alerts you when someone it doesn't recognize is inside while you're away, without putting a camera inside your home.

**This is a concept prototype. Nothing here senses real WiFi; every event is simulated.**

## What you can try
- Intro demo, then setup (who lives here, pets, inviting roommates, optional LiDAR or photo scan)
- Home screen with a live room map (Rooms, 3D and Dots views) and today's log
- Full daily log, animated replay of where someone walked
- Settings: alert sensitivity, how long data is kept, away mode, party mode, off-limits rooms
- Demo buttons (right side on desktop, the orange "Demo" button on phones) that simulate a stranger, an unclear visitor, a party, and more. The app reacts based on your Settings.

The floor plan and 3D view come from a LiDAR scan with photos and colors removed (shapes only).

## Files
- `index.html`: the whole app (HTML, CSS and JavaScript in one file)
- `apt-3d.png`, `apt-dots.png`: images for the 3D and dot views

## Put it on GitHub Pages
1. Create a new public repository on GitHub.
2. Upload these three files (Add file, then Upload files) and commit.
3. Go to Settings, then Pages. Under "Build and deployment," choose "Deploy from a branch," pick `main` and `/ (root)`, and save.
4. After a minute or two, your site is live at `https://<your-username>.github.io/<repo-name>/`.

To rename the app, change `APP_NAME` near the top of the script in `index.html`.
