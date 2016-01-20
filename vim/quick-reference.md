# Weston's Vim Quick Reference
+ `h j k l` Move cursor left, line down, line up, cursor right
+ `i` Enter insert mode
+ `^ $` Beginning, end of line
+ `i a` Insert before, after cursor
+ `I A` Insert at beginning, end of line
+ `rw` Replace character under cursor with `w`
+ `:sp [filename]` Create horizontal split
+ `:vsp [filename]` Create vertical split
+ `Ctrl-w =` Resize all windows to equal dimensions

+ `:e <file name>` Create a new file
+ `:set expandtab` Convert all tabs to spaces
+ `:set tabstop=4` Set tabs to be 2 spaces

#### Searching
+ `d<line number>G`<sup>[[0]](http://stackoverflow.com/questions/6384561/delete-to-line-number-in-vi)</sup> Delete lines [current line, line number]
  + e.g. `d53G`
    + Delete all lines from current line to line 53

#### Config
+ Set a prefix key to be the leader key for mappings
  + `let mapleader = "<character>"`<sup>[source](http://learnvimscriptthehardway.stevelosh.com/chapters/06.html)</sup>
    + e.g. `let mapleader = ","`
            `:nnoremap <leader>d dd`
      + Remaps `,d` to `dd`
+ Ignore case while searching
  + `set ignorecase`<sup>[source](http://vim.wikia.com/wiki/Searching)</sup>
+ Hide buffer when unloading instead of closing it
  + `set hidden`<sup>[source](http://usevim.com/2012/10/19/vim101-set-hidden/)</sup>
+ Re-map a key (non-recursively)
  + `noremap <key to remap> <command to map to>`
    + e.g. `noremap ,d dd`


#### Help
`:h startup` - Vim startup