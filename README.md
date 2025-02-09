# Flatpak package for [shijima-qt](https://getshijima.app/) by pixelomer
To build and install:

`$ flatpak-builder --user --install-deps-from=flathub --install --force-clean builddir app.getshijima.shijima-qt`

## Issues
- It currently needs full access to the session dbus, or else the error "No windows observer backend available" will show. This is a huge security risk of course.
- The app needs access to `/tmp/shijima_get_active_window.js`, which is currently hardcoded. Unless this is addressed upstream, it currently has full access to /tmp, which is of course another huge security risk.
- Since this app is proprietary, no files from the release binaries are contained in this repo. I will also not provide flatpak bundles. You have to build it yourself.
