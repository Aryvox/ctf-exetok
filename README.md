# ExeTok - Gestionnaire de Secrets

Un système simple de gestion de secrets avec authentification.

## Installation

```bash
git clone exetok
cd exetok
pip install -r requirements.txt
```

## Utilisation

Le programme offre plusieurs commandes :

1. Ajouter un secret :
```bash
python main.py -u admin -p admin123 -a add -k mon_secret -v "valeur_secrete"
```

2. Récupérer un secret :
```bash
python main.py -u admin -p admin123 -a get -k mon_secret
```

3. Créer une sauvegarde :
```bash
python main.py -u admin -p admin123 -a backup
```

4. Afficher l'aide :
```bash
python main.py --help
```

## Identifiants par défaut
- Utilisateur : admin
- Mot de passe : admin123

## Sécurité
Ce projet est uniquement à des fins de démonstration.
Ne pas utiliser en production. "# Exetok" 
"# ctf-exetok" 
"# ctf-exetok" 
