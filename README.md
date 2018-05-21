# dotFiles

some dotFiles, of my own

```js
.
├── .config                    // XDG_CONFIG_HOME
│   ├── fish
│   │   ├── conf.d
│   │   │   └── rocka.fish     // fishshell alias
│   │   └── fishfile           // fisherman
│   ├── fontconfig
│   │   └── fonts.conf         // fontconfig
│   └── libinput-gestures.conf // kde flavored libinput-gestures config
├── .eslintrc.json             // default settings for eslint
├── .gitconfig                 // git proxy and alias
├── .gnupg                     // GnuPG
│   ├── gpg-agent.conf
│   └── gpg.conf
├── LICENSE                    // WTFPL
├── .local
│   └── bin                    // local bin/ path
│       └── yd                 // stupid GUI wrap for `ydcv`
├── .pac                       // config for genpac (deprecated now)
│   ├── config.ini             // ├── config
│   └── user-rules.txt         // └── gfwlist user rules
├── .pam_environment           // set some env
├── README.md                  // this README
└── .vimrc                     // very simple vimrc
```

> the file tree above can be generated by `tree -aL 4 -I .git`

1. fonts needed in my fontconfig: [`noto-fonts`][noto], [`noto-fonts-cjk`][noto-cjk], [`ttf-mph-2b-damase`][mph-2b-damase], [`ttf-symbola`][ttf-symbola], [`ttf-hack`][hack], [`ttf-droid-monovar`][droid-monovar]<sup>AUR</sup>, [`ttf-iosevka-term`][ttf-iosevka-term]<sup>AUR</sup>, [`noto-fonts-emoji-blob`][blobmoji]<sup>AUR</sup>
2. install [fisherman][fisherman] before using my fishfile
3. [libinput-gestrures][gestrures]
4. `.pac` is config for [genpac][genpac] (deprecated now)
5. install package [`ydcv`][ydcv] and [`kdialog`][kdialog] before using the script `yd`

[noto]: https://www.archlinux.org/packages/extra/any/noto-fonts/
[noto-cjk]: https://www.archlinux.org/packages/extra/any/noto-fonts-cjk/
[mph-2b-damase]: https://www.archlinux.org/packages/extra/any/ttf-mph-2b-damase/
[ttf-symbola]: https://www.archlinux.org/packages/extra/any/ttf-symbola/
[hack]: https://www.archlinux.org/packages/extra/any/ttf-hack/
[droid-monovar]: https://aur.archlinux.org/packages/ttf-droid-monovar/
[ttf-iosevka-term]: https://aur.archlinux.org/packages/ttf-iosevka-term/
[blobmoji]: https://aur.archlinux.org/packages/noto-fonts-emoji-blob/
[fisherman]: https://github.com/fisherman/fisherman
[gestrures]: https://github.com/bulletmark/libinput-gestures
[genpac]: https://github.com/JinnLynn/genpac
[ydcv]: https://www.archlinux.org/packages/community/any/ydcv/
[kdialog]: https://www.archlinux.org/packages/extra/x86_64/kdialog/
