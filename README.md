# SuperNav-1.5 video assets

Large video files for the [SuperNav-1.5 project page](https://zju3dv.github.io/SuperNav-1.5/). The website source and lightweight images/fonts live in the separate project-page repository.

## Layout

- `assets/overview/`: rendered 63-second overview video.
- `assets/realworld_demos/`: six real-world demonstrations.
- `assets/simulation_demos/`: twelve simulation demonstrations.

Files use ordinary Git, not Git LFS, so public media URLs deliver the actual MP4 rather than an LFS pointer. Every video is below GitHub's per-file size limit.

The website uses the base URL `https://raw.githubusercontent.com/bugByteMe/SuperNav-1.5-assets/main/`, followed by the relative file path. Keep existing paths stable when updating a video.

To regenerate website thumbnails or the overview, copy this repository's `assets/` folders into the project page's `SuperNav-1.5/assets/` directory. Those local MP4 copies are ignored by the website repository.
