# tmux Quick Reference

+ Enable vi cursor movement in copy mode
  + `set-window-option -g mode-keys vi`<sup>https://awhan.wordpress.com/2010/06/20/copy-paste-in-tmux/</sup>
+ Reload tmux config
  + From within tmux `:source-file ~/.tmux.conf` <sup>http://blog.sanctum.geek.nz/reloading-tmux-config/</sup>
  + From shell `tmux source-file ~/.tmux.conf`
