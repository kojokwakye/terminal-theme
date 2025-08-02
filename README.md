install this theme on my new ubuntu pc

export  
`terminal-theme.dconf` or  
`night-owl.dconf` from repo to pc's home directory

install with this code
> `dconf load /org/gnome/terminal/legacy/profiles:/ < terminal-theme.dconf`


## clean up file 
Removes old revisions of snaps
> `sudo bash clean-up.sh`

> `dconf load /org/gnome/terminal/legacy/profiles:/ < terminal-theme.dconf`   
> `dconf load /org/gnome/terminal/legacy/profiles:/ < night-owl.dconf`

## reset foliate epub  
`dconf reset -f /com/github/johnfactotum/Foliate/`

## disable the new notification badges 
`gsettings set org.gnome.shell.extensions.dash-to-dock show-icons-emblems false`


## enable 'minimize on click'  
`gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'`
