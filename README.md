## [MC Editor](https://midnight-commander.org) syntax higlighter definitions for [FreeDesktop.org](https://freedesktop.org) .desktop files

**Author:** <small>Maxim Zhukov [`mzhukov31415dev@gmail.com`](mzhukov31415dev@gmail.com)</small><br>
**GitHub repository:** [`https://github.com/mzhukov1973/mcedit-syntax-highlighter-desktop`](https://github.com/mzhukov1973/mcedit-syntax-highlighter-desktop)

**Based on:** [FreeDesktop specs](https://standards.freedesktop.org/desktop-entry-spec/latest) (version 1.2alpha from 2017-12-24)

**Created on:** 2018-05-06<br><br>
**Last updated on:** 2019-09-14

**Version:** `0.0.2`

**License:** [MIT](https://opensource.org/licenses/MIT)

**Changes<sup>0.0.2</sup>:** Added rules for .vala, [web]manifest.json & meson.build files.

**Changes<sup>0.0.1</sup>:** Initial commit, first draft.

### Setup:
*For personal use:*

Just drop `desktop.syntax` in `~/.config/mc/mcedit/syntax` directory and add following two lines to the `~/.config/mc/mcedit/Syntax`:

```php
file ..\*\\.(desktop|DESKTOP)$ Desktop\sDefinition
include /home/yourusername/.config/mc/mcedit/syntax/desktop.syntax
```
*Globaly, for everyone on the machine mc is running on:*

Copy `desktop.syntax` in `/usr/share/mc/syntax` directory and add following two lines to the `/usr/share/mc/syntax/Syntax`:

```php
file ..\*\\.(desktop|DESKTOP)$ Desktop\sDefinition
include /home/yourusername/.config/mc/mcedit/syntax/desktop.syntax
```
