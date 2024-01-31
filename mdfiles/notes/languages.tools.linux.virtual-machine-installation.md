---
id: hf9n3k1guskku3fwzhiysmv
title: Installing Linux on a virtual machine
desc: ''
updated: 1706629322238
created: 1706629322238
author: huscous
description: Quick write up just for reference
---
I must admit, I have done this before. But I figure it would be good to
have *some* sort of 'documentation' for this procedure (installing
Ubuntu server on MacOS).

1.  Install VMware Fusion (Workstation is a Linux/Windows specific)
  -   You will need a free licence that can be generated at VMware website
  -   use the following
      [document](https://communities.vmware.com/t5/VMware-Fusion-Documents/The-Unofficial-Fusion-13-for-Apple-Silicon-Companion-Guide/ta-p/2939907)
      in-case of any problems
1.  Download and install the live server iso from ubuntu (go through the
    installation guide)
  -   if the architecture on your Mac is Apple silicon, the guest OS must
      be compliant with that (can **not** run x64/x86 OS on the player)
1.  Run `sudo apt update -y` and then `sudo apt upgrade -y`
1.  Add your dot-files `.vimrc`, `.bashrc`, `.tmux.conf` etc
