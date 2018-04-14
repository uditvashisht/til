#Create aliases for Terminal commands on Macos:
You can easily create shortcut commands called aliases for the long day to day commands.\
Open .bash_profile in your favorite text-editor.(I use Sublime Text 3)
`subl ~/.bash_profile`
Then add your aliases as under:-
```
alias py='python3'
alias gc='git commit -m'
alias work='cd Path/to/desired/directory'
```
Save and close the .bash_profile and run 

`source ~/.bash_profile `

You can quickly check the aliases by typing alias in the terminal
`alias`
