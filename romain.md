# Liste des commandes de Romain 


## Préparation 

- git clone https://github.com/Ch0cap1csou/projet-git
- cd projet-git/
- ls
- git config --global user.email "rbbarnerias@gmail.com"
- git config --global user.name "Itadakii"
- git checkout -b romain
- touch romain.md
- nano romain.md
- git add romain.md
- git commit -m "ajout de l'historique des commandes faites"
- git push origin romain

## Commandes du projet 

- nano index.html
- git add index.html 
- git commit -m "site web v1"
- git push origin romain
- nano index.html
- git add index.html
- git commit -m "html v2"
- git push origin romain
- nano index.html
- git add index.html
- git commit -m "html v3"
- git push origin romain

## Correction des erreurs et ajout version finale 

- git pull origin romain 
- git config pull.rebase false
- ls
- rm index.html.save 
- git pull origin romain 
- ls
- git add index.html
- git commit -m "html v4"
- git rm index.html.save 
- git commit -m "html v4"
- git push origin romain
