# Emekçi

A Turkish variant for the Workman keyboard layout originally proposed by OJ
Bucao at https://workmanlayout.org.

## Installation

Right now there is only a layout file for Xorg 7+ so you just copy it to the
directory the other layout symbols reside in, most likely
`/usr/share/X11/xkb/symbols/`.

```
cp xorg/emekci /usr/share/X11/xkb/symbols
setxkbmap emekci
```

## Changes

- The number row behaves the same as a regular Turkish Q keyboard.
- The upper row ends with "`I Ü Ğ`" instead of "`; [ ]`".
- The home row ends with "`İ Ş`" instead of "`I '`".
- The decimal key, at the end of the home row, is set to comma.
- The lower row ends with "`Ö Ç .`" instead of "`, . /`".
