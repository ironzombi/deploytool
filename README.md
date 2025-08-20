# Deploy-tool

Copies data from SRC to DST while making a backup.

---
## Usage
    --src DIR
    --dst DIR
    --backup DIR
    --dry-run
    --verbose
    --prune
    --force
    --file-type EXT
    -h --help

deploytool --src /home/user1/code/site-code --dst /var/www/webpage --file-type .html 
you have to update the DEFAULTS in deploytool or pass the --src --dst as above.
the default locations are ./src and ./dst
the default backup location will be in the current working directory.
### Install
```
./install.sh

Installs the script deploytool to your home drive $HOME/.bin $HOME/bin
also adds manpage, which will require sudo access.
```
#### Disclaimer
yes this is useless, I get it.
