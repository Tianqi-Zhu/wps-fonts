# wps-fonts
wps fonts download

https://askubuntu.com/questions/861588/wps-office-equation-editor

download fonts from here
create a folder sudo mkdir /usr/share/fonts/kingsoft
copy the contents of that download to folder in (2)
run sudo chown -R $USER:$USER /usr/share/fonts/kingsoft
run sudo chmod -R o+rw,g+rw /usr/share/fonts/kingsoft or leave as is if it has read and write permissions for owner (you)
run sudo fc-cache -vfs
