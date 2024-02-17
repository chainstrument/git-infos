

### Commande de base
 
initialiser \
```git init``` 

pour ajouter dans la boite \
```git add .``` 

pour commiter avec message\
```git commit -m "mon message" ``` 

pour envoyer sur le depot\
```git push ``` 


### La configuration

pour envoyer sur le depot\
```git config --list ``` 

pour definir le mail d'un utilisateur\
 ``` git config --global user.email sam@email.com ```

 Applique une configuration a tous le systeme d'exploitation(--global)\
 ```  git config --global user.email "your_email@example.com"  ``` 

Alias (ici lancer "git ci" pour lancer git commit)\
```git config --global alias.ci commit ```

### comparaison

pour comparer\
``` git diff ```

pour comparer avec les elments staged\
```git diff --staged ```

pour comparer avec les element sur le distant\
```git diff HEAD ```




 
