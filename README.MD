# Configuration backup in Ubuntu
This is the conf of various program in Ubuntu, I aggregate these configuration into one folder by hard link(`cp -l`).
### Sublime Text 3
##### Preferences.sublime-settings
- path: `~/.config/sublime-text-3/Packages/User`
- also form menu: `preferences -> setting-user`
- this is the main config of sublime

##### user.sublime-commands
- path: `~/.config/sublime-text-3/Packages/User`
- I create it manually, it controls the commands in palette

### .bashrc
- path: `~`

### .vimperatorrc
- path: `~`

### aria2.conf 
- path: `~/.aria2`
- when this file is created, you just need to run `aria2`, and it will read this config automatically.
