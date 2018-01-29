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

Ce sont tous les chemins possibles et imaginables dans ton application rails. 
Plus concrêtement, les routes indiquent les pages accessibles avec le chemin précis, le type de requête qu'il est possible d'appliquer et les méthodes qui sont connues dans l'application.

#### 4. Les Bases de Données

Les bases de données ! Les grosses BDD ! Pour vulgariser, on pourrait comparer ça à de gros tableaux excel qui contiennent toutes les informations de l'application, c'est un peu la mémoire de l'application. Par exemple, c'est dans la base de donnée que seront les informations relatives à l'utilisateur (nom, prénom, email ...) lors de la création de son profil. 
L'intérêt des bases de données c'est qu'on peut manipuler les données qu'elles contiennent. A la fois pour s'en servir dans les programmes ou aussi pour les modifier. L'appel à ces données se fait avec des petites requêtes SQL ! 

#### 5. GET / POST 

Les copines GET / POST sont des méthodes qui ont chacune leur utilité. 
GET va permettre de récupérer des données du serveur, pour afficher une page par exemple. 
POST va permettre d'envoyer des données au serveur, par exemple soumettre un formulaire.

> On va manipuler ça toute la semaine, tu vas trop comprendre à la fin !

#### 6. Le concept de migration

So so, la migration est la modification de la BDD, c'est une modification à chaud avec rails, du temps réel si tu préfères !
Ca rend les modifications de la base hyper simple et ca :
> C'est trop cool ! 

#### 7. Les relations entre les models des BDD

Mariés pour la vie, ok je reformule. 

Les models interragissent avec la BDD, si on regarde le schéma du point 2, on voit que les models servent à faire le lien entre le controller et la BDD. Les models vont donc recevoir une requête du controller, ils iront chercher la bonne information qui pourra être retournée au controller. 

#### 8. Les fonctions du CRUD

Ok ca repart en acronyme, ce coup ci avec une liste non ordonnée ! 
- Create
- Read
- Update
- Detroy

Le CRUD permet de créer l'ensemble de ces fonctions. Il faut vraiment que je te l'explique ? Allez c'est bien parce que je suis cool ! Ce sont des méthodes qui pourront être appelées dans ton application rails
Create, ca permet de créer, un nouvel article par exemple. Avec read, tu vas pouvoir consulter une donnée, accéder à un article. Avec update, on est plutôt sur de la mise à jour, encore avec mon exemple d'article, tu pourras le modifier. Et enfin, l'arme de destruction massive : le destroy, pour tout péter, ou plus pour supprimer un objet, au hasard un article qui a été crée. 

---

### Voilà, c'est fini ! J'espère que tout est clair pour toi, je laisse à Felix le mot de la fin 
> Trop cool Seb, tu déchires grave !

---

Bisous !! :heart::heart:
Et mon slack c'est Seb si besoin !
