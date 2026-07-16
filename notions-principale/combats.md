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

#### Les combats de joueurs

Un combat peut être lancé avec la commande `/combat`. Vous affronterez une IA avec la classe et les statistiques d'un joueur aléatoire (à condition que sa gloire de défense soit au maximum 450 points au-dessus ou en dessous de votre gloire d'attaque et que vous l'avez affronté moins de 3 fois depuis le début de la saison). Le gagnant remporte de la gloire :sparkles: ,le perdant en perd et l'énergie perdue est consommée.

{% hint style="info" %}
Il n'est possible de lancer une combat que si vous possédez 80% ou plus d'énergie.
{% endhint %}

{% hint style="info" %}
Votre gloire est divisée en 2 parties dont la somme forme la gloire affichée sur le profil :&#x20;

-La gloire d'attaque : lorsque vous combattez l'IA d'un joueur.

-La gloire de défense : lorsque votre IA est attaquée par un joueur.
{% endhint %}

{% hint style="info" %}
A la fin de chaque combat, vous obtenez, en plus de la gloire, de l'argent et des points (dans la limite de 200 pièces et 105 points par jour).&#x20;
{% endhint %}

#### Les combats de monstres

Voir [iles-mysterieuses.md](../notions-avancees/iles-mysterieuses.md "mention")

### Déroulement d'un combat

Le combat est basé sur un système de tour par tour. À chaque tour, vous aurez le choix entre des attaques qui dépendent de votre classe.

Ces attaques sont réparties dans les différentes classes du jeu :&#x20;

* Fantassin : Attaque simple :crossed\_swords:, Attaque perçante :sewing\_needle:, Attaque puissante :axe:, Attaque chargée :magnet:, Protection :person\_gesturing\_no:.
* Tank : Attaque simple :crossed\_swords:, Attaque intense :triumph:, Attaque riposte :boxing\_glove:, Attaque bouclier :shield:, Boost de la défense :person\_in\_lotus\_position:.
* Canonnier : Attaque rapide :dagger:, Attaque sabotage :hammer\_pick:, Attaque boomerang :boomerang:, Attaque canon :gun:, Attaque intense :triumph:.
* Chevalier : Attaque simple :crossed\_swords:, Attaque rapide :dagger:, Attaque lourde :person\_lifting\_weights:, Bénédiction :angel:, Repos :bed:.
* Paladin : Attaque simple :crossed\_swords:, Attaque bélier :ram:, Attaque ultime :comet:, Attaque bouclier :shield:, Attaque divine :pray:.
* Vétéran : Attaque rapide :dagger:, Attaque énergique :zap:, Attaque chargée :magnet:, Attaque perçante :sewing\_needle:, Concentration :dart:.
* Mage : Attaque empoisonnée :test\_tube:, Attaque feu :fire:, Attaque vol de souffle :dash:, Attaque maudite :smiling\_imp:, Attaque sombre :eight\_pointed\_black\_star:.

{% hint style="danger" %}
Les attaques ci-dessus restent toujours les mêmes pour l'équivalent de la classe associée en fonction du niveau.
{% endhint %}

{% hint style="success" %}
Le joueur le plus rapide commence toujours le combat. (En cas d'égalité, c'est aléatoire.)
{% endhint %}

### Détail des différentes attaques

Vous pouvez retrouvez le détail des attaques sur le document ci-dessous.

<figure><img src="../.gitbook/assets/combat_5.1.7.png" alt="Liste des attaques de Crownicles et leurs spéficités"><figcaption></figcaption></figure>

**Quelles attaques ne peuvent pas être contrées par l'attaque riposte** 🥊 ?

_Pour les joueurs :_

> 🔥 Attaque feu, 😈 Attaque maudite, ✴️ Attaque sombre , ☄️ Attaque ultime, 🙏 Attaque divine, 👼 Bénédiction, 🧪 Attaque empoisonnée, 🎯 Concentration, 🙅 Protection, 🛏️ Repos, 🥊 Attaque riposte, 🧘‍♂️ Boost de défense, 💨 Attaque vol de souffle

_Pour les monstres :_

> 💢 Colère, 🔊 Rugissement, 🧑‍🤝‍🧑 Invocation d'alliés, 😶‍🌫️ Discrétion, 🌋 Éruption, ♨️ Vague de lave, 🛁 Bain de magma, 🧑‍🌾 Tir de boue, 🏺 boue brûlante, 🌡️ Drain de chaleur

### Gestion du souffle

Chaque attaque nécessite une certaine quantité de souffle. Chaque usage de cette attaque retirera de la réserve de souffle du combattant le montant spécifié. Au début de son tour, le combattant reçoit une quantité de souffle définie par la statistique de récupération de souffle :lungs:  dépendant de sa classe. Les informations sur les réserves de souffle liées à une classe et la consommation de souffle des différentes attaques peuvent être consultées via la commande `/infosclasses`.

{% hint style="info" %}
Si un joueur est essoufflé et tente d'utiliser une attaque qui nécessite plus de souffle que ce dont il dispose, l'attaque n'aura qu'une faible probabilité d'être lancée.
{% endhint %}

### Conditions de victoire

Dès lors que l'énergie :zap: de l'un des combattants tombe à 0, le combat s'arrête. Le joueur encore debout remporte le combat.

Un combat peut se terminer sur une égalité si le 26e tour se finit sans vainqueur ou si les deux combattants atteignent 0 :zap: au cours du même tour.

Une fois un combat terminé, vous devrez attendre un certain temps avant de récupérer l'énergie :zap:que vous avez perdue.

{% hint style="danger" %}
Si vous êtes inactif pendant plus de 45 secondes, le combat est considéré comme terminé. Vous perdrez  automatiquement le combat et donc la totalité de votre énergie.
{% endhint %}

### Historique des combats

La commande `/historiquecombat` permet d'afficher les résultats des combats que vous avez fait en tant qu'attaquant et défenseur.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-22 100445.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-22 100522.png" alt=""></picture><figcaption><p>Comme votre IA peut combattre pour vous, il peut être intéressant de savoir comment votre gloire a évolué en votre absence.</p></figcaption></figure>
