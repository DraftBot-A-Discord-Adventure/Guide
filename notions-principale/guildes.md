---
description: Un guide à propos des guildes.
---

# Guildes

Une guilde permet de réunir jusqu'à 6 personnes, afin de gagner des récompenses journalières de plus en plus conséquentes au fur et à mesure que chacun investira son argent dans l'achat d'expérience.

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
Il est impossible de renommer une guilde. Soyez donc certains de vouloir donner tel nom à votre guilde avant de valider la commande !
{% endhint %}

### Comment rejoindre une guilde ?

Tous les joueurs ayant atteint le niveau 10 peuvent rejoindre une guilde. Seul le chef de guilde et l'ainé peuvent inviter des joueurs dans leur guilde grâce à la commande `/invitationguilde`.

{% hint style="info" %}
Un salon destiné à recueillir les annonces de recrutement est disponible sur le discord du bot.
{% endhint %}

### Comment voir les statistiques d'une guilde ?

La commande `/guilde` permet d'afficher les informations de la guilde de la personne effectuant la commande.

Il existe également 3 options à cette commande:

* `guilde` Permet de voir les informations d'une guilde à partir de son nom.
* `utilisateur` Permet de voir les informations d'une guilde à partir du nom d'un de ses membres.
* `classement` Permet de voir les informations d'une guilde à partir du classement d'un de ses membres.

### Monter de niveau une guilde.

#### Dans le magasin de guilde

Dans le magasin de guilde, le joueur peut acheter de l'expérience pour sa guilde.\
Pour 1000 pièces,la guilde recevra aléatoirement entre 50 et 450 :star:et pour 15000 pièces elle recevra entre 750 et 6750 :star:.

#### Dans les récompenses quotidiennes

Toutes les 22h, il est possible d'utiliser la commande `/bonusjournalierguilde` afin d'obtenir une récompense qui peut être de l'expérience de guilde, de l'argent... Le type de récompense varie en fonction du niveau de votre guilde.&#x20;

| Niveau de la guilde | Un peu d'argent | Expérience de guilde | Expérience personnelle | Soin des altérations d'état | Gain de vie | Régénération totale de la vie | 350 d'argent | Badge guilde puissante | Badge guilde très puissante  | 5 friandises pour les familiers |
| ------------------- | --------------- | -------------------- | ---------------------- | --------------------------- | ----------- | ----------------------------- | ------------ | ---------------------- | ---------------------------- | ------------------------------- |
| 0-9                 | 97              | 0                    | 0                      | 0                           | 0           | 0                             | 0            | 0                      | 0                            | 3                               |
| 10-19               | 59.8            | 25                   | 5                      | 2                           | 5           | 0.2                           | 2.5          | 0                      | 0                            | 0.5                             |
| 20-29               | 57              | 25                   | 5                      | 2                           | 5.2         | 0.3                           | 5            | 0                      | 0                            | 0.5                             |
| 30-39               | 54.2            | 25                   | 5                      | 2                           | 5.4         | 0.4                           | 7.5          | 0                      | 0                            | 0.5                             |
| 40-49               | 46.4            | 25                   | 10                     | 2                           | 5.6         | 0.5                           | 10           | 0                      | 0                            | 0.5                             |
| 50-59               | 41.6            | 25                   | 10                     | 2.5                         | 5.8         | 0.6                           | 12.5         | 1                      | 0                            | 0.5                             |
| 60-69               | 37.8            | 25                   | 10                     | 2.5                         | 6           | 0.7                           | 15           | 2                      | 0                            | 1                               |
| 70-79               | 33.5            | 25                   | 10                     | 3                           | 6.2         | 0.8                           | 17.5         | 3                      | 0                            | 1                               |
| 80-89               | 24.2            | 25                   | 15                     | 3.5                         | 6.4         | 0.9                           | 20           | 4                      | 0                            | 1                               |
| 90-99               | 19.9            | 25                   | 15                     | 4                           | 6.6         | 1                             | 22.5         | 5                      | 0                            | 1                               |
| 100-149             | 29.7            |                      | 20                     | 6                           | 6.8         | 1.5                           | 25           | 10                     |                              |                                 |
| 150                 |                 | 0                    |                        |                             |             |                               |              |                        |                              |                                 |



{% hint style="danger" %}
Le badge guilde très puissante :mirror\_ball:ne dépend pas uniquement du niveau de la guilde mais également de son classement.Pour plus de détails,se référer à [Badges](../notions-avancees/badges.md) ou [PVE](../notions-avancees/pve.md).
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
* 5 soupes ultime

{% hint style="info" %}
Vous pouvez acheter de la nourriture dans le magasin de la guilde.
{% endhint %}

### Comment quitter une guilde ?

Il est possible à tout moment de quitter une guilde avec la commande `/quitterguilde`.\
Le chef de la guilde peut aussi utiliser la commande `/exclureguilde` pour expulser un membre de la guilde.
