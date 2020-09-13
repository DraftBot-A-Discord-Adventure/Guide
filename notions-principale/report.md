# Rapports

Les rapports représentent la base du jeu. Il s'agit d'une petite description de ce qu'il est advenu du personnage contrôlé par le joueur depuis leur dernière interaction. Pour demander un rapport, le joueur doit utiliser la commande `!report`.

### Fonctionnement

Le personnage récolte environ 1 point à chaque minute et 1 d'argent toutes les 6 minutes. Il est impossible de récolter deux rapports à moins d'une heure d'intervalle. 

Il existe **2 types** de rapports :

* Les rapports dits **simples**. Positifs à tous les coups, ils ne nécessitent pas de choix de la part des joueurs et ne permettent pas le changement de statut, le gain d'item et la perte ou le gain de vie.
* Les **événements** \(ou évents\) sont souvent préférés grâce à l'interactivité qu'ils proposent. Ils ont plus de chance de subvenir lorsque le temps écoulé depuis le rapport précédent est conséquent.

{% hint style="warning" %}
Au bout de 16 heures et 40 minutes sans interaction, le personnage cesse de récolter des points et de l'argent.
{% endhint %}

La probabilité d'obtenir un rapport simple dépend du temps écoulé depuis le rapport précédent effectué par le joueur. Plus un joueur attend plus il a de chance que quelque chose qui necessite son attention soit survenu. Au bout de 6 heures et 40 minute la probabilité d'avoir un évènement est de 100%

Avant les 6h40 la probabilité peut se calculer ainsi :

$$
Probabilité = x /400
$$

Avec x le nombre de minutes écoulé depuis le précédent rapport.

{% hint style="danger" %}
La durée d'une altération d'état ne compte pas dans le temps écoulé
{% endhint %}

