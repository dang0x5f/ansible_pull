# GIT CLONES
- git clone https://github.com/dang0x5f/scripts.git 
    (not necessary, configuration.yml already sets up $HOME/.local/bin)
- git clone https://github.com/dang0x5f/herbefork.git
- git clone https://github.com/dang0x5f/stfork.git
- git clone https://github.com/dang0x5f/ticker.git
- git clone https://github.com/dang0x5f/pomobar.git
- git clone https://github.com/dang0x5f/homepage.git

# TODO
- compile github binaries
- modify rc.conf, if necessary (e.g., kld_list="nvidia-modeset")
- setup ssh keys
- modify xmobarrc
- setup homepage path & config.py (.config/qutebrowser/config.py)
- if virtual machine, delete /usr/local/etc/X11/xorg.conf.d/driver-nvidia.conf and
    create /usr/local/etc/X11/xorg.conf.d/driver-scfb.conf with small change from 
    nvidia driver => Driver "scfb" , but make sure to delete nvidia driver too.
