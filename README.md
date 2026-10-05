# River Cleaning: a game about keeping rivers clean

A small educational game made in Python with [pygame](https://www.pygame.org/), inspired by the
Yarkon River, one of the most polluted rivers in Israel.

Rubbish floats up the river: bottles and plastic bags. **Click a piece of rubbish and it turns into
a fish** that swims away, earning you 10 points. Clean up enough of the river (500 points) to win.

The idea is to teach, through play, that every piece of rubbish removed gives the river back to
the life that belongs in it.

## Running it

```bash
python -m venv venv
venv\Scripts\activate          # Windows
pip install -r requirements.txt
jupyter notebook river_clean.ipynb
```

Run all cells. Press any key on the intro screen to start, click rubbish to clean it, and press
`Esc` to quit.

### Images

The game art is not included in this repository. Place these images (transparent PNGs) next to the
notebook:

| File         | Used for                      |
| ------------ | ----------------------------- |
| `river.png`  | River background              |
| `bottle.png` | Floating rubbish              |
| `bag.png`    | Floating rubbish              |
| `fish.png`   | What a cleaned item turns into |

## Credits

Based on a pygame tutorial: https://www.youtube.com/watch?v=9SpwelHPUo8

## Licence

[MIT](LICENSE). You're free to use, change and share this project, as long as you credit
**Elisheva Shiri Decktor**.
