# git-bash-utils

Download the following files in a folder (cmdline_scripts) under your home (~) directory

* bash_colors
* bash_functions
* git-completion.bash

Add the following to your .bashrc or .bash_profile scripts (update folder name accordinigly)

```
. ${HOME}/cmdline_scripts/bash_functions
. ${HOME}/cmdline_scripts/bash_colors
PROMPT_COMMAND=my_prompt 
```
