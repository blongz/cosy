# Cosy Color Scheme for Vim
基于 blongz/detorte ，做了一些微调，去掉底色的模糊感。
变更名称，避免插件更新时出现冲突。

***
# Installation
Copy the files on your .vim/colors folder. Or alternatively, use a plugin manager such as Vundle, or Pathogen.

If you prefer the dark theme, add this in your `.vimrc` file:

```
let g:cosy_theme_mode = 'dark'
```

Or the light theme:

```
let g:cosy_theme_mode = 'light'
```

# Useful Commands
- CosyHighContrastFn  
Turn on high contrast mode in dark theme mode. It is useful when you are presenting your screen.
- CosyHighlight <group> <fg-color-num> <bg-color-num> [style]  
Change both the GUI and CTerm settings of highlight group `<group>`. `<fg-color-num>` and `<bg-color-num>` are the 256 color number and `-1` means not specified.  
`[style]` is `bold`, `italic`, or `none`.  
Example: `CosyHighlight CursorLine 16 -1 none`.

***
# Screenshots
![Screenshots_01](https://github.com/blongz/cosy/blob/master/screenshots/cosy_01.png)

![Screenshots_02](https://github.com/blongz/cosy/blob/master/screenshots/cosy_02.png)

![Screenshots_03](https://github.com/blongz/cosy/blob/master/screenshots/cosy_03.png)

![Screenshots_04](https://github.com/blongz/cosy/blob/master/screenshots/cosy_04.png)
