# XKB keyboard layout for X11 - Algeria
XKB keyboard layout for X11 - Algeria

I'm working on an alternative standardised layout of the dz xkb for GNU/Linux based on the freedesktop package, mainly `/usr/share/X11/xkb/symbols/dz` and `/usr/share/X11/xkb/rules/*`

Note : Please don't use this work in production situation. It is a work in progress.

Main changes :

- Introducing ɛ Ɛ γ Γ alphabetic letters and commonly used Unicode symbols
- Getting rid off extra characters such as egrave, apostrophe, agrave, ccedilla and so on : éèùàç'
- Reorganising the dz syntax with tabs
- Better ASCII keyboard layouts view in terminal mode
- Using kab or regional kab_dz as ISO since Tamazight is not defined.

## Work in progress (future)

The idea is to add a Dvorak, Bépo, Colemak like layouts for Kabyle and take into consideration Mac layout and other OS.

## Related links
- https://github.com/BoFFire/Kabyle-latin-script
- https://github.com/nlouahedj/tamazight-layout
- AnySoftKeyboard Tamazight layout WIP :https://github.com/BoFFire/LanguagePack
