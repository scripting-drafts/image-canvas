# ding-image-canvas

Patched DING for Ubuntu 22.04 / GNOME 42 with:
- Firefox ESR 153.6 images dragged to the desktop or folder icon stay full resolution.
- Right-click a desktop image for Open With Image Canvas; Ctrl+W closes, left-drag moves.
Install: `./install.sh` then restart the shell (Alt+F2, `r`, Enter). Revert: `./revert.sh`.
Installs `image-canvas` to `~/bin` and registers the extension menu.
Viewer: `image-canvas IMAGE`; Ctrl+W or Esc closes, left-drag moves the window.
See `nautilus/README.md` for the Nautilus 42.6 URL-drop fix.
Based on DING (https://gitlab.com/rastersoft/desktop-icons-ng), GPL-3.0. See NOTICE and `patch/`.
