# Mini-évènements

Il existe actuellement 25 types de mini-évènements différents dans le bot. Voici quelques informations au sujet des mini-évènements qui vous permettront d'aborder cette fonctionnalité de manière plus stratégique.

Plus la valeur de la rareté d'un mini-évènement est élevée, plus celui-ci est fréquent.

{% hint style="info" %}
La rareté maximale actuelle est de 12 (très fréquent) !
{% endhint %}

## Mini-shop

**Rareté :** **4**

Vous permet d'acheter un objet pour pas cher (60 % du prix). Il n'est pas possible d'obtenir des objets de rareté supérieure à spécial. Si vous achetez un objet mais que vous n'acceptez pas de remplacer votre objet, l'objet sera racheté par le vendeur pour un prix réduit à son prix d'achat.

{% hint style="warning" %}
Attention une faible proportion de vendeurs sont des arnaqueurs et tenteront de vous vendre des items pour 5 fois plus cher !
{% endhint %}

![Un exemple de mini-shop](<../.gitbook/assets/image (44).png>)

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

| Malus                           | Probabilité |
| ------------------------------- | ----------- |
| Perte de vie (1 à 5)            | Moyenne     |
| Perte d'argent (20 à 70)        | Moyenne     |
| Perte de temps (5 à 20 minutes) | Moyenne     |
| Perte d'affection (1 à 3)       | Moyenne     |
| Fuite du familier               | Très faible |

![Un exemple d'interaction avec un familier.](<../.gitbook/assets/image (45).png>)

## Trouver un familier

**Rareté : 2**

Le joueur découvre un familier qui le rejoint dans son aventure. Si le joueur a déjà un familier, le nouveau est placé dans le refuge de la guilde du joueur.

{% hint style="danger" %}
Si il n'y a plus de place dans le refuge de la guilde du joueur et que ce dernier possède déjà un familier alors cet évènement ne rapportera pas de nouveau familier.
{% endhint %}

Voilà les probabilités d'obtention pour chaque rareté de familiers :

|          |          |         |         |         |
| -------- | -------- | ------- | ------- | ------- |
| 1 :star: | 2 :star: | 3:star: | 4:star: | 5:star: |
| 87.6%    | 9.64%    | 1.664%  | 0.65%   | 0.446%  |

![Ne me demandez pas comment elle était montée là haut](<../.gitbook/assets/image (52).png>)

## Trouver un équipement

**Rareté : 2**

Le joueur découvre un équipement aléatoire. Il n'est pas possible d'obtenir des objets légendaires ou mythiques dans ce mini-évènement.

![Exemple de découverte d'un équipement](<../.gitbook/assets/image (53).png>)

## Rien ne se passe

**Rareté : 8**&#x20;

Ce mini-évènement affiche simplement une phrase d'encouragement pour le joueur.

![Un exemple du mini-évènement "Rien ne se passe"](<../.gitbook/assets/image (55).png>)

## Petit malheur

**Rareté : 8**

Parfois, tout ne se passe pas comme prévu. Certains mini-évènements amènent à de petits malus.

| Malus                    | Effet                        |
| ------------------------ | ---------------------------- |
| Perte de vie             | 1 à 5 points de vie perdus   |
| Perte d'argent           | 10 à 50 d'argent perdus      |
| Perte de temps aléatoire | 5 minutes à 2 heures perdues |

![Un exemple de petit malheur](<../.gitbook/assets/image (56).png>)

## Gros malheur

**Rareté : 1**

Parfois, tout ne se passe pas comme prévu. Certain mini-évènements amènent à de gros malus. Heureusement, cela reste très rare !

| Malus             | Effet                                                |
| ----------------- | ---------------------------------------------------- |
| Perte de vie      | 5 à 30 points de vie perdus                          |
| Perte d'argent    | 50 à 250 d'argent perdus                             |
| Altération d'état | Le joueur peut être touché par une altération d'état |

![Un exemple de gros malheur](<../.gitbook/assets/image (57).png>)

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

<figure><img src="../.gitbook/assets/loterie.PNG" alt=""><figcaption><p>Un exemple de loterie</p></figcaption></figure>

## Interaction avec un joueur sur le même trajet

**Rareté : 12**

Il est possible de rencontrer d'autres joueurs sur le même trajet en voyageant. Ce mini-évènement permet de discuter avec un joueur que vous croisez, que vous suivez ou que vous précédez !

Il existe une multitude de phrases en fonction de la situation de la personne que vous croisez !

Voilà la liste des caractéristiques qui peuvent être exploitées :

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
* Point du classement de la semaine
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

![Un exemple d'interaction avec un autre joueur](<../.gitbook/assets/image (58).png>)

## Avancement du temps

**Rareté : 6**

Avance le temps de 10 à 50 minutes.

<figure><img src="../.gitbook/assets/Capture d’écran 2023-05-26 162600.png" alt=""><figcaption><p>Exemple d'avancement du temps</p></figcaption></figure>

## Faits du Bot

**Rareté : 2**

Raconte une information à propos du bot parmi celles-ci :

* Moyenne des points totaux des joueurs
* Moyenne des points durant la semaine
* Nombre de joueurs qui ont commencé leur aventure
* Moyenne du niveaux des joueurs
* Argent total en circulation
* Balance du joueur le plus riche
* Nombre de pets dressés
* Nombre de pets fielleux
* Pourcentage de pets femelles dans le jeu
* Pourcentage de pets mâles dans le jeu
* Moyenne du niveau des guildes
* Nombre de joueurs d'une classe
* Nombre de joueurs voyageant sur notre chemin&#x20;

<figure><img src="../.gitbook/assets/Capture d’écran 2023-05-26 164600.png" alt=""><figcaption><p>Exemple d'une information à propos du bot</p></figcaption></figure>

## Vote

**Rareté : 4**

Obtenir une récompense en ayant voté pour le bot sur top.gg parmi celles-ci :

* Argent (entre 150 et 250)
* Item aléatoire

Si vous n'aviez pas voté pour le bot, vous ne verrez qu'un rappel pour voter pour celui-ci.

<figure><img src="../.gitbook/assets/Capture d’écran 2023-05-26 164938.png" alt=""><figcaption><p>Exemple de récompense du vote</p></figcaption></figure>

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

<figure><img src="../.gitbook/assets/Capture d’écran 2023-05-26 171548.png" alt=""><figcaption><p>Exemple de gain dépendant d'une classe</p></figcaption></figure>

## Trouver une mission

**Rareté : 6**

Vous obtenez une mission secondaire.

{% hint style="info" %}
Vous pouvez avoir jusqu'à 3 missions secondaires au maximum.
{% endhint %}

<figure><img src="../.gitbook/assets/Screenshot_20230526_212110_Discord[1] (1).jpg" alt=""><figcaption><p>Exemple d'obtention d'une mission secondaire</p></figcaption></figure>

## Trouver une potion

**Rareté : 8**

Vous trouvez une potion aléatoire.

<figure><img src="../.gitbook/assets/Screenshot_20230526_213001_Discord[1].jpg" alt=""><figcaption><p>Exemple de gain de potion</p></figcaption></figure>

## Gobelets

**Rareté : 2**

Un homme suspect s'approche de vous et vous fait participer à un jeu composé de trois gobelets :&#x20;

* Gobelet en métal :dragon\_face:
* Grand gobelet :bucket:
* Gobelet scintillant sculpté dans un bois bleu :sparkles:

Vous devrez faire un choix entre ces trois gobelets qui vous donnera une des issues suivantes :&#x20;

* Perdre une certaine quantité de vie dépendant de votre niveau
* Une altération qui dépend de votre niveau
* Rien

{% hint style="info" %}
En réagissant avec :end:, l'action "Ne rien faire" se déclenche et vous perdez une quantité de vie dépendant de votre niveau.
{% endhint %}

<figure><img src="../.gitbook/assets/Screenshot_20230526_215537_Discord[1].jpg" alt=""><figcaption><p>Exemple du jeu de gobelets</p></figcaption></figure>

## Membres du staff

**Rareté : 1**

Ce mini-évènement vous contera une histoire à propos d'un membre du staff.

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

<figure><img src="../.gitbook/assets/Screenshot_20230527_091722_Discord[1].jpg" alt=""><figcaption><p>Exemple de légende d'un staff</p></figcaption></figure>

## Espace

**Rareté : 3**

Vous rencontrez un homme se disant être un oracle, il vous donnera une vraie information (hormis quelques détails, comme les noms) sur l'espace parmi celles-ci :

* Un objet se rapprochant de la Terre
* Les phases de la Lune
* La prochaine pleine Lune
* La prochaine éclipse lunaire partielle
* La prochaine éclipse lunaire totale

<figure><img src="../.gitbook/assets/Screenshot_20230527_092955_Discord[1].jpg" alt=""><figcaption><p>Exemple de rencontre avec l'oracle</p></figcaption></figure>

## Récupération totale d'énergie

**Rareté : 8**

Vous rencontrez une jeune femme qui vous fera regagner toute votre énergie.

{% hint style="info" %}
Vous n'obtiendrez ce mini-évènement uniquement si votre énergie n'est pas déjà complète.
{% endhint %}

{% hint style="info" %}
La guérisseuse ne se balade qu'autour de Claire De Ville.&#x20;
{% endhint %}

<figure><img src="../.gitbook/assets/Capture d’écran 2023-05-27 105208.png" alt=""><figcaption><p>Exemple de récupération d'énergie</p></figcaption></figure>

## Gagner de l'expérience de guilde

**Rareté : 5**

Grâce à vous, votre guilde se fait connaitre et elle remporte de l'expérience de guilde dépendant du niveau de celle-ci.

{% hint style="info" %}
Vous n'obtiendrez ce mini-évènement uniquement si vous faites parti d'une guilde qui n'est pas niveau 100.
{% endhint %}

<figure><img src="../.gitbook/assets/Screenshot_20230527_095045_Discord[1].jpg" alt=""><figcaption><p>Exemple de gain d'expérience de guilde</p></figcaption></figure>

## Gagner des points de vies

**Rareté : 3**

Durant votre voyage, il vous arrivera de pouvoir récupérer des points de vies entre 1:heart:et 4:heart:.&#x20;

{% hint style="info" %}
Vous n'obtiendrez ce mini-évènement uniquement si votre vie n'est pas déjà à son maximum.
{% endhint %}

<figure><img src="../.gitbook/assets/Screenshot_20230527_100240_Discord[1].jpg" alt=""><figcaption><p>Exemple de gain de points de vie</p></figcaption></figure>

## Gagner de l'expérience

**Rareté : 3**

Durant votre voyage, il vous arrivera de gagner de l'expérience entre 10:star:et 35:star:.

<figure><img src="../.gitbook/assets/Screenshot_20230527_100724_Discord[1].jpg" alt=""><figcaption><p>Exemple de gain d'expérience</p></figcaption></figure>

## Sorcière

**Rareté : 4**

Vous rencontrez une sorcière préparant une potion. Vous pourrez lui conseiller de :&#x20;

* Faire une action
* Ajouter un ingrédient
* Ajouter un ingrédient ou faire une action

Selon votre choix, vous pourrez :&#x20;

* Recevoir une potion
* Avoir une altération d'état
* Perdre la vie
* Ne rien avoir

{% hint style="info" %}
En réagissant avec :end:, l'action "Ne rien faire" se déclenche et il ne vous arrivera rien.
{% endhint %}

{% hint style="info" %}
Si vous êtes de la classe **Mage Mystique** :mage:, un quatrième choix s'offrira à vous et vous pourrez soit ajouter un ingrédient ou faire une action.
{% endhint %}

<figure><img src="../.gitbook/assets/Screenshot_20230527_102423_Discord[1].jpg" alt=""><figcaption><p>Exemple de rencontre avec la sorcière</p></figcaption></figure>

## Marchand ultime de nourriture

**Rareté : 1**

Vous rencontrez un marchand qui vous donnera une récompense parmi celles-ci :

* XP pour votre guilde si celle-ci n'est pas déjà au niveau max.
* Des bonbons si votre guilde est inférieur au niveau 30 et que votre entrepôt vous le permet
* Des soupes ultimes si votre guilde est supérieure ou égale au niveau 30 et que votre entrepôt vous le permet
* Un item aléatoire, dépendant de votre niveau, si votre guilde est supérieure ou égale au niveau 30

Si vous n'avez pas de guilde, vous recevrez de l'argent.

<figure><img src="../.gitbook/assets/Screenshot_20230527_114742_Discord[1].jpg" alt=""><figcaption><p>Exemple du marchand ultime de nourriture</p></figcaption></figure>

## Récompenses de ligue

**Rareté : 2**

Ce mini-évènement vous donnera des informations sur les récompenses de votre ligue.

<figure><img src="../.gitbook/assets/Screenshot_20230527_123645_Discord[1].jpg" alt=""><figcaption><p>Exemple d'informations des récompenses de ligue</p></figcaption></figure>

## Voyage vers l'île du [PVE](pve.md)

**Rareté : 12 (si les conditions sont remplies)**

Ce mini-event vous permet de voyager vers l'île du PVE, celui-ci ne se déclenche que si vous êtes à 80% minimum de votre énergie maximale et son prix augmente à chaque trajet effectué dans l'ordre suivant : Gratuit - 15 :gem: - 25 :gem:. Une fois 3 trajets effectués il ne vous est plus possible d'aller sur l'île, vous devrez attendre la semaine prochaine !

{% hint style="warning" %}
Ce mini-event ne se déclenche qu'au bord d'un point d'eau !
{% endhint %}

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>et c'est parti !</p></figcaption></figure>
