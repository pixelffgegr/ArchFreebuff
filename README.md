# archfreebuff

freex appimage for arch (x86_64), fixed up and ready to run 🐧

## grab it

the appimage isn't committed here (161mb, github blocks files over 100mb) so grab
it from the releases page instead:

-> `ArchFreebuff.AppImage`

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
751aec0468ef7fec56ea5b11421875fa25a2dce1913a1c16a1c984d141323260
```

run `sha256sum ArchFreebuff.AppImage` and it should print that ✨

168,715,274 bytes, x86_64 linux, built for arch but runs fine on most modern distros.
