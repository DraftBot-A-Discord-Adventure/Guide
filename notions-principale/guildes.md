---
description: Un guide à propos des guildes.
---

# Guildes

Une guilde permet de réunir jusqu'à 6 personnes, afin de gagner des récompenses journalières de plus en plus conséquentes au fur et à mesure que chacun investira son argent dans l'achat d'expérience.

### Comment créer une guilde ?

Créer une guilde est possible à l'aide de la commande `!guildcreate <nom de guilde>`. Cela vous coûtera 5000 pièces d'argent.

Vous pouvez ajouter une description à votre guilde avec la commande `!guilddesc <description de ma super guilde>`.

{% hint style="warning" %}
Le nom d'une guilde est unique, il doit respecter un certain nombre de règles :

* Utiliser au moins une lettre
* Ne pas mettre plus de 2 espaces consécutifs
* Les caractères spéciaux ne sont pas autorisés
* Entre 2 et 14 caractères
* Ne doit pas déjà être pris
{% endhint %}

{% hint style="danger" %}
Il est impossible de renommer une guilde
{% endhint %}

### Comment rejoindre une guilde ?

Tous les joueurs ayant atteint le niveau 10 peuvent rejoindre une guilde. Seul le chef de guilde et l'ainé peuvent inviter des joueurs dans sa guilde grâce à la commande `!guildadd <@player>`.

{% hint style="info" %}
Un salon destiné à recueillir les annonces de recrutement est disponible sur le discord du bot.
{% endhint %}

### Voir les statistiques d'une guilde ? 

La commande `!guild` permet d'afficher les informations de la guilde de la personne effectuant la commande.

Il existe également deux façons alternatives d'utiliser cette commande:

* `!guild <nom de la guilde>` Permet de voir les informations d'une guilde à partir de son nom.
* `!guild <@mention>` Permet de voir les informations d'une guilde à partir de l'un de ses membres.

### Monter de niveau une guilde.

#### Dans la boutique 

Dans la boutique, l'expérience est représentée par l'icône :star: . \
Contre 1000 d'argent,  vous pourrez apporter aléatoirement entre 50 et 450 points d'expérience pour votre guilde. 

####  Dans les récompenses quotidiennes 

Tous les 22h, il est possible d'utiliser la commande `!guilddaily` afin d'obtenir une récompense qui peut être de l'expérience de guilde, de l'argent .... Le type de récompense varie en fonction du niveau de votre guilde.

| Niveau de la guilde | Un peu d'Argent | Expérience de guilde  | Expérience personnelle  | Soin des altérations d'état | Gain de vie | Régénération totale de la vie | 350 d'argent | Badge | 5 friandises pour les familiers |
| ------------------- | --------------- | --------------------- | ----------------------- | --------------------------- | ----------- | ----------------------------- | ------------ | ----- | ------------------------------- |
| 0-10                | 97              | 0                     | 0                       | 0                           | 0           | 0                             | 0            | 0     | 3                               |
| 10-20               | 59.8            | 25                    | 5                       | 2                           | 5           | 0.2                           | 2.5          | 0     | 0.5                             |
| 20-30               | 57              | 25                    | 5                       | 2                           | 5.2         | 0.3                           | 5            | 0     | 0.5                             |
| 30-40               | 54.2            | 25                    | 5                       | 2                           | 5.4         | 0.4                           | 7.5          | 0     | 0.5                             |
| 40-50               | 46.4            | 25                    | 10                      | 2                           | 5.6         | 0.5                           | 10           | 0     | 0.5                             |
| 50-60               | 41.6            | 25                    | 10                      | 2.5                         | 5.8         | 0.6                           | 12.5         | 1     | 0.5                             |
| 60-70               | 37.8            | 25                    | 10                      | 2.5                         | 6           | 0.7                           | 15           | 2     | 1                               |
| 70-80               | 33.5            | 25                    | 10                      | 3                           | 6.2         | 0.8                           | 17.5         | 3     | 1                               |
| 80-90               | 24.2            | 25                    | 15                      | 3.5                         | 6.4         | 0.9                           | 20           | 4     | 1                               |
| 90-100              | 19.9            | 25                    | 15                      | 4                           | 6.6         | 1                             | 22.5         | 5     | 1                               |
| 100                 | 29.7            | 0                     | 20                      | 6                           | 6.8         | 1.5                           | 25           | 10    | 1                               |

### Mettre un ainé ?

Vous pouvez mettre un ainé pour votre guilde avec la commande `!guildelder<@mention>`l'ainé pourra alors recruter des gens et modifier la description de votre guilde. Bien sur si celui-ci vous énerve vous pouvez le retirer avec la commande` !guildelderremove`.

### Quitter une guilde ? 

Il est possible à tout moment de quitter une guilde avec la commande `!guildleave`. \
Le chef de la guilde, peut aussi utiliser la commande `!guildkick`, pour expulser un membre de la guilde.
