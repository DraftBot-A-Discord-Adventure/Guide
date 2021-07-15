# Familiers

Depuis la version [2.1.2](https://history.draftbot.com/draftbot-v2/2.1.2) de DraftBot, vous pouvez avoir un ou plusieurs **familiers**. Ils s'obtiennent dans les récompenses de [guilde ](guildes.md)en fonction du niveau de votre guilde.

{% hint style="info" %}
Pour le moment les familiers sont purement esthétiques. Ils n'ont pas de fonction à proprement parler, mais cela est amené à changer dans une future mise à jour.
{% endhint %}

Pour avoir les informations sur votre familier, vous devez utiliser la commande `!mypet` .

Il y a 5 niveaux de **rareté** de familiers, ceux-ci sont représentés par des étoiles ⭐ ⭐ ⭐ ⭐ ⭐ 

Les familiers ont un **moral**, si vous les nourrissez à intervalle régulier leur moral augmentera. A contrario, si vous délaissez vos familiers leur moral diminuera.

### Comment obtenir un familier ?

Les familiers s'obtiennent dans les récompenses de guildes `!guilddaily` avec 1% de chance ou alors dans un mini-évènement.

La probabilité d'avoir des raretés supérieures augmente avec le niveau de votre guilde.

| Niveau guilde/rareté familier | 1⭐  | 2 ⭐  | 3 ⭐  | 4 ⭐  | 5 ⭐  |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 90% | 9% | 0.9% | 0.09% | 0.01% |
| 10 | 89.4% | 9.16% | 1.091% | 0.23% | 0.119% |
| 20 | 87.6% | 9.64% | 1.664% | 0.65% | 0.446% |
| 30 | 84.6% | 10.44% | 2.619% | 1.35% | 0.991% |
| 40 | 80.4% | 11.56% | 3.956% | 2.33% | 1.754% |
| 50 | 75% | 13% | 5.675% | 3.59% | 2.735% |
| 60 | 68.4% | 14.76% | 7.776% | 5.13% | 3.934% |
| 70 | 60.6% | 16.84% | 10.259% | 6.9499% | 5.3511% |
| 80 | 51.6% | 19.24% | 13.124% | 9.0499% | 6.9861% |
| 90 | 41.4% | 21.96% | 16.371% | 11.4299% | 8.8391% |
| 100 | 30% | 25% | 20% | 14.0899% | 10.9101% |

{% hint style="info" %}
Si un pet est obtenu dans un mini-évènement, sa rareté est générée avec les statistiques des guildes de niveau 20.
{% endhint %}

Vous pouvez libérer votre familier avec la commande `!petfree` .

{% hint style="danger" %}
`Attention, cette action est irréversible, si vous libérez un familier, c'est définitif.`
{% endhint %}

### Comment nourrir mon familier ?

#### Acheter de la nourriture.

L'achat de nourriture pour les familiers se fait dans le magasin de votre guilde. Si vous n'avez pas de guilde, vous n'aurez accès qu'a la forme la plus basique de nourriture pour votre animal.

![Le magasin de guilde permet d&apos;acheter diff&#xE9;rentes sortes de nourritures](../.gitbook/assets/image%20%2818%29.png)

La nourriture va permettre d'influer sur le moral de votre animal, pour nourrir votre familier vous devez utiliser la commande `!feedpet` ou son alias `!fp`.

![La commande feedpet](../.gitbook/assets/image%20%2819%29.png)

Chaque type de nourriture fera gagner une quantité différente de points d'affection à votre familier. 

* Les friandises feront gagner 1 point d'affection.
* Les steaks et salade feront gagner 3 points d'affections.
* Les soupes ultimes feront gagner 5 points d'affections.

Cependant, le type de nourriture n'a pas d'influence sur la durée pendant laquelle votre familier n'a pas faim.

{% hint style="info" %}
La durée pendant laquelle un familier n'a pas faim dépend uniquement de la rareté du pet. Le nombre d'étoiles de rareté est égal au nombre d'heures qu'il faut attendre entre deux repas.
{% endhint %}

Certains familiers suivent un régime particulier \(herbivores ou carnivores\) et ne pourront donc pas profiter de certaines sources de nourritures. Ne donnez pas de salade à votre T-rex !

Ne négligez pas votre familier ! Son moral baissera si vous oubliez de vous en occuper. 

{% hint style="warning" %}
Le moral d'un familier baisse de deux points par jour en moyenne, cette baisse ne tient pas compte de la rareté du pet.
{% endhint %}

{% hint style="danger" %}
Il n'est pas possible d'effectuer certaines actions avec un familier fielleux !
{% endhint %}

Il existe pour le moment 5 niveaux de moral qui correspondent à la mentalité de votre familier, ils sont classés de cette manière :

1.  😼 Fielleux
2.  😾 Sauvage
3.  🙀 Craintif
4.  😺 Apprivoisé
5.  😻 Dressé

{% hint style="info" %}
Les animaux dressés ne perdent plus de moral et n'ont donc pas besoin d'être nourris pour être aimé \(mais vous pouvez le faire quand même\).
{% endhint %}

{% hint style="danger" %}
Échanger ou vendre un familier avec un autre joueur réinitialisera son moral à 😾 Sauvage.

Changer de propriétaire, c'est dur à supporter pour un animal !
{% endhint %}

### Comment stocker mon familier ?

Vous avez la possibilité de stocker votre familier dans le **refuge de votre guilde**. Ou alors de le récupérer avec vous. Pour cela, vous devez effectuer la commande `!pettransfer <id du familier>` exemple :`!pettransfer 1` permet de récupérer le familier n°1 du refuge.

Pour visualiser le refuge, vous pouvez utiliser la commande `!shelter`.

![Refuge de la guilde Draftpedia](../.gitbook/assets/shelter-pets.png)

{% hint style="info" %}
Le refuge de votre guilde permet d'accueillir jusqu'à 6 familiers différents.
{% endhint %}

### Surnommer un familier

Vous pouvez définir un surnom pour votre familier pour rendre ce dernier unique. Pour cela, quand vous avez un familier avec vous tapez la commande `!petnickname <surnom>` exemple : `!petnickname Henri` permet de surnommer votre familier "Henri".

![Commande !mypet avec affichage du surnom du familier](../.gitbook/assets/rename-pets.png)

* Le vendeur ne gagnera pas d'argent lors de la transaction, mais de l'expérience de guilde.

###  Échange de familiers

L'implémentation de cette mise à jour favorise l'interaction entre joueurs puisque vous avez la possibilité d'échanger un familier avec la commande `!pettrade <mention joueur>` exemple : `!pettrade @Heliox#1119` permet d'ouvrir l'interface d'échange de familier avec le joueur **Heliox**.

![Menu d&apos;&#xE9;change de familiers](../.gitbook/assets/trade-pets.png)

### Vente de familiers

Si vous souhaitez vous débarrasser d'un familier mais que vous n'avez pas le cœur de le libérer, \(ou alors que vous aimez l'argent\), il est possible d'échanger le familier que vous transportez contre un peu d’expérience pour votre guilde. Pour cela, vous pouvez utiliser la commande `!petsell [prix]`.

![Ici le familier &quot;Elle&quot; est vendu](../.gitbook/assets/image%20%2817%29.png)

Il y a des conditions importantes à respecter pour la vente de familier:

* Il n'est pas possible de vendre un pet à un membre de sa guilde.
* Il est nécessaire d'appartenir à une guilde pour vendre un pet mais pas pour l'acheter.

{% hint style="warning" %}
Le vendeur ne gagnera pas d'argent lors de la transaction, mais de l'expérience de guilde.
{% endhint %}

### **Liste des familiers disponibles**

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>Commun</b>
      </th>
      <th style="text-align:left"><b>Peu commun</b>
      </th>
      <th style="text-align:left"><b>Rare</b>
      </th>
      <th style="text-align:left"><b>Tr&#xE8;s rare</b>
      </th>
      <th style="text-align:left"><b>L&#xE9;gendaire</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p>Chien&#x1F415;</p>
        <p>Caniche&#x1F429;</p>
        <p>Chat&#x1F408;</p>
        <p>Chat noir
          <img src="https://discord.com/assets/a784784c984905c2a74507d57aa3523e.svg"
          alt=":black_cat:" />
        </p>
        <p>Souris&#x1F401;</p>
        <p>Hamster
          <img src="https://discord.com/assets/fc50a173b1afcfb37d141e4bee11e479.svg"
          alt=":hamster:" />
        </p>
        <p>Lapin
          <img src="https://discord.com/assets/e076bda560b596a206ea032e02bd411b.svg"
          alt=":rabbit2:" />
        </p>
        <p>Vache
          <img src="https://discord.com/assets/3c6d0d0cdd8a07c4c6837fd143e1e60c.svg"
          alt=":cow2:" />
        </p>
        <p>Cochon
          <img src="https://discord.com/assets/d083412544c302d290775006877f6202.svg"
          alt=":pig2:" />
        </p>
        <p>Poule / Coq
          <img src="https://discord.com/assets/468644ef0a79a3d8163f7778164b756d.svg"
          alt=":chicken:" />
        </p>
        <p>Oiseau
          <img src="https://discord.com/assets/cf725f98edb284d25530f5dbd7d30ee4.svg"
          alt=":bird:" />
        </p>
        <p>Canard
          <img src="https://discord.com/assets/5e623785155f790f48901eeb4e5022c9.svg"
          alt=":duck:" />
        </p>
        <p>Cheval
          <img src="https://discord.com/assets/591183f3386ef43f266bd7bcf03ef83f.svg"
          alt=":racehorse:" />
        </p>
        <p>Tortue
          <img src="https://discord.com/assets/0da5614923cc73f71ea9641a5cdb5a3e.svg"
          alt=":turtle:" />
        </p>
        <p>Serpent
          <img src="https://discord.com/assets/dbfbe586e724f4a0cd993d0c1048316b.svg"
          alt=":snake:" />
        </p>
        <p>L&#xE9;zard
          <img src="https://discord.com/assets/1703f9a3721beece0d66f10c0ef9d3d0.svg"
          alt=":lizard:" />
        </p>
        <p>B&#xE9;lier / Mouton
          <img src="https://discord.com/assets/1118afb9d722b17e0cb0595bbe4f6e0a.svg"
          alt=":sheep:" />
        </p>
        <p>Ch&#xE8;vre / Bouc
          <img src="https://discord.com/assets/55aecf5f15c4f21115d04f8cd63fb3ab.svg"
          alt=":goat:" />
        </p>
        <p>Dindon
          <img src="https://discord.com/assets/618ca8489ae1ab5f94fde2e3a7fb2c0c.svg"
          alt=":turkey:" />
        </p>
      </td>
      <td style="text-align:left">
        <p>Renard
          <img src="https://discord.com/assets/ba34ab28ffd9aeddbce8253362a33dd1.svg"
          alt=":fox:" />
        </p>
        <p>Ours
          <img src="https://discord.com/assets/589b531ad20f070bbee33f31f233c135.svg"
          alt=":bear:" />
        </p>
        <p>Koala
          <img src="https://discord.com/assets/6ea80059130bde711bef1b446f78e282.svg"
          alt=":koala:" />
        </p>
        <p>Grenouille
          <img src="https://discord.com/assets/68af06bbac9f4830d08fa474f201f92b.svg"
          alt=":frog:" />
        </p>
        <p>Singe
          <img src="https://discord.com/assets/766e42505fdf9dc7c390ecd08c0bc4a6.svg"
          alt=":monkey:" />
        </p>
        <p>Pingouin
          <img src="https://discord.com/assets/727bc86f98316c40c37e48797f2ab196.svg"
          alt=":penguin:" />
        </p>
        <p>Hibou
          <img src="https://discord.com/assets/59e611bd4994d2978d695df90db540c4.svg"
          alt=":owl:" />
        </p>
        <p>Chauve-souris
          <img src="https://discord.com/assets/af70a9ae5dd90f1078e363eab1c855cc.svg"
          alt=":bat:" />
        </p>
        <p>Loup
          <img src="https://discord.com/assets/70c59f59ef85eeddfd7d3962a4840cb8.svg"
          alt=":wolf:" />
        </p>
        <p>Sanglier
          <img src="https://discord.com/assets/1a7689368e6b9d41ce8db98f709ca08a.svg"
          alt=":boar:" />
        </p>
        <p>Otarie
          <img src="https://discord.com/assets/a6e116c71ab2e177001c5ca9977e68d1.svg"
          alt=":seal:" />
        </p>
        <p>Hippopotame
          <img src="https://discord.com/assets/77c65f388b96be7a8bd2d8334fb546bc.svg"
          alt=":hippopotamus:" />
        </p>
        <p>Lama
          <img src="https://discord.com/assets/fa08c3c8afc72844296f9c00465be77a.svg"
          alt=":llama:" />
        </p>
        <p>Cygne
          <img src="https://discord.com/assets/05d31fd63d5a6a3cef375d3d326a8a0c.svg"
          alt=":swan:" />
        </p>
        <p>Flamand rose
          <img src="https://discord.com/assets/430705f097a53695b1bf71c6de22b866.svg"
          alt=":flamingo:" />
        </p>
        <p>Raton Laveur
          <img src="https://discord.com/assets/09b38a6de1509c805be67eed340e2f8f.svg"
          alt=":raccoon:" />
        </p>
        <p>Putois
          <img src="https://discord.com/assets/7631a1b3137202d7b80e48d99987484f.svg"
          alt=":skunk:" />
        </p>
        <p>Blaireau
          <img src="https://discord.com/assets/82cb4a510436e4755388615426d2de73.svg"
          alt=":badger:" />
        </p>
        <p>Castor
          <img src="https://discord.com/assets/0ee00f8f2f780bb43828baa8684991e2.svg"
          alt=":beaver:" />
        </p>
        <p>Paresseux
          <img src="https://discord.com/assets/cdc3facd345983768d3bd16aa6021f90.svg"
          alt=":sloth:" />
        </p>
        <p>Tamia
          <img src="https://discord.com/assets/de0f03380b137cdb950b1a9d2ca04a3b.svg"
          alt=":chipmunk:" />
        </p>
        <p>H&#xE9;risson&#x1F994;&#xFE0F;</p>
      </td>
      <td style="text-align:left">
        <p>Ours polaire
          <img src="https://discord.com/assets/eb3b52294d6cbab490cdb577afe40b11.svg"
          alt=":polar_bear:" />
        </p>
        <p>Panda
          <img src="https://discord.com/assets/ffa1f81e3c3364ef04f9a1a26b55b42b.svg"
          alt=":panda_face:" />
        </p>
        <p>Scorpion
          <img src="https://discord.com/assets/738160272d6024585562a55a39e1cb25.svg"
          alt=":scorpion:" />
        </p>
        <p>Crocodile
          <img src="https://discord.com/assets/fface028e87dd156db7f772d5009211e.svg"
          alt=":crocodile:" />
        </p>
        <p>&#xC9;l&#xE9;phant
          <img src="https://discord.com/assets/a2893dfac8eccc398a9b14402df114c2.svg"
          alt=":elephant:" />
        </p>
        <p>Z&#xE8;bre
          <img src="https://discord.com/assets/536b3e1a4ba312bd793ca96a4d0487f2.svg"
          alt=":zebra:" />
        </p>
        <p>Rhinoc&#xE9;ros
          <img src="https://discord.com/assets/1d5443faf52d355d2abd7900449eb5ae.svg"
          alt=":rhino:" />
        </p>
        <p>Dromadaire
          <img src="https://discord.com/assets/14baad8ac7905736f0505fef9e6761a8.svg"
          alt=":dromedary_camel:" />
        </p>
        <p>Chameau
          <img src="https://discord.com/assets/aa2e827a8b3c78ded1a842fa19f89326.svg"
          alt=":camel:" />
        </p>
        <p>Girafe
          <img src="https://discord.com/assets/d0f34dde89da79643396c7bdc41493bd.svg"
          alt=":giraffe:" />
        </p>
        <p>Kangourou
          <img src="https://discord.com/assets/e6afe8d972ad58432c61bd59e9df132f.svg"
          alt=":kangaroo:" />
        </p>
        <p>Paon
          <img src="https://discord.com/assets/4a5fb8d468c3d4c13216440813feb418.svg"
          alt=":peacock:" />
        </p>
        <p>P&#xE9;rroquet
          <img src="https://discord.com/assets/ef02cd8645bcdff874d23500b2b516fd.svg"
          alt=":parrot:" />
        </p>
        <p>Loutre
          <img src="https://discord.com/assets/a8ef7bbc89c69e7de6d38b6fc1f92dab.svg"
          alt=":otter:" />
        </p>
      </td>
      <td style="text-align:left">
        <p>Tigre
          <img src="https://discord.com/assets/df8b26ce08bff3cc70d505b48ccdc71c.svg"
          alt=":tiger2:" />
        </p>
        <p>Lion
          <img src="https://discord.com/assets/e23557c7f844b57a30a431444b64af5f.svg"
          alt=":lion_face:" />
        </p>
        <p>Aigle
          <img src="https://discord.com/assets/eefee5ca29d3804705c4c61dc104efb1.svg"
          alt=":eagle:" />
        </p>
        <p>Dodo
          <img src="https://discord.com/assets/76174ac71d3cebcc5ec2949e33a2ed25.svg"
          alt=":dodo:" />
        </p>
        <p>L&#xE9;opard
          <img src="https://discord.com/assets/a4ae9ac0cb5ad12a68f767d39b249811.svg"
          alt=":leopard:" />
        </p>
        <p>Mammouth
          <img src="https://discord.com/assets/af5f26288872cf6f0f22ef421fc394cd.svg"
          alt=":mammoth:" />
        </p>
        <p>Colombe
          <img src="https://discord.com/assets/49533def46858e98682242755ef6912b.svg"
          alt=":dove:" />
        </p>
      </td>
      <td style="text-align:left">
        <p>Licorne&#x1F984;&#xFE0F;</p>
        <p>Dragon
          <img src="https://discord.com/assets/d73ab953aa1a3b9cca3a5a0bb6c37842.svg"
          alt=":dragon:" />
        </p>
        <p>T-rex&#x1F996;&#xFE0F;</p>
        <p>Stitch/Angel</p>
        <p>
          <img src="https://discord.com/assets/35fce59c5d17a56d69c3de3d8864ed22.svg"
          alt=":blue_circle:" />
        </p>
      </td>
    </tr>
  </tbody>
</table>

