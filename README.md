# Flatpak package for [shijima-qt](https://getshijima.app/) by pixelomer
To build and install:

``` bash
flatpak-builder --user --install-deps-from=flathub --install --force-clean builddir com.pixelomer.ShijimaQT
```

You can install it from my personal flatpak repo (remove the --user argument to install system-wide)
``` bash
flatpak remote-add --user roddy-flatpak https://kichirouhoshino.github.io/roddy-flatpaks/index.flatpakrepo
flatpak install roddy-flatpak com.pixelomer.ShijimaQt
```

Flatpak bundles are also available on the actions tab.

https://github.com/pixelomer/Shijima-Qt/issues/7
