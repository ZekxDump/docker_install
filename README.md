# Docker_Setup
This script will help install any, or all, of Docker-CE, Docker-Compose, NGinX Proxy Manager,Navidrome and Portainer-CE.


## Using this script

1. Clone the repo ( `git clone https://github.com/ZekXtreme/docker_install.git` ), or copy / paste the code from the `setup.sh` file into a file on your server. 
2. Change the permissions of the .sh file to make it executable with.

`chmod +x <your-new-file>.sh`

3. Run the installer with

`./<your-new-file>.sh`

## Prompts from the script
First, you'll be prompted to select the number for your OS / Distro.  Currently I support CentOS 7 and 8, Debian 10 and 11, Ubuntu 18.04, 20.04, 22.04, Arch Linux. 

Next, you'll be asked to answer "y" to any of the four software packages you'd like to install. 
- Docker-CE
- Docker-Compose
- NGinx Proxy Manager
- Navidrome (music player))
- Portainer-CE
  - if you answer y to Portainer, you'll be asked another question

Do you want 
  1. full Portainer-CE with the web UI, or 
  2. just Portainer-agent (which you connect to another full portainer instance). 

Make that selection, and the install will continue.

Answering "n" to any of them will cause them to be skipped.

### NOTE
* You must have Docker-CE (or some version of Docker) installed in order to run any of the other three packages.
* You must have Docker-Compose installed in order to run NGinX Proxy Manager.

### Credits

[Original Repo](https://gitlab.com/bmcgonag/docker_installs) Full Credits to original author
