# TrackPoint Courier

A small, dependency-free TrackPoint training game. Built with plain HTML, CSS and JavaScript.

## Play

Open `index.html` in a modern browser. No build step or server is required.

Packages fall from the top of the screen. Catch each one before it hits the ground by scrolling the delivery box underneath it — or grab a package directly and drag it in yourself. Every catch adds to your score and streak; drops reset your streak but never end the run.

## Controls

- **Scroll** (left/right) to move the delivery box — this is the *only* way to move it, by design. It's the core TrackPoint movement the game is built to train.
- **Click and hold a package, then drag it** straight into the box — the other core TrackPoint skill: click-and-drag.
- There's no keyboard or click-to-jump control for the box, and no other way to move it — the two moves above are the whole game.

## Difficulty

There are no rounds or a completion screen. The box starts large, packages fall slowly, and only a couple are ever on screen at once — it's meant to be easy to pick up. From there, difficulty increases gradually as you catch more: packages fall a little faster, spawn a little more often, and the box shrinks a little, stage by stage, rather than in big jumps. Occasional gold packages are worth 3x points. Pause and resume anytime without losing your run.

## Deploy to GitHub Pages

1. Open **Settings → Pages** in the repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and `/ (root)`, then save.
4. Wait for the Pages URL to appear in the Pages settings.

Every game asset is inline; there are no dependencies, API calls, or build tools.

## TrackPoint technique

Keep your hands in typing position. Use your index finger on the red cap, scrolling to steer the box. Use your thumbs for the physical buttons, or click-and-hold with the cap, when dragging a package into the box.
