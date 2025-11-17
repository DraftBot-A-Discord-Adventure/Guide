# Mini-évènements sur le continent principal

Il existe actuellement plusieurs types de mini-évènement dans le bot. Voici quelques informations au sujet des mini-évènements qui vous permettront d'aborder cette fonctionnalité de manière plus stratégique.

Plus la valeur de la rareté d'un mini-évènement est élevée, plus celui-ci est fréquent.

{% hint style="success" %}
La rareté maximale actuelle est de 12 (très fréquent) !
{% endhint %}

{% hint style="info" %}
Info supplémentaire :  Pour le coté technique, la sélection aléatoire des mini-évènements se déroule ainsi : Toutes les raretés de tous les mini-évènements sont additionnées, puis un nombre aléatoire entre 0 et le résultat est choisi aléatoirement, puis dans un ordre précis on soustrait à ce nombre la rareté de différents mini-évènements, et celui qui le fait atteindre 0 est choisi.
{% endhint %}

## Mini-shop

**Rareté :** **4**

Vous permet d'acheter un objet pour pas cher (60 % du prix). Il n'est pas possible d'obtenir des objets de rareté supérieure à spécial. Si vous achetez un objet mais que vous n'acceptez pas de remplacer votre ancien objet, l'objet sera racheté par le vendeur pour un prix inférieur à son prix d'achat.

{% hint style="warning" %}
Attention, une faible proportion de vendeurs sont des arnaqueurs et tenteront de vous vendre des items pour 5 fois plus cher !
{% endhint %}

<picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191024.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191037.png" alt="Un exemple de mini-shop"></picture>

## Interaction avec un familier

**Rareté : 10** - Nécessite d'avoir un familier équipé pour apparaître.

Réalise une interaction entre le propriétaire d'un familier et son familier. Ce mini-évènement peut être positif ou négatif en fonction de l'affection du familier. Les familiers plus rares permettent d'obtenir de meilleures récompenses.

| Récompense                 | Nombre d'étoiles du familier | Probabilité |
| -------------------------- | ---------------------------- | ----------- |
| Argent (20 à 70)           | 3                            | Élevée      |
| Nourriture                 | 1                            | Moyenne     |
| Item                       | 5                            | Faible      |
| Points de vie (1 à 5)      | 4                            | Moyenne     |
| Rien ne se passe           | 1                            | Très élevée |
| Un peu d'affection (1 à 3) | 2                            | Moyenne     |
| Temps (5 à 20 minutes)     | 3                            | Faible      |
| Points bonus (20 à 70)     | 1                            | Moyenne     |
| Badge                      | 6                            | Très faible |
| Énergie (10 à 250)         | 1                            | Élevée      |

{% hint style="success" %}
Si un familier est dressé, il compte dans le calcul des récompenses accessibles comme ayant une étoile en plus.
{% endhint %}

Si le familier est fielleux, il ne vous apportera que des malus:

| Malus                           | Probabilité |
| ------------------------------- | ----------- |
| Perte de vie (1 à 5)            | Moyenne     |
| Perte d'argent (20 à 70)        | Moyenne     |
| Perte de temps (5 à 20 minutes) | Moyenne     |
| Perte d'affection (1 à 3)       | Moyenne     |
| Fuite du familier               | Très faible |

<picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191231.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191219.png" alt="Un exemple d&#x27;interaction avec un familier"></picture>

## Trouver un familier

**Rareté : 2**

Le joueur découvre un familier qui le rejoint dans son aventure. Si le joueur a déjà un familier, le nouveau est placé dans le refuge de la guilde du joueur.

{% hint style="danger" %}
S'il n'y a plus de place dans le refuge de la guilde du joueur et que ce dernier possède déjà un familier alors ce mini-évènement ne rapportera pas de nouveau familier.
{% endhint %}

Voilà les probabilités d'obtention de chaque rareté de familiers :

|          |          |         |         |         |
| -------- | -------- | ------- | ------- | ------- |
| 1 :star: | 2 :star: | 3:star: | 4:star: | 5:star: |
| 87.6%    | 9.64%    | 1.664%  | 0.65%   | 0.446%  |

<picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191320.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191334.png" alt="Un exemple de rapport où le joueur trouve un familier."></picture>

## Trouver un équipement

**Rareté : 2**

Le joueur découvre un équipement aléatoire. Il n'est pas possible d'obtenir des objets légendaires ou mythiques dans ce mini-évènement.

<picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191454.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191443.png" alt="Exemple de découverte d&#x27;un équipement"></picture>

## Rien ne se passe

**Rareté : 8**&#x20;

Ce mini-évènement affiche simplement une phrase d'encouragement pour le joueur.

<picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191537.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191547.png" alt="Un exemple du mini-évènement &#x22;Rien ne se passe&#x22;"></picture>

## Petit malheur

**Rareté : 8**

Parfois, tout ne se passe pas comme prévu. Certains mini-évènements amènent à de petits malus.

| Malus                    | Effet                        |
| ------------------------ | ---------------------------- |
| Perte de vie             | 1 à 5 points de vie perdus   |
| Perte d'argent           | 10 à 50 d'argent perdus      |
| Perte de temps aléatoire | 5 minutes à 2 heures perdues |

<picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191648.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191637.png" alt="Un exemple de petit malheur"></picture>

## Gros malheur

**Rareté : 1**

Parfois, tout ne se passe pas comme prévu. Certain mini-évènements amènent à de gros malus. Heureusement, cela reste très rare !

| Malus             | Effet                                                |
| ----------------- | ---------------------------------------------------- |
| Perte de vie      | 5 à 30 points de vie perdus                          |
| Perte d'argent    | 50 à 250 d'argent perdus                             |
| Altération d'état | Le joueur peut être touché par une altération d'état |

<picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191743.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191805.png" alt="Un exemple de gros malheur"></picture>

## Loterie

**Rareté : 3**

Durant votre voyage, un gérant de jeu de hasard peut vous croiser et vous proposer de tenter votre chance pour recevoir un peu d'argent, d'XP ou de points. Pour cela, 3 mises sont à disposition:

* :coin: **Petite mise**
* :dollar: **Mise moyenne**
* :moneybag: **Grosse mise**

Les gains et malus dépendent de la mise choisie:

{% tabs %}
{% tab title="Petite mise" %}
Gains possibles (80%) :&#x20;

* 35 :medal:
* 70 XP de guilde
* 50 :moneybag:
* 40 :star:

Malus  :&#x20;

* Rien (20%)
{% endtab %}

{% tab title="Mise moyenne" %}
Gains possibles (50%) :&#x20;

* 105 :medal:
* 210 XP de guilde
* 150 :moneybag:
* 120 :star:

Malus :&#x20;

* 10 minutes :clock1: (100%)
{% endtab %}

{% tab title="Grosse mise" %}
Gains possibles (20%) :&#x20;

* 350 :medal:
* 700 XP de guilde
* 500 :moneybag:
* 400 :star:

Malus :&#x20;

* 10 minutes :clock1: (100%)
* 175 :money\_with\_wings: (10%)
{% endtab %}
{% endtabs %}

{% hint style="warning" %}
Vous devez avoir au moins 175 d'argent pour tenter votre chance à la loterie. Si vous en possédez moins, votre mise sera rejetée par le gérant du jeu de hasard.
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191915.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 191904.png" alt=""></picture><figcaption><p>Un exemple de loterie</p></figcaption></figure>

## Interaction avec un joueur sur le même trajet

**Rareté : 12**

Il est possible de rencontrer d'autres joueurs sur le même trajet en voyageant. Ce mini-évènement permet de discuter avec un joueur que vous croisez, que vous suivez ou que vous précédez !

Il existe une multitude de phrases en fonction de la situation de la personne que vous croisez !

<details>

<summary>Voilà la liste des caractéristiques qui peuvent être exploitées :</summary>



* Top 10
* Top 50
* Top 100
* Top 1
* Guilde puissante
* Débutant
* Niveau 50 ou plus
* Inactif
* Même classe que le joueur
* Même guilde
* Membre du staff
* Points du classement de la semaine
* Peu de vie
* Beaucoup de vie
* Mieux classé
* Moins bien classé
* Riche
* Pauvre
* Duplication de potion
* Familier
* Chef de guilde
* Aîné de guilde
* Classe du joueur
* Altération d'état
* Inventaire du joueur

</details>



<picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192003.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192013.png" alt="Un exemple d&#x27;interaction avec un autre joueur"></picture>

## Avancement du temps

**Rareté : 6**

Avance le temps de 10 à 50 minutes.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192306.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192316.png" alt=""></picture><figcaption><p>Exemple d'avancement du temps</p></figcaption></figure>

## Faits du Bot

**Rareté : 2**

Vous découvrirez une information à propos du bot.

<details>

<summary>Une liste des différentes informations possibles:</summary>

* Moyenne des points totaux des joueurs
* Moyenne des points durant la semaine
* Nombre de joueurs qui ont commencé leur aventure
* Moyenne du niveau des joueurs
* Argent total en circulation
* Balance du joueur le plus riche
* Nombre de familiers dressés
* Nombre de familiers fielleux
* Pourcentage de familiers femelles dans le jeu
* Pourcentage de familiers mâles dans le jeu
* Moyenne du niveau des guilde
* Nombre de joueurs d'une classe
* Nombre de joueurs voyageant sur votre chemin&#x20;

</details>



<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192421.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192409.png" alt=""></picture><figcaption><p>Exemple d'une information à propos du bot</p></figcaption></figure>

## Classes

**Rareté : 4**

Vous gagnez une récompense qui dépend de votre classe.

| Classes                               | Items                                                                   |
| ------------------------------------- | ----------------------------------------------------------------------- |
| Recrue :herb:                         | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Combattant :axe:                      | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Soldat :dagger:                       | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Fantassin :crossed\_swords:           | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Ganté :boxing\_glove:                 | Objet de défense, potion de défense ou armure                           |
| Casqué :military\_helmet:             | Objet de défense, potion de défense ou armure                           |
| Maillé :chains:                       | Objet de défense, potion de défense ou armure                           |
| Tank :shield:                         | Objet de défense, potion de défense ou armure                           |
| Lanceur de pierre :rock:              | Objet d'attaque, potion d'attaque ou arme                               |
| Frondeur :mechanical\_arm:            | Objet d'attaque, potion d'attaque ou arme                               |
| Archer :bow\_and\_arrow:              | Objet d'attaque, potion d'attaque ou arme                               |
| Canonnier :gun:                       | Objet d'attaque, potion d'attaque ou arme                               |
| Ecuyer :broom:                        | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Cavalier :horse\_racing:              | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Piquier :probing\_cane:               | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Chevalier :person\_fencing:           | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Paladin :fleur-de-lis:                | Objet de défense, potion de défense ou armure                           |
| Vétéran :trident:                     | Item au hasard ou gagner des points de vie (entre 1:heart:et 5:heart:)  |
| Fantassin puissant :crossed\_swords:  | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Tank impénétrable :shield:            | Objet de défense, potion de défense ou armure                           |
| Canonnier redoutable :gun:            | Objet d'attaque, potion d'attaque ou arme                               |
| Chevalier valeureux :person\_fencing: | Item au hasard ou argent (entre 50:moneybag:et 150:moneybag:)           |
| Paladin lumineux :fleur-de-lis:       | Objet de défense, potion de défense ou armure                           |
| Vétéran chevronné :trident:           | Item au hasard ou gagner des points de vie (entre 1 :heart:et 5:heart:) |
| Mage mystique :mage:                  | Item au hasard ou gagner des points de vie (entre 1 :heart:et 5:heart:) |

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192517.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192528.png" alt=""></picture><figcaption><p>Exemple de gain dépendant d'une classe</p></figcaption></figure>

## Trouver une mission

**Rareté : 6**

Vous obtenez une mission secondaire.

{% hint style="info" %}
Vous pouvez avoir jusqu'à 3 missions secondaires.
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 190037.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 190047.png" alt=""></picture><figcaption><p>Exemple d'obtention d'une mission secondaire</p></figcaption></figure>

## Trouver une potion

**Rareté : 8**

Vous trouvez une potion aléatoire.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192729.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192718.png" alt=""></picture><figcaption><p>Exemple de gain de potion</p></figcaption></figure>

## Gobelets

**Rareté : 2**

Un homme suspect s'approche de vous et vous fait participer à un jeu composé de trois gobelets :&#x20;

* Gobelet en métal :dragon\_face:
* Grand gobelet :bucket:
* Gobelet scintillant sculpté dans un bois bleu :sparkles:

Vous devrez faire un choix entre ces trois gobelets qui vous donnera une des issues suivantes :&#x20;

* Perdre une quantité de vie dépendant de votre niveau
* Une altération qui dépend de votre niveau
* Rien

{% hint style="info" %}
En réagissant avec :end:, l'action "Ne rien faire" se déclenche et vous perdez une quantité de vie dépendant de votre niveau.
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192829.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192839.png" alt=""></picture><figcaption><p>Exemple du jeu de gobelets</p></figcaption></figure>

{% hint style="info" %}
Ce mini-événement n'apparait pas autour de la Route des Merveilles, de la Route Marécageuse et du mont Célestrum.
{% endhint %}

## Membres du staff

**Rareté : 1**

Ce mini-évènement vous contera une histoire à propos d'un membre du staff.

<details>

<summary>Liste des membres qui possèdent leurs légendes:</summary>

* Nysvaa
* Thero1st
* Oscar
* QQtin
* LePourfendeur
* Ines
* romain22222
* Izuku
* Draft
* Royal
* Max
* Eagle
* DeadAngelV6
* Kyusaki
* Greninja\_san
* nwcubeok
* SuperBananeNinja
* Hitori
* Pietagorh
* Doctor
* KirIcare
* symsym
* Pagotortoise
* Voltou
* Ntalcme
* aureochocob0n
* BananePlantain
* Ravenclaw
* GabrieLre



</details>

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192946.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 192935.png" alt=""></picture><figcaption><p>Exemple de légende d'un staff</p></figcaption></figure>

## Espace

**Rareté : 3**

<details>

<summary>Vous rencontrez un homme se disant être un oracle, il vous donnera une vraie information (hormis quelques détails, comme les noms) sur l'espace parmi celles-ci: </summary>

* Un objet se rapprochant de la Terre
* Les phases de la Lune
* La prochaine pleine Lune
* La prochaine éclipse lunaire partielle
* La prochaine éclipse lunaire totale

</details>

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193031.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193040.png" alt=""></picture><figcaption><p>Exemple de rencontre avec l'oracle</p></figcaption></figure>

## Récupération totale d'énergie

**Rareté : 8**

Vous rencontrez une jeune femme qui vous fera regagner toute votre énergie.

{% hint style="info" %}
Vous n'obtiendrez ce mini-évènement que si votre énergie n'est pas déjà complète.
{% endhint %}

{% hint style="info" %}
La guérisseuse ne se balade qu'autour de Claire De Ville.&#x20;
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193145.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193135.png" alt=""></picture><figcaption><p>Exemple de récupération d'énergie</p></figcaption></figure>

## Gagner de l'expérience de guilde

**Rareté : 5**

Grâce à vous, votre guilde se fait connaitre et elle remporte de l'expérience de guilde. La quantité d'expérience de guilde reçue dépend de son niveau.

{% hint style="info" %}
Vous n'obtiendrez ce mini-évènement que si vous faites partie d'une guilde qui n'est pas niveau 150.
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193231.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193244.png" alt=""></picture><figcaption><p>Exemple de gain d'expérience de guilde</p></figcaption></figure>

## Gagner des points de vie

**Rareté : 3**

Durant votre voyage, il vous arrivera de récupérer des points de vies (entre 1:heart:et 4:heart:).&#x20;

{% hint style="info" %}
Vous n'obtiendrez ce mini-évènement que si votre vie n'est pas déjà à son maximum.
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193352.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193340.png" alt=""></picture><figcaption><p>Exemple de gain de points de vie</p></figcaption></figure>

## Gagner de l'expérience

**Rareté : 3**

Durant votre voyage, il vous arrivera de gagner de l'expérience (entre 10:star:et 35:star:).

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193445.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193457.png" alt=""></picture><figcaption><p>Exemple de gain d'expérience</p></figcaption></figure>

## Sorcière

**Rareté : 4**

Vous rencontrez une sorcière préparant une potion. Vous pourrez lui conseiller de :&#x20;

* Faire une action
* Ajouter un ingrédient
* Ajouter un ingrédient ou faire une action

Selon votre choix, vous pourrez :&#x20;

* Recevoir une potion
* Avoir une altération d'état
* Perdre de la vie
* Ne rien avoir

{% hint style="info" %}
Si vous êtes de la classe **Mage Mystique** :mage:, un quatrième choix s'offrira à vous et vous pourrez soit ajouter un ingrédient soit faire une action.
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193607.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193555.png" alt=""></picture><figcaption><p>Exemple de rencontre avec la sorcière (en étant mage mystique)</p></figcaption></figure>

## Marchand ultime de nourriture

**Rareté : 1**

Vous rencontrez un marchand qui vous donne une récompense parmi celles-ci :

* Des friandises si votre niveau est inférieur au niveau 30 et que votre entrepôt vous le permet.
* Des soupes ultimes si votre niveau est supérieur ou égal au niveau 30 et que votre entrepôt vous le permet.
* Un item aléatoire, dépendant de votre niveau, si le niveau de votre guilde est supérieur ou égal au niveau 30.

Si vous n'avez pas de guilde, vous recevrez de l'argent.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193704.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193715.png" alt=""></picture><figcaption><p>Exemple de mini-évènement du marchand ultime de nourriture</p></figcaption></figure>

## Récompenses de ligue

**Rareté : 2**

Ce mini-évènement vous donnera des informations sur les récompenses de votre ligue.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193840.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193830.png" alt=""></picture><figcaption><p>Exemple de mini-évènement d'informations sur les récompenses de ligue</p></figcaption></figure>

{% hint style="info" %}
Ce mini-évènement n'apparait plus le dimanche si vous avez déjà récupéré votre récompense de ligue.
{% endhint %}

## Voyage vers les [îles mystérieuses](iles-mysterieuses.md)

**Rareté : 12 (si les conditions sont remplies)**

Ce mini-évènement vous permet de voyager vers les îles mystérieuses, il ne se déclenche que si vous êtes à 80% minimum de votre énergie maximale et son prix augmente à chaque trajet effectué dans l'ordre suivant : Gratuit - 15 :gem: - 25 :gem:. Une fois 3 trajets effectués il ne vous est plus possible d'aller sur l'île, vous devrez attendre la semaine prochaine !

{% hint style="warning" %}
Ce mini-évènement ne se déclenche qu'au bord d'un point d'eau !
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193928.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 193938.png" alt=""></picture><figcaption><p>et c'est parti !</p></figcaption></figure>



## Marchand épique

**Rareté : 1**

Ce mini-événement vous fera rencontrer Aldéric, un marchand qui vous proposera un item de la rareté épique à la rareté légendaire (voir [items.md](../notions-principale/items.md "mention")) à l'exceptions des potions.

{% hint style="info" %}
Voyager sur le chemin de la :motorway: **Route des merveilles** réduira considérablement le prix de l'achat sinon vous avez 10% de chance d'avoir une réduction mais moins considérable.
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 194042.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 194032.png" alt=""></picture><figcaption><p>Exemple du marchand épique</p></figcaption></figure>

## Une charrette rapide

**Rareté : 1**

Ce mini-événement vous fera rencontrer un individu mystérieux qui vous proposera une destination connue ou non selon les critères suivants:&#x20;

* 35% de chances d'avoir un voyage dont vous connaissez la destination.
* 30% de chances d'avoir un voyage dont vous ne connaissez pas la destination avec un prix réduit.
* 15% de chances d'avoir une destination fausse mais dont le prix est diminué.
* Sinon le voyage est juste moins cher.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 194155.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 194206.png" alt=""></picture><figcaption><p>Exemple d'un voyage rapide</p></figcaption></figure>

## Le nain fan des animaux

**Rareté: 5**

Ce mini-événement vous fera rencontrer Talvar, un nain amoureux de la cause animale. Il vous récompensera avec une gemme à chaque nouvelle espèce que vous lui présenterait  si votre animal n'est pas fielleux (sinon il vous réprimandera vertement ) . Une fois toutes les espèces répertoriés (mâle ou femelle n'a pas d'importance), vous gagnerez en signe de profond respect le [badge](badges.md) :feet: (et de l'argent si vous l'avez déjà) .

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-22 120719.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-22 120730.png" alt=""></picture><figcaption><p>On raconte que son amour des animaux est aussi immense que sa richesse.</p></figcaption></figure>

{% hint style="info" %}
Ce mini-événement n'apparaît qu'autour du Mont Célestrum.
{% endhint %}

## Informations sur les combats

**Rareté : 3**&#x20;

Ce mini-événement  vous fera rencontrer Sir Rowan, ancien capitaine de la garde royale.Il vous présentera les différentes attaques du jeu qu'elles soient humaines ou monstrueuses.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 194531.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 194650.png" alt=""></picture><figcaption></figcaption></figure>

{% hint style="info" %}
Sir Rowan a également une (infime) chance de vous indiquer si votre personnage est droitier ou gaucher.
{% endhint %}

## L'homme étrange amoureux de sa ville

Rareté : 2

Ce mini-événement vous fera rencontrer un conteur passionné par une cité lointaine. Il vous interrogera sur l’intérêt que vous portez à cette ville. Vos réponses détermineront s’il vous récompense ou non.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-10-08 175955.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-10-08 180321.png" alt=""></picture><figcaption></figcaption></figure>

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-10-08 180038.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-10-08 180405.png" alt=""></picture><figcaption><p>Exemple de récompenses obtenues selon vos réponses.</p></figcaption></figure>
