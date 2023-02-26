# Neovim configurations
This file contains a summary of the installed plugins, the shortcuts and useful general vim stuff that probably I would forget otherwhise.

The use of neovim was inspired by [ThePrimeagen](https://www.youtube.com/@ThePrimeagen) and his [configuration video](https://www.youtube.com/watch?v=w7i4amO_zaE).

## Remaps
The leader charatacter is the space.

`leader + pv` takes to directory navigation

## Plugins
To add a plugin:
- add the use clause in the Packer file;
- if necessary add a configuration file under 'after/plugin/{plugin_name}.lua';
- run `so`;
- run `PackerSync`

### Harpoon
Bookmark files and quickly move across them

In normal mode:
- `Ctrl + e` opens harpoon menu and shows the bokmarked files. Here you can remove bookmarked file with `dd`;
- `leader + a` adds current file to harpoon,
- `Ctrl + h` navigate to file 1;
- `Ctrl + t` navigate to file 2;
- `Ctrl + n` navigate to file 3;
- `Ctrl + s` navigate to file 4;

### Telescope 
Navigate across files

In normal mode:
- `leader + pf` find accross all the files in the folder;
- `Ctrl + p` find across files in the current git repository;
- `leader + ps` find word across file in the current folder;

### Treesitter
Syntax hilighting


### Undotree
See the modifications tree to the current file (to move across different windows in vim you can use `Ctrl + w + w `

`leader + u` open modifications tree;

### Fugitive
A git interface for vim, `:Git` calls any arbitrary Git command

`leader + gs` open git status;

### LSP zero
Language server protocol

- `Ctrl + p` select the previous suggested item;
- `Ctrl + n` select the next suggested item;
- `Ctrl + y` confirm selection;
- `Ctrl + space` autocomplete;
- `gd` go to definition;

### Markdown Preview
Allows to open a web page that renders a markdown file

- `MarkdownPreview` starts the preview;
- `MarkdownPreviewStop` stop the preview;

## Useful vim commands
- `:!{command}`: {command} will be executed as a terminal command;
