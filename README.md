<!-- SDDM Themes-->

<h1 align="center">
    Hogwarts dark theme
</h1>

<p align="center">

</p>

<div align="center">
    <img alt="Github last commit (branch)" src="https://img.shields.io/github/last-commit/carmoruda/hogwarts-dark/master?color=2ea043&labelColor=202328&label=Last Update%3F&style=for-the-badge">
    <img alt="Github repo stars" src="https://img.shields.io/github/stars/carmoruda/hogwarts-dark?color=db6d28&labelColor=202328&style=for-the-badge">
    <img alt="Github repo forks" src="https://img.shields.io/github/forks/carmoruda/hogwarts-dark?color=388bfd&labelColor=202328&style=for-the-badge">
    <img alt="Github repo open issues" src="https://img.shields.io/github/issues/carmoruda/hogwarts-dark?color=f85149&labelColor=202328&style=for-the-badge">
    <img alt="Github repo open pull requests" src="https://img.shields.io/github/issues-pr/carmoruda/hogwarts-dark?color=a371f7&labelColor=202328&style=for-the-badge">
    <img alt="Github repo license" src="https://img.shields.io/github/license/carmoruda/hogwarts-dark?color=15121C&labelColor=202328&style=for-the-badge">
</div>

## ℹ️ Info

SDDM is an acronym for "Simple Desktop Display Manager". It is a [display manager](https://en.wikipedia.org/wiki/X_display_manager) for the [X11](https://x.org/) and [Wayland](https://wayland.freedesktop.org/) windowing systems. It was dvelop to be fast, simple and highly customizable.

### 🐛 Dependencies

- [SDDM >= 0.18.0](https://github.com/sddm/sddm)
- [Qt5 >= 5.11.0](https://doc.qt.io/qt-5/index.html)
- [Qt5-quickcontrols2 >= 5.11.0](https://doc.qt.io/qt-5/qtquickcontrols-index.html)
- [Qt5-quickcontrols2 >= 5.11.0](https://doc.qt.io/qt-5/qtquickcontrols-index.html)
- [Qt5-svg >= 5.11.0]()

### 📥 Installation

1. Clone this repository to `/usr/share/sddm/themes`:

   ```sh
   sudo git clone https://github.com/carmoruda/sddm-hogwarts-themes.git /usr/share/sddm/themes
   ```

2. Then edit `/etc/sddm.conf`, so that it looks like this (example for [Autumn Hogwarts](./autumn-hogwarts/):

   ```conf
    [Theme]
    #Current theme name
    Current=autumn-hogwarts
   ```

### 🌟 Showcase

| Theme                                          | Preview                                                                                                                                             | Background image credit                                                             |
| ---------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| [🍂](./autumn-hogwarts/) Autumn Hogwarts       | <img src="./autumn-hogwarts/Previews/preview-hpah-1.png" width="350"> <img src="./autumn-hogwarts/Previews/preview-hpah-2.png" width="350">         | [Artstation - Jerome Comentale](https://www.artstation.com/artwork/J9g2YR)          |
| [🏫](./back-at-hogwarts/) Back at Hogwarts     | <img src="./back-at-hogwarts/Previews/preview-hpbah-1.png" width="350"> <img src="./back-at-hogwarts/Previews/preview-hpbah-2.png" width="350">     | [Artstation - Jakob Vandenabeele](https://www.artstation.com/artwork/e0rOgw)        |
| [🐍](./chamber-of-secrets/) Chamber of secrets | <img src="./chamber-of-secrets/Previews/preview-hpcof-1.png" width="350"> <img src="./chamber-of-secrets/Previews/preview-hpcof-2.png" width="350"> | [Artstation - Vladislav Pantic](https://www.artstation.com/artwork/5XnNNW)          |
| [🌲](./forest-hogwarts/) Forest Hogwarts       | <img src="./forest-hogwarts/Previews/preview-hpfh-1.png" width="350"> <img src="./forest-hogwarts/Previews/preview-hpfh-2.png" width="350">         | [Artstation - Samantha Chow](https://www.artstation.com/artwork/Dx6NQE)             |
| [📚](./hogwarts-library/) Hogwarts Library     | <img src="./hogwarts-library/Previews/preview-hphl-1.png" width="350"> <img src="./hogwarts-library/Previews/preview-hphl-2.png" width="350">       | [Artstation - Jefferson Bacquey Habrylo](https://www.artstation.com/artwork/X1nNx0) |
| [📐](./poly-hogwarts/) Poly Hogwarts           | <img src="./poly-hogwarts/Previews/preview-hpph-1.png" width="350"> <img src="./poly-hogwarts/Previews/preview-hpph-2.png" width="350">             | [Artstation - Björn Kiefer](https://www.artstation.com/artwork/XnzJRY)              |

### 👥 Credits

[SDDM login manager](https://github.com/sddm/sddm") theme based on the theme [`Sugar Dark for SDDM`](https://github.com/MarianArlt/sddm-sugar-dark) by **MarianArlt** and forked from [`Astronaut theme for SDDM`](https://github.com/Keyitdev/sddm-astronaut-theme) by **Keyitdev**.

### ⚖️ License

Distributed under the [GPLv3+](https://www.gnu.org/licenses/gpl-3.0.html) License.
