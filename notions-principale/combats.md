---
description: Un guide à propos des combats.
---

# Combats

Une fois que votre personnage a atteint le **niveau 8**, vous débloquez la capacité de faire des **combats**. Ce guide vous permet de comprendre les bases.

### Avant de commencer

Pendant un combat, vous devez impérativement prendre en compte les statistiques suivantes :

* :zap: Énergie
* :dagger: Points d'attaque
* :shield: Points de défense
* :rocket: Points de vitesse

{% hint style="info" %}
Vous trouverez plus d'informations sur les statistiques dans le guide consacré au [profil](profile.md).
{% endhint %}

### Types de combats

#### Les combats normaux

Un combat normal peut être lancé avec la commande `!fight`. La variante `!fight <@user>` permet de défier un utilisateur en particulier. Si vous n'êtes pas l'initiateur du combat et que vous n'avez pas d'altération d'état, vous pouvez accepter le combat avec la réaction :white\_check\_mark:. Dans ce type de combat, le gagnant remporte des :medal: points de classement et le perdant en perd.

#### Les combats amicaux

Les combats amicaux sont similaires aux combats normaux, à la seule différence que vous ne perdez ni ne gagnez pas de points. La commande pour lancer un combat amical est `!friendlyfight` .

### Déroulement d'un combat

Le combat est basé sur un système de tour par tour. À chaque tour, vous aurez le choix entre 6 actions :

| Action                                                                               | Description                                                                                                                                                                                                                                 |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| :crossed\_swords: Attaque simple                                                     | Attaque classique, les chances de réussite et les dégâts sont moyens.                                                                                                                                                                       |
| :dagger: Attaque rapide                                                              | Attaque moins puissante mais qui ignore l'armure. Sa puissance diminue si on l'utilise trop.                                                                                                                                                |
| <img src="../.gitbook/assets/axe.png" alt=":axe:" data-size="line">Attaque puissante | Une attaque plus risquée mais plus puissante. Baisse la vitesse du combattant qui l'utilise.                                                                                                                                                |
| :bomb: Attaque ultime                                                                | Une attaque sur 2 tours à utiliser en dernier recours.                                                                                                                                                                                      |
| :firecracker: Attaque bélier                                                         | Attaque qui fait des dégâts à tous les combattants, utile si vous avez plus de défense que votre adversaire.                                                                                                                                |
| :rocket: Prise d'élan                                                                | Augmente vos points de vitesse. Toutes les attaques hormis l'attaque ultime et l'attaque bélier ont plus de chance de réussite si votre vitesse dépasse celle de votre adversaire. Plus cette action est utilisée, moins elle est efficace. |

{% hint style="info" %}
Le joueur le plus rapide commence toujours le combat. (En cas d'égalité, c'est aléatoire.)
{% endhint %}

### Présentation détaillée des actions

Voici une présentation plus détaillée de chacune des actions que vous pouvez réaliser.

{% hint style="info" %}
La notion de "puissance de l'attaque" sera utilisée pour comparer plus simplement les différentes attaques ci-dessous. En réalité, cette puissance est mise en facteur avec les statistiques d'attaque de l'attaquant.
{% endhint %}

#### :crossed\_swords: Attaque simple

Cette attaque est principalement utile en fin de combat pour être certain d'atteindre son adversaire. En effet, elle engendrera à coup sûr un minimum de dégâts. Il est cependant difficile de se reposer seulement sur cette attaque pour gagner un combat puisqu'elle reste assez faible. Elle peut cependant s'avérer utile pour éviter certaines prises de risques.

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

|                        | Attaque réussie parfaitement | Attaque réussie | Attaque échouée |
| ---------------------- | ---------------------------- | --------------- | --------------- |
| Puissance de l'attaque | 120 + x                      | 90 + x          | 40 + x          |

$$
x = random(1, a / 4)
$$

* x représente le minimum de dégâts qui sera effectué quoi qu'il arrive par l'attaque.
* a représente la statistique d'attaque du combattant effectuant l'attaque.

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

|                        | Attaque réussie parfaitement | Attaque réussie | Attaque échouée |
| ---------------------- | ---------------------------- | --------------- | --------------- |
| Adversaire plus rapide | 40%                          | 50%             | 10%             |
| Adversaire plus lent   | 90%                          | 0%              | 10%             |

#### :dagger: Attaque Rapide

Cette attaque permet d'atteindre un ennemi ayant une forte armure. Elle échoue également très peu et n'engendre aucun effet négatif sur les statistiques de l'attaquant. Elle diminue cependant en puissance si elle est trop utilisée.

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

|                        | Attaque réussie parfaitement | Attaque échouée |
| ---------------------- | ---------------------------- | --------------- |
| Puissance de l'attaque | 85                           | 10              |

{% hint style="info" %}
Cette attaque transperce l'armure, seuls 10% des points de défense sont utilisés pour la contrer.
{% endhint %}

{% hint style="warning" %}
La puissance de cette attaque diminue progressivement à partir de la quatrième utilisation réussie.
{% endhint %}

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

|                        | Attaque réussie parfaitement | Attaque échouée |
| ---------------------- | ---------------------------- | --------------- |
| Adversaire plus rapide | 30%                          | 70%             |
| Adversaire plus lent   | 95%                          | 5%              |

#### <img src="../.gitbook/assets/axe.png" alt=":axe:" data-size="line"> Attaque puissante

Cette attaque permet d'infliger des dégâts importants à l'adversaire. Bien que puissante cette attaque doit cependant être utilisée avec parcimonie puisque chacune de ses utilisations engendre une perte de vitesse. Il est possible de contrer cette attaque en profitant d'une statistique de défense importante tant que l'attaque n'est pas parfaitement réussie.

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

|                        | Attaque réussie parfaitement | Attaque réussie | Attaque échouée |
| ---------------------- | ---------------------------- | --------------- | --------------- |
| Puissance de l'attaque | 215                          | 140             | 0               |

{% hint style="info" %}
La défense est 50% plus efficace sur cette attaque, il vaut mieux avoir un gros bouclier qu'être un sac à points de vie. Cependant, ce boost ne suffira pas à se protéger d'une attaque parfaitement réussie.
{% endhint %}

{% hint style="danger" %}
Cette attaque diminue la vitesse de l'attaquant, de 10% si l'attaque échoue et de 25% si elle réussit.
{% endhint %}

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

|                        | Attaque réussie parfaitement | Attaque réussie | Attaque échouée |
| ---------------------- | ---------------------------- | --------------- | --------------- |
| Adversaire plus rapide | 20%                          | 30%             | 50%             |
| Adversaire plus lent   | 70%                          | 20%             | 10%             |

#### :bomb: Attaque ultime

Cette attaque permet d’asséner un dernier coup à son adversaire quand la situation devient trop difficile. Il peut être délicat d'utiliser cette attaque au bon moment, mais elle peut également renverser le cours du combat.

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

|                        | Attaque réussie | Attaque échouée |
| ---------------------- | --------------- | --------------- |
| Puissance de l'attaque | 350             | 0               |

L'attaque ne pourra pas infliger plus de 60% de la vie initiale du défenseur, même si le calcul théorique dépasse ce palier.

{% hint style="warning" %}
Cette attaque dure 2 tours ! Pendant le premier tour, vous ne pourrez faire aucune action et le malus sera déjà effectif !
{% endhint %}

{% hint style="danger" %}
Cette attaque diminue la défense de l'attaquant de 40% ! À n'utiliser qu'en dernier recours !
{% endhint %}

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

|                                         | Attaque réussie | Attaque échouée |
| --------------------------------------- | --------------- | --------------- |
| L'attaquant a plus de 50% de sa vie     | 10%             | 90%             |
| L'attaquant a entre 25 et 50% de sa vie | 80%             | 20%             |
| L'attaquant a moins de 25% de sa vie    | 100%            | 0%              |

#### :firecracker: Attaque bélier

Cette attaque permet d'infliger des dégâts importants à tous les combattants permettant de miser sur une défense plus importante pour en subir moins que son adversaire. Elle n'est donc pas utilisable contre tous mais peut permettre d'affaiblir un adversaire quand la puissance d'attaque est plus faible. Un suicide stratégique peut également parfois permettre d'obtenir une égalité.

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

La puissance de cette attaque est de 250.

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

Cette attaque a 15 % de chance d'échouer.

{% hint style="danger" %}
Un échec de cette attaque affaiblit l'attaquant en lui infligeant les dégâts de l'attaque sans les infliger à son adversaire.
{% endhint %}

#### :rocket: Prise d'élan

Cette action permet de gagner en vitesse. Plusieurs attaques dépendent de cette statistique pour être plus efficaces. Il peut être intéressant d'augmenter cette caractéristique pour mieux se défendre contre ces attaques et pour mieux les utiliser, ou pour temporiser durant le combat. L'efficacité du gain décroît au fur et à mesure qu'il est utilisé.

$$
Gain De Vitesse = random(0, x)
$$

* x représente le maximum de gain de vitesse possible qui est de 30 au début du combat.

À chaque utilisation du boost, x est divisé par 2.

### Conditions de victoire

Dès lors que :zap: l'énergie de l'un des adversaire tombe à 0, le combat s'arrête. Le joueur encore debout remporte le combat et gagne des :medal: points de classement.

Un combat peut aussi se terminer sur une égalité si ce dernier atteint les 25 tours consécutifs ou si les deux combattants arrivent à court d'énergie durant le même tour.

Une fois un combat terminé, vous devrez attendre un certain temps avant de récupérer :zap: l'énergie que vous avez perdu.

{% hint style="danger" %}
Si un des adversaires est inactif pendant 30 secondes, le combat est considéré comme nul et s'arrête.
{% endhint %}
