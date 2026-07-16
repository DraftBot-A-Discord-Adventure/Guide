---
tags:
  - images-pas-a-jour
---

# Familiers

Depuis la version [2.1.2](https://history.crownicles.com/crownicles-v2/2.1.2) de Crownicles, vous pouvez avoir un ou plusieurs **familiers**.

Pour avoir les informations sur votre familier, vous devez utiliser la commande `/familier`.

Les niveaux de **rareté** de familiers sont les mêmes que pour les équipements (de commun à mythique).

Les familiers ont un **moral**, si vous les nourrissez à intervalle régulier leur moral augmentera. A contrario, si vous délaissez vos familiers leur moral diminuera.

### Comment obtenir un familier ?

Les familiers s'obtiennent dans les récompenses de guilde `/bonusjournalierguilde` avec 7% de chance, ou alors dans les mini-évènements.

La probabilité d'avoir des raretés supérieures augmente avec le niveau de votre guilde.

|                               |                                 |                   |                    |               |                 |               |                    |                |
| ----------------------------- | ------------------------------- | ----------------- | ------------------ | ------------- | --------------- | ------------- | ------------------ | -------------- |
| Niveau guilde/rareté familier | Commun :large\_orange\_diamond: | Peu commun :fire: | Exotique :trident: | Rare :comet:  | Spécial :dizzy: | Épique :star: | Légendaire :star2: | Mythique :gem: |
| 0-29                          | 43,76%                          | 25%               | 15%                | 10%           | 5%              | 1%            | 0,23%              | 0,02%          |
| 30-59                         | 0%                              | 44,44%            | 26,67%             | 17,78%        | 8,89%           | 1,78%         | 0,41%              | 0,04%          |
| 60-89                         | 0%                              | 0%                | 48%                | 32%           | 16%             | 3,2%          | 0,74%              | 0,06%          |
| 90-119                        | 0%                              | 0%                | 0%                 | 61,54%        | 30,77%          | 6,15%         | 1,42%              | 0,12%          |
| 120-150                       | 0%                              | 0%                | 0%                 | 0%            | 80%             | 16%           | 3,68%              | 0,32%          |

{% hint style="info" %}
Si un familier est obtenu dans un mini-évènement, sa rareté est générée avec les statistiques des guildes de niveau 20.
{% endhint %}

Vous pouvez libérer votre familier ou un familier de l'abri de guilde avec la commande `/libererfamilier`.

{% hint style="danger" %}
Attention, cette action est irréversible. Le fait de libérer un familier est définitif.
{% endhint %}

## A quoi sert un familier ?

Un familier a les fonctions suivantes:

* Lors des mini-événements, vous interagissez avec votre familier. Il peut vous donner (ou vous faire perdre) des ressources selon son moral, gagner (ou perdre) des points d'affection ou simplement ne rien se passer.
* Lors des combats, chaque familier aidera (ou du moins essayera d'aider) son propriétaire.
* Vous pouvez envoyer votre familier explorer le monde et vous rapporter des récompenses grâce aux expéditions.

Vous pouvez également le caresser (mais cela n'a aucun effet sur son moral).

<figure><picture><source srcset="../.gitbook/assets/familier_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/familier_clair (1).png" alt=""></picture><figcaption></figcaption></figure>

### Comment dresser mon familier ?

#### Acheter de la nourriture.

L'achat de nourriture pour les familiers se fait dans les villes, à l'approvisionnement de la guilde. Si vous n'avez pas de guilde, vous n'aurez accès qu'à la forme la plus basique de nourriture, c'est-à-dire la friandise, pour votre animal.

<picture><source srcset="../.gitbook/assets/Screenshot_20250617-151531.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 184818.png" alt="Le magasin de guilde permet d&#x27;acheter différentes sortes de nourriture"></picture>

{% hint style="info" %}
Il est aussi possible que votre familier trouve de la nourriture pendant l'aventure.
{% endhint %}

{% hint style="success" %}
Chaque combat peut renforcer le lien d'affection avec votre familier si celui n'est pas dressé.
{% endhint %}

#### Donner de la nourriture

La nourriture va permettre d'influer sur le moral de votre animal. Pour nourrir votre familier, vous devez utiliser la commande `/nourrirfamilier`.

<figure><picture><source srcset="../.gitbook/assets/nourrirfamilier_sombre (2).png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/nourrirfamilier_clair (2).png" alt="Don de nourriture à son familier via la commande /nourrirfamilier"></picture><figcaption><p>La commande /nourrirfamilier</p></figcaption></figure>

Chaque type de nourriture fera gagner une quantité différente de points d'affection à votre familier.

* Les friandises feront gagner 1 point d'affection.
* Les steaks et salade feront gagner 3 points d'affection.
* Les soupes ultimes feront gagner 5 points d'affection.

Cependant, le type de nourriture n'a pas d'influence sur la durée pendant laquelle votre familier n'a pas faim.

{% hint style="info" %}
La durée pendant laquelle un familier n'a pas faim dépend uniquement de l'espèce du familier (entre 30m et 5h).
{% endhint %}

{% hint style="warning" %}
Certains familiers suivent un régime particulier (herbivore ou carnivore) et ne pourront donc pas profiter de certaines sources de nourriture. Ne donnez pas de salade à votre T-rex !
{% endhint %}

#### Niveaux de moral

Ne négligez pas votre familier ! Son moral baissera si vous oubliez de vous en occuper.

{% hint style="warning" %}
Le moral d'un familier baisse de un point par jour en moyenne, cette baisse ne tient pas compte de la rareté du pet.
{% endhint %}

Il existe pour le moment 5 niveaux de moral qui correspondent à la mentalité de votre familier, ils sont classés de cette manière :

1. :smirk\_cat: Fielleux (entre 0 et 4 points d'affection)
2. :pouting\_cat: Sauvage (entre 5 et 24 points d'affection)
3. :scream\_cat: Craintif (entre 25 et 49 points d'affection)
4. :smiley\_cat: Apprivoisé (entre 50 et 99 points d'affection)
5. :heart\_eyes\_cat: Dressé (entre 100 et 110 points d'affection)

{% hint style="danger" %}
Il n'est pas possible d'effectuer certaines actions avec un familier fielleux !
{% endhint %}

{% hint style="warning" %}
Vendre un familier avec un autre joueur réinitialisera son moral à :pouting\_cat: Sauvage.

Changer de propriétaire, c'est dur à supporter pour un animal !
{% endhint %}

Contre 3 gemmes, le vétérinaire de la cour vous donnera des informations sur le familier que vous possédez actuellement, et lui donnera 15 points d'amour :revolving\_hearts:. La consultation s'obtient à Mergagnan ou Claire de Ville.&#x20;

<figure><picture><source srcset="../.gitbook/assets/vétérinaire_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/vétérinaire_clair.png" alt="Description du familier avec le vétérinaire , achetable via le magasin de missions , la commande /magasinmissions"></picture><figcaption><p>Il est toujours utile pour savoir s'il a perdu du moral ou pas de façon précise, quand il aura faim mais encore bien plus.</p></figcaption></figure>

### Comment stocker mon familier ?

Vous avez la possibilité de stocker votre familier dans le **refuge de votre guilde** ou alors de le récupérer avec vous. Pour cela, vous devez effectuer la commande `/transfererfamilier` . Un menu vous permet de choisir de déposer votre familier dans le refuge, de l'échanger contre un du refuge (ou d'annuler le transfert).

Pour visualiser le refuge, vous pouvez utiliser la commande `/abriguilde`.

<picture><source srcset="../.gitbook/assets/abriguilde_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/abriguilde_clair.png" alt="Refuge d&#x27;une guilde"></picture>

{% hint style="info" %}
Le refuge de votre guilde permet d'accueillir jusqu'à 6 familiers différents par défaut et bien plus en l'améliorant.&#x20;
{% endhint %}

### Comment surnommer un familier ?

Vous pouvez définir un surnom pour votre familier afin de rendre ce dernier unique. Pour cela, quand vous avez un familier avec vous tapez la commande `/surnomfamilier.`Exemple : `/surnomfamilier surnom:Henri` permet de surnommer votre familier "Henri".

<picture><source srcset="../.gitbook/assets/familer_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/familier_clair (2).png" alt="Commande /familier avec affichage du surnom du familier"></picture>

### Comment vendre un familier ?

Si vous souhaitez vous débarrasser d'un familier mais que vous n'avez pas le cœur de le libérer (ou alors que vous aimez l'argent), il est possible de vendre le familier que vous transportez. Pour cela, vous pouvez utiliser la commande `/vendrefamilier` en précisant le prix attendu. Par exemple, pour proposer votre familier à la vente pour 1000:moneybag:, entrez la commande `/vendrefamilier prix:1000`.

<figure><picture><source srcset="../.gitbook/assets/vendrefamilier_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/vendrefamilier_clair.png" alt=""></picture><figcaption><p>Ici, le familier "Chewbie" va être vendu pour 100 <span data-gb-custom-inline data-tag="emoji" data-code="1f4b0">💰</span></p></figcaption></figure>

Il y a des conditions importantes à respecter pour la vente de familiers :

* Il n'est pas possible de vendre un familier à un membre de sa guilde.
* Il est nécessaire d'appartenir à une guilde pour vendre un familier, mais pas pour l'acheter.
* Vous ne pouvez pas vendre un familier en dessous de 100:moneybag:, ni au-dessus de 50 000 :moneybag:.

{% hint style="warning" %}
L'argent sera transféré dans la trésorerie de la guilde du vendeur, moyennant une commission de 5% (maximum 350 :moneybag:)
{% endhint %}

### **Liste des familiers disponibles**

<table><thead><tr><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th width="151.2000732421875"></th></tr></thead><tbody><tr><td>Commun 🔶</td><td>Peu commun 🔥</td><td>Exotique 🔱</td><td>Rare ☄️</td><td>Spécial 💫</td><td>Épique ⭐</td><td>Légendaire 🌟</td><td>Mythique 💎</td></tr><tr><td><p>Chien.ne <span data-gb-custom-inline data-tag="emoji" data-code="1f415">🐕</span><br>Caniche <span data-gb-custom-inline data-tag="emoji" data-code="1f429">🐩</span><br>Chat.te <span data-gb-custom-inline data-tag="emoji" data-code="1f408">🐈</span><br>Chat.te noir<span data-gb-custom-inline data-tag="emoji" data-code="1f408-2b1b">🐈‍⬛</span><br>Rongeur/Souris <span data-gb-custom-inline data-tag="emoji" data-code="1f401">🐁</span><br>Hamster <span data-gb-custom-inline data-tag="emoji" data-code="1f439">🐹</span><br>Lapin.ne<br><span data-gb-custom-inline data-tag="emoji" data-code="1f407">🐇</span></p><p>Bœuf/ Vache <span data-gb-custom-inline data-tag="emoji" data-code="1f404">🐄</span><br>Porc/Truie <span data-gb-custom-inline data-tag="emoji" data-code="1f416">🐖</span><br>Poule/Coq <span data-gb-custom-inline data-tag="emoji" data-code="1f414">🐔</span><br>Oiseau <span data-gb-custom-inline data-tag="emoji" data-code="1f426">🐦</span><br>Canard/Cane <span data-gb-custom-inline data-tag="emoji" data-code="1f986">🦆</span><br>Colombe <span data-gb-custom-inline data-tag="emoji" data-code="1f54a">🕊️</span><br>Poisson <span data-gb-custom-inline data-tag="emoji" data-code="1f41f">🐟</span><br>Escargot <span data-gb-custom-inline data-tag="emoji" data-code="1f40c">🐌</span><br>Poussin <span data-gb-custom-inline data-tag="emoji" data-code="1f424">🐤</span></p></td><td>Étalon/Jument <span data-gb-custom-inline data-tag="emoji" data-code="1f40e">🐎</span><br>Bélier/Brebis <span data-gb-custom-inline data-tag="emoji" data-code="1f411">🐑</span><br>Bouc/Chèvre <span data-gb-custom-inline data-tag="emoji" data-code="1f410">🐐</span><br>Dindon/Dinde <span data-gb-custom-inline data-tag="emoji" data-code="1f983">🦃</span> <br>Renard.e <span data-gb-custom-inline data-tag="emoji" data-code="1f98a">🦊</span><br>Crapaud/Grenouille <span data-gb-custom-inline data-tag="emoji" data-code="1f438">🐸</span><br>Hibou/Chouette <span data-gb-custom-inline data-tag="emoji" data-code="1f989">🦉</span><br>Chauve-souris <span data-gb-custom-inline data-tag="emoji" data-code="1f987">🦇</span><br>Sanglier/Laie <span data-gb-custom-inline data-tag="emoji" data-code="1f417">🐗</span><br>Phoque/Otarie <span data-gb-custom-inline data-tag="emoji" data-code="1f9ad">🦭</span><br>Rat.e <span data-gb-custom-inline data-tag="emoji" data-code="1f400">🐀</span><br>Oie <span data-gb-custom-inline data-tag="emoji" data-code="1fabf">🪿</span></td><td><p>Tortue <span data-gb-custom-inline data-tag="emoji" data-code="1f422">🐢</span><br>Serpent <span data-gb-custom-inline data-tag="emoji" data-code="1f40d">🐍</span><br>Lézard.e <span data-gb-custom-inline data-tag="emoji" data-code="1f98e">🦎</span><br>Koala <span data-gb-custom-inline data-tag="emoji" data-code="1f428">🐨</span><br>Pingouin.e <span data-gb-custom-inline data-tag="emoji" data-code="1f427">🐧</span></p><p>Hippopotame <span data-gb-custom-inline data-tag="emoji" data-code="1f99b">🦛</span><br>Lama.te <span data-gb-custom-inline data-tag="emoji" data-code="1f999">🦙</span><br>Cygne <span data-gb-custom-inline data-tag="emoji" data-code="1f9a2">🦢</span><br>Flamant rose <span data-gb-custom-inline data-tag="emoji" data-code="1f9a9">🦩</span><br>Raton.ne laveur <span data-gb-custom-inline data-tag="emoji" data-code="1f99d">🦝</span><br>Putois/Mouffette <span data-gb-custom-inline data-tag="emoji" data-code="1f9a8">🦨</span><br>Blaireau/Blairelle <span data-gb-custom-inline data-tag="emoji" data-code="1f9a1">🦡</span><br>Castor <span data-gb-custom-inline data-tag="emoji" data-code="1f9ab">🦫</span><br>Âne.sse <span data-gb-custom-inline data-tag="emoji" data-code="1facf">🫏</span></p></td><td><p></p><p>Ours.e <span data-gb-custom-inline data-tag="emoji" data-code="1f43b">🐻</span><br>Loup/Louve <span data-gb-custom-inline data-tag="emoji" data-code="1f43a">🐺</span><br>Paresseux/Paresseuse <span data-gb-custom-inline data-tag="emoji" data-code="1f9a5">🦥</span><br>Tamia <span data-gb-custom-inline data-tag="emoji" data-code="1f43f">🐿️</span><br>Hérisson.ne <span data-gb-custom-inline data-tag="emoji" data-code="1f994">🦔</span><br>Ours.e polaire <span data-gb-custom-inline data-tag="emoji" data-code="1f43b-2744">🐻‍❄️</span><br>Panda <span data-gb-custom-inline data-tag="emoji" data-code="1f43c">🐼</span><br>Scorpion.ne <span data-gb-custom-inline data-tag="emoji" data-code="1f982">🦂</span><br>Crocodile <span data-gb-custom-inline data-tag="emoji" data-code="1f40a">🐊</span><br>Éléphant.e <span data-gb-custom-inline data-tag="emoji" data-code="1f418">🐘</span><br>Zèbre.lle <span data-gb-custom-inline data-tag="emoji" data-code="1f993">🦓</span><br>Méduse <span data-gb-custom-inline data-tag="emoji" data-code="1fabc">🪼</span><br>Crevette <span data-gb-custom-inline data-tag="emoji" data-code="1f990">🦐</span><br>Crabe <span data-gb-custom-inline data-tag="emoji" data-code="1f980">🦀</span></p></td><td>Singe/Guenon <span data-gb-custom-inline data-tag="emoji" data-code="1f412">🐒</span><br>Rhinocéros <span data-gb-custom-inline data-tag="emoji" data-code="1f98f">🦏</span><br>Dromadaire/Chamelle <span data-gb-custom-inline data-tag="emoji" data-code="1f42a">🐪</span><br>Chameau/Chamelle <span data-gb-custom-inline data-tag="emoji" data-code="1f42b">🐫</span><br>Girafe <span data-gb-custom-inline data-tag="emoji" data-code="1f992">🦒</span><br>Kangourou <span data-gb-custom-inline data-tag="emoji" data-code="1f998">🦘</span><br>Paon.ne <span data-gb-custom-inline data-tag="emoji" data-code="1f99a">🦚</span><br>Perroquet <span data-gb-custom-inline data-tag="emoji" data-code="1f99c">🦜</span><br>Loutre <span data-gb-custom-inline data-tag="emoji" data-code="1f9a6">🦦</span><br>Tigre.sse <span data-gb-custom-inline data-tag="emoji" data-code="1f405">🐅</span><br>Poulpe/Pieuvre <span data-gb-custom-inline data-tag="emoji" data-code="1f419">🐙</span><br>Baleine <span data-gb-custom-inline data-tag="emoji" data-code="1f40b">🐋</span><br>Cerf/Biche <span data-gb-custom-inline data-tag="emoji" data-code="1f98c">🦌</span><br>Bison.ne <span data-gb-custom-inline data-tag="emoji" data-code="1f9ac">🦬</span><br>Élan <span data-gb-custom-inline data-tag="emoji" data-code="1face">🫎</span></td><td><p>Lion.ne <span data-gb-custom-inline data-tag="emoji" data-code="1f981">🦁</span><br>Aigle <span data-gb-custom-inline data-tag="emoji" data-code="1f985">🦅</span><br>Dodo <span data-gb-custom-inline data-tag="emoji" data-code="1f9a4">🦤</span><br>Léopard.e <span data-gb-custom-inline data-tag="emoji" data-code="1f406">🐆</span><br>Mammouth <span data-gb-custom-inline data-tag="emoji" data-code="1f9a3">🦣</span><br>Bonhomme/Dame de neige <span data-gb-custom-inline data-tag="emoji" data-code="26c4">⛄</span><br>Manchot.e <span data-gb-custom-inline data-tag="emoji" data-code="1f427">🐧</span><br>Poisson-globe <span data-gb-custom-inline data-tag="emoji" data-code="1f421">🐡</span><br>Requin <span data-gb-custom-inline data-tag="emoji" data-code="1f988">🦈</span><br>Homard <span data-gb-custom-inline data-tag="emoji" data-code="1f99e">🦞</span><br>Dauphin <span data-gb-custom-inline data-tag="emoji" data-code="1f42c">🐬</span><br>Buffle d'eau <span data-gb-custom-inline data-tag="emoji" data-code="1f403">🐃</span><br>Orang-outan<br><span data-gb-custom-inline data-tag="emoji" data-code="1f9a7">🦧</span></p><p>Gorille <span data-gb-custom-inline data-tag="emoji" data-code="1f98d">🦍</span></p></td><td>Licorne  <span data-gb-custom-inline data-tag="emoji" data-code="1f984">🦄</span><br>Dragon.ne <span data-gb-custom-inline data-tag="emoji" data-code="1f409">🐉</span><br>T-Rex <span data-gb-custom-inline data-tag="emoji" data-code="1f996">🦖</span><br>Stitch/Angel <span data-gb-custom-inline data-tag="emoji" data-code="1f535">🔵</span>/ <span data-gb-custom-inline data-tag="emoji" data-code="1f7e3">🟣</span><br>Canard/Cane écarlate <span data-gb-custom-inline data-tag="emoji" data-code="1f986">🦆</span><br>Bonhomme/Dame de neige <span data-gb-custom-inline data-tag="emoji" data-code="2603">☃️</span><br>Alien.ne <span data-gb-custom-inline data-tag="emoji" data-code="1f47d">👽</span><br>Poisson tropical <span data-gb-custom-inline data-tag="emoji" data-code="1f420">🐠</span><br>Baleine <span data-gb-custom-inline data-tag="emoji" data-code="1f433">🐳</span><br>Phénix <span data-gb-custom-inline data-tag="emoji" data-code="1f426">🐦</span><span data-gb-custom-inline data-tag="emoji" data-code="1f525">🔥</span><br>Diplodocus <span data-gb-custom-inline data-tag="emoji" data-code="1f995">🦕</span><br>Merle <span data-gb-custom-inline data-tag="emoji" data-code="1f426-2b1b">🐦‍⬛</span><br>Corbeau <span data-gb-custom-inline data-tag="emoji" data-code="1f426-2b1b">🐦‍⬛</span><br>Jack-o'-lantern <span data-gb-custom-inline data-tag="emoji" data-code="1f383">🎃</span><br>Fantôme <span data-gb-custom-inline data-tag="emoji" data-code="1f47b">👻</span></td><td><p>Fée <span data-gb-custom-inline data-tag="emoji" data-code="1f9da">🧚</span></p><p>Vampire <span data-gb-custom-inline data-tag="emoji" data-code="1f9db">🧛</span></p></td></tr></tbody></table>

{% hint style="info" %}
Le Bonhomme de neige existe en deux versions :

* La version épique.
* La version légendaire.

On peut distinguer la version la plus rare assez facilement car l'émoji qui la représente est entouré de flocons de neige !

Il y a également deux baleines dans le jeu :

* La version spécial, une baleine classique.
* La version légendaire qui se distingue par un jet d'eau sur son dos.

La Chamelle spécial se retrouve aussi deux fois :&#x20;

* En tant que femelle du Chameau :camel:&#x20;
* En tant que femelle du Dromadaire :dromedary\_camel:&#x20;

L’émoji qui la représente permet de différencier les deux animaux !
{% endhint %}

### Pouvoir des familiers en combat

{% tabs %}
{% tab title="1 *" %}
Les familiers 1 :star:

\
:cat2: **chat.te** : griffe légèrement l’adversaire\
:dog2: **chien.ne** : mord légèrement l'adversaire\
:poodle: **caniche** : mord légèrement l'adversaire\
:rat: **rat.e** : mord l'adversaire en l'empoisonnant parfois\
:chicken: **poule/coq** : frappe l'adversaire de son bec\
:bird: **oiseau** : frappe l'adversaire de son bec\
:duck: **canard/cane** : frappe l'adversaire de son bec\
:goose: **oie** : frappe l'adversaire de son bec\
:pig: **cochon/truie** : charge l'adversaire\
:sheep: **bélier/brebis** : charge l'adversaire\
:goat: **chèvre/bouc** : charge l'adversaire\
:snake: **serpent** : mord et empoisonne l'adversaire\
:cow2: **boeuf/vache** : charge et étourdit l'adversaire\
:black\_cat: **chat.te noir.e** : jette une malédiction sur l'adversaire\
:snowman:**bonhomme de neige** : gèle l'adversaire\
:racehorse: **étalon/jument** : boost la vitesse de son propriétaire\
:turtle: **tortue** : augmente la défense de son propriétaire, mais le ralentit\
:lizard: **lézard** : soigne légèrement son propriétaire\
:fish: **poisson** : protège son propriétaire du feu\
:mouse2: **souris/rongeur** : effraie l'éléphant adverse\
:hamster: **hamster** : inflige des dégâts dérisoires à l'adversaire\
:rabbit2: **lapin.e** : inflige des dégâts dérisoires à l'adversaire\
:turkey: **dinde/dindon** : inflige des dégâts insignifiants à l’adversaire\
:hatching\_chick: **poussin** : inflige des dégâts insignifiants à l’adversaire\
:snail: **escargot** : ne fait absolument rien (mais il le fait bien)
{% endtab %}

{% tab title="2*" %}


Les familiers 2 :star::star:\
\
:fox: **renard.e** : mord l'adversaire\
:wolf: **loup/louve** : mord l'adversaire\
:crab: **crabe** : pince l'adversaire\
:badger: **blaireau/blairelle** : griffe légèrement l’adversaire\
:hedgehog: **hérisson.ne** : pique l'adversaire après une attaque physique\
:penguin: **pingouin.e** : fonce sur l’adversaire en glissant\
:bat: **chauve-souris** : attaque l'adversaire et soigne son propriétaire\
:boar: **sanglier/laie** : charge et étourdit l'adversaire\
:swan: **cygne** : charge l'adversaire\
:llama: **lama.te** : crache sur l'adversaire après une attaque physique\
:jellyfish: **méduse** : paralyse l'adversaire\
:frog: **grenouille/crapaud** : empoisonne l'adversaire\
:skunk: **putois/moufette** : empoisonne l'adversaire\
:raccoon: **raton laveur/ratonne** : dérobe l'arme de l'adversaire\
:monkey: **singe/guenon** : dérobe l'arme de l'adversaire\
:beaver: **castor** : boost la défense de son propriétaire\
:donkey:**âne.sse** : boost la vitesse de son propriétaire\
:owl:**hiboux/chouette** : protège son propriétaire de l'aveuglement\
:seal: **otarie/phoque** : redonne du souffle à son propriétaire\
:flamingo: **flamant rose** : inflige des dégâts insignifiants à l'adversaire\
:chipmunk: **tamia** : inflige des dégâts insignifiants à l'adversaire\
:koala: **koala** : ne fait rien (et assume pleinement)\
:sloth: **paresseux/paresseuse** : ne fait rien (et c’est déjà un exploit)\
:shrimp: **crevette** : ne fait rien (mais le cœur y est)
{% endtab %}

{% tab title="3*" %}
Les familiers 3 :star::star::star:\
\
:elephant: **éléphant.e** : resitue le souffle consommé à son propriétaire\
:zebra: **zèbre.lle** : boost la vitesse de son propriétaire\
:dromedary\_camel: **dromadaire** : boost la vitesse de son propriétaire\
:camel: **chameau/chamelle** : boost la vitesse de son propriétaire\
:moose: **élan** : vole le bouclier de l'adversaire\
:whale2: **baleine** : avale l'adversaire\
:scorpion: **scorpion.ne** : mord et empoisonne l'adversaire\
:bison: **bison.ne** : charge et étourdit l'adversaire\
:bear: **ours.e** : charge et étourdit l'adversaire\
:crocodile: **crocodile** : mord l'adversaire\
:rhino: **rhinocéros** : donne un coup de corne à l'adversaire\
:deer: **cerf/biche** : donne un coup de corne à l'adversaire\
:kangaroo: **kangourou** : assène un coup de poing à l'adversaire\
:hippopotamus: **hippopotame** : attaque sauvagement l'adversaire\
:peacock: **paon.ne** : frappe l'adversaire de son bec\
:parrot: **perroquet** : frappe l'adversaire de son bec\
:black\_bird: **merle** : frappe l'adversaire de son bec\
:otter: **loutre** : redonne du souffle à son propriétaire\
:octopus: **poulpe** : rend l'adversaire aveugle\
:giraffe: **girafe** : protège son propriétaire de l'aveuglement
{% endtab %}

{% tab title="4*" %}
Les familiers 4 :star::star::star::star:\
\
:tiger2: **tigre.sse** : griffe férocement l'adversaire\
:lion\_face: l**ion.ne** : griffe férocement l'adversaire\
:leopard: **léopard.e** : griffe férocement l'adversaire\
:eagle: **aigle** : protège son propriétaire de l'aveuglement\
:dodo: **dodo** : frappe l'adversaire de son bec\
:mammoth: **mammouth** : protège son propriétaire du froid\
:dove: **colombe** : soigne à la fois son propriétaire et l'adversaire\
:penguin: **manchot.e** : percute l'adversaire en glissant\
:snowman2: **bonhomme de neige** : gèle l'adversaire\
:dolphin: **dauphin** : protège son propriétaire du feu\
:lobster: **homard** : pince l'adversaire\
:shark: **requin** : effraie tous les poissons\
:orangutan: **orang-outan** : boost aléatoirement la vitesse la défense ou l'attaque de son propriétaire\
:gorilla: **gorille** : assène un coup de poing à l'adversaire\
:black\_bird:  **corbeau** : maudit l'adversaire\
:water\_buffalo: **buffle d'eau** : charge et étourdit l'adversaire\
:polar\_bear: **ours.e polaire** : protège son propriétaire du froid\
:blowfish: **poisson globe** : protège son propriétaire du feu\
:panda\_face: **panda** : ne fait rien (la flemme, tout simplement)

:ghost:**fantôme** : jette une malédiction sur l'adversaire

:jack\_o\_lantern:**jack-o-lantern** : son regard hypnotique pétrifie l'adversaire
{% endtab %}

{% tab title="5*" %}
Les familiers 5 ⭐⭐⭐⭐⭐&#x20;

:dragon:**dragon.ne**: brûle l'adversaire

:unicorn:**licorne**: soigne son propriétaire après une attaque magique

:t\_rex:**t-rex:** attaque sauvagement l'adversaire et inflige de légers dégâts à son propriétaire&#x20;

:blue\_circle:**stitch/angel**: attaque sauvagement l'adversaire et inflige de légers dégâts à son propriétaire

:alien: **alien.ne**: rend l'adversaire confus&#x20;

🦆 **canard écarlate/cane écarlate**: attaque sauvagement l'adversaire en fin de combat&#x20;

🐠 **poisson tropical**: protège son propriétaire du feu&#x20;

🐳 **baleine**: avale l'adversaire&#x20;

:sauropod: **diplodocus**: écrase l'adversaire&#x20;

🐦‍🔥 **phénix**: soigne son propriétaire
{% endtab %}

{% tab title="Mythique" %}
Les familiers mythiques :gem:

:vampire:**vampire**: soigne son adversaire à partir de l'énergie vitale de son adversaire, sa morsure fait saigner

:fairy:**fée**: soigne son propriétaire avec efficacité et régularité
{% endtab %}
{% endtabs %}

### Les expéditions

Pour débloquer les expéditions,il faudra le talisman d'ancrage qui est remis par [Velanna ](../notions-avancees/mini-evenements.md#conseils-sur-les-expeditions)à partir de votre troisième rencontre si vous avez un familier nourri et non fielleux, que vous êtes au moins niveau 30, que vous appartenez à une guilde et que votre familier a déjà été présenté à [Talvar](../notions-avancees/mini-evenements.md#le-nain-fan-des-animaux).

Les expéditions coûtent des provisions (jusqu'à 32) et ont une durée (jusqu'à 3 jours) mais rapportent des jetons, de l'argent, de l'expérience, des points et un équipement en cas de succès partiel ou total.

{% hint style="info" %}
Pensez à vérifier l’entrepôt de la guilde avant de laisser partir votre familier en expédition. Si ce dernier n'a pas assez de provisions ses chances de succès sont considérablement diminuées.
{% endhint %}

Pour commencer une expédition, le joueur doit posséder un familier nourri et avec 50 points d'amour ou plus et un talisman d'ancrage. Il vous suffira ensuite de cliquer sur le bouton :map:**Expédition** pour qu'apparaisse un menu qui vous proposera trois destinations.

<figure><picture><source srcset="../.gitbook/assets/expedition_generation_entier_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/expedition_generation_entier_clair.png" alt="Le talisman d&#x27;ancrage propose 3 expéditions avec leurs destinations, leurs durées, leurs dangerosités, la difficulté de leurs terrain, leurs récompenses et les vôutrs en provisions."></picture><figcaption><p>C'est parti pour l'aventure</p></figcaption></figure>

{% hint style="info" %}
Chaque expédition a une plage de durée définie : moins d'une heure pour la première, moins de 10h pour la deuxième et 12h à 3j pour la troisième. Chaque familier possède une statistique de vitesse, comprise entre 1 et 30, qui peut raccourcir ou allonger la durée finale.
{% endhint %}

{% hint style="warning" %}
Si vous décidez d'annuler le départ en expédition et à partir de la deuxième fois en 7j, votre familier perdra considérablement confiance en vous et ce de plus en plus.
{% endhint %}

Avant de choisir une expédition, il faut savoir que son taux de réussite et ses récompenses dépend de pleins de facteurs.

| Dangerosité                                                                                                                                                                                         | Terrain                                                                                                                                                                                            |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>-Tranquille 🌿 (0–10)<br>-Serein ☀️ (11-20)<br>-Hasardeux 🌤️ (21–32)<br>-Risqué ⚡ (33–45)<br>-Dangereux 🔥 (46–58)<br>-Périlleux ⚠️ (59-72)<br>-Mortel 💀 (73–86)<br>-Désespéré ⚰️ (87–100)</p> | <p>-Paisible <span data-gb-custom-inline data-tag="emoji" data-code="1f338">🌸</span>(0-20)<br>-Praticable 🌲(21-40)<br>-Accidenté ⛰️ (41-60)<br>-Hostile 🏔️ (61-80)<br>-Périlleux 🌋(81-100)</p> |

{% hint style="info" %}
Le type de terrain influence la difficulté du terrain, en effet une grotte est plus souvent hostile et une plaine plus souvent paisible mais aussi les récompenses : certains terrains donne plus d'expérience, d'autre plus de points ou d'argent.
{% endhint %}

Pour augmenter vos chances de réussite de vos expéditions, en plus de regarder la difficulté et le terrain, vous pouvez:

* Dresser votre familier.
* Choisir un familier avec une meilleure statistique de force.
* Envoyer votre familier dans un lieu qu'il apprécie particulièrement
* Vérifier que l’entrepôt de votre guilde contient suffisamment de provisions.

Une fois l'expédition terminée:

<table><thead><tr><th width="304.39996337890625">Échec</th><th width="443.4000244140625">Succès</th></tr></thead><tbody><tr><td>L'expédition est un échec:  le familier perd 3 points d'affection.</td><td><p>Vous recevrez: </p><p>-des jetons (si vous avez de la place),</p><p>-de l'argent, </p><p>-de l'expérience, </p><p>-des points,</p><p>-un équipement,</p><p>-des matériaux.</p><p>Ensuite, les récompenses estimées, la probabilité de succès et les rations utilisées permettent de statuer sur la valeur de ces récompenses (quantité de ressources ou qualité de l'équipement).</p><p>Un terrain apprécié par le familier permet de récupérer 100% des récompenses, là où un terrain neutre ne gagne que 80% et détesté 25%. </p><p>Les expéditions mentionnant un trésor en jetons possèdent un multiplicateur de jetons.</p></td></tr></tbody></table>

{% hint style="warning" %}
Quand votre familier est en expédition, il n'est pas considéré comme équipé, il ne vous assistera pas pendant les mini-événements, les combats (attaque et défense) et sur les îles mystérieuses.
{% endhint %}

{% hint style="success" %}
Les jetons en récompenses des expéditions peuvent vous faire dépasser la limite de 20.
{% endhint %}

{% hint style="info" %}
Vous pouvez trouver au cours de vos expéditions avec une petite probabilité un talisman de clonage (certains expéditions parle de ce talisman ce qui se traduit par un multiplicateur x10). Ce puissant artefact crée un double de votre familier qui vous aidera dans les mini-événements et les combats en défense.
{% endhint %}
