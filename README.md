# Simply run Sublime Text on Alpine/musl!

## Steps

1. `flatpak-builder --user --install --force-clean build-dir com.sublimehq.SublimeText.yaml`
2. `flatpak-builder --user --install --force-clean build-dir com.sublimehq.SublimeText.yaml`
3. `flatpak run com.sublimehq.SublimeText`
4. (*Optional*) `ln -s ~/.local/share/flatpak/exports/bin/com.sublimehq.SublimeText /usr/bin/sublimetext`
