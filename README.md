# wps-fonts
wps fonts download

https://askubuntu.com/questions/861588/wps-office-equation-editor

1. download fonts from here
2. create a folder sudo mkdir /usr/share/fonts/kingsoft
3. copy the contents of that download to folder in (2)
4. run sudo chown -R $USER:$USER /usr/share/fonts/kingsoft
5. run sudo chmod -R o+rw,g+rw /usr/share/fonts/kingsoft or leave as is if it has read and write permissions for owner (you)
6. run sudo fc-cache -vfs
