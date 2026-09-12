# Neon Rider

3-lane neon motorcycle endless runner built with **Three.js**.

**Play live:** [https://neon-rider.vercel.app](https://neon-rider.vercel.app)

## Controls

| Input | Action |
|--------|--------|
| ← / → or A / D | Change lane |
| Space / ↑ | Nitro (or start game) |
| Enter | Start / restart |
| Mobile | Swipe left/right or use on-screen buttons |

## How to play

1. Click **Anza Ride**
2. Stay on the road and switch between 3 lanes
3. Avoid cars
4. Collect gold coins for bonus points
5. Speed increases over time — survive as long as you can

High score is saved in the browser (`localStorage`).

## Run locally

Open `index.html` in a modern browser (Chrome, Firefox, Edge, Safari).  
No build step required — Three.js is loaded from CDN via import map.

```bash
# optional local server
npx serve .
# or
python3 -m http.server 8080
```

## Stack

- Vanilla HTML / CSS / JS
- [Three.js](https://threejs.org/) r170
- Deployed on Vercel

## License

MIT
