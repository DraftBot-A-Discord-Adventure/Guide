---
description: Un guide à propos des guildes.
---

# Guildes

Une guilde permets de réunir jusqu'à 6 personnes, afin de gagner des récompenses journalières de plus en plus conséquentes au fur et à mesure que chacun investira son argent dans l'achat d'expérience.

### Comment créer une guilde ?

Créer une guilde est possible à l'aide de la commande `!guildcreate <nom de guilde>`. 

Vous pouvez ajouter une description à votre guilde avec la commande `!guilddesc <descrption de ma super guilde>`.

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

Tous les joueurs ayant atteint le niveau 10 peuvent rejoindre une guilde. Seul le chef de guilde peut inviter des joueurs dans sa guilde grâce à la commande `!guildadd <@player>`.

{% hint style="info" %}
Un salon destiné à recueillir les annonces de recrutement est disponible sur le discord du bot.
{% endhint %}

### Voir les statistiques d'une guilde ? 

La commande `!guild` permet d'afficher les informations de la guilde de la personne effectuant la commande.

Il existe également deux façons alternatives d'utiliser cette commande:

* `!guild <nom de la guilde>` Permet de voir les informations d'une guilde à partir de son nom
* `!guild <@mention>` Permet de voir les informations d'une guilde à partir de l'un de ses membres

### Monter de niveau une guilde.

#### Dans la boutique 

Dans la boutique, l'expérience est représentée par l'icône⭐.   
Contre 1000 d'argent,  vous pourrez apporter aléatoirement entre 50 et 450 points d'expérience pour votre guilde. 

####  Dans les récompenses quotidiennes 

Tous les 22h, il est possible d'utiliser la commande `!guilddaily` afin d'obtenir une récompense qui peut être de l'expérience de guilde, de l'argent .... Le type de récompense varie en fonction du niveau de votre guilde.

| Niveau de la guilde | Un peu d'Argent | Expérience de guilde  | Expérience personnelle  | Soin des altérations d'état | Gain de vie | Régénération totale de la vie | 350 d'argent | Badge |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0-10 | 100% | 0% | 0% | 0% | 0% | 0% | 0% | 0% |
| 10-20 | 59.8% | 15% | 5% | 10% | 5% | 0.2% | 5% | 0% |
| 20-30 | 55.7% | 15% | 5% | 10% | 6% | 0.3% | 8% | 0% |
| 30-40 | 52.6% | 15% | 5% | 10% | 6% | 0.4% | 11% | 0% |
| 40-50 | 49.5% | 10% | 10% | 10% | 6% | 0.5% | 14% | 0% |
| 50-60 | 45.4% | 10% | 10% | 10% | 6% | 0.6% | 17% | 1% |
| 60-70 | 41.3% | 10% | 10% | 10% | 6% | 0.7% | 20% | 2% |
| 70-80 | 37.2% | 10% | 10% | 10% | 6% | 0.8% | 23% | 3% |
| 80-90 | 33.1% | 15% | 5% | 10% | 6% | 0.9% | 26% | 4% |
| 90-100 | 20% | 24% | 5% | 10% | 6% | 1% | 29% | 5% |
| 100 | 20.5% | 0% | 20% | 10% | 6% | 1.5% | 32% | 10% |

### Quitter une guilde ? 

Il est possible à tout moment de quitter une guilde avec la commande `!guildleave`.   
Le chef de la guilde, peut aussi utiliser la commande `!guildkick`, pour expulser un membre de la guilde.

