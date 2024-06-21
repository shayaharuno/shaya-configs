Godot Neovim Setup

1. Get Windows Terminal or Powershell 7
2. winget install Git.Git
3. winget install Neovim.Neovim
4. winget install Chocolatey
restart
6. (admin) choco install -y ripgrep make mingw fd unzip zip wget
7. git clone https://github.com/nvim-lua/kickstart.nvim.git $HOME/AppData/Local/nvim -q
restart
8. winget install nmap
9. place plugins and init.lua into C:\Users\%USERNAME%\AppData\Local\nvim