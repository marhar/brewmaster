# brewmaster
Synchronize homebrew installations between multiple computers

- Uses dropbox to synchronize metadata
- Puts manifests of each computer in $HOME/Dropbox/brewmaster

commands:

- homebrew report:  show what's waiting to be sync'ed
- homebrew snap:  capture the current state of your current box
- homebrew sync:  synchronize needed packages to your box, update all packages

To use:

- on computer A:  homebrew snap
- on computer B:  homebrew snap
- on both computers:  homebrew sync

To Do:

- synchronize font installation
