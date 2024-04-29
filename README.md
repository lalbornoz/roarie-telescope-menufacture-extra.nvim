# roarie-telescope-menufacture-extra

`roarie-telescope-menufacture-extra` is an extension for the
[telescope-menufacture](https://github.com/molecule-man/telescope-menufacture)
extension for [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim).
It adds several additional menu options/actions. Please refer to the telescope-menufacture
documentation for installation, usage, etc.

# Installation

```lua
--
-- Ensure this executes after telescope.nvim and telescope-menufacture
-- have both been loaded and setup successfully.
--
require("roarie-telescope-menufacture-extra")
```

# Additional menus available by default

## find_files

| Menu item                    | Description                                                     | menu_action                       |
| ---------------------------- | ----------------------------------------------------------------| --------------------------------- |
| back...                      | exit telescope-menufacture menu and go back to telescope picker |                                   |
| change directory...          | change current directory with browser                           | change_directory                  |
| change into directory        | change into top-level directory of selected item                | change_into_directory             |
| change into parent directory | change into parent directory                                    | change_into_parent_directory      |
| decrease maximum depth       | decrease maximum search directory depth by 1                    | decrease_maximum_depth            |
| decrease path shorten        | decrease path shortening character count by 1                   | decrease_path_shorten             |
| edit ignore patterns...      | input and edit array of patterns to ignore files with           |                                   |
| increase maximum depth       | increase maximum search directory depth by 1                    | increase_maximum_depth            |
| increase path shorten        | increase path shortening character count by 1                   | increase_path_shorten             |
| live grep here...            | open live grep picker at current working directory              | live_grep_here                    |
| set maximum depth...         | input and set maximum search directory depth                    |                                   |
| toggle hidden                | toggle including hidden files (e.g. dotdir/files)               | toggle_hidden                     |
| toggle ignore ^%.git/        | toggle ignoring the pattern ^%.git/                             |                                   |
| toggle wrap                  | toggle wrapping lines in picker window                          |                                   |

[modeline]: # ( vim: set tw=0: )
