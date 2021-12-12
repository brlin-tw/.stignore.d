# .stignore.d

[Syncthing](https://syncthing.net/) ignore patterns, distributed in a organized way.

## How to use

1. Clone this repository to your sync folder
1. Include ignore patterns that you'd prefer by adding a `#include` pattern in your .stignore file:

    ```stignore
    #include .stignore.d/backup-files.stignore
    #include .stignore.d/logs.stignore
    #include .stignore.d/vagrant.stignore
    ```

## Licensing

[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/), or any of its more recent version you'd prefer.

## Credits

This project is inspired by [M-Mono/Syncthing-Ignore-Patterns: Useful .stignore Patterns for Syncthing](https://github.com/M-Mono/Syncthing-Ignore-Patterns).

## Reference

* [Ignoring Files — Syncthing v1 documentation](https://docs.syncthing.net/users/ignoring.html)
