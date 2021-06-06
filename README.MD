#GIVE USER MICROCONTROLLER UPLOAD PERMISSION BY ADDING TO GROUP uucp

check the group ls -l /dev/ttyUSB0

sudo gpasswd -a user group
