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

L'achat de nourriture pour les familiers se fait dans les villes, au ravitaillement de guilde. Si vous n'avez pas de guilde, vous n'aurez accès qu'à la forme la plus basique de nourriture, c'est-à-dire la friandise :candy:, pour votre animal. Si vous êtes dans la ville de votre domaine de guilde :european\_castle:, l'approvisionnement se fait dans la boutique de la guilde :shopping\_cart:.&#x20;

<picture><source srcset="../.gitbook/assets/RavitaillementHorde_sombre.jpg" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/RavitaillementHorde_clair.jpg" alt="Le ravitaillement permet d&#x27;acheter différentes sources de nourriture"></picture>

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

Contre 3 gemmes, le vétérinaire de la cour vous donnera des informations sur le familier que vous possédez actuellement, et lui donnera 15 points d'amour :revolving\_hearts: s'il n'est pas déjà apprivoisé ou dressé. La consultation s'obtient à Mergagnan ou Claire de Ville.&#x20;

<figure><picture><source srcset="../.gitbook/assets/Veterinaire_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/Veterinaire_clair.png" alt="Description du familier avec le vétérinaire , achetable via le magasin de missions , la commande /magasinmissions"></picture><figcaption><p>Il est toujours utile pour savoir s'il a perdu du moral ou pas de façon précise, quand il aura faim mais encore bien plus.</p></figcaption></figure>

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

<figure><picture><source srcset="../.gitbook/assets/VentePet_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/VentePet_clair.png" alt=""></picture><figcaption><p>Ici, le familier "hukarere" est vendu pour 100 <span data-gb-custom-inline data-tag="emoji" data-code="1f4b0">💰</span>.. La guilde La Horde 3 récupère 95% de l'argent pour sa trésorerie.</p></figcaption></figure>

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
{% tab title="Commun" %}
#### Les familiers communs :large\_orange\_diamond:

🐕 **chien.ne** : mord légèrement l'adversaire

🐩 **caniche** : mord légèrement l'adversaire

🐈 **chat.te** : griffe légèrement l’adversaire

🐈‍⬛ **chat.te noir.e** : jette une malédiction sur l'adversaire

🐭 **souris/rongeur** : effraie l'éléphant adverse

🐹 **hamster** : inflige des dégâts dérisoires à l'adversaire

🐰 **lapin.e** : inflige des dégâts dérisoires à l'adversaire

🐄 **boeuf/vache** : charge et étourdit l'adversaire

🐖 **cochon/truie** : charge l'adversaire

🐓 **poule/coq** : frappe l'adversaire de son bec

🐦 **oiseau** : frappe l'adversaire de son bec

🦆 **canard/cane** : frappe l'adversaire de son bec

🕊️ **colombe** : soigne à la fois son propriétaire et l'adversaire

🐟 **poisson** : protège son propriétaire du feu

🐌 **escargot** : ne fait absolument rien (mais il le fait bien)

🐥 **poussin** : inflige des dégâts insignifiants à l'adversaire
{% endtab %}

{% tab title="Peu commun" %}
#### Les familiers peu communs :fire:

🐎 **étalon/jument** : boost la vitesse de son propriétaire

🐏 **bélier/brebis** : charge l'adversaire

🐐 **chèvre/bouc** : charge l'adversaire

🦃 **dinde/dindon** : inflige des dégâts insignifiants à l’adversaire

🦊 **renard.e** : mord l'adversaire

🐸 **grenouille/crapaud** : empoisonne l'adversaire

🦉 **hiboux/chouette** : protège son propriétaire de l'aveuglement

🦇 **chauve-souris** : attaque l'adversaire et soigne son propriétaire

🐗 **sanglier/laie** : charge et étourdit l'adversaire

🦭 **otarie/phoque** : redonne du souffle à son propriétaire

🐀 **rat.e** : mord l'adversaire en l'empoisonnant parfois

🪿 **oie** : frappe l'adversaire de son bec
{% endtab %}

{% tab title="Exotique" %}
#### Les familiers exotiques :trident:

🐢 **tortue** : augmente la défense de son propriétaire, mais le ralentit

🐍 **serpent** : mord et empoisonne l'adversaire

🦎 **lézard** : soigne légèrement son propriétaire

🐨 **koala** : ne fait rien (et assume pleinement)

🐧 **pingouin.e** : fonce sur l’adversaire en glissant

🦛 **hippopotame** : attaque sauvagement l'adversaire

🦙 **lama.te** : crache sur l'adversaire après une attaque physique

🦢 **cygne** : charge l'adversaire

🦩 **flamant rose** : inflige des dégâts insignifiants à l'adversaire

🦝 **raton laveur/ratonne** : dérobe l'arme de l'adversaire

🦨 **putois/moufette** : empoisonne l'adversaire

🦡 **blaireau/blairelle** : griffe légèrement l’adversaire

🦫 **castor** : boost la défense de son propriétaire

🫏 **âne.sse** : boost la vitesse de son propriétaire
{% endtab %}

{% tab title="Rare" %}
#### Les familiers rares :comet:

🐻 **ours.e** : charge et étourdit l'adversaire

🐺 **loup/louve** : mord l'adversaire

🦥 **paresseux/paresseuse** : ne fait rien (et c’est déjà un exploit)

🐿️ **tamia** : inflige des dégâts insignifiants à l'adversaire

🦔 **hérisson.ne** : pique l'adversaire après une attaque physique

🐻‍❄️ **ours.e polaire** : protège son propriétaire du froid

🐼 **panda** : ne fait rien (la flemme, tout simplement)

🦂 **scorpion.ne** : mord et empoisonne l'adversaire

🐊 **crocodile** : mord l'adversaire

🐘 **éléphant.e** : resitue le souffle consommé à son propriétaire

🦓 **zèbre.lle** : boost la vitesse de son propriétaire

🪼 **méduse** : paralyse l'adversaire

🦐 **crevette** : ne fait rien (mais le cœur y est)

🦀 **crabe** : pince l'adversaire
{% endtab %}

{% tab title="Spécial" %}
#### Les familiers spéciaux :dizzy:

🐒 **singe/guenon** : dérobe l'arme de l'adversaire

🦏 **rhinocéros** : donne un coup de corne à l'adversaire

🐪 **dromadaire** : boost la vitesse de son propriétaire

🐫 **chameau/chamelle** : boost la vitesse de son propriétaire

🦒 **girafe** : protège son propriétaire de l'aveuglement

🦘 **kangourou** : assène un coup de poing à l'adversaire

🦚 **paon.ne** : frappe l'adversaire de son bec

🦜 **perroquet** : frappe l'adversaire de son bec

🦦 **loutre** : redonne du souffle à son propriétaire

🐅 **tigre.sse** : griffe férocement l'adversaire

🐙 **poulpe** : rend l'adversaire aveugle

🐋 **baleine** : avale l'adversaire

🦌 **cerf/biche** : donne un coup de corne à l'adversaire

🦬 **bison.ne** : charge et étourdit l'adversaire

🫎 **élan** : vole le bouclier de l'adversaire
{% endtab %}

{% tab title="Épique" %}
#### Les familiers épiques :star:

🦁 **lion.ne** : griffe férocement l'adversaire

🦅 **aigle** : protège son propriétaire de l'aveuglement

🦤 **dodo** : frappe l'adversaire de son bec

🐆 **léopard.e** : griffe férocement l'adversaire

🦣 **mammouth** : protège son propriétaire du froid

⛄ **bonhomme de neige** : gèle l'adversaire

🐧 **manchot.e** : percute l'adversaire en glissant

🐡 **poisson globe** : protège son propriétaire du feu

🦈 **requin** : effraie tous les poissons

🦞 **homard** : pince l'adversaire

🐬 **dauphin** : protège son propriétaire du feu

🐃 **buffle d'eau** : charge et étourdit l'adversaire

🦧 **orang-outan** : boost aléatoirement la vitesse la défense ou l'attaque de son propriétaire

🦍 **gorille** : assène un coup de poing à l'adversaire
{% endtab %}

{% tab title="Mythique" %}
#### Les familiers mythiques :gem:

:vampire:**vampire**: soigne son adversaire à partir de l'énergie vitale de son adversaire, sa morsure fait saigner

:fairy:**fée**: soigne son propriétaire avec efficacité et régularité
{% endtab %}

{% tab title="Légendaire" %}
#### Les familiers légendaire :star2:

🦄 **licorne** : soigne son propriétaire après une attaque magique

🐉 **dragon.ne** : brûle l'adversaire

🦖 **t-rex** : attaque sauvagement l'adversaire et inflige de légers dégâts à son propriétaire

🟣 **stitch/angel** : attaque sauvagement l'adversaire et inflige de légers dégâts à son propriétaire

🦆 **canard écarlate/cane écarlate** : attaque sauvagement l'adversaire en fin de combat

☃️ **bonhomme de neige** : gèle l'adversaire

👽 **alien.ne** : rend l'adversaire confus

🐠 **poisson tropical** : protège son propriétaire du feu

🐳 **baleine** : avale l'adversaire

🐦‍🔥 **phénix** : soigne son propriétaire

🦕 **diplodocus** : écrase l'adversaire

🐦‍⬛ **merle** : frappe l'adversaire de son bec

🐦‍⬛ **corbeau** : maudit l'adversaire

🎃 **jack-o-lantern** : son regard hypnotique pétrifie l'adversaire

👻 **fantôme** : jette une malédiction sur l'adversaire
{% endtab %}
{% endtabs %}

### Les expéditions

Pour débloquer les expéditions,il faudra le talisman d'ancrage qui est remis par [Velanna ](../notions-avancees/mini-evenements.md#conseils-sur-les-expeditions)à partir de votre troisième rencontre si vous avez un familier nourri et non fielleux, que vous êtes au moins niveau 30, que vous appartenez à une guilde et que votre familier a déjà été présenté à [Talvar](../notions-avancees/mini-evenements.md#le-nain-fan-des-animaux).

Les expéditions coûtent des provisions (jusqu'à 32 :meat\_on\_bone:) et ont une durée (jusqu'à 3 jours) mais rapportent des jetons :coin:, de l'argent :moneybag:, de l'expérience :star:, des points :medal:, des matériaux :bricks: et un équipement :hammer\_pick:en cas de succès partiel ou total.

{% hint style="info" %}
Pensez à vérifier l’entrepôt de la guilde avant de laisser partir votre familier en expédition. Si ce dernier n'a pas assez de provisions ses chances de succès sont considérablement diminuées.
{% endhint %}

Pour commencer une expédition, le joueur doit posséder un familier nourri et avec 20 points d'amour ou plus et un talisman d'ancrage. Il vous suffira ensuite de cliquer sur le bouton :map:**Expédition** pour qu'apparaisse un menu qui vous proposera trois destinations.

<figure><picture><source srcset="../.gitbook/assets/expedition_generation_entier_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/expedition_generation_entier_clair.png" alt="Le talisman d&#x27;ancrage propose 3 expéditions avec leurs destinations, leurs durées, leurs dangerosités, la difficulté de leurs terrain, leurs récompenses et les vôutrs en provisions."></picture><figcaption><p>C'est parti pour l'aventure</p></figcaption></figure>

{% hint style="info" %}
Chaque expédition a une plage de durée définie : moins d'une heure pour la première, moins de 10h pour la deuxième et 12h à 3j pour la troisième. Chaque familier possède une statistique de vitesse, comprise entre 1 et 30, qui peut raccourcir ou allonger la durée finale.
{% endhint %}

{% hint style="info" %}
Le biome des deux premières expéditions dépend de votre position sur la carte, et correspond à vos lieux de départ et d'arrivée.
{% endhint %}

{% hint style="warning" %}
Si vous décidez d'annuler le départ en expédition et à partir de la deuxième fois en 7j, votre familier perdra considérablement confiance en vous et ce de plus en plus.
{% endhint %}

Avant de choisir une expédition, il faut savoir que son taux de réussite et ses récompenses dépend de pleins de facteurs. La dangerosité et le terrain augmente les échecs, là où la force :muscle: et l'amour :revolving\_hearts: du familier les réduisent.&#x20;

| Dangerosité                                                                                                                                                                                         | Terrain                                                                                                                                                                                            |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p>-Tranquille 🌿 (0–10)<br>-Serein ☀️ (11-20)<br>-Hasardeux 🌤️ (21–32)<br>-Risqué ⚡ (33–45)<br>-Dangereux 🔥 (46–58)<br>-Périlleux ⚠️ (59-72)<br>-Mortel 💀 (73–86)<br>-Désespéré ⚰️ (87–100)</p> | <p>-Paisible <span data-gb-custom-inline data-tag="emoji" data-code="1f338">🌸</span>(0-20)<br>-Praticable 🌲(21-40)<br>-Accidenté ⛰️ (41-60)<br>-Hostile 🏔️ (61-80)<br>-Périlleux 🌋(81-100)</p> |

{% hint style="info" %}
Le Terrain impacte 4 fois moins les échecs que la Dangerosité, pour la même influence sur le butin.&#x20;
{% endhint %}

{% hint style="info" %}
Le biome de l'expédition influence la dangerosité, en effet une grotte est plus souvent périlleuse et une plaine plus souvent tranquille ; mais aussi les récompenses : certains terrains donne plus d'expérience :star:, d'autres plus de points :medal: ou d'argent :moneybag:.
{% endhint %}

Pour augmenter vos chances de réussite de vos expéditions, en plus de regarder la difficulté et le terrain, vous pouvez:

* Dresser votre familier.
* Choisir un familier avec une meilleure statistique de force.
* Envoyer votre familier dans un lieu qu'il apprécie particulièrement. Cela réduit de 5% les échecs.
* Vérifier que l’entrepôt de votre guilde contient suffisamment de provisions.

{% hint style="danger" %}
Une expédition détestée de moins de 12h aura 10% d'échec supplémentaire.
{% endhint %}

{% hint style="info" %}
Vous pouvez connaître les appréciations d'un familier à l'aide du :health\_worker: vétérinaire, ou en essayant diverses biomes.
{% endhint %}

Une fois l'expédition terminée, vous pourrez appeler votre familier pour récupérer le butin avec le bouton :map: Expédition après avoir fait la commande `/familier` .

<figure><picture><source srcset="../.gitbook/assets/FinExpedition_sombre.png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/FinExpedition_clair.png" alt="Interface du /familier puis appui sur le bouton Expedition pour le rappeler"></picture><figcaption><p>Fin d'une expédition de familier et ouverture du butin</p></figcaption></figure>

Si l'expédition est un échec, le familier perd 3 points d'affection :revolving\_hearts:.

Sinon, vous recevez de l'argent :moneybag:, de l'expérience :star: et des points :medal:. La difficulté de l'expédition et de son terrain ainsi que les rations consommées :meat\_on\_bone:, le type de biome et une réussite totale ou partielle (/2 des gains) statuent sur leurs valeurs. Les expéditions rapportent aussi des jetons :coin:, des matériaux :bricks: et un équipement :hammer\_pick:, dont la quantité et la rareté varie selon la richesse du butin.&#x20;

<details>

<summary>Tableau des gains <span data-gb-custom-inline data-tag="emoji" data-code="1f4ca">📊</span></summary>

Le tableau ci-dessous résume les gains de base des expédions selon le nombre de rations :meat\_on\_bone: consommées. Il faut ensuite ajouter les coefficients de chaque biome :map: ainsi que les préférences et la possibilité d'un succès partiel (récompenses /2, incluant le nombre de matériaux mais ni les jetons ni la rareté de l'équipement). Une expédition de plus de 1h rapportera aussi 1 jeton :coin: supplémentaire, sauf pour le palier 0 qui est entre 1 et 2 :coin:.&#x20;

Les jetons et l'équipement n'est pas impacté par les biomes, le succès ou les préférences.

<table data-search="false"><thead><tr><th width="147.5" align="center">Palier de récompenses</th><th width="119.5" align="right">🍖 Rations</th><th width="109" align="right">💰 Argent</th><th width="139" align="right">⭐ Expérience</th><th width="108.5" align="right">🏅 Points</th><th width="110.5" align="center">🪙 Jetons</th><th width="128">💫 Rareté équipement</th><th>Nombre de matériaux</th></tr></thead><tbody><tr><td align="center">0</td><td align="right">1 🍖</td><td align="right">50 💰</td><td align="right">35 ⭐</td><td align="right">6 🏅</td><td align="center">1 🪙</td><td>max 💫</td><td>0</td></tr><tr><td align="center">1</td><td align="right">3 🍖</td><td align="right">120 💰</td><td align="right">105 ⭐</td><td align="right">20 🏅</td><td align="center">1–3 🪙</td><td>max 💫</td><td>1</td></tr><tr><td align="center">2</td><td align="right">5 🍖</td><td align="right">235 💰</td><td align="right">245 ⭐</td><td align="right">75 🏅</td><td align="center">2–4 🪙</td><td>max ⭐</td><td>2</td></tr><tr><td align="center">3</td><td align="right">6 🍖</td><td align="right">435 💰</td><td align="right">420 ⭐</td><td align="right">145 🏅</td><td align="center">3–5 🪙</td><td>max 🌟</td><td>2</td></tr><tr><td align="center">4</td><td align="right">8 🍖</td><td align="right">710 💰</td><td align="right">665 ⭐</td><td align="right">210 🏅</td><td align="center">4–6 🪙</td><td>Quelconque</td><td>3</td></tr><tr><td align="center">5</td><td align="right">10 🍖</td><td align="right">1300 💰</td><td align="right">980 ⭐</td><td align="right">340 🏅</td><td align="center">5–7 🪙</td><td>Quelconque</td><td>3</td></tr><tr><td align="center">6</td><td align="right">12 🍖</td><td align="right">2100 💰</td><td align="right">1365 ⭐</td><td align="right">420 🏅</td><td align="center">6–8 🪙</td><td>🔥–💎</td><td>4</td></tr><tr><td align="center">7</td><td align="right">15 🍖</td><td align="right">3200 💰</td><td align="right">1785 ⭐</td><td align="right">585 🏅</td><td align="center">7–9 🪙</td><td>🔱–💎</td><td>4</td></tr><tr><td align="center">8</td><td align="right">25 🍖</td><td align="right">4200 💰</td><td align="right">2100 ⭐</td><td align="right">650 🏅</td><td align="center">8–10 🪙</td><td>☄️–💎</td><td>5</td></tr><tr><td align="center">9</td><td align="right">32 🍖</td><td align="right">5000 💰</td><td align="right">2450 ⭐</td><td align="right">710 🏅</td><td align="center">9–11 🪙</td><td>💫–💎</td><td>5</td></tr></tbody></table>

{% hint style="info" %}
Les bénédictions peuvent aussi augmenter ces gains, que ce soit la bénédiction Gloire accrue pour les points :medal:, Bourse dorée pour l'argent :moneybag: ou Jeton d'expédition pour les jetons :coin:.
{% endhint %}

</details>

<details>

<summary>Les biomes et leurs gains <span data-gb-custom-inline data-tag="emoji" data-code="1f5fa">🗺️</span></summary>

Le tableau ci-dessous répertorie les coefficients d'argent :moneybag:, d'expérience :star: et de points :medal:de chaque biome, classés par difficulté. Les plaines :ear\_of\_rice:, les plus faciles, sont équilibrées entre les butins là où les grottes :hole:, particulièrement difficiles, priorisent l'argent :moneybag:.

<table data-search="false"><thead><tr><th width="133">Biome</th><th>Coefficient argent</th><th>Coefficient expérience</th><th>Coefficient points</th></tr></thead><tbody><tr><td>Plaine <span data-gb-custom-inline data-tag="emoji" data-code="1f33e">🌾</span></td><td>1</td><td>1</td><td>1</td></tr><tr><td>Côte <span data-gb-custom-inline data-tag="emoji" data-code="1f30a">🌊</span></td><td>1,2</td><td>0,7</td><td>0,8</td></tr><tr><td>Forêt <span data-gb-custom-inline data-tag="emoji" data-code="1f332">🌲</span></td><td>0,8</td><td>1,3</td><td>0,9</td></tr><tr><td>Désert <span data-gb-custom-inline data-tag="emoji" data-code="1f3dc">🏜️</span></td><td>0,6</td><td>0,4</td><td>1,5</td></tr><tr><td>Montagne <span data-gb-custom-inline data-tag="emoji" data-code="26f0">⛰️</span></td><td>1,9</td><td>1</td><td>0,3</td></tr><tr><td>Marais <span data-gb-custom-inline data-tag="emoji" data-code="1f33f">🌿</span></td><td>0,4</td><td>1</td><td>1,6</td></tr><tr><td>Ruine <span data-gb-custom-inline data-tag="emoji" data-code="1f3db">🏛️</span></td><td>1,7</td><td>1</td><td>0,5</td></tr><tr><td>Grotte <span data-gb-custom-inline data-tag="emoji" data-code="1f573">🕳️</span></td><td>2,2</td><td>0,5</td><td>0,2</td></tr></tbody></table>

Voici la liste des correspondances lieux - biomes.&#x20;

* **Plaine 🌾:** Mergagnan 🏘️, Voie champrête 🛣️, Berceau 🌺, Grande Rue 🛣️, Grand Axe 🛣️, Étendue 🌺, Croisement des Destins 🛣️, Claire de Ville 🏘️ & Route des Merveilles 🛣️
* **Côte 🌊 :** Rivière aux Crabes 🏞️, Plage Sentinelle 🏖️ & Rivière Vacarme 🏞️
* **Forêt 🌲 :** Forêt du Vieillard 🌳, Forêt Célestrum 🌳 & Chemin aux Loups 🛣️
* **Grotte 🕳️ :** Bois Hurlant 🌳, Cour du Château :homes: & Boug-Coton 🛖
* **Montagne ⛰️ :** Mont Célestrum ⛰️ & Route Grimpante 🛣️
* **Désert 🏜️ :** Village Coco 🛖 & Dune 🏖️
* **Ruine 🏛️ :** Ville Forte 🏚️, Chemin du Dédale 🛣️ & Vallée des Rois 🏜️
* **Marais 🌿 :** Route Marécageuse 🛣️ & Lac Mirage 🚣‍♂️

</details>

Un terrain apprécié :green\_heart: par le familier permet de récupérer 100% des récompenses, là où un terrain neutre ne gagne que 80% et détesté :broken\_heart: 25%. Le familier reçoit aussi des points d'amour :revolving\_hearts:, et plus encore s'il a apprécié le terrain de son aventure.

{% hint style="info" %}
Les expéditions mentionnant un trésor en jetons rapporteront trois fois plus de jetons :coin: !
{% endhint %}

<figure><picture><source srcset="../.gitbook/assets/ExpeditionReward_sombre (1).png" media="(prefers-color-scheme: dark)"><img src="../.gitbook/assets/ExpeditionReward_clair.png" alt=""></picture><figcaption><p>Une réussite d'expédition longue dans un biome grotte <span data-gb-custom-inline data-tag="emoji" data-code="1f573">🕳️</span></p></figcaption></figure>

{% hint style="warning" %}
Quand votre familier est en expédition, il n'est pas considéré comme équipé, il ne vous assistera pas pendant les mini-événements, les combats (attaque et défense) et sur les îles mystérieuses.
{% endhint %}

{% hint style="success" %}
Les jetons en récompenses des expéditions peuvent vous faire dépasser la limite de 20.
{% endhint %}

{% hint style="info" %}
Vous pouvez trouver au cours de vos expéditions avec une petite probabilité un talisman de clonage :dna: (certains expéditions parle de ce talisman ce qui se traduit par un multiplicateur x10). Ce puissant artefact crée un double de votre familier qui vous aidera dans les mini-événements et les combats, en défense uniquement.
{% endhint %}
