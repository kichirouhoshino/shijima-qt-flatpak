# Flatpak package for [shijima-qt](https://getshijima.app/) by pixelomer
To build and install:

`$ flatpak-builder --user --install-deps-from=flathub --install --force-clean builddir com.pixelomer.ShijimaQT`

Note that this currently does not build as I'm currently experimenting with getting proper sandboxing working. Currently in touch with the dev. You can follow the progress [here](https://github.com/pixelomer/Shijima-Qt-releases/issues/13).
