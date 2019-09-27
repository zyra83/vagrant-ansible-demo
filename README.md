# Vagrant pour tester ses playbooks Ansible

## Marche à suivre

Créer le [Vagrantfile](Vagrantfile).

Il contient la configuration de la VM avec son provisionner. En l'occurence [le playbook](playbook.yml).

Dans ce playbook, cibler toutes les machines.

## Execution

```bash
# premier lancement de la machine, télécharge la box et crée la VM.
vagrant up

# forcer un provisionning (par exemple suite à une mise à jour du playbook)
vagrant provision

# detruire la VM
vagrant destroy

# rentrer dans le VM pour faire joujou à la main
vagrant ssh

```
