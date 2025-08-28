# kickstart.nvim
I forked [this](https://github.com/nvim-lua/kickstart.nvim) repository in order to save my specific nvim plugin configuration. Using nvim in linux I just clone the repository:

```sh
git clone https://github.com/nvim-lua/kickstart.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```

In the machine i need it. If you make changes to the configuration, like adding a new plugin, just commit and push to your own fork.

```sh
cd "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
git add .
git commit -m "<changes description>"
git push origin master
```

