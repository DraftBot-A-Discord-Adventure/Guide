# Rapports

Les rapports représentent la base du jeu. Il s'agit d'une petite description de ce qu'il est advenu du personnage contrôlé par le joueur depuis leur dernière interaction. Pour demander un rapport, le joueur doit utiliser la commande `/rapport`.

### Interface :

La commande `/rapport` possède 4 états différents :

* Le joueur est en train de voyager.
* Le joueur est victime d'une altération d'état.
* Le joueur réalise un évènement.
* Le joueur réalise un mini-évènement.

![Interface de la commande report quand le joueur est en train de voyager](../.gitbook/assets/RapportPrésentation.png)

### Mini-Évènements :

Le joueur met environ 9 minutes et 45 secondes à réaliser un trajet entre deux mini-évènements.

![Un exemple de mini-évènement](../.gitbook/assets/RapportMiniEvent.png)

Un mini-évènement est souvent une simple phrase. Il existe cependant des mini-évènements qui peuvent vous faire gagner des objets, de la vie ou encore de l'argent.

{% hint style="info" %}
Chaque mini-évènement rapporte au joueur une quantité de points diminuant à chaque nouveau mini-évènement. Ces points sont ajoutés au nombre de points remportés lors de l'évènement suivant.
{% endhint %}

![Une fois le mini-évènement passé, il apparaît sur l'interface de voyage](../.gitbook/assets/RapportTemps.png)

Vous pouvez voir le nombre de points récoltés avec les mini-évènements ainsi que le temps d'attente avant le prochain.

### Évènements :

Les évènements sont le cœur du jeu, le joueur doit simplement réagir à une situation à choix multiples à l'aide des réactions Discord. En fonction de son choix, différentes issues surviennent.

![Un exemple d'évènement](../.gitbook/assets/RapportEvent.png)

Ici, le joueur possède 5 choix différents : les 4 choix de réaction mais également le choix de ne rien faire.

{% hint style="info" %}
Le non-choix ("Ne rien faire") se déclenche automatiquement au bout de 2 minutes en l'absence de choix explicite. Il est possible de forcer ce non-choix en ajoutant manuellement la réaction :end: (:end:) au texte de l'évènement.
{% endhint %}

{% hint style="success" %}
Dans certains évènements, ne rien faire est le meilleur choix ! (Dans d'autres c'est le pire.)
{% endhint %}

Une fois un choix réalisé par le joueur, ce dernier peut cliquer sur une réaction (ou attendre 2 minutes), ce qui déclenche l'issue.

![Un exemple d'issue](../.gitbook/assets/RapportEventSortie.png)

### Destination :

Après un évènement, le joueur est amené à choisir une destination. Il n'est pas possible pour un joueur de faire un retour sur ses pas (sauf si c'est le seul choix possible).

![Exemple de choix de destination](../.gitbook/assets/choix-destination.png)

Le temps indiqué entre parenthèses est le temps de voyage pour parvenir jusqu'au lieu, un point d'interrogation signifie que le temps est inconnu. Dans un 15% des cas, le bot choisit automatiquement la destination du joueur.

![Voici votre information sur votre destination](../.gitbook/assets/destination-choisie.png)

###
