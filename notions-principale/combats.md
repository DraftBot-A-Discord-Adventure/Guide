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
* 🌬 Souffle
* :lungs: Récupération de souffle

{% hint style="info" %}
Vous trouverez plus d'informations sur les statistiques dans le guide consacré au [profil](profile.md).
{% endhint %}

### Types de combats

#### Les combats normaux

Un combat normal peut être lancé avec la commande `/combat`. L'option `utilisateur` permet de défier un utilisateur en particulier. Si vous n'êtes pas l'initiateur du combat et que vous n'avez pas d'altération d'état, vous pouvez accepter le combat avec la réaction :white\_check\_mark:. Dans ce type de combat, le gagnant remporte des :medal: points de classement et le perdant en perd.

{% hint style="info" %}
Les combats normaux sont désactivés pour le moment mais la commande reste la même : `/combat.`

Ceci se dérouleront donc comme des combats amicaux (voir ci-dessous).
{% endhint %}

#### Les combats amicaux

Les combats amicaux sont similaires aux combats normaux, à la seule différence que vous ne perdez ni ne gagnez pas de points.

### Déroulement d'un combat

Le combat est basé sur un système de tour par tour. À chaque tour, vous aurez le choix entre 5 attaques qui dépendent de votre classe.

Ces attaques sont réparties dans les différentes classes du jeu :&#x20;

* Fantassin : Attaque simple, Attaque perçante, Attaque puissante, Attaque chargée, Protection.
* Tank : Attaque simple, Attaque intense, Attaque riposte, Attaque bouclier, Boost de la défense.
* Cannonier : Attaque rapide, Attaque sabotage, Attaque boomerang, Attaque canon, Attaque intense.
* Chevalier : Attaque simple, Attaque rapide, Attaque lourde, Bénédiction, Repos.
* Paladin : Attaque simple, Attaque bélier, Attaque ultime, Attaque bouclier, Attaque divine.
* Vétéran : Attaque rapide, Attaque énergique, Attaque chargée, Attaque perçante, Concentration.
* Mage : Attaque vol de souffle, Attaque maudite, Attaque sombre, Attaque feu, Attaque empoisonnée

{% hint style="danger" %}
Les attaques ci-dessus restent toujours les mêmes pour l'équivalent de la classe associée en fonction du niveau.
{% endhint %}

{% hint style="success" %}
Le joueur le plus rapide commence toujours le combat. (En cas d'égalité, c'est aléatoire.)
{% endhint %}

### Détaillé des différentes attaques

Vous pouvez retrouvez le détaillé des attaques sur le document ci-dessous.

<figure><img src="../.gitbook/assets/image (72).png" alt=""><figcaption><p>Détail de toutes les attaques du jeu.</p></figcaption></figure>

### Gestion du souffle

Chaque attaque nécessite une certaine quantité de souffle. Chaque lancement de cette attaque retirera de la réserve de souffle du combatant le montant spécifié. Au début de son tour, un combatant reçoit une quantité de souffle en fonction de sa classe. Les informations sur les réserves de souffle liées à une classe où les consommation de souffle des différentes attaques peuvent être consultées via la commande `/infosclasses`

{% hint style="info" %}
Si un joueur est essoufflé et tente d'utiliser une attaque qui nécessite plus de souffle que ce dont il dispose, l'attaque n'aura qu'une faible probabilité d'être lancée.
{% endhint %}

### Conditions de victoire

Dès lors que :zap: l'énergie de l'un des adversaire tombe à 0, le combat s'arrête. Le joueur encore debout remporte le combat.

Un combat peut aussi se terminer sur une égalité si ce dernier atteint les 24 tours consécutifs ou si les deux combattants arrivent à court d'énergie durant le même tour.

Une fois un combat terminé, vous devrez attendre un certain temps avant de récupérer :zap: l'énergie que vous avez perdu, sauf si il s'agissait d'un combat amical.

{% hint style="danger" %}
Si un des adversaires est inactif pendant plus de 30 secondes, le combat est considéré comme nul et s'arrête. Le combatant innactif perd le combat.
{% endhint %}
