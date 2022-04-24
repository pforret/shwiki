![bash_unit CI](https://github.com/pforret/shwiki/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/shwiki/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/shwiki)
![GH stars](https://img.shields.io/github/stars/pforret/shwiki)
![GH tag](https://img.shields.io/github/v/tag/pforret/shwiki)
![GH License](https://img.shields.io/github/license/pforret/shwiki)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# shwiki

Wikipedia CLI in bash

## 🔥 Usage

```
Program: shwiki 1.0.3 by peter@forret.com
Updated: Apr 24 23:47:08 2022
Description: Wikipedia CLI in bash
Usage: shwiki [-h] [-q] [-v] [-c] [-f] [-l <log_dir>] [-t <tmp_dir>] [-w <width>] [-p <paragraphs>] [-s <sentences>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] output more [default: off]
    -c|--cleanup     : [flag] cleanup Wikipedia text [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/shwiki]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /Users/pforret/Code/Github/shwiki/.tmp]
    -w|--width <?>   : [option] max line width  [default: 100]
    -p|--paragraphs <?>: [option] stop after N paragraphs  [default: 1]
    -s|--sentences <?>: [option] stop after N sentences  [default: 10]
    <action>         : [choice] action to perform  [options: search,action2,check,env,update]
    <input>          : [parameter] search term (optional)
```

## ⚡️ Examples

```bash
> shwiki search London
# get Wikipedia information about London

> shwiki -p 2 -s 10 -c search London
# get Wikipedia information about London, max 2 paragraphs, max 10 sentences, and clean up the text
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/shwiki

or with `git`

	$ git clone https://github.com/pforret/shwiki.git
	$ cd shwiki

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2022 Peter Forret
