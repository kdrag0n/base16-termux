# base16-termux

A set of [Base16](https://github.com/chriskempson/base16) scheme templates for
the [Termux](https://github.com/termux/) terminal emulator app for Android. These
templates can be used with any compliant Base16 builder. **Pre-built** schemes
are also available in the [`colors`](https://github.com/kdrag0n/base16-termux/tree/master/colors)
directory of this repository for convenience.

## [More themes](https://hueflake.dev/?utm_source=gh-base16-termux)

[**Check out Hueflake for high-quality, infinitely customizable Termux themes**](https://hueflake.dev/?utm_source=gh-base16-termux)

## Installation

Simply move the built color scheme to `~/.termux/colors.properties` within the
Termux environment. Replace the existing file if necessary.

You will need to either restart Termux or run the `termux-reload-settings`
command for the change to take effect.

## 256-color variants

The 256-color variants are for those who wish to use the 16 ANSI colors while
retaining accuracy for bright color variants. This is achieved by making the
bright variants mirror their regular counterparts instead of attempting to map
them to other Base16 colors.

**TL;DR**: If some colors look strange or darker than normal, try the
256-color variant of your scheme of choice.
