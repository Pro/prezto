chroot
======

Add current chroot environment to zsh

Usage Example
-------------

First, format the system informations attributes:

    zstyle ':prezto:module:chroot:info:format' format '(%C)'

Last, add `$chroot_info` to `$PROMPT`and call `chroot-info` in the `prompt_name_setup` function.

