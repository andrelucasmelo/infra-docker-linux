## Infra for Docker on Linux
repo: infra-docker-linux

### Description:
If you needed a docker instance to make tests or simply learning to use docker, you found now! We mounted a infrastructure based on virtual machine with Xenial Ubuntu Linux with docker installed. To use this package, you must have a lastest version of Hashicorp Vagrant and Virtual Box installed in your computer. After this, you clone this repository and run "vagrant ssh docker1" command on same directory. To access your linux docker instance you can use "vagrant ssh dck1"

### System Requirements
- CPU with 4 cores
- 8 GB RAM
- 10 GB of Free Disk Space

### Software Requirements
- Vagrant 2.0 or upper versions
- Virtual Box 6.0.0 or upper versions

### How to use it ?
- Clone the git repository.
- Install Virtual Box and Vagrant in your computer.
- On repository folder, run "vagrant up" command.
- After Vagrant and Ansible process, run "vagrant ssh docker1" command.
