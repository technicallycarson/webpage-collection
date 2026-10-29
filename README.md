# Webpage Collection

A collection of browser games and an interactive 4D geometry visualizer. Each page is an HTML file.

## Collections

- [4D Visualizer](4D-visualizer/README.md) — explore and rotate four-dimensional shapes.
- [Browser Games](browser-games/README.md) — play five games, from city building to arcade action.

## Run locally

Open an HTML file in a modern browser. No build or package installation is needed.

You can also serve the collection from this directory:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000/> and choose a page.

Some games load Three.js from the internet. Cadillacs & Dinosaurs requires a connection and WebGL; the other games have built-in offline renderers. Games that save progress use browser storage, so clearing browser data can remove saves.

## License

Original project code is available under the [MIT License](LICENSE). Third-party names and properties belong to their respective owners.
