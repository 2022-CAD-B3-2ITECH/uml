# correction exercice 1

## Commentaires sur vos travaux

PS : **UC = cas d'utilisation**

1. Attention les associations << includes >> et << extends >> ne sont pas systématiques dans un diagramme de cas d'utilisation (il y en a pas toujours). Mettez-les uniquement si ça apporte de la valeur dans votre diagramme.
A consommer avec modération.

2. Attention à ne pas confondre détails par exemple "renseigner les informations" ou les conditions "date de naissance", "produits moins vendus" comme un cas d'utilisation.

3. Attention à bien séparer les cas d'utilisation et à les regrouper en thème lorsque c'est possible.

4. Posez vous bien la question de QUI(acteur) et QUOI(objectif  = cas d'utilisation)

5. Attention les commentaires pour apporter des précisions sur vos UC doivent être en dehors de la frontière de votre système. la frontière est délimité par le frame (grand carré ou rectangle qui contient uniquement les UC et le nom du sytème ou du package des US).

6. Les principaux acteurs doivent être situés à gauche du diagramme et si vous avez des acteurs sécondaires comme d'autres systèmes par exemple la banque, colissimo etc. Ils doivent être situés à droite, vous pouvez précisez le stéréotype << syst >> avant le nom pour qu'on puisse identifier leur nature.

7. Attention, UC connexion --->(include) créer compte signifie qu'à chaque que l'utilisateur doit se connecter il devra satisfaire obligatoirement le cas d'utilisation créer un compte. Autrement dit à chaque fois que je veux me connecter, je dois créer un compte. La meilleure solution est de ne pas mettre de relation include entre les 2 cas.
Dans la description de la connexion, dans les pré-conditions on pourra mettre que pour pouvoir se connecter, l'utilisateur doit avoir un compte dans le système donc qu'il s'est inscrit avant.

8. Attention, respectez bien les standars UML
- il n' y a pas de fleche entre une association entre acteur et un cas d'utilisation.
- include et extend, pointillé avec une flèche (pas un triangle blanc qui représente l'héritage).

9. UC parrainer suffit à lui tout seul pour représenter l'objectif du parranaige, vous n'avez pas besoin de rajouter un UC "envoyer le lien de parrainage" qui lui est un détail voir une fin cad solution. Pour rappel, dans un diagramme de cas d'utilisation, on modélise le système du point de vue de l'utilisateur par rapport à ses besoins et objectifs que le système doit satisfaire. Il est encore trop tôt pour parler de la solution.



## Rappels de besoins


Cadeau d'anniversaire pour un client qui effectue un achat le jour de son anniversaire.
Parrainage avec des récompenses pour le filleul et le parrain.
Offres promotionnelles des produits les moins vendues.

### Solutions de modélisation possibles

![uc_achat](img/uc_achat.png)
![parrain](img/uc_parrainage.png)
![promo](img/uc_promo.png)
