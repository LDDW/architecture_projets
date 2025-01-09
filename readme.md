# Guide de Déploiement

## Configuration du vps

Pour lancer la configuration, exécutez :

```sh
ansible-playbook -i inventory/hosts.ini playbooks/install_vps.yml
```

## Ajouter les projets au vps

Pour ajouter des projets au vps, exécutez :

```sh
ansible-playbook -i inventory/hosts.ini playbooks/deploy.yml
```

## Problème avec la clé ssh

```sh
nano ~/.ssh/known_hosts  
```