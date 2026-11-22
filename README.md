# T-Rex Runner

An endless runner inspired by the offline dinosaur game: jump over cacti and try to beat your high score.

## How to play
- Press **Space** to jump.
- The game speeds up as your score grows.
- Click **restart** after a crash. Your high score is saved in the browser.

## Run it locally
Browsers block games that load images and scripts straight from disk, so serve the folder with any small web server:

```bash
git clone https://github.com/Aakash12321/Trex-game-.git
cd Trex-game-
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser. (The VS Code **Live Server** extension works too.)

## Built with
- p5.js
- p5.play
