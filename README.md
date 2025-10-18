# Rock Paper Scissors Game

A simple client-side Rock-Paper-Scissors game built with HTML, CSS, and JavaScript. This project contains two versions of the game (`rock-paper-scissors` and `2-rock-paper-scissors`) demonstrating slight variations in layout and styling.

## Files

- `rock-paper-scissors.html` — Primary HTML for the first version.
- `2-rock-paper-scissors.html` — HTML for the second version.
- `styles/rock-paper-scissors.css` — Styles for the first version.
- `styles/2-rock-paper-scissors.css` — Styles for the second version.
- `scripts/rock-paper-scissors.js` — JavaScript for the first version.
- `scripts/2-rock-paper-scissors.js` — JavaScript for the second version.
- `images/` — Images used by the game (icons, backgrounds).

## How to run

Open either `rock-paper-scissors.html` or `2-rock-paper-scissors.html` in a web browser. No build tools or servers are required.

Steps:

1. Clone or download the repository.
2. Open `rock-paper-scissors.html` (or `2-rock-paper-scissors.html`) in your browser.

On Windows you can right-click the file and choose "Open with" → your browser, or use PowerShell:

```powershell
Start-Process -FilePath "rock-paper-scissors.html"
```

## Features

- Player vs computer gameplay.
- Score tracking and simple UI feedback.
- Two variations included for experimentation with layout and styles.

## Contributing

Contributions are welcome. Create an issue or a pull request explaining your change.

## License

This project is provided under the MIT License. See `LICENSE` if included or add one to your repo.

## Notes

- This is a static front-end project. If you want to serve it via a simple local HTTP server (useful for testing fetches or service workers), you can run:

```powershell
# Using Python 3.x
python -m http.server 8000;
Start-Process -FilePath "http://localhost:8000/rock-paper-scissors.html"
```

Or with Node.js:

```powershell
npx http-server -p 8000;
Start-Process -FilePath "http://localhost:8000/rock-paper-scissors.html"
```
