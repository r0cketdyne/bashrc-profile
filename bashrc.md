# Define colors
green="\[\e[32m\]"
blue="\[\e[34m\]"
cyan="\[\e[36m\]"
reset="\[\e[0m\]"

# Define prompt
PS1="$green\u$reset@$blue\h $cyan\W$reset\\$ "

# Optional: Set title of terminal window
PS1="\[\e]0;\u@\h: \w\a\]$PS1"
