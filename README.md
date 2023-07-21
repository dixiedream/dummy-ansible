# Ansible

Playbooks created for basic Ubuntu based distro setup and assistance.

## Requirements

Install `git` and `ansible`

**WARN**
For some strange reason on Pop!\_OS the Ansible version shipped in the repo is not as updated as Debian version.
Please install Ansible through [official documentation](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html#installing-ansible-on-ubuntu)

## Usage

### A few info
In the scripts folder there are different launching options depending on your setup... here are some clarification:

- `baseInstall.sh` Install a very resource friendly [Xorg](https://wiki.archlinux.org/title/Xorg) environment (tested on **Archlinux**, **Debian testing**, **Artix Linux**)

### Steps
1. Run one of the scripts in `scripts`, for example `sh ./scripts/baseInstall.sh`
