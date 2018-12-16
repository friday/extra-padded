# Extra-padded (plank theme)

Plank's autohide is triggered too easily by mistake, unlike the dock in Mac OS or Docky, which both have outer padding that prevents this. This transparent theme adds sufficient padding (at least for me), and nothing else.

## Installing

You just have to put it in ~/.local/share/plank/themes or /usr/share/plank/themes

Ex:
```sh
mkdir -p ~/.local/share/plank/themes/extra-padded
curl -L https://api.github.com/repos/friday/extra-padded/tarball | tar xz -C ~/.local/share/plank/themes/extra-padded --strip-components=1
```

To change the theme, hold Ctrl and right click on the plank menu to get to preferences.
