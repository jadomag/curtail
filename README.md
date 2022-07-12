# curtail

Warm color scheme with a limited palette for Vim.

Inspired by [Gruvbox](https://github.com/morhetz/gruvbox) and [Jonathan
Blow](https://www.youtube.com/user/jblow888)'s personal syntax theme.

## Installation

Install with your favorite package manager and add the following to your vimrc:

```
syntax enable           " enable syntax highlighting
set termguicolors       " enable true color support
set background=dark     " set to dark mode; use 'light' for light mode
colorscheme curtail     " set the colorscheme to curtail
```

Following snippet may be required if colors aren't displayed correctly:

```
execute "set t_8f=\e[38;2;%lu;%lu;%lum"
execute "set t_8b=\e[48;2;%lu;%lu;%lum"
```

## Screenshots

### Dark mode

![Screenshot of dark mode](https://i.imgur.com/ClqoJ76.png)

### Light mode

![Screenshot of light mode](https://i.imgur.com/PVzrCG1.png)

## Palette

### Dark mode

![Palette for dark mode](https://i.imgur.com/20j9auZ.png)

### Light mode

![Palette for light mode](https://i.imgur.com/KFbtOv0.png)

## License

[BSD-2-Clause-Patent (BSD+Patent)](https://opensource.org/licenses/BSDplusPatent)
