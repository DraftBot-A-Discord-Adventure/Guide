---
description: Un guide à propos des combats.
---

# Combats

Une fois que votre personnage a atteint le **niveau 8**, vous débloquez la capacité de faire des **combats**. Ce guide vous permet de comprendre les bases.

### Avant de commencer 

Pendant un combat, vous devez impérativement prendre en compte les statistiques suivantes :

* ![:zap:](https://discord.com/assets/bcca43b1c7aa91d47f62962ce2422ae1.svg) L'énergie
* ![:dagger:](https://discord.com/assets/47f10f1fb3beec3810f0f37cf4cccd95.svg) Points d'attaque
* ![:shield:](https://discord.com/assets/ad2e4d6e7b90ca6005a5038e22b099cc.svg) Points de défense  
* ![:rocket:](https://discord.com/assets/748ff0e7b2f1f22adecad8463de25945.svg) Points de vitesse 

{% hint style="info" %}
 Vous trouverez plus d'informations sur les statistiques dans le guide consacré au [profil](profile.md).
{% endhint %}

### Types de combats 

#### Les combats normaux

Un combat normal peut être lancé avec la commande`!fight`. La variante `!fight <@user>` permets de défier un utilisateur en particulier. Si vous n'êtes pas l'initiateur du combat, et que vous n'avez pas d'altération d'état, vous pouvez accepter le combat avec la réaction ![:white\_check\_mark:](https://discord.com/assets/212e30e47232be03033a87dc58edaa95.svg). Dans ce type de combat, le gagnant remporte des ![:medal:](https://discord.com/assets/c9b563417a1ff01700edc358b5fc309f.svg) points de classement, et le perdant en perds.

#### Les combats amicaux 

Les combats amicaux sont similaires aux combats normaux, à la seule différence que vous ne perdez ni ne gagnez pas de points. La commande pour lancer un combat amical est `!friendlyfight` 

### Déroulement d'un combat 

Le combat est basé sur un système de tour par tour. A chaque tour, vous aurez le choix entre 6 actions :

| Action | Description |
| :--- | :--- |
| ![:crossed\_swords:](https://discord.com/assets/e7159ba0fcc85f39f95227dd85f44aeb.svg)Attaque simple | Attaque classique, les chances de réussite et les dégâts sont moyens. |
| ![:dagger:](https://discord.com/assets/47f10f1fb3beec3810f0f37cf4cccd95.svg)Attaque rapide | Attaque moins puissante mais qui ignore l'armure. Sa puissance diminue si on l'utilise trop. |
| ![:axe:](https://discord.com/assets/76e6d179559520cd50c0f603ca15c517.svg)Attaque puissante | Une attaque plus risquée mais plus puissante. Baisse la vitesse du combattant qui l'utilise. |
| ![:bomb:](https://discord.com/assets/31ef50db484eb3d4b2fbebb4e91a0764.svg)Attaque ultime | Une attaque sur 2 tours à utiliser en dernier recours |
| ![:shield:](../.gitbook/assets/image%20%2826%29.png)Attaque bélier    | Attaque qui fait des dégâts à tous les combattants, utile si vous avez plus de défense que votre adversaire. |
| ![:rocket:](https://discord.com/assets/748ff0e7b2f1f22adecad8463de25945.svg)Prise d'élan                           | Augmente vos points de vitesse. Toutes les attaques hormis l'attaque ultime et l'attaque bélier ont plus de chance de réussite si votre vitesse dépasse celle de votre adversaire. Plus cette action est utilisée, moins elle est efficace. |

{% hint style="info" %}
Le joueur le plus rapide commence toujours le combat. \(en cas d'égalité, c'est aléatoire\)
{% endhint %}

### Présentation détaillée des actions

Voici une présentation plus détaillée de chacune des actions que vous pouvez réaliser

{% hint style="info" %}
La notion de "puissance de l'attaque" sera utilisée pour comparer plus simplement les différentes attaques ci-dessous. En réalité cette puissance est mise en facteur avec les statistiques d'attaque de l'attaquant.
{% endhint %}

#### ![:crossed\_swords:](https://discord.com/assets/e7159ba0fcc85f39f95227dd85f44aeb.svg) Attaque simple

Cette attaque est principalement utile en fin de combat être certain d'atteindre son adversaire. En effet, elle engendrera à coup sur un minimum de dégâts. Il est cependant difficile de se reposer seulement sur cette attaque pour gagner un combat puisqu'elle reste assez faible. Elle peut cependant s'avèrer utile pour éviter certaines prise de risques.

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

|  | Attaque réussie parfaitement  | Attaque réussie | Attaque échouée |
| :--- | :--- | :--- | :--- |
| Puissance de l'attaque | 120 + x | 90 + x | 40 + x  |

$$
x = random(1, a / 4)
$$

* x représente le minimum de dégât qui sera effectué quoi qu'il arrive par l'attaque
* a représente la statistique d'attaque du combattant effectuant l'attaque

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

|  | Attaque réussie parfaitement  | Attaque réussie | Attaque échouée |
| :--- | :--- | :--- | :--- |
| Adversaire plus rapide | 40% | 50% | 10% |
| Adversaire plus lent | 90% | 0% | 10% |

#### ![:dagger:](https://discord.com/assets/47f10f1fb3beec3810f0f37cf4cccd95.svg) Attaque Rapide

Cette attaque permet d'atteindre un ennemi ayant une forte armure. Elle échoue également très peu et n'engendre aucun effet négatif sur les statistique de l'attaquant. Elle diminue cependant en puissance si elle est trop utilisée.

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

|  | Attaque réussie parfaitement  | Attaque échouée |
| :--- | :--- | :--- |
| Puissance de l'attaque | 85 | 10 |

{% hint style="info" %}
Cette attaque transperce l'armure, seul 10% des points de défense sont utilisés pour la contrer.
{% endhint %}

{% hint style="warning" %}
La puissance de cette attaque diminue progressivement à partir de la quatrième utilisation réussie
{% endhint %}

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

|  | Attaque réussie parfaitement  | Attaque échouée |
| :--- | :--- | :--- |
| Adversaire plus rapide | 30% | 70% |
| Adversaire plus lent | 95% | 5% |

#### ![:axe:](https://discord.com/assets/76e6d179559520cd50c0f603ca15c517.svg) Attaque puissante

Cette attaque permet d'infliger des dégâts importants à l'adversaire. Bien que puissante \(lol\) cette attaque doit cependant être utilisée avec parcimonie puisque chacune de ses utilisation engendre une perte de vitesse. Il est possible de contrer cette attaque en profitant d'une statistique de défense importante tant que l'attaque n'est pas réussie parfaitement.

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

|  | Attaque réussie parfaitement  | Attaque réussie | Attaque échouée |
| :--- | :--- | :--- | :--- |
| Puissance de l'attaque | 215 | 140 | 0 |

{% hint style="info" %}
La défense est 50% plus efficace sur cette attaque, il vaut mieux avoir un gros bouclier qu'être un sac à pv. Cependant, ce boost ne suffira pas à se protéger d'une attaque parfaitement réussie
{% endhint %}

{% hint style="danger" %}
Cette attaque diminue la vitesse de l'attaquant, de 10% si l'attaque échoue et de 25% si elle réussie.
{% endhint %}

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

|  | Attaque réussie parfaitement  | Attaque réussie | Attaque échouée |
| :--- | :--- | :--- | :--- |
| Adversaire plus rapide | 20% | 30% | 50% |
| Adversaire plus lent | 70% | 20% | 10% |

#### ![:bomb:](https://discord.com/assets/31ef50db484eb3d4b2fbebb4e91a0764.svg)Attaque ultime

Cette attaque permet d’asséner un dernier coup à son adversaire quand la situation deviens trop difficile. Il peut être délicat d'utiliser cette attaque au bon moment mais elle peut également renverser le cours du match.

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

|  | Attaque réussie  | Attaque échouée |
| :--- | :--- | :--- |
| Puissance de l'attaque | 350 | 0 |

L'attaque ne pourra pas infliger plus de 60% de la vie initiale du défenseur, même si le calcul théorique dépasse ce palier.

{% hint style="warning" %}
Cette attaque dure 2 tours ! Pendant le premier tour, vous ne pourrez faire aucune action et le malus sera déjà effectif !
{% endhint %}

{% hint style="danger" %}
Cette attaque diminue la défense de l'attaquant de 40% ! A n'utiliser qu'en dernier recours !
{% endhint %}

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

|  | Attaque réussie  | Attaque échouée |
| :--- | :--- | :--- |
| L'attaquant a plus de 50% de sa vie | 10% | 90% |
| L'attaquant a entre 25 et 50% de sa vie | 80% | 20% |
| L'attaquant a moins de 25% de sa vie | 100% | 0% |

####  ![:shield:](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-MH1fCvNZ7zikrWd7dJj%2F-MVDlmmdOFCzSJ17u9Bx%2F-MVDmnCLMmrv_Ohz3-j8%2Fimage.png?alt=media&token=bf93d8a6-d631-4778-a1bf-5bd174348fb9)Attaque bélier

Cette attaque permet d'infliger des dégâts important à tous les combattants permettant de miser sur une défense plus importante pour mieux les amortir. Elle n'est donc pas utilisable contre tous les adversaires mais peut permettre d'affaiblir un adversaire quand la puissance d'attaque est plus faible. Un suicide stratégique peut également parfois permettre d'obtenir une égalité

**Voilà les dégâts de l'attaque en fonction de la situation du combat :**

La puissance de cette attaque est de 250. 

**Voilà les probabilités d’échec ou de réussite de l'attaque :**

Cette attaque a 15 % de chance d'échouer. 

{% hint style="danger" %}
Un échec de cette attaque affaibli l'attaquant en lui infligeant les dégâts de l'attaque sans les infliger à son adversaire.
{% endhint %}

#### ![:rocket:](https://discord.com/assets/748ff0e7b2f1f22adecad8463de25945.svg) Prise d'élan 

Cette action permet de gagner en vitesse. Plusieurs attaques dépendent de cette statistique pour être plus efficace. Il peut être intéressant de booster cette caractéristique pour mieux défendre contre ces attaques, pour mieux les utiliser, ou pour temporiser durant le combat. L'efficacité du boost décroît au fur et à mesure qu'il est utilisé.                      

$$
Gain De Vitesse = random(0, x)
$$

* x représente le maximum de gain de vitesse possible qui est de 30 au début du combat

à chaque utilisation du boost, x est divisé par 2

### Conditions de victoire

Dès lors que![:zap:](https://discord.com/assets/bcca43b1c7aa91d47f62962ce2422ae1.svg)l'énergie de l'un des adversaire tombe à 0, le combat s'arrête. Le joueur encore debout remporte le combat et gagnes des ![:medal:](https://discord.com/assets/c9b563417a1ff01700edc358b5fc309f.svg) points de classement.

Un combat peut aussi se terminer sur une égalité si ce dernier atteint les 25 tours consécutifs ou si les deux combattants arrivent à cours d'énergie durant le même tour.

 Une fois un combat terminé, vous devrez attendre un certain temps avant de récupérer l'énergie![:zap:](https://discord.com/assets/bcca43b1c7aa91d47f62962ce2422ae1.svg)que vous avez perdu.

{% hint style="danger" %}
Si un des adversaire est inactif pendant 30 seconde, le combat est considéré comme nul et s'arrête.
{% endhint %}





