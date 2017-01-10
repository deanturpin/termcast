# termcast
Based on an article by [hisdeedsaredust](https://github.com/hisdeedsaredust).

**termcast** captures terminal keystrokes to a file and replays them while
rendering the display to an animated GIF.

- Open terminal
- Make full screen (F11)
- Hide menu
- Zoom in a few times (ctrl-+)

```bash
# Capture keystrokes
./termcast-capture

# TYPE SOME STUFF
# Followed by ^D

# Render animated GIF
./termcast-render
```

- View in a browser ```firefox keys.gif```

![](https://raw.githubusercontent.com/deanturpin/feedback/master/examples/echo/keys.gif)

## Installation
```bash
sudo cp termcast* /usr/bin/
```

## Dry run without rendering to GIF
```bash
./termcast-play
```
