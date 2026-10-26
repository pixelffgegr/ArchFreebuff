# archfreebuff

Freebuff For arch! (x86_64)

current: upstream **0.0.192** (CodebuffAI/codebuff-community `freebuff-desktop-v0.0.192`),
repackaged with the wayland desktop-name fix baked in (`CHROME_DESKTOP=freebuff.desktop`
exported in AppRun - that's the issue that made the dock icon show as a generic cog).

## grab it

the appimage is in the release - grab `ArchFreebuff.AppImage` from the releases page.

## run it

```bash
chmod +x ArchFreebuff.AppImage
./ArchFreebuff.AppImage
```

if fuse is being difficult this usually does the trick:

```bash
./ArchFreebuff.AppImage --appimage-extract-and-run
```

## checksum

```
73feaa5ed6dde2cedf35c598f0162ea795a987fae3bf237c1e545b0c1ad1acc5
```

run `sha256sum ArchFreebuff.AppImage` and it should print that.
