# Debian Docker install

This Ansible Playbook follows the instructions for installing Docker on Debian 10.  https://docs.docker.com/engine/install/debian/

## How To Use

Edit the `inventory.ini.example` and rename to `inventory.ini`.

Within this file, replace the IP address `10.0.0.1` to the IP address of your Debian installation where you want to install Docker.  Likewise, replace the values for `ansible_user` and any other values you need to connect Ansible to your target host.

After you have specified the connection information for Ansible, run the following to install Docker on the target machine.

```bash
`ansible-playbook site.yaml`
```
