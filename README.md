# Command-lines-Git_Bash_shortcuts-
# this is my initial file for learning command line shortcuts and bash #

*my first task*

-simple customize my terminal color, username, and hostname-

PS1 – Default interactive prompt (this is the variable most often customized)
PS2 – Continuation interactive prompt (when a long command is broken up with \ at the end of the line) default=">"
PS3 – Prompt used by “select” loop inside a shell script
PS4 – Prompt used when a shell script is executed in debug mode (“set -x” will turn this on) default ="++"
PROMPT_COMMAND - If this variable is set and has a non-null value, then it will be executed just before the PS1 variable.

Set your prompt by changing the value of the PS1 environment variable, as follows:

$ export PS1="My simple prompt> "
>

This change can be made permanent by placing the "export" definition in your ~/.bashrc file.

Special prompt variable characters:
 \d   The date, in "Weekday Month Date" format (e.g., "Tue May 26"). 

 \h   The hostname, up to the first . (e.g. deckard) 
 \H   The hostname. (e.g. deckard.SS64.com)

 \j   The number of jobs currently managed by the shell. 

 \l   The basename of the shell's terminal device name. 

 \s   The name of the shell, the basename of $0 (the portion following 
      the final slash). 

 \t   The time, in 24-hour HH:MM:SS format. 
 \T   The time, in 12-hour HH:MM:SS format. 
 \@   The time, in 12-hour am/pm format. 

 \u   The username of the current user. 

 \v   The version of Bash (e.g., 2.00) 

 \V   The release of Bash, version + patchlevel (e.g., 2.00.0) 

 \w   The current working directory. 
 \W   The basename of $PWD. 

 \!   The history number of this command. 
 \#   The command number of this command. 

 \$   If you are not root, inserts a "$"; if you are root, you get a "#"  (root uid = 0) 

 \nnn   The character whose ASCII code is the octal value nnn. 

 \n   A newline. 
 \r   A carriage return. 
 \e   An escape character (typically a color code). 
 \a   A bell character.
 \\   A backslash. 

 \[   Begin a sequence of non-printing characters. (like color escape sequences). This
      allows bash to calculate word wrapping correctly.

 \]   End a sequence of non-printing characters.
 
 \e[0;30m = Dark Gray
\e[1;30m = Bold Dark Gray
\e[0;31m = Red
\e[1;31m = Bold Red
\e[0;32m = Green
\e[1;32m = Bold Green
\e[0;33m = Yellow
\e[1;33m = Bold Yellow
\e[0;34m = Blue
\e[1;34m = Bold Blue
\e[0;35m = Purple
\e[1;35m = Bold Purple
\e[0;36m = Turquoise
\e[1;36m = Bold Turquoise
\e[0;37m = Light Gray
\e[1;37m = Bold Light Gray

Background colors:

\e[40m = Dark Gray
\e[41m = Red
\e[42m = Green
\e[43m = Yellow
\e[44m = Blue
\e[45m = Purple
\e[46m = Turquoise
\e[47m = Light Gray

some credit goes to: 
url(https://ss64.com/bash/syntax-prompt.html
