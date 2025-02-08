# 0-iam_betty

Ce script change l'utilisateur actuel pour l'utilisateur `betty`.

## Utilisation

Ce script utilise la commande `su betty` pour effectuer le changement d'utilisateur. 

- Le script doit être exécuté avec des privilèges suffisants pour permettre le changement d'utilisateur.
- Assurez-vous que l'utilisateur `betty` existe sur le système.

## Contenu du script

```bash
#!/bin/bash
su betty
