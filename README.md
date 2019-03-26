# pretty-bash-prompt
![screenshot pretty bash prompt](https://github.com/cmicheledelaney/pretty-bash-prompt/blob/master/screenshot_pretty_bash_prompt.png)  
Based on [sexy_bash_prompt by twolfson](https://github.com/twolfson/sexy-bash-prompt)  
  
  
A bash prompt with the username, the current working directory and the git branch as well as the statuses.
These are the symbols for the git statuses:  
  
synced = ""  
dirty & synced = *  
unpushed = △  
dirty & unpushed = ▲  
unpulled = ▽  
dirty & unpulled = ▼  
unpushed & unpulled = ⬡  
dirty, unpushed & unpulled= ⬢  

#### Installation
Get the .pretty_bash_prompt file:  
`curl https://raw.githubusercontent.com/cmicheledelaney/pretty-bash-prompt/master/.pretty_bash_prompt > ~/.pretty_bash_prompt`    
Change your shell to bash and add this line of code in your .bashrc:  
`source ~/.pretty_bash_prompt`  

#### Settings
There are four available colorschemes:  
- rose  
- blue  
- red  
- yellow

By default 'rose' is set but you can easily change it by setting the COLOR_SCHEME_BASH_PROMPT variable to the colorscheme you want.  
Example:  
`export COLOR_SCHEME_BASH_PROMPT="blue"`  
Just add that line in your .bashrc before it sources the .pretty_bash_prompt file.  
![colorschemes](https://github.com/cmicheledelaney/pretty-bash-prompt/blob/master/screenshot_colorschemes.png)  
  
You can change the color of the directory or the branch with the variables DIR_COLOR and BRANCH_COLOR.  
Once you sourced the .pretty_bash_prompt file you can run the command  
`print_colorscheme`  
which will show you the colors you can choose from.  
When ythe default colorscheme is set these are your options:  
![colorscheme blue](https://github.com/cmicheledelaney/pretty-bash-prompt/blob/master/screenshot_colorscheme_blue.png)  
To change the default directory color just add the variable DIR_COLOR with the new value to your .bashrc:  
`export DIR_COLOR=4`  
When another colorscheme is set print_colorscheme will show you different color options. In the red one these are your options:  
![colorscheme red](https://github.com/cmicheledelaney/pretty-bash-prompt/blob/master/screenshot_colorscheme_red.png)  
  
To change the branch color you have to do basically the same, just change your BRANCH_COLOR variable:  
`export BRANCH_COLOR=4`  
Just be aware that you need to set those values before you source the .pretty_bash_prompt file. Also, when you want to change your colorscheme and/or one of the colors you need to source the .pretty_bash_prompt again.  

