# Nom du Projet :
UnrealPlateformer

## Description du projet :
Faire un jeu de plateforme 3D avec Unreal Engine.

## Membres du Groupe :
- Yoann Meier
- Alexandre Babich

## 12/10/2023
Aujourd'hui, j'ai tout d'abord installer Unreal Engine sur le disque pour ce cours.<br>
Ensuite, j'ai suivis un tutoriel (https://www.youtube.com/watch?v=RTvTIbCpODU) sur unreal engine et sur la création d'un plateformer. <br> 
J'ai crée un personnage et fait 2 animations en BluePrint. <br>
Je continuerai le tuto la semaine prochaine.

## 19/10/2023
Aujourd'hui, j'ai continué le tutoriel. J'ai fait le saut et également se baisser.<br>
Mais lors de la pause, unreal a crash et j'ai perdu certaine choses. <br>
J'ai du les refaires mais à la fin du saut, le personnage ne retombe plus sur le sol. <br>
Je réglerais ca la semaine prochaine.

## 02/11/2023
Aujourd'hui, j'ai continué à suivre le tutoriel. Maintenant, n plus de ce baisser, mon personnage peut faire une roulade. <br>
Nous avons décidé de temporairement ignorer le bug lorsque l'on retombe sur le sol et de le laisser pour plus tard.<br>
Ensuite, j'ai commencé à apprendre à créer une map grâce à un tutoriel sur youtube (https://www.youtube.com/watch?v=rAVPEGnyatk)  (34:30 min)<br>
J'ai notamment fait que lorsque le personnage tombe de la plateforme et touche le sol, il revient à la position de départ.
La semaine prochaine, je vais continué ce tutoriel.

## 09/11/2023
Aujourd'hui, j'ai finis le tuto d'unreal engine. J'ai créer des plateformes en mouvement, crée une clé pour déverouiller une porte et ajouter des pièces.<br>
Ensuite, j'ai commencer à faire des ajouts par moi même : j'ai fait une gemme (similaire au pièces) et j'ai fait en sorte qu'il faut avoir la clé et une gemme pour rentrer.<br>
J'ai donc bien avancer aujourd'hui.

## 16/11/2023
Aujourd'hui, j'ai fais un projet à partir de rien. J'ai fait le personnage, ses déplacements, et son saut. Lorsqu'il tombe dans le vide, il réapparait au spawn.<br>
Ensuite, j'ai fait une balle que l'on peut tirer pour toucher un but de foot.<br>
Néanmoins, cela ne marche pas encore et je vais régler cela la semaine prochaine.

## 23/11/2023
Aujourd'hui, j'ai finis la balle qui maintenant active la physique du but lorsqu'il y a collision.<br>
Ensuite, j'ai fait en sorte que la balle réaparaisse à sa position d'origine lorsque son z est inférieur à -500.<br>
Le mur disparait lui à -500.<br>
Après, j'ai fait le sprint du personnage et j'ai commencé un piège qui fait tomber 2 bûches sur le personnage.<br>
je continurai la prochaine fois.

## 30/11/2023
Aujourd'hui, j'ai finis le piège. Maintenant, lorsque le personnage touche une collision invisible, deux cylindre tombes sur lui et le tue s'il se fait toucher.<br>
Sinon, les cylindres retournent à leurs places. J'ai remarqué que si je tire la balle sur la collision, les cylindres tombes.<br>
Plus tard, nous pourrons faire en sorte que les cylindes tombent tellement vite que le joueur va forcement mourrir, même avec le sprint.<br>
Nous pourrons alors tirer avec la balle qui détruira le piège.<br>
La prochaine fois, je ferai tomber des rochers, ce qui sera utile avec la montagnes que fait Alexandre. 

## 07/12/2023
Aujourd'hui, j'ai totalement finis le piège. Maintenant, lorsque les cylindres se touchent ils tombent. <br>
Ensuite, j'ai fait un item qui augmente le jump pendant 4 secondes et une plateforme où lorsque l'on saute en étant dessus, le saut est également augmenter.<br>
Ensuite, j'a commencer la chute de pierre. <br>
Je finirai la semaine prochaine.<br>

## 14/12/2023
Aujourd'hui, j'ai totalement finis l'éboulement. Maintenant, lorsque le joueur touche un collision invisible, l'éboulement se déclanche et les pierres repoussent le personnage. <br>
Ensuite, j'a fais une plateforme qui baisse lorsque le joueur est dessus et puis remonte jusqu'à sa position initiale lorsque le joueur quitte la plateforme.<br>
Et puis, j'ai fais une plateforme qui se détruit soit lorsque le joueur est dessus, ou lorsque le joueur saute de la plateforme selon un booléean.
La prochaine fois, je ferai un ennemi immobile qui nous tire dessus en suivant ce tuto : https://www.youtube.com/watch?v=RKHM862PWKU.

## 18/01/2024
Aujourd'hui, j'ai fais des animations : un double saut, une roulade et s'accroupir. J'ai suivit des tutos et je n'ai eu aucun problème.<br>
Nous avons également commencer à rassembler les projets.La prochaine fois, je vais essayer d'ajouter sa map dans mon projet.<br>

## 25/01/2024
Aujourd'hui, avons essayer de rassembler les projets : nous avons essayer de push le projet d'alexandre, sans succès à cause du nombre de fichier et de leurs tailles.<br>
Nous nous avons essayer de copier le niveau et la map dans mon projet, sans succès.<br>
La semaine prochaine, alexandre va utiliser mon travail et l'ajouter sur son projet, et je vais développer ce dont il aurait besoin.

## 01/02/2024
Aujourd'hui, Alexandre a continué à créer le jeu et a ajouter des éléments que j'ai précédement créé.<br>
Pour ma part, j'ai corrigé les bugs créer par l'ajout de mes fonctionnalités dans son projet.<br>
J'ai également ajouter des messages qui apparaissent sur l'écran lorsque le joueur doit faire une action précise (ex: Appuie sur E).<br>
J'ai aussi commencer la documentation technique et Alexandre a finit le poster.<br>
La semaine prochaine, nous allons continuer la documentation et d'améliorer le niveau créer par Alexandre.

## 08/02/2024
Aujourd'hui, j'ai aidé Alexandre à ajouter des fonctionnalités que j'ai déjà développé dans son projet. Le checkpoint en fait partie.<br>
Nous avons passé du temps à essayer de comprendre pourquoi le checkpoint nous faisais réapparaitre au 0 0 0. En fait, le checkpoint nous fais réapparaitre un peu dans une texture ce qui provoque le bug.<br>
J'ai donc fais en sorte que le checkpoint nous fasse apparaitre un peu au dessus du checkpoint.<br>
J'ai également ajouté une musique dans le jeu et une flèche pour montrer la direction du prochain checkpoint.<br>
La semaine prochaine nous allons nous concentrer sur la documentation intermédiaire à rendre et ajouter de nouveaux éléments au jeu.

## 15/02/2024
Aujourd'hui, nous avons continué le projet et finit la documentation temporaire. Nous avons finit la documentation technique et la documentation utilisateur.<br>
Dans le projet, nous avons ralongé la durée du niveau et ajouter quelques fonctionnalité au joueur : un sprint, une roulade, et la possibilité de se baisser.<br>

## 29/02/2024
Aujourd'hui, nous avons continué le projet. Alexandre a continué la création du niveau.<br>
Moi, j'ai fais un écran de fin lorsque tous les checkpoints ont été pris et un timer afficher dans le jeu.<br>
J'ai aussi régler un bug de l'item de boost de saut.<br>

## 07/03/2024
Aujourd'hui, nous avons enfin réussi à build le projet pour obtenir un éxécutable ! Nous avons suppris les textures provoquant des erreurs.<br>
J'ai également ajouté dans le projet final le timer, le nombre de point de vie et l'écran de fin.<br>
Nous avons aussi préparé le PowerPoint pour la semaine prochaine et finit la documentation.<br>
C'est donc la fin de ce très bon projet, très instructif et très intéressant.