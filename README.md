# If you're really tired of SYSTEM SLEEP ON MAC: 
alias nosleep=caffeinate -t 360000

#If you're keep forgeting your aliases, here is quick script to see your list of aliases :
alias lsalias="grep -in --color -e '^alias\s+*' ~/mymacrc | sed 's/alias //' | grep --color -e ':[a-z][a-z0-9]*'"
