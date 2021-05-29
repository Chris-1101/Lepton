![Lepton][0]

Fork of the popular *GitHub Gist* client, [Lepton][1], implementing a different dark theme colour scheme and some minor UI modifications.

### Preview
![Preview][2]
<sub>Theme preview &mdash; affected by minor translucency and background blur using compositor **picom**</sub>

### Instructions (Arch Linux)
* `yarn install`
* `yarn build`
* `yarn dist`
* `cd PKGBUILD`
* `ln -s ../dist/Lepton-VERSION.AppImage .`
* AUR Utils: `aur build` & `sudo pacman -S lepton-arclight-appimage`
* Manually: `makepkg` & `sudo pacman -U RESULTING_PKG_FILE.pkg.tar.zst`

### Credits
* [Hackjutsu][3] (CosmoX): `Lepton` Project
* [Hwangeug][4] (Eugene Hwang): `lepton-snippet-manager-appimage` AUR Repo (`PKGBUILD/`)

[0]: ./docs/img/new_logo.png
[1]: https://github.com/hackjutsu/Lepton
[2]: ./docs/img/preview.png
[3]: https://github.com/hackjutsu
[4]: https://github.com/hwangeug
