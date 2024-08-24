# Wayland layer_shell backend for egui with WGPU renderer

This is an **early and work in progress** repository working on a layer shell backend for egui using wgpu for rendering and smithay client toolkit for the wayland client.

> [!WARNING]
> Do not use this yet, the rendering part works, but plenty of things are not yet implemented.

## todo

This is a likely incomplete list of things that need to be done:

- [ ] keyboard input (implemented, but not wired up)
- [ ] mouse button input
- [ ] scroll support
- [ ] clipboard, copy/cut/paste
- [ ] fractional scaling
- [ ] multiple windows
- [ ] ime support
- [ ] touch input
- [ ] drag and drop
- [ ] touchpad gestures (pinch to zoom, etc)

The code is also in a really dirty state, it'll take some time to clean it up and find a good way to structure and abstract over things.
