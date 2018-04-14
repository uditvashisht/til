# Set Sublime Text 3 as your default editor for CLI.

Using Vim is a nightmare, you can easily set Sublime Text 3 as your default editor.

First of all you need to find the path for the 'subl'. Generally it's :-

`
/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/
`

Alternatively, you can find it as under:-
* Find the Sublime Text app in applications folder.
* Right click and select 'Show Package Content'.
* Browse to Contents->SharedSupport->bin.
* You will find the subl file there.
* Right click, press option and copy "subl" as path name.

You will have to use "\\" to escape white space.

Now, open .bash_profile in your favorite editor and add the following line (You will get the file at ~/.bash_profile):

`
export PATH=$PATH:/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/
`

Save and close the .bash_profile and run:- 

`
source ~/.bash_profile
`

You are ready to go, now Sublime Text is your default text editor, also you can use to open the file:-

`
subl filename.extension
`

