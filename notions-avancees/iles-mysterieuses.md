---
description: >-
  Les îles mystérieuses sont des lieux où les joueurs peuvent se rendre avec
  leur guilde afin d'affronter des monstres sauvages.
---

# Îles mystérieuses

Les monstres sont réparties sur 2 îles : l'île volcanique et l'île de glace.

{% hint style="info" %}
&#x20;Chaque semaine une île est choisie et il ne peut pas avoir 2 semaines de suite la même île.
{% endhint %}

## Comment y aller ?

Ces îles mystérieuses peuvent être rejointes au travers d'un [mini-évènement](mini-evenements.md) à partir du niveau 20.

<figure><picture><source srcset="../.gitbook/assets/bateau_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/bateau.png" alt=""></picture><figcaption><p>On dirait que quelqu'un est sur le point de partir…</p></figcaption></figure>

{% hint style="success" %}
Si un membre de votre guilde est déjà sur un bateau, il vous suffit de faire `/rejoindrebateau` pour le rejoindre !
{% endhint %}

Sur ces îles, le jeu se déroule comme des trajets normaux, à la différence que le temps y passe plus vite : un mini-évènement est disponible toutes les 18s environ et les trajets entre les lieux durent 4min.

{% hint style="info" %}
Les trajets pour aller sur une île et pour la quitter auront des temps différents de ceux sur cette île:

* pour aller sur une île, cela prendra 30 minutes, avec le temps habituel entre 2 mini-évènements ;
* pour quitter l'île, vous ne prendrez que 5 minutes sans mini-évènement, mais avec un évènement spécifique célébrant votre exploit ;
* une fois l'île quittée, votre destination sera une côte du continent principal et son trajet durera 8 minutes.
{% endhint %}

{% hint style="success" %}
Vous pouvez quitter l'île à la fin de chaque combat si vous sentez que vous ne tiendrez pas le coup face au prochain monstre avec votre énergie restante.
{% endhint %}

{% hint style="info" %}
Si vous choisissez de vous rendre sur l'île avec des membres de votre guilde, le bonus "allié.s" sera activé.&#x20;

Ce bonus réduira les malus rencontrés lors des mini-évènements. Il est actif lors qu'un membre descend du bateau et jusqu'à une heure après son départ de l'île.&#x20;

Pour connaître le nombre d'alliés présents sur l'île, utilisez la commande /guilde et consultez la section des informations sous la liste des membres de la guilde. Le nombre d'alliés sur l'île est indiqué dans la ligne "Nombre d'alliés sur l'île mystérieuse".&#x20;

Vous pouvez également identifier les alliés présents grâce à l'émoji :handshake: affiché à côté de leur pseudo.
{% endhint %}

{% hint style="danger" %}
Sur l'île, vous ne regagnerez pas d'énergie naturellement, le seul moyen étant de tomber sur des mini-évènements de gain d'énergie.

Certaines commandes seront aussi interdites sur l'île afin d'empêcher toute tentative de triche.
{% endhint %}

## Combats

Les îles se décomposent en une série de lieux, avec un monstre à combattre différent pour chacun d'entre eux. Après une victoire face à un monstre, vous gagnerez de l'argent et de l'expérience. De plus, si vous appartenez à une guilde, elle recevra aussi de l'expérience (si votre guilde n'est pas au niveau 150) et des points de guilde !

{% hint style="info" %}
Pendant le combat, si vous êtes plusieurs dans votre guilde à être sur l'île, il y a une petite chance que l'attaque de guilde :stadium: apparaisse : sa puissance varie avec le nombre de membres présents !
{% endhint %}

{% hint style="warning" %}
Si vous perdez face à un des monstres ci-dessous, vous quitterez instantanément l'île et serez déposé vers un lieu aléatoire avec l'altération :confounded:. De plus, vous perdez de l'argent :moneybag: et des points de guilde (si vous appartenez à une guilde). Si vous n'avez pas de guilde, vous perdez le double d'argent.
{% endhint %}

## Liste des monstres de l'île volcanique :

<figure><img src="../.gitbook/assets/carte_ile_volcanique_fr.jpg" alt=""><figcaption><p>Il y a une odeur de cendres dans l'air !</p></figcaption></figure>

### Forêt de la pénombre

Ici, vous affrontez aléatoirement l'un des ces 2 monstres :

**Monstre : Troll de la forêt**

> Un grand troll qui vit dans les forêts. Très fort et très résistant, il est aussi très agressif et attaque tout ce qui bouge. Il est très dangereux pour les aventuriers qui s'aventurent dans les forêts.

**Attaques**:

| Nom de l'attaque                            | Description                                                                                                                                                         | Consommation en souffle |
| ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :cricket\_game: Attaque gourdin             | Attaque en deux tours, avec une charge puissante au deuxième.                                                                                                       | 9                       |
| :martial\_arts\_uniform: Attaque projection | Projette l'adversaire s'il utilise une attaque physique. Peut étourdir l'adversaire.                                                                                | 6                       |
| :rage: Colère                               | Augmente son attaque de 100%, en dépit de 75% de sa défense.                                                                                                        | 1                       |
| :sound:Rugissement                          | Baisse l'attaque et la vitesse de l'adversaire.                                                                                                                     | 4                       |
| :triumph: Attaque intense                   | <p>Niveau 50+ uniquement. </p><p>Voir la page des <a href="https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques">combats</a></p> | 4                       |

**Monstre : Mutant Vaseux**

> Le Mutant Vaseux est un monstre pouvant copier les autres monstres ou son adversaire directement. Il est très polyvalent et peut s'adapter à toutes les situations.

| Nom de l'attaque                          | Description                                                                                                                                                                                                      | Consommation en souffle |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :performing\_arts:Attaque mimique magique | <p>Niveau 60+ uniquement. </p><p>Fonctionne comme une <a href="iles-mysterieuses.md#combats">attaque simple</a> en temps normal sauf si l'adversaire lance une attaque magique, celle-ci se verra répliquer.</p> | 3                       |
| :test\_tube:Attaque empoisonnée           | Voir la page des [combats](https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques)                                                                                              | 3                       |
| :farmer:Attaque tir de boue               | Lance de la boue sur l'adversaire qui le rend sale et augmente de 5% son attaque, l'altération a 20% de chances de disparaître à chaque tour.                                                                    | 5                       |
| :amphora: Attaque boue brûlante           | Attaque puissante si l'adversaire est sali ! Sinon dégâts classiques.                                                                                                                                            | 9                       |

### Mine brumeuse

**Monstre : Araignée**

> Une grosse araignée poilue. D'une espèce inconnue, elle attaque tous les voyageurs qui s'approchent de son nid. Venimeuse, elle peut aussi projeter de la soie pour immobiliser ses proies.

**Attaques**:

| Nom de l'attaque                      | Description                                                                                                                                                                     | Consommation en souffle |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :test\_tube: Attaque empoisonnée      | <p>Niveau 40+ uniquement. </p><p>Voir la page des <a href="https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques">combats</a></p>             | 3                       |
| :spider\_web: Attaque jet de toile    | Envoie un jet de toile qui blesse et ralentit l'adversaire.                                                                                                                     | 8                       |
| :face\_in\_clouds: Discrétion         | Se cache afin de doubler les dégâts de la prochaine attaque.                                                                                                                    | 6                       |
| :crossed\_swords: Attaque simple      | Voir la page des [combats](https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques)                                                             | 2                       |
| :fork\_knife\_plate: Repas de famille | Niveau 60+ uniquement. Appelle des alliés pour dévorer l'adversaire et l'empoisonner au passage. Inflige l'altération "Repu" au lanceur, l'empêchant de bouger pendant 2 tours. | 20                      |

### Village en ruines

**Monstre : Squelette**

> Un squelette étrange, il semble être un ancien guerrier. Il paraît faible mais est en réalité très dangereux et nombreux sont ceux qui se sont laissés surprendre.

**Attaques**:

| Nom de l'attaque                             | Description                                                                                                                                                         | Consommation en souffle |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :crossed\_swords: Attaque simple             | Voir la page des [combats](https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques)                                                 | 2                       |
| :shield: Attaque bouclier                    | Voir la page des [combats](https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques)                                                 | 6                       |
| :bed: Repos                                  | Voir la page des [combats](https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques)                                                 | 0                       |
| :smiling\_imp: Attaque maudite               | <p>Niveau 50+ uniquement. </p><p>Voir la page des <a href="https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques">combats</a></p> | 6                       |
| :people\_holding\_hands: Invocation d'alliés | Niveau 65+ uniquement. Appelle des alliés afin de cumuler les dégâts infligés par chacun des adversaires invoqués en plus de ceux du lanceur.                       | 5                       |

### Chemin escarpé

**Monstre : Golem de roche**

> Un immense golem de roche. Animé par le désir d'écraser tout ce qui s'en approche. Il est très lent, mais ses attaques sont dévastatrices.

**Attaques**:

| Nom de l'attaque             | Description                                                                                                                                     | Consommation en souffle |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :rock: Attaque rocheuse      | Lance des rochers sur l'adversaire. Peut l'étourdir.                                                                                            | 6                       |
| :foot: Attaque impact        | Le lanceur se jette sur l'adversaire, lui réduisant sa vitesse.                                                                                 | 6                       |
| :bricks: Peau de roche       | Recouvre sa peau de roches, augmentant sa défense considérablement si cette attaque est lancée plusieurs fois d'affilée.                        | 3                       |
| :mountain: Bouclier de roche | Crée un bouclier avec des rochers, amortissant la moitié des dégâts de la prochaine attaque de l'adversaire.                                    | 2                       |
| :headstone: Pétrification    | Niveau 50+ uniquement. Transforme l'adversaire en pierre et l'empêche d'attaquer pendant quelques tours, mais en augmentant sa défense de 200%. | 8                       |

### Volcan grondant

**Monstre : Titan de magma**

> Le monstre le plus puissant de l'île. Bouillant de chaleur, il est capable de faire fondre les roches les plus dures. Très peu d'aventuriers ont réussi à s'en défaire et il serait périlleux de l'attaquer seul.

**Attaques**:

| Nom de l'attaque           | Description                                                                                                                                                                                                          | Consommation en souffle |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :volcano: Éruption         | Fait entrer en éruption le volcan grondant. Émet des rochers en fusion infligeant des dégâts à l'adversaire pendant quelques tours.                                                                                  | 7                       |
| :foot: Attaque impact      | Le lanceur se jette sur l'adversaire, lui réduisant sa vitesse.                                                                                                                                                      | 6                       |
| :fire:Attaque feu          | Voir la page des [combats](https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques)                                                                                                  | 8                       |
| :bathtub: Bain de magma    | Fonctionne comme Repos (voir page des [combats](https://guide.draftbot.com/notions-principale/combats#detaille-des-differentes-attaques)). Le lanceur se baigne dans du magma, régénérant une partie de son énergie. | 2                       |
| :hotsprings: Vague de lave | Niveau 50+ uniquement. Le lanceur surfe sur une vague de lave se dirigeant droit sur l'adversaire, infligeant des dégâts importants et le brûlant au passage.                                                        | 15                      |

## Liste des monstres de l'île de glace :

<figure><img src="../.gitbook/assets/carte_ile_de_glace_fr.png" alt=""><figcaption><p>Il vaut mieux bien se couvrir !</p></figcaption></figure>

### Toundra&#x20;

#### Monstre : loup blanc

> Un prédateur féroce et agile. Ses griffes acérées pourraient sceller votre destin. Le froid et les sentiers sinueux lui offrent un grand avantage face aux aventuriers imprudents.

| Nom de l'attaque                 | Description                                                                                                                       | Consommation en souffle |
| -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :tooth:Attaque morsure puissante | Une morsure qui applique l'altération saignement.                                                                                 | 6                       |
| :face\_in\_clouds:Discrétion     | Se cache afin de doubler les dégâts de la prochaine attaque.                                                                      | 6                       |
| 🌕Hurlement                      | Améliore aléatoirement l'attaque, la défense ou la vitesse.                                                                       | 1                       |
| :feet:Attaque griffure           | Un violent coup de griffe.                                                                                                        | 2                       |
| :wolf:Appel à la meute           | Il appelle sa meute à l'aide. La première attaque fait de faible dégâts et les suivantes sont renforcés par la force de la meute. | 9                       |

### Caverne de cristal

#### Monstre : Élémentaire brillant

> Un être né des cristaux de la caverne. Il n'hésitera pas à utiliser ses pouvoirs élémentaires pour vous faire valser à l'autre bout du chemin.

| Nom de l'attaque                | Description                                                                                                                                     | Consommation en souffle |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| 🪦 Pétrification                | Niveau 50+ uniquement. Transforme l'adversaire en pierre et l'empêche d'attaquer pendant quelques tours, mais en augmentant sa défense de 200%. | 8                       |
| 🪡Attaque perçante              | Voir la page des [combats](../notions-principale/combats.md#detail-des-differentes-attaques)                                                    | 5                       |
| ⛰️ Bouclier de roche            | Crée un bouclier avec des rochers, amortissant la moitié des dégâts de la prochaine attaque de l'adversaire.                                    | 2                       |
| :sunny:Attaque rayon de lumière | Un rayon de lumière si puissant qu'il peut vous brûler ou vous aveugler.                                                                        | 7                       |
| 🔮Attaque éclat de cristal      | Niveau 90+. Une attaque qui inflige plus de dégâts aux adversaires lents.                                                                       | 3                       |

### Lac souterrain

#### Monstre : Crocodile

> Un grand crocodile terrifiant, à la recherche d'un aventurier pour en faire son festin.

| Nom de l'attaque                 | Description                                                                                                            | Consommation en souffle |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :tooth:Attaque morsure puissante | Une morsure qui applique l'altération saignement.                                                                      | 6                       |
| :foot:Attaque impact             | Le lanceur se jette sur l'adversaire, lui réduisant sa vitesse.                                                        | 6                       |
| 🐊Attaque coup de queue          | Une puissante coup de queue qui peut étourdir.                                                                         | 2                       |
| 🥋 Attaque projection            | Niveau 40+. Projette l'adversaire s'il utilise une attaque physique. Peut étourdir l'adversaire.                       | 6                       |
| :face\_in\_clouds:Embuscade      | Niveau 80+. Annule les dégâts de la prochaine attaque du joueur tout en augmentant les dégâts de sa prochaine attaque. | 0                       |

### Village dévasté&#x20;

#### Monstre : Yuki Onna

> Une femme esprit des neiges. Elle est très belle mais aussi très dangereuse. Elle peut geler ses proies d'un simple regard et les faire disparaître dans la neige.

| Nom de l'attaque                  | Description                                                                                                                                      | Consommation en souffle |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------- |
| 🌡️ Attaque drain de chaleur      | Augmente l'attaque du lanceur et gèle l'adversaire.                                                                                              | 7                       |
| :dash:Attaque vol de souffle      | Niveau 50+. Voir la page des [combats](../notions-principale/combats.md#detail-des-differentes-attaques)                                         | 1                       |
| ❄️ Attaque séduction glaciale     | Niveau 110+. Peut geler ou rendre confus l'adversaire en plus de lui infliger des dégâts.                                                        | 5                       |
| 💋Attaque baiser gelé             | Gèle et fait des dégâts (fortement réduits si déjà gelé).                                                                                        | 4                       |
| :ghost:Attaque revanche spectrale | Semblable à [l'attaque riposte](../notions-principale/combats.md#detail-des-differentes-attaques).Échoue si l'attaque précédente était magique.  | 8                       |

### Portes sacrées

#### Monstre : gardien céleste

> Le gardien des portes sacrées. Empêcher les aventuriers de passer est son devoir, et il utilisera son marteau divin pour vous faire comprendre que vous n'êtes pas le bienvenu.

| Nom de l'attaque                      | Description                                                                                                                                                       | Consommation de souffle |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :pray:Attaque divine                  | Voir la page des [combats](../notions-principale/combats.md#detail-des-differentes-attaques)                                                                      | 9                       |
| :axe:Attaque puissante                | Voir la page des [combats](../notions-principale/combats.md#detail-des-differentes-attaques)                                                                      | 6                       |
| :bed:Repos                            | Voir la page des [combats](../notions-principale/combats.md#detail-des-differentes-attaques)                                                                      | 0                       |
| :sunny:Attaque rayon radieux explosif | Charge son attaque pendant 2 tours et inflige de gros dégâts au troisième tour pouvant brûler ou aveugler.                                                        | 8                       |
| :hammer:Attaque marteau sismique      | Niveau 50+. Le lanceur frappe le sol avec une force titanesque, infligeant de lourds dégâts.Il est possible d'esquiver les séismes à l'aide d'un familier volant. | 9                       |

### Pic enneigé&#x20;

#### Monstre : Seigneur des glaces

> Un majestueux dragon aux écailles cristallines qui règne depuis les sommets glacés. Perché sur les pics les plus élevés, il surveille son territoire d'un œil vigilant. Son souffle glacial peut transformer un aventurier en statue de glace en quelques secondes, et ses serres acérées lui permettent de fondre sur ses proies depuis les hauteurs avec une précision mortelle.

| Nom de l'attaque                | Description                                                                                                                               | Consommation en souffle |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| :feet:Attaque griffure          | Un violent coup de griffe.                                                                                                                | 2                       |
| :dragon:Attaque souffle glacial | Libère un vent glacé qui inflige des dégâts à l'adversaire et a une chance de le geler.                                                   | 13                      |
| 🌨️ Attaque rage de blizzard    | Peut geler, ralentir et réduire la défense de l'adversaire. Utilisable une fois par combat.                                               | 10                      |
| 🦅Attaque plongée aérienne      | Niveau 80+. Il fond sur son adversaire depuis les airs. Échoue si l'attaque précédente est une attaque à distance.                        | 8                       |
| 🧊Attaque armure cristalline    | Niveau 50+. Utilise le bouclier de l'adversaire pour attaquer. Réussit uniquement si l'attaque précédente de son adversaire est physique. | 3                       |

### Nid glacé

#### Monstre : Reine des glaces

> Une redoutable dragonne qui protège férocement son trésor et sa progéniture dans les profondeurs glacées de son antre. Plus agressive que son compagnon, elle n'hésite pas à déchaîner sa fureur contre quiconque ose s'approcher de son nid. Ses écailles scintillent comme des diamants et sa queue peut briser la glace la plus épaisse d'un seul coup.

| Nom de l'attaque                | Description                                                                                                                                    | Consommation en souffle |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| 🐊Attaque coup de queue         | Une puissante coup de queue qui peut étourdir.                                                                                                 | 2                       |
| 🤍Étreinte de glace             | Niveau 70+. Fait des dégâts et peut vous geler. Cette étreinte se prolongera si vous ne vous ne vous défendez pas avec une attaque à distance. | 7                       |
| 🧊Attaque armure cristalline    | Utilise le bouclier de l'adversaire pour attaquer. Réussit uniquement si l'attaque précédente de son adversaire est physique.                  | 3                       |
| 🐉Attaque souffle glacial       | Libère un vent glacé qui inflige des dégâts à l'adversaire et a une chance de le geler.                                                        | 13                      |
| 💥Attaque effondrement glacial  | Niveau 50+.  Une chute de stalactites qui peut être esquiver par anticipation en faisant une attaque physique.                                 | 9                       |

## Mini-évènements

Pendant vos trajets, vous rencontrerez des obstacles différents du continent. Ceux-ci sont listés ci dessous :

{% hint style="info" %}
La rareté représente la fréquence à laquelle vous risquez de tomber sur l'un des mini-évènements ci-dessous : plus la rareté est élevée, plus le mini-évènement est fréquent.
{% endhint %}

{% hint style="info" %}
De plus, la présence d'un ou plusieurs membres de votre guilde sur l'île en même temps que vous aura une influence sur la qualité des mini-évènements rencontrés.
{% endhint %}

### Gain d'énergie

**rareté : 5**

Comme son nom l'indique, il vous permet de récupérer un peu d'énergie.

<figure><picture><source srcset="../.gitbook/assets/gainenergyonisland_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/gainenergyonisland_clair.png" alt=""></picture><figcaption><p>Exemple de mini-évènement de gain d'énergie</p></figcaption></figure>

### Péripéties

**rareté : 8**

Durant votre expédition sur l'île, certaines péripéties peuvent survenir, et vous (ainsi que votre guilde si vous en avez une) tentez de surmonter ces catastrophes. Ces mini-évènements ont des issues dépendantes de votre appartenance à une guilde. Ils peuvent ne rien faire, apporter un gain (points de guilde, expérience...) ou vous faire perdre de l'énergie, de l'argent ou de la vie.

{% hint style="warning" %}
Les gains ne sont récoltés que si vous appartenez à une guilde. Si vous êtes du genre solitaire, vous ne gagnerez rien, même si l'issue est positive !
{% endhint %}

<figure><img src="../.gitbook/assets/péripétie_clair.png" alt=""><figcaption><p>Exemple de péripétie</p></figcaption></figure>

### Combat face à un animal sauvage

**rareté : 8**

Vous rencontrez un animal sauvage qui se met à vous attaquer ! Pour le calmer, vous disposez de 2 à 4 options choisies aléatoirement, dépendant de votre niveau et de votre classe.

{% hint style="success" %}
Si vous réussissez à calmer l'animal (ou à faire en sorte qu'il ne vous attaque pas), vous obtenez un point de rage (cumulable), c'est-à-dire des dégâts supplémentaires face au monstre de la zone suivante, appliqués en début de combat avant la 1ère attaque du joueur.
{% endhint %}

<figure><img src="../.gitbook/assets/image (79).png" alt=""><figcaption><p>L'appel à l'aide est parfois une bonne solution !</p></figcaption></figure>

### Informations sur l'île

**rareté : 1 - uniquement disponible sur le trajet en bateau vers l'île**

L'équipage du bateau vous donnera des informations sur l'île vers laquelle vous vous dirigez. Ces infos peuvent vous être utiles pour votre aventure au-delà des côtes du continent principal.

<figure><img src="../.gitbook/assets/boatAdvice.png" alt=""><figcaption><p>Exemple de mini-évènement donnant des informations sur l'île</p></figcaption></figure>

{% hint style="info" %}
Malgré sa rareté de 1, il est le seul mini-événement disponible sur le trajet en bateau vers l'île.
{% endhint %}

## Classement des guildes

Au fil de votre progression, les joueurs gagnent des points de guilde :mirror\_ball: après chaque victoire face à un monstre (et en perdent après une défaite) ou lors de mini-évènements sur l'île. Ces points permettent de faire progresser sa guilde parmi un classement visible avec la commande `/classement guildes`.

&#x20;&#x20;

<figure><picture><source srcset="../.gitbook/assets/classement_guildes_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/classement_guildes.png" alt=""></picture><figcaption><p>Première page du classement des guildes avec le nom, niveau et nombre de points de chaque guilde</p></figcaption></figure>
