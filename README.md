# Setting up dev env
## Installation of Vagrant, VirtualBox and Ruby
### vagrant command
- `vagrant init` to create .Vagrantfile at default directory
- `vagrant up` to launch the vm 
- `vagrant destroy` to delete everything
- `vagrant reload` to reload any new instruction in our .vagrantfile
- `vagrant ssh` to enter VM

For a full set of commands, simply type `vagrant`.
```commandline
Usage: vagrant [options] <command> [<args>]

    -h, --help                       Print this help.

Common commands:
     autocomplete    manages autocomplete installation on host
     box             manages boxes: installation, removal, etc.
     cloud           manages everything related to Vagrant Cloud
     destroy         stops and deletes all traces of the vagrant machine
     global-status   outputs status Vagrant environments for this user
     halt            stops the vagrant machine
     help            shows the help for a subcommand
     init            initializes a new Vagrant environment by creating a Vagrantfile
     login
     package         packages a running vagrant environment into a box
     plugin          manages plugins: install, uninstall, update, etc.
     port            displays information about guest port mappings
     powershell      connects to machine via powershell remoting
     provision       provisions the vagrant machine
     push            deploys code in this environment to a configured destination
     rdp             connects to machine via RDP
     reload          restarts vagrant machine, loads new Vagrantfile configuration
     resume          resume a suspended vagrant machine
     snapshot        manages snapshots: saving, restoring, etc.
     ssh             connects to machine via SSH
     ssh-config      outputs OpenSSH valid configuration to connect to the machine
     status          outputs status of the vagrant machine
     suspend         suspends the machine
     up              starts and provisions the vagrant environment
     upload          upload to machine via communicator
     validate        validates the Vagrantfile
     version         prints current and latest Vagrant version
     winrm           executes commands on a machine via WinRM
     winrm-config    outputs WinRM configuration to connect to the machine

For help on any individual command run `vagrant COMMAND -h`
```

- use `apt-get` package manager in Linux (for mac `homebrew` or simply `brew`).
- To use the command in `admin` mode we can use `sudo before the command
- `sudo apt-get upgrade -y`
- `ping www.bbc.co.uk`
- `sudo apt-get install <package-name>`
- To work in as an admin `admin mode` at all times (not recommended) `sudo -su` and you'll land in admin mode.
- we will install nginx in our guest machine/VM.Ubuntu 16.04
- Launch the default nginx page in host 
