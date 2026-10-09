# Arch Freebuff AppImage fixed

AppImage distribution for FreeX, built for x86_64 Arch Linux.

## Download

The AppImage is not committed to this repository (it is ~161 MiB, well over git's
100 MiB file limit). Grab it from the **Releases** page of this repository:
`FreeX.AppImage`.

## Run

```bash
chmod +x FreeX.AppImage
./FreeX.AppImage
```

If FUSE is unavailable on your system, extract and run instead:

```bash
./FreeX.AppImage --appimage-extract-and-run
```

## Artifact details

| Field    | Value |
| -------- | ----- |
| File     | `FreeX.AppImage` |
| Size     | 168,715,274 bytes (~161 MiB) |
| Arch     | ELF 64-bit LSB executable, x86-64, dynamically linked, stripped |
| SHA-256  | `751aec0468ef7fec56ea5b11421875fa25a2dce1913a1c16a1c984d141323260` |

## Verifying a download

```bash
sha256sum FreeX.AppImage
```

The output must match the SHA-256 above.
