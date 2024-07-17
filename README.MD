# Modern Server Management with Ansible

This repository is intended for configuring Ansible within a lab environment and following the the blogpost [*Modern Server Management with Ansible*](https://pigeon-pelican-c93p.squarespace.com/config/pages/661c45d5f2d78e5316a6be62/content)

## Community Resources
Special thanks to Josh King for his presentations:
- [*Ansible 101: For the Windows SysAdmin*](https://www.youtube.com/watch?v=SqO2HkKep90) 
- [*Your Superpowered Windows Infrastructure Toolkit: Ansible, PowerShell, and Chocolatey*](https://www.youtube.com/watch?v=oKJtlEenaog&t=4664s) 

and to Jeremy Murrah for his presentation [*Ansible for the Windows Admin presentation*](https://youtu.be/ZI20Y10OKd0)
- [*Ansible for the Windows Admin GitHub repo*](https://github.com/murrahjm/PSSummit2019)


## Azure Arc

Update the Azure resource variables to reflect your own Azure lab environment.


## Chocolatey

To simplify this blogpost, please reference the fantastic [*Chocolatey Ansible Community Documentation*](https://docs.ansible.com/ansible/latest/collections/chocolatey/chocolatey/win_chocolatey_module.html) for package management and corresponding modules.


## Usage

Before running this playbook, run the following command to install the required modules

```bash
ansible-galaxy install -r collections/requirements.yml
```
