# Tools
---
## No Brainers
* Terminal tools <!-- .element: class="fragment"-->
  * [zsh](https://ohmyz.sh/) - better shell, jam packed with tons of great default features
  * Tmux, screen, terminator, CMDER
  * git workflow
* Improvements <!-- .element: class="fragment"-->
  * [ripgrep](https://github.com/BurntSushi/ripgrep): better grep
```bash
grep -r "surrogate.*comp" 
rg "surrogate.*comp"
  ```
    * **Warning**: ignores `.gitignore` files by default!
  * [fd](https://github.com/sharkdp/fd) - better find 
```bash
  find . -iname "effectiveenv*" # or find . -name "EffectiveEnv*"
  fd effectiveenv
```
  * [fzf](https://github.com/junegunn/fzf): search for when you're a bit *fuzzy* on what you're looking for
  * [autojump](https://github.com/wting/autojump): what you alway wished `cd` was
  * [bat](https://github.com/sharkdp/bat): a `cat` clone with wings!
---
## Additonal Great Tools
* Window managers - I3, regolith
* Dotfile sync
---
## Misc Tips
* Chaining commands with `exec` and $()
