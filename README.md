# lazyvim_fav

My favortite configurations for LazyVim

## [Supertab](/plugins/supertab.lua)

### Behavior

IntelliJ-like mapping

- If no completion is selected, insert the fist one in the list
- If a completion is selected, insert this one

Safety select entries with `<CR>`

- If nothing is selected (including preselections) add a newline as usual
- If something has explicitly been selected by the user, select it

### Prerequisite

- `nvim-cmp` has been installed
  You can install automatically by command `:LazyExtras` -> `coding.nvim-cmp`

### Installation

- Copy the `supertab.lua` file to `~/.config/nvim/lua/plugins`

## [Show hidden files](plugins/show-hidden-files.lua)

### Behavior

- Show all hidden files in `neo-tree` excluding `.git` and `.DS_Store`

### Installation

- Copy the `show-hidden-files.lua` file to `~/.config/nvim/lua/plugins`
