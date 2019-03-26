# pretty-bash-prompt
![Image description](https://github.com/cmicheledelaney/pretty-bash-prompt/blob/master/screenshot_pretty_bash_prompt.png)
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
Get the .my_prompt file:  
`curl https://raw.githubusercontent.com/cmicheledelaney/my_prompt/master/.my_prompt > ~/.my_prompt`    
Change your shell to bash and add this line of code in your .bashrc:  
`source ~/.my_prompt`  
If you change the path of the .my_prompt file, change it in your .bashrc accordingly.
