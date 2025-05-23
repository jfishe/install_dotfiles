![bash_unit CI](https://github.com/jfishe/install_dotfiles/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/jfishe/install_dotfiles/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/jfishe/install_dotfiles)
![GH stars](https://img.shields.io/github/stars/jfishe/install_dotfiles)
![GH tag](https://img.shields.io/github/v/tag/jfishe/install_dotfiles)
![GH License](https://img.shields.io/github/license/jfishe/install_dotfiles)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# install_dotfiles

Install applications and configuration with RCRC.

## 🔥 Usage

```
Program : install_dotfiles  by jdfenw@gmail.com
Version : v0.0.1 (Apr 22 16:07:13 2023)
Purpose : Install applications and configuration with RCRC.
Usage   : install_dotfiles [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/script]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/script]
    <action>         : [choice] action to perform  [options: action1,action2,check,env,update]
                                  
### TIPS & EXAMPLES
* use install_dotfiles action1 to ...
  install_dotfiles action1
* use install_dotfiles action2 to ...
  install_dotfiles action2
* use install_dotfiles check to check if this script is ready to execute and what values the options/flags are
  install_dotfiles check
* use install_dotfiles env to generate an example .env file
  install_dotfiles env > .env
* use install_dotfiles update to update to the latest version
  install_dotfiles update
* >>> bash script created with pforret/bashew
* >>> for bash development, also check out pforret/setver and pforret/progressbar
```

## ⚡️ Examples

```bash
> install_dotfiles -h 
# get extended usage info
> install_dotfiles env > .env
# create a .env file with default values
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install jfishe/install_dotfiles

or with `git`

	$ git clone https://github.com/jfishe/install_dotfiles.git
	$ cd install_dotfiles

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2025 John D. Fisher
