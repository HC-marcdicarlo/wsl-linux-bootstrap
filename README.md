# wsl-linux-bootstrap

### Windows Linux Subsystem (WSL):

https://docs.microsoft.com/en-us/windows/wsl/install-on-server

### WSL fedora remix download

https://github.com/WhitewaterFoundry/Fedora-Remix-for-WSL/releases

### X server:

https://sourceforge.net/projects/vcxsrv/

### Terminator terminal app:

https://launchpad.net/~gnome-terminator/+archive/ubuntu/ppa

```sudo apt-get terminator -y```

### TerminalScript:
add to startup folder:

<term.vbs>

https://gist.github.com/HC-marcdicarlo/e1925b2121855b1172e0a4656c1ad682#file-xserver-term

```WScript.CreateObject("Shell.Application").ShellExecute "C:\Users\A058384\Documents\config.xlaunch"
args = "-c" & " -l " & """DISPLAY=:0 terminator -l new_layout"""
WScript.CreateObject("Shell.Application").ShellExecute "bash", args, "", "open", 0
```

### vim config
https://vim-bootstrap.com/

### Vim Awesome (VIMPlug plugins)

https://vimawesome.com/

Place this in your .vimrc:
```
Plugin 'chase/vim-ansible-yaml'
```

… then run the following in Vim:
```
:source %
:PlugInstall
:PlugUpdate
```

additional plugins:

```
Plug 'pearofducks/ansible-vim'
Plug 'glench/vim-jinja2-syntax'
```

### VIM cheatsheet:
https://vim.rtorr.com/

### Learn git basics:
https://www.codecademy.com/learn/learn-git
https://try.github.io/
