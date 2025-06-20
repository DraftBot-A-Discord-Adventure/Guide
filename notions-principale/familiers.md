# Familiers

Depuis la version [2.1.2](https://history.draftbot.com/draftbot-v2/2.1.2) de DraftBot, vous pouvez avoir un ou plusieurs **familiers**.

Pour avoir les informations sur votre familier, vous devez utiliser la commande `/familier`.

Il y a 5 niveaux de **rareté** de familiers, ceux-ci sont représentés par des étoiles :star: :star: :star: :star: :star:.

Les familiers ont un **moral**, si vous les nourrissez à intervalle régulier leur moral augmentera. A contrario, si vous délaissez vos familiers leur moral diminuera.

### Comment obtenir un familier ?

Les familiers s'obtiennent dans les récompenses de guilde `/bonusjournalierguilde` avec 1% de chance, ou alors dans les mini-évènements.

La probabilité d'avoir des raretés supérieures augmente avec le niveau de votre guilde.

|                               |         |          |          |          |          |
| ----------------------------- | ------- | -------- | -------- | -------- | -------- |
| Niveau guilde/rareté familier | 1:star: | 2 :star: | 3 :star: | 4 :star: | 5 :star: |
| 0-9                           | 90%     | 9%       | 0.9%     | 0.09%    | 0.01%    |
| 10-19                         | 89.4%   | 9.16%    | 1.091%   | 0.23%    | 0.119%   |
| 20-29                         | 87.6%   | 9.64%    | 1.664%   | 0.65%    | 0.446%   |
| 30-39                         | 84.6%   | 10.44%   | 2.619%   | 1.35%    | 0.991%   |
| 40-49                         | 80.4%   | 11.56%   | 3.956%   | 2.33%    | 1.754%   |
| 50-59                         | 75%     | 13%      | 5.675%   | 3.59%    | 2.735%   |
| 60-69                         | 68.4%   | 14.76%   | 7.776%   | 5.13%    | 3.934%   |
| 70-79                         | 60.6%   | 16.84%   | 10.259%  | 6.9499%  | 5.3511%  |
| 80-89                         | 51.6%   | 19.24%   | 13.124%  | 9.0499%  | 6.9861%  |
| 90-99                         | 41.4%   | 21.96%   | 16.371%  | 11.4299% | 8.8391%  |
| 100-150                       | 30%     | 25%      | 20%      | 14.0899% | 10.9101% |

{% hint style="info" %}
Si un familier est obtenu dans un mini-évènement, sa rareté est générée avec les statistiques des guildes de niveau 20.
{% endhint %}

Vous pouvez libérer votre familier avec la commande `/libererfamilier`.

{% hint style="danger" %}
Attention, cette action est irréversible. Le fait de libérer un familier est définitif.
{% endhint %}

## A quoi sert un familier ?

Un familier a 2 fonctions:

* Lors de ce [mini-événement](https://guide.draftbot.com/notions-avancees/mini-evenements#interaction-avec-un-familier), vous interagissez avec votre familier. Il peut vous donner (ou vous faire perdre) des ressources selon son moral, gagner (ou perdre s'il n'est pas dressé) des points d'affection ou simplement ne rien se passer.
* Lors des combats, chaque familier aidera (ou du moins essayera d'aider) son propriétaire.

### Comment nourrir mon familier ?

#### Acheter de la nourriture.

L'achat de nourriture pour les familiers se fait dans le magasin de votre guilde. Si vous n'avez pas de guilde, vous n'aurez accès qu'à la forme la plus basique de nourriture, c'est-à-dire la friandise, pour votre animal.

<picture><source srcset="../.gitbook/assets/Screenshot_20250617-151531.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 184818.png" alt="Le magasin de guilde permet d&#x27;acheter différentes sortes de nourritures"></picture>

{% hint style="info" %}
Il est aussi possible que votre familier trouve de la nourriture pendant l'aventure.
{% endhint %}

#### Donner de la nourriture

La nourriture va permettre d'influer sur le moral de votre animal. Pour nourrir votre familier, vous devez utiliser la commande `/nourrirfamilier`.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 184644.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 184653.png" alt="Don de nourriture à son familier via la commande /nourrirfamilier"></picture><figcaption><p>La commande /nourrirfamilier</p></figcaption></figure>

Chaque type de nourriture fera gagner une quantité différente de points d'affection à votre familier.

* Les friandises feront gagner 1 point d'affection.
* Les steaks et salade feront gagner 3 points d'affection.
* Les soupes ultimes feront gagner 5 points d'affection.

Cependant, le type de nourriture n'a pas d'influence sur la durée pendant laquelle votre familier n'a pas faim.

{% hint style="info" %}
La durée pendant laquelle un familier n'a pas faim dépend uniquement de la rareté du pet. Le nombre d'étoiles de rareté est égal au nombre d'heures qu'il faut attendre entre deux repas.
{% endhint %}

{% hint style="warning" %}
Certains familiers suivent un régime particulier (herbivore ou carnivore) et ne pourront donc pas profiter de certaines sources de nourriture. Ne donnez pas de salade à votre T-rex !
{% endhint %}

#### Niveaux de moral

Ne négligez pas votre familier ! Son moral baissera si vous oubliez de vous en occuper.

{% hint style="warning" %}
Le moral d'un familier baisse de deux points par jour en moyenne, cette baisse ne tient pas compte de la rareté du pet.
{% endhint %}

Il existe pour le moment 5 niveaux de moral qui correspondent à la mentalité de votre familier, ils sont classés de cette manière :

1. :smirk\_cat: Fielleux (entre 0 et 4 points d'affection)
2. :pouting\_cat: Sauvage (entre 5 et 24 points d'affection)
3. :scream\_cat: Craintif (entre 25 et 49 points d'affection)
4. :smiley\_cat: Apprivoisé (entre 50 et 99 points d'affection)
5. :heart\_eyes\_cat: Dressé (100 points d'affection)

{% hint style="info" %}
Les animaux dressés ne perdent plus de moral et n'ont donc pas besoin d'être nourris pour être aimés (mais vous pouvez le faire quand même).
{% endhint %}

{% hint style="danger" %}
Il n'est pas possible d'effectuer certaines actions avec un familier fielleux !
{% endhint %}

{% hint style="warning" %}
Vendre un familier avec un autre joueur réinitialisera son moral à :pouting\_cat: Sauvage.

Changer de propriétaire, c'est dur à supporter pour un animal !
{% endhint %}

Contre 3 gemmes, le vétérinaire de la cour vous donnera des informations sur le familier que vous possédez actuellement. La consultation s'obtient dans le [magasin de missions](missions.md#magasin-des-missions).

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 185320.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 185338.png" alt="Description du familier avec le vétérinaire , achetable via le magasin de missions , la commande /magasinmissions"></picture><figcaption><p>Il est toujours utile pour savoir s'il a perdu du moral ou pas de façon précise, et quand il aura faim.</p></figcaption></figure>

### Comment stocker mon familier ?

Vous avez la possibilité de stocker votre familier dans le **refuge de votre guilde** ou alors de le récupérer avec vous. Pour cela, vous devez effectuer la commande `/transfererfamilier` . Un menu vous permet de choisir de déposer votre familier dans le refuge, de l'échanger contre un du refuge (ou d'annuler le transfert).

Pour visualiser le refuge, vous pouvez utiliser la commande `/abriguilde`.

<picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 185446.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 185435.png" alt="Refuge de la guilde B1 Bis Alpha"></picture>

{% hint style="info" %}
Le refuge de votre guilde permet d'accueillir jusqu'à 6 familiers différents.
{% endhint %}

### Comment surnommer un familier ?

Vous pouvez définir un surnom pour votre familier afin de rendre ce dernier unique. Pour cela, quand vous avez un familier avec vous tapez la commande `/surnomfamilier.`Exemple : `/surnomfamilier surnom:Henri` permet de surnommer votre familier "Henri".

<picture><source srcset="../.gitbook/assets/Screenshot_20250617-152124.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 195918.png" alt="Commande /familier avec affichage du surnom du familier"></picture>

### Comment vendre un familier ?

Si vous souhaitez vous débarrasser d'un familier mais que vous n'avez pas le cœur de le libérer (ou alors que vous aimez l'argent), il est possible de vendre le familier que vous transportez. Pour cela, vous pouvez utiliser la commande `/vendrefamilier` en précisant le prix attendu. Par exemple, pour proposer votre familier à la vente pour 1000:moneybag:, entrez la commande `/vendrefamilier prix:1000`.

<figure><picture><source srcset="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 185603.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Capture d&#x27;écran 2025-06-19 185616.png" alt=""></picture><figcaption><p>Ici, le familier "Poulpe" va être vendu pour 1000 <span data-gb-custom-inline data-tag="emoji" data-code="1f4b0">💰</span></p></figcaption></figure>

Il y a des conditions importantes à respecter pour la vente de familiers :

* Il n'est pas possible de vendre un familier à un membre de sa guilde.
* Il est nécessaire d'appartenir à une guilde pour vendre un familier, mais pas pour l'acheter.
* Vous ne pouvez pas vendre un familier en dessous de 100:moneybag:, ni au-dessus de 50 000 :moneybag:.

{% hint style="warning" %}
Le vendeur ne gagnera pas d'argent lors de la transaction, mais de l'expérience de guilde.
{% endhint %}

### **Liste des familiers disponibles**

<table><thead><tr><th></th><th width="200"></th><th></th><th></th><th></th></tr></thead><tbody><tr><td><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span></td><td><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span><span data-gb-custom-inline data-tag="emoji" data-code="2b50">⭐</span></td></tr><tr><td><p>Chien <span data-gb-custom-inline data-tag="emoji" data-code="1f415">🐕</span></p><p>Caniche <span data-gb-custom-inline data-tag="emoji" data-code="1f429">🐩</span></p><p>Chat <span data-gb-custom-inline data-tag="emoji" data-code="1f408">🐈</span></p><p>Chat noir <span data-gb-custom-inline data-tag="emoji" data-code="1f408-2b1b">🐈‍⬛</span></p><p>Souris <span data-gb-custom-inline data-tag="emoji" data-code="1f401">🐁</span></p><p>Hamster <span data-gb-custom-inline data-tag="emoji" data-code="1f439">🐹</span></p><p>Lapin <span data-gb-custom-inline data-tag="emoji" data-code="1f407">🐇</span></p><p>Vache <span data-gb-custom-inline data-tag="emoji" data-code="1f404">🐄</span></p><p>Cochon <span data-gb-custom-inline data-tag="emoji" data-code="1f437">🐷</span></p><p>Poule / Coq <span data-gb-custom-inline data-tag="emoji" data-code="1f414">🐔</span></p><p>Oiseau <span data-gb-custom-inline data-tag="emoji" data-code="1f426">🐦</span></p><p>Canard <span data-gb-custom-inline data-tag="emoji" data-code="1f986">🦆</span></p><p>Cheval <span data-gb-custom-inline data-tag="emoji" data-code="1f40e">🐎</span></p><p>Tortue <span data-gb-custom-inline data-tag="emoji" data-code="1f422">🐢</span></p><p>Serpent <span data-gb-custom-inline data-tag="emoji" data-code="1f40d">🐍</span></p><p>Lézard <span data-gb-custom-inline data-tag="emoji" data-code="1f98e">🦎</span></p><p>Bélier / Mouton <span data-gb-custom-inline data-tag="emoji" data-code="1f411">🐑</span></p><p>Chèvre / Bouc <span data-gb-custom-inline data-tag="emoji" data-code="1f410">🐐</span></p><p>Dindon <span data-gb-custom-inline data-tag="emoji" data-code="1f983">🦃</span></p><p>Bonhomme de neige <span data-gb-custom-inline data-tag="emoji" data-code="26c4">⛄</span> </p><p>Poisson <span data-gb-custom-inline data-tag="emoji" data-code="1f41f">🐟</span> </p><p>Escargot <span data-gb-custom-inline data-tag="emoji" data-code="1f40c">🐌</span></p><p>Poussin <span data-gb-custom-inline data-tag="emoji" data-code="1f423">🐣</span> </p><p>Rat <span data-gb-custom-inline data-tag="emoji" data-code="1f400">🐀</span></p></td><td><p>Renard <span data-gb-custom-inline data-tag="emoji" data-code="1f98a">🦊</span></p><p>Ours <span data-gb-custom-inline data-tag="emoji" data-code="1f43b">🐻</span></p><p>Koala <span data-gb-custom-inline data-tag="emoji" data-code="1f428">🐨</span></p><p>Grenouille <span data-gb-custom-inline data-tag="emoji" data-code="1f438">🐸</span></p><p>Singe <span data-gb-custom-inline data-tag="emoji" data-code="1f412">🐒</span></p><p>Pingouin <span data-gb-custom-inline data-tag="emoji" data-code="1f427">🐧</span></p><p>Hibou <span data-gb-custom-inline data-tag="emoji" data-code="1f989">🦉</span></p><p>Chauve-souris <span data-gb-custom-inline data-tag="emoji" data-code="1f987">🦇</span></p><p>Loup <span data-gb-custom-inline data-tag="emoji" data-code="1f43a">🐺</span></p><p>Sanglier <span data-gb-custom-inline data-tag="emoji" data-code="1f417">🐗</span></p><p>Otarie <span data-gb-custom-inline data-tag="emoji" data-code="1f9ad">🦭</span></p><p>Hippopotame <span data-gb-custom-inline data-tag="emoji" data-code="1f99b">🦛</span></p><p>Lama <span data-gb-custom-inline data-tag="emoji" data-code="1f999">🦙</span></p><p>Cygne <span data-gb-custom-inline data-tag="emoji" data-code="1f9a2">🦢</span></p><p>Flamant rose <span data-gb-custom-inline data-tag="emoji" data-code="1f9a9">🦩</span></p><p>Raton Laveur <span data-gb-custom-inline data-tag="emoji" data-code="1f99d">🦝</span></p><p>Putois <span data-gb-custom-inline data-tag="emoji" data-code="1f9a8">🦨</span></p><p>Blaireau <span data-gb-custom-inline data-tag="emoji" data-code="1f9a1">🦡</span></p><p>Castor <span data-gb-custom-inline data-tag="emoji" data-code="1f9ab">🦫</span></p><p>Paresseux <span data-gb-custom-inline data-tag="emoji" data-code="1f9a5">🦥</span></p><p>Tamia <span data-gb-custom-inline data-tag="emoji" data-code="1f43f">🐿️</span></p><p>Hérisson 🦔️ </p><p>Crevette 🦐 </p><p>Méduse <span data-gb-custom-inline data-tag="emoji" data-code="1fabc">🪼</span> </p><p>Crabe <span data-gb-custom-inline data-tag="emoji" data-code="1f980">🦀</span></p><p></p></td><td><p>Ours polaire <span data-gb-custom-inline data-tag="emoji" data-code="1f43b-2744">🐻‍❄️</span></p><p>Panda <span data-gb-custom-inline data-tag="emoji" data-code="1f43c">🐼</span></p><p>Scorpion <span data-gb-custom-inline data-tag="emoji" data-code="1f982">🦂</span></p><p>Crocodile <span data-gb-custom-inline data-tag="emoji" data-code="1f40a">🐊</span></p><p>Éléphant <span data-gb-custom-inline data-tag="emoji" data-code="1f418">🐘</span></p><p>Zèbre <span data-gb-custom-inline data-tag="emoji" data-code="1f993">🦓</span></p><p>Rhinocéros <span data-gb-custom-inline data-tag="emoji" data-code="1f98f">🦏</span></p><p>Dromadaire <span data-gb-custom-inline data-tag="emoji" data-code="1f42a">🐪</span></p><p>Chameau <span data-gb-custom-inline data-tag="emoji" data-code="1f42b">🐫</span></p><p>Girafe <span data-gb-custom-inline data-tag="emoji" data-code="1f992">🦒</span></p><p>Kangourou <span data-gb-custom-inline data-tag="emoji" data-code="1f998">🦘</span></p><p>Paon <span data-gb-custom-inline data-tag="emoji" data-code="1f99a">🦚</span></p><p>Perroquet <span data-gb-custom-inline data-tag="emoji" data-code="1f99c">🦜</span></p><p>Loutre <span data-gb-custom-inline data-tag="emoji" data-code="1f9a6">🦦</span></p><p>Poulpe <span data-gb-custom-inline data-tag="emoji" data-code="1f419">🐙</span></p><p>Baleine🐋<br>Poisson-globe <span data-gb-custom-inline data-tag="emoji" data-code="1f421">🐡</span></p><p>Cerf <span data-gb-custom-inline data-tag="emoji" data-code="1f98c">🦌</span></p><p>Bison <span data-gb-custom-inline data-tag="emoji" data-code="1f9ac">🦬</span></p><p>Merle <span data-gb-custom-inline data-tag="emoji" data-code="1f426-2b1b">🐦‍⬛</span></p></td><td><p>Tigre <span data-gb-custom-inline data-tag="emoji" data-code="1f405">🐅</span></p><p>Lion <span data-gb-custom-inline data-tag="emoji" data-code="1f981">🦁</span></p><p>Aigle <span data-gb-custom-inline data-tag="emoji" data-code="1f985">🦅</span></p><p>Dodo <span data-gb-custom-inline data-tag="emoji" data-code="1f9a4">🦤</span></p><p>Léopard <span data-gb-custom-inline data-tag="emoji" data-code="1f406">🐆</span></p><p>Mammouth <span data-gb-custom-inline data-tag="emoji" data-code="1f9a3">🦣</span></p><p>Colombe <span data-gb-custom-inline data-tag="emoji" data-code="1f54a">🕊️</span></p><p>Manchot <span data-gb-custom-inline data-tag="emoji" data-code="1f427">🐧</span></p><p>Bonhomme de neige <span data-gb-custom-inline data-tag="emoji" data-code="2603">☃️</span> </p><p>Dauphin 🐬 </p><p>Homard 🦞 </p><p>Requin 🦈 </p><p>Buffle d'eau <span data-gb-custom-inline data-tag="emoji" data-code="1f403">🐃</span></p><p>Orang-outan <span data-gb-custom-inline data-tag="emoji" data-code="1f9a7">🦧</span></p><p>Gorille <span data-gb-custom-inline data-tag="emoji" data-code="1f98d">🦍</span> </p><p>Corbeau <span data-gb-custom-inline data-tag="emoji" data-code="1f426-2b1b">🐦‍⬛</span></p></td><td><p>Licorne <span data-gb-custom-inline data-tag="emoji" data-code="1f984">🦄</span></p><p>Dragon <span data-gb-custom-inline data-tag="emoji" data-code="1f409">🐉</span></p><p>T-rex <span data-gb-custom-inline data-tag="emoji" data-code="1f996">🦖</span></p><p>Stitch/Angel <span data-gb-custom-inline data-tag="emoji" data-code="1f7e3">🟣</span><br>Alien <span data-gb-custom-inline data-tag="emoji" data-code="1f47d">👽</span><br>Canard écarlate 🦆</p><p>Baleine  🐳 </p><p>Poisson tropical 🐠</p><p>Phénix 🐦‍🔥</p><p>Diplodocus <span data-gb-custom-inline data-tag="emoji" data-code="1f995">🦕</span></p></td></tr></tbody></table>



{% hint style="info" %}
Le Bonhomme de neige existe en deux versions :

* La version :star: qui est celle de base.
* La version :star::star::star::star: qui est une version bien plus rare.

On peut distinguer la version rare assez facilement car l'émoji qui la représente est entouré de flocons de neige !

Il y a également deux baleines dans le jeu :

* La version **⭐⭐⭐**, une baleine classique.
* La version **⭐⭐⭐⭐⭐**&#x71;ui se distingue par un jet d'eau sur son dos.
{% endhint %}
