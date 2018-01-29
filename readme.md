# Bienvenue à toi !

### Petite citation pour te mettre en joie

> C'est trop cool ici, tu vois voir j'explique pleins de trucs, concepts, machins hyper trop stylés ! Parce que moi j'adore trop Rails, je t'envoie du :heart: 
> (Felix)

### Allez c'est parti pour une belle liste, de type ordonnée, de ce qu'on va voir ensemble : 
1. La différence entre un site statique et un site dynamique
2. Le MVC
3. Les routes 
4. Les Bases de Données
5. GET / POST
6. Le concept de migration
7. Les relations entre les models des BDD
8. Les fonctions du CRUD

> Désolé si le programme n'est pas hyper sexy mais tu vas voir, on va quand même s'amuser ! Oui tu viens de le comprendre, Felix sera parmi nous durant l'ensemble de ce readme :boom: c'est cadeau, je sais que tu n'en as pas assez eu hier ... 

#### 1. La différence entre un site statique et un site dynamique

Site statique | Site dynamique
------------ | -------------
Statique | Dynamique

Voilà j'ai placé le skill du tableau, next
Bon ok, un site statique ne tient pas compte de l'utilisateur, il affichera toujours les mêmes données, sans personnalisation. Alors qu'un site dynamique va récupérer pleins d'info sur toi et trop cool après il pourra te dire "Bonjour #{user}" mais surtout il pourra te targeter avec des pubs parfaites pour que tu craques !

> Trop cool le web !

#### 2. Le MVC

Hi le MVC, alors là j'insère une belle image et centrée s'il vous plait !

<p align="center"> 
<img src="http://french.railstutorial.org/images/figures/mvc_detailed-full.png">
</p>

Alors le MVC, vient de l'acronyme : Model View Controller. Avec mes mots, c'est le modèle appliqué pour les interactions backend d'une application rails. 
On va commencer par le **controller**, qui est la pièce maitresse du modèle. Il coordonne l'ensemble des opérations, lorsque l'utilisateur va faire une requête, le router va orienter la requête sur le **controller** qui appelera la méthode correspondante, il intéragira ensuite avec le **model** qui ira chercher les bonnes infos dans la base de donnée et renverra le résultat directement à notre pote le **controller**. Ce même **controller** enverra une requête au **view** qui lui retournera la page html (avec un peu de ruby dedans) qui va bien. Enfin toujours ce fameux **controller** renverra le tout à notre gentil utilisateur pour qu'il ait une belle page personalisée !

> Trop puissant le controller ! 

#### 3. Les routes 

Ce sont les chemins 


---
