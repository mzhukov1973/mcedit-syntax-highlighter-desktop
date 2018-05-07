## [MC Editor](https://midnight-commander.org) syntax higlighter definitions for [FreeDesktop.org](https://freedesktop.org) .desktop files

**Author:** <small>Maxim Zhukov [`mzhukov31415dev@gmail.com`](mzhukov31415dev@gmail.com)</small><br>
**GitHub repository:** [`https://github.com/mzhukov1973/mcedit-syntax-highlighter-desktop`](https://github.com/mzhukov1973/mcedit-syntax-highlighter-desktop)

**Based on:** [FreeDesktop specs](https://standards.freedesktop.org/desktop-entry-spec/latest) (version 1.2alpha from 2017-12-24)<br>
**Created on:** 2018-05-06<br>
**Last updated on:** 2018-05-07

**Version:** `0.0.1`

**Changes in 0.0.1:** Initial commit, first draft.

### Setup:
##### For personal use:
Just drop `desktop.syntax` in `~/.config/mc/mcedit/syntax` directory and add following two lines to the `~/.config/mc/mcedit/Syntax`:

```php
file ..\*\\.(desktop|DESKTOP)$ Desktop\sDefinition
include /home/mzhukov/.config/mc/mcedit/syntax/desktop.syntax
```
##### Globaly, for everyone on the machine mc is running on:
Copy `desktop.syntax` in `/usr/share/mc/syntax` directory and add following two lines to the `/usr/share/mc/syntax/Syntax`:

```php
file ..\*\\.(desktop|DESKTOP)$ Desktop\sDefinition
include /home/mzhukov/.config/mc/mcedit/syntax/desktop.syntax
```
