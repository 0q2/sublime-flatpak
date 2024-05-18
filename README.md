# Simply run Sublime Text 4 on Alpine/musl!

## Steps

1. `flatpak-builder build-dir com.sublimehq.SublimeText.yaml`
2. `flatpak-builder --user --install --force-clean build-dir com.sublimehq.SublimeText.yaml`
3. `flatpak run com.sublimehq.SublimeText`
4. (*Optional*) `ln -s ~/.local/share/flatpak/exports/bin/com.sublimehq.SublimeText /usr/bin/sublimetext`
