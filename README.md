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

- [`SDDM` >= 0.18.0](https://github.com/sddm/sddm)
- [Qt5 >= 5.11.0](https://doc.qt.io/qt-5/index.html)
- [Qt5-quickcontrols2 >= 5.11.0](https://doc.qt.io/qt-5/qtquickcontrols-index.html)
- [Qt5-quickcontrols2 >= 5.11.0](https://doc.qt.io/qt-5/qtquickcontrols-index.html)
- [Qt5-svg >= 5.11.0]()

### 📥 Installation

1. Clone this repository to `/usr/share/sddm/themes`:

   ```sh
   sudo git clone https://github.com/carmoruda/hogwarts-dark.git /usr/share/sddm/themes/hogwarts-darl
   ```

2. Then edit `/etc/sddm.conf`, so that it looks like this:

   ```conf
    [Theme]
    #Current theme name
    Current=hogwarts-darkV
   ```

### 🌟 Showcase

![Preview 1](./Previews/preview-1.png)
![Preview 2](./Previews/preview-2.png)

### 👥 Credits

[SDDM login manager](https://github.com/sddm/sddm") theme based on the theme [`Sugar Dark for SDDM`](https://github.com/MarianArlt/sddm-sugar-dark) by **MarianArlt** and forked from [`Astronaut theme for SDDM`](https://github.com/Keyitdev/sddm-astronaut-theme) by **Keyitdev**.

### ⚖️ License

Distributed under the [GPLv3+](https://www.gnu.org/licenses/gpl-3.0.html) License.
