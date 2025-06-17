---
description: Un guide à propos des guildes.
---

# Guildes

Une guilde permet de réunir jusqu'à 6 personnes, afin de gagner des récompenses journalières de plus en plus conséquentes à mesure de l'augmentation du niveau de la guilde (sauf les niveaux au-dessus de 100 qui sont essentiellement cosmétiques) . Le niveau maximum d'une guilde est 150.

### Comment créer une guilde ?

Créer une guilde est possible à l'aide de la commande `/creationguilde`. Cela vous coûtera 5000 pièces d'argent.

Vous pouvez ajouter une description à votre guilde avec la commande `/descriptionguilde`.

{% hint style="warning" %}
Le nom d'une guilde est unique, il doit respecter un certain nombre de règles :

* Utiliser au moins une lettre
* Ne pas mettre plus de 2 espaces consécutifs
* Les caractères spéciaux ne sont pas autorisés
* Entre 2 et 14 caractères
* Ne doit pas déjà être pris
{% endhint %}

{% hint style="danger" %}
Il est impossible de renommer une guilde. Soyez donc certain de vouloir donner tel nom à votre guilde avant de valider la commande !
{% endhint %}

### Comment rejoindre une guilde ?

Tous les joueurs ayant atteint le niveau 10 peuvent rejoindre une guilde. Seul le chef de guilde et l'aîné peuvent inviter des joueurs dans leur guilde grâce à la commande `/invitationguilde`.

{% hint style="info" %}
Un salon destiné à recueillir les annonces de recrutement est disponible sur le discord du bot.
{% endhint %}

### Comment voir les statistiques d'une guilde ?

La commande `/guilde` permet d'afficher les informations de la guilde de la personne effectuant la commande.

Il existe également 3 options à cette commande:

* `guilde` Permet de voir les informations d'une guilde à partir de son nom.
* `utilisateur` Permet de voir les informations d'une guilde à partir du nom d'un de ses membres.
* `classement` Permet de voir les informations d'une guilde à partir du classement d'un de ses membres.

### Monter de niveau une guilde:

#### Dans les mini-événements

Lors d'un mini-événement de ce [type](https://guide.draftbot.com/notions-avancees/mini-evenements#gagner-de-lexperience-de-guilde), vous pouvez gagner de l'expérience de guilde.

#### Dans le magasin de guilde

Dans le magasin de guilde, le joueur peut acheter de l'expérience pour sa guilde.\
Pour 1 000 pièces, la guilde recevra aléatoirement entre 50 et 450:star: et pour 15 000 pièces elle recevra entre 750 et 6750:star:.

#### Dans les récompenses quotidiennes

Toutes les 22h, il est possible d'utiliser la commande `/bonusjournalierguilde` afin d'obtenir une récompense qui peut être de l'expérience de guilde, de l'argent… Le type de récompense varie en fonction du niveau de votre guilde.&#x20;

{% hint style="info" %}
Les valeurs exprimées dans le tableau ci-dessous sont les pourcentages de probabilité de recevoir telle récompense de guilde selon son niveau.
{% endhint %}

| Niveau de la guilde | Un peu d'argent | Expérience de guilde | Expérience personnelle | Soin des altérations d'état | Gain de vie | Régénération totale de la vie | Avancement du temps | Badge guilde puissante | Badge guilde très puissante  | 5 friandises pour les familiers |
| ------------------- | --------------- | -------------------- | ---------------------- | --------------------------- | ----------- | ----------------------------- | ------------------- | ---------------------- | ---------------------------- | ------------------------------- |
| 0-9                 | 35              | 15                   | 0                      | 20                          | 5           | 0                             | 0                   | 0                      | 0                            | 25                              |
| 10-19               | 35              | 15                   | 1                      | 19                          | 5           | 0,2                           | 1                   | 0                      | 0                            | 23,8                            |
| 20-29               | 35              | 15                   | 2                      | 18                          | 5           | 0,3                           | 2                   | 0                      | 0                            | 22,7                            |
| 30-39               | 35              | 15                   | 4                      | 17                          | 5           | 0,4                           | 3                   | 0                      | 0                            | 20,6                            |
| 40-49               | 35              | 15                   | 6                      | 16                          | 5           | 0,5                           | 4                   | 0                      | 0                            | 18,5                            |
| 50-59               | 35              | 15                   | 8                      | 15                          | 5           | 0,6                           | 5                   | 1                      | 0                            | 15,4                            |
| 60-69               | 35              | 15                   | 10                     | 14                          | 5           | 0,7                           | 6                   | 1                      | 0                            | 13,3                            |
| 70-79               | 35              | 15                   | 15                     | 13                          | 5           | 0,8                           | 7                   | 1                      | 0                            | 8,2                             |
| 80-89               | 35              | 15                   | 20                     | 12                          | 5           | 0,9                           | 8                   | 1                      | 0                            | 3,1                             |
| 90-99               | 35              | 15                   | 20                     | 10                          | 5           | 1                             | 10                  | 1                      | 0                            | 3                               |
| 100-149             | 35              | 15                   | 20                     | 10                          | 5           | 1                             | 10                  | 1                      | 1                            | 2                               |
| 150                 | 40              | 0                    | 30                     | 10                          | 5           | 1                             | 10                  | 1                      | 1                            | 2                               |

{% hint style="danger" %}
Le badge guilde très puissante :mirror\_ball: ne dépend pas uniquement du niveau de la guilde mais également de son classement. Pour plus de détails, se référer à [Badges](../notions-avancees/badges.md) ou [PVE](../notions-avancees/iles-mysterieuses.md).
{% endhint %}

{% hint style="info" %}
Vous avez également une petite chance de trouver en plus un [familier](familiers.md).
{% endhint %}

### Mettre un aîné ?

Vous pouvez mettre un aîné pour votre guilde avec la commande `/aineguilde`. L'aîné pourra alors recruter des gens et modifier la description de votre guilde. Bien sûr si celui-ci vous énerve vous pouvez le retirer avec la commande `/supprimeraineguilde`.

### Voir le stockage de la guilde.

Vous pouvez afficher la nourriture stockée dans votre guilde avec la commande `/entrepotguilde`. Vous pouvez stocker jusqu'à :&#x20;

* 25 friandises
* 15 salades
* 15 viandes
* 5 soupes ultimes

{% hint style="info" %}
Vous pouvez acheter de la nourriture dans le magasin de la guilde.
{% endhint %}

### Comment quitter une guilde ?

Il est possible à tout moment de quitter une guilde avec la commande `/quitterguilde`.\
Le chef de la guilde peut aussi utiliser la commande `/exclureguilde` pour expulser un membre de la guilde.

{% hint style="info" %}
Si un chef de guilde part de sa guilde, le statut de chef est transféré à l'aîné de la guilde. S'il n'y a pas d'aîné, la guilde est dissoute.
{% endhint %}
