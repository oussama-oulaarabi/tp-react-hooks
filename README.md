# TP React Hooks - Application de Gestion de Produits

Ce TP a pour objectif de mettre en pratique l'utilisation des Hooks React (useState, useEffect, useContext) ainsi que la création de Hooks personnalisés.

## Installation et configuration initiale

1. Cloner le dépôt :
```bash
git clone https://github.com/pr-daaif/tp-react-hooks.git
cd tp-react-hooks
```
![](pictures/clone.png)
2. Créer votre propre dépôt sur Github et changer le remote :
```bash
# Supprimer le remote origine
git remote remove origin

# Ajouter votre nouveau remote
git remote add origin https://github.com/[votre-username]/tp-react-hooks.git

# Premier push
git push -u origin main

```
![](pictures/removeOrigine.png)
![](pictures/addRemote.png)
![](pictures/push.png)
3. Installer les dépendances :
```bash
npm install

```
![](pictures/npm-install.png)
4. Lancer l'application :
```bash
npm start

```
![](pictures/start.png)
## Instructions pour le TP

Pour chaque exercice :
1. Lisez attentivement l'énoncé
2. Implémentez la solution
3. Testez votre implémentation (pensez à faire des copies d'écran)
4. Mettez à jour la section correspondante dans ce README avec :
   - Une brève explication de votre solution
   - Des captures d'écran montrant le fonctionnement
   - Les difficultés rencontrées et comment vous les avez résolues
5. Commitez vos changements avec un message descriptif

### Exercice 1 : État et Effets 
#### Objectif : Implémenter une recherche en temps réel

- [ ] 1.1 Modifier le composant ProductSearch pour utiliser la recherche
- [ ] 1.2 Implémenter le debounce sur la recherche
- [ ] 1.3 Documenter votre solution ici


Etat de recherche avec debounce juste après l'insertion et après 1 second: 

![](pictures/before.png)
![](pictures/after.png)


### Exercice 2 : Context et Internationalisation
#### Objectif : Gérer les préférences de langue

- [ ] 2.1 Créer le LanguageContext
- [ ] 2.2 Ajouter le sélecteur de langue
- [ ] 2.3 Documenter votre solution ici

_Votre réponse pour l'exercice 2 :

francais
![](pictures/francais.png)

anglais

![](pictures/anglais.png)
### Exercice 3 : Hooks Personnalisés
#### Objectif : Créer des hooks réutilisables

- [ ] 3.1 Créer le hook useDebounce
- [ ] 3.2 Créer le hook useLocalStorage
- [ ] 3.3 Documenter votre solution ici

_Votre réponse pour l'exercice 3 :_
```
[] Hook useDebounce:
Ajout d’un délai avant la mise à jour d’une valeur.

[] Hook useLocalStorage:
Permet de stocker des valeurs dans localStorage pour éviter la perte de données après un rafraîchissement.
```

### Exercice 4 : Gestion Asynchrone et Pagination
#### Objectif : Gérer le chargement et la pagination

- [ ] 4.1 Ajouter le bouton de rechargement
- [ ] 4.2 Implémenter la pagination
- [ ] 4.3 Documenter votre solution ici

_Votre réponse pour l'exercice 4 :_
Gérer le chargement et la pagination
```
Ajout d’un bouton de rechargement :
Un bouton Recharger permet de relancer l’appel API.

Implémentation de la pagination :
Gestion des pages avec nextPage et previousPage.
```

```
pagination
```
![](pictures/pagination.png)
```
reload
```
![](pictures/reload.png)
## Rendu

