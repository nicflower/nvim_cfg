# Neovim configurations

## Remaps
The leader charatacter is the space.

leader + pv takes to directory navigation
## Plugins
To add a plugin:
- add the use clause in the Packer file;
- if necessary add a configuration file under 'after/plugin/{plugin_name}.lua';
- run `so`;
- run `PackerSync`

### Harpoon
Bookmark files and quickly move across them

In normal mode:
`Ctrl + e` opens harpoon menu and shows the bokmarked files;
`leader + a` adds current file to harpoon,
`Ctrl + h` navigate to file 1;
`Ctrl + t` navigate to file 2;
`Ctrl + n` navigate to file 3;
`Ctrl + s` navigate to file 4;

### Telescope 
Navigate across files

In normal mode:
`leader + pf` find accross all the files in the folder;
`Ctrl + p` find across files in the current git repository;
`leader + ps` find word across file in the current folder;

### Treesitter
Syntax hilighting


### Undotree
See the modifications tree to the current file (to move across different windows in vim you can use `Ctrl + w + w `

`leader + u` open modifications tree;


### Fugitive
A git interface for vim

`leader + gs` open git status;

### LSP zero
Language server protocol

`Ctrl + p` select the previous suggested item;
`Ctrl + n` select the next suggested item;
`Ctrl + y` confirm selection;
`Ctrl + space` autocomplete;


