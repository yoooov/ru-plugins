


Repo contains a new filemanager, but the additional plugins dont work yet, needed to be rewritten according to the new filemanager code.

# rutorrent-thirdparty-plugins
Plugins for ruTorrent web client, filemanager, fileshare, fileupload, mediastream

easily manage your shell files from rutorrent web interface

setup:  
edit filemanager/conf.php  
chmod 755 plugins/filemanager/scripts/*  

# fileshare plugin setup
- create a symlink to /fileshare/share.php outside the AUTH protected space (domain.com/noauth/share.php, cdn.domain.com/fshare.php, etc)
- edit fileshare/conf.php with that full domain path
