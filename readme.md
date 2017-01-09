# Screencast
Based on an article by [hisdeedsaredust](https://github.com/hisdeedsaredust).

Screencast captures terminal keystrokes to a file and then replays them while rendering the display to an animated GIF.

- Open terminal
- Make full screen (F11)
- Hide menu
- Zoom in a few times (ctrl-+)

```bash
# Capture keystrokes
./capture

# TYPE SOME STUFF
# Followed by ^D

# Render animated GIF
./render
```

- View in a browser ```firefox keys.gif```

![](https://raw.githubusercontent.com/deanturpin/feedback/master/examples/echo/keys.gif)
