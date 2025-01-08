# Guide de Déploiement

## Configuration du vps

Pour lancer la configuration, exécutez :

```ssh
ansible-playbook -i inventory/hosts.ini playbooks/install_vps.yml
```

## Ajouter les projets au vps

Pour ajouter des projets au vps, exécutez :

```ssh
ansible-playbook -i inventory/hosts.ini playbooks/deploy.yml
``