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

Un combat normal peut être lancé avec la commande `!fight`. La variante `!fight <@user>` permets de défier un utilisateur en particulier. Si vous n'êtes pas l'initiateur du combat, et que vous n'avez pas d'altération d'état, vous pouvez accepter le combat avec la réaction ![:white\_check\_mark:](https://discord.com/assets/212e30e47232be03033a87dc58edaa95.svg). Dans ce type de combat, le gagnant remporte des ![:medal:](https://discord.com/assets/c9b563417a1ff01700edc358b5fc309f.svg) points de classement, et le perdant en perds.

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
| ![:shield:](https://discord.com/assets/ad2e4d6e7b90ca6005a5038e22b099cc.svg)Défense    | Augmente vos![:shield:](https://discord.com/assets/ad2e4d6e7b90ca6005a5038e22b099cc.svg)points de défense ce qui permet de mieux absorber les dégâts des attaques de votre adversaire. Plus cette action est utilisée, moins elle est efficace. |
| ![:rocket:](https://discord.com/assets/748ff0e7b2f1f22adecad8463de25945.svg)Prise d'élan                           | Augmente vos![:rocket:](https://discord.com/assets/748ff0e7b2f1f22adecad8463de25945.svg)points de vitesse. Toutes les attaques hormis l'attaque ultime ont plus de chance de réussite si votre vitesse dépasse celle de votre adversaire. Plus cette action est utilisée, moins elle est efficace. |

### Chances de réussite.

Voici le tableau qui pour chaque attaque en fonction de la situation, indique les % de réussite.

#### ![:crossed\_swords:](https://discord.com/assets/e7159ba0fcc85f39f95227dd85f44aeb.svg) Attaque simple

| Situation | Attaque réussie parfaitement  | Attaque réussie | Attaque échouée |
| :--- | :--- | :--- | :--- |
| Puissance de l'attaque | 100 | 70 | 40 |
| Adversaire plus rapide | 40% | 50% | 10% |
| Adversaire plus lent | 90% | 0% | 10% |

{% hint style="info" %}
Cette attaque fera forcément un tout petit peu de dégâts. Même si elle échoue. Ces dégâts sont égaux à un nombre aléatoire entre 1 et la puissance de l'attaquant divisé par 8.
{% endhint %}

#### ![:dagger:](https://discord.com/assets/47f10f1fb3beec3810f0f37cf4cccd95.svg) Attaque Rapide

| Situation | Attaque réussie parfaitement  | Attaque échouée |
| :--- | :--- | :--- |
| Puissance de l'attaque | 70 | 10 |
| Adversaire plus rapide | 30% | 70% |
| Adversaire plus lent | 95% | 5% |

{% hint style="info" %}
Cette attaque transperce l'armure, seul 10% des points de défense sont utilisés pour la contrer.
{% endhint %}

{% hint style="warning" %}
La puissance de cette attaque diminue progressivement à partir de 3 utilisations réussies
{% endhint %}

#### ![:axe:](https://discord.com/assets/76e6d179559520cd50c0f603ca15c517.svg) Attaque puissante

| Situation | Attaque réussie parfaitement  | Attaque réussie | Attaque échouée |
| :--- | :--- | :--- | :--- |
| Puissance de l'attaque | 215 | 140 | 0 |
| Adversaire plus rapide | 20% | 30% | 50% |
| Adversaire plus lent | 70% | 20% | 10% |

{% hint style="info" %}
La défense est 50% plus efficace sur cette attaque, il vaut mieux avoir un gros bouclier qu'être un sac à pv.
{% endhint %}

{% hint style="danger" %}
Cette attaque diminue la vitesse de l'attaquant, de 10% si l'attaque échoue et de 25% si elle réussie.
{% endhint %}

#### ![:bomb:](https://discord.com/assets/31ef50db484eb3d4b2fbebb4e91a0764.svg)Attaque ultime

| Situation | Attaque réussie  | Attaque échouée |
| :--- | :--- | :--- |
| Puissance de l'attaque | Enlève 60% de la vie de l'adversaire | 0 |
| L'attaquant a plus de 50% de sa vie | 10% | 90% |
| L'attaquant a entre 25 et 50% de sa vie | 80% | 20% |
| L'attaquant a moins de 25% de sa vie | 100% | 0% |

{% hint style="info" %}
Cette attaque ignore complètement l'armure et la statistiques d'attaque de l'attaquant, les dégâts seront toujours égaux à 60% de la vie de base de l'adversaire
{% endhint %}

{% hint style="warning" %}
Cette attaque dure 2 tours ! Pendant le premier tour, vous ne pourrez faire aucune action !
{% endhint %}

{% hint style="danger" %}
Cette attaque diminue la défense de l'attaquant de 20% ! A n'utiliser qu'en dernier recours !
{% endhint %}

### Conditions de victoire

Dès lors que![:zap:](https://discord.com/assets/bcca43b1c7aa91d47f62962ce2422ae1.svg)l'énergie de l'un des adversaire tombe à 0, le combat s'arrête. Le joueur encore debout remporte le combat et gagnes des ![:medal:](https://discord.com/assets/c9b563417a1ff01700edc358b5fc309f.svg) points de classement.

Un combat peut aussi se terminer sur une égalité si ce dernier atteint les 25 tours consécutifs.

 Une fois un combat terminé, vous devrez attendre un certain temps avant de récupérer l'énergie![:zap:](https://discord.com/assets/bcca43b1c7aa91d47f62962ce2422ae1.svg)que vous avez perdu.

{% hint style="danger" %}
Si un des adversaire est inactif pendant 30 seconde, le combat est considéré comme nul et s'arrête.
{% endhint %}





