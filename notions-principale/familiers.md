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
* Les steaks et salade feront gagner 3 points d'affection.
* Les soupes ultimes feront gagner 5 points d'affection.

Cependant, le type de nourriture n'a pas d'influence sur la durée pendant laquelle votre familier n'a pas faim.

{% hint style="info" %}
La durée pendant laquelle un familier n'a pas faim dépend uniquement de la rareté du pet. Le nombre d'étoiles de rareté est égal au nombre d'heures qu'il faut attendre entre deux repas.
{% endhint %}

Certains familiers suivent un régime particulier \(herbivore ou carnivore\) et ne pourront donc pas profiter de certaines sources de nourritures. Ne donnez pas de salade à votre T-rex !

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

Vous pouvez définir un surnom pour votre familier afin de rendre ce dernier unique. Pour cela, quand vous avez un familier avec vous tapez la commande `!petnickname <surnom>` exemple : `!petnickname Henri` permet de surnommer votre familier "Henri".

![Commande !mypet avec affichage du surnom du familier](../.gitbook/assets/rename-pets.png)

###  Échange de familiers

L'implémentation de cette mise à jour favorise l'interaction entre joueurs puisque vous avez la possibilité d'échanger un familier avec la commande `!pettrade <mention joueur>` exemple : `!pettrade @Heliox#1119` permet d'ouvrir l'interface d'échange de familier avec le joueur **Heliox**.

![Menu d&apos;&#xE9;change de familiers](../.gitbook/assets/trade-pets.png)

### Vente de familiers

Si vous souhaitez vous débarrasser d'un familier mais que vous n'avez pas le cœur de le libérer, \(ou alors que vous aimez l'argent\), il est possible de vendre le familier que vous transportez. Pour cela, vous pouvez utiliser la commande `!petsell [prix]`.

![Ici le familier &quot;Elle&quot; est vendu](../.gitbook/assets/image%20%2817%29.png)

Il y a des conditions importantes à respecter pour la vente de familier:

* Il n'est pas possible de vendre un familier à un membre de sa guilde.
* Il est nécessaire d'appartenir à une guilde pour vendre un familier mais pas pour l'acheter.

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
        <p>Hamster &#x1F439;</p>
        <p>Lapin &#x1F407;</p>
        <p>Vache &#x1F404;</p>
        <p>Cochon &#x1F437;</p>
        <p>Poule / Coq &#x1F414;</p>
        <p>Oiseau &#x1F426;</p>
        <p>Canard &#x1F986;</p>
        <p>Cheval &#x1F40E;</p>
        <p>Tortue &#x1F422;</p>
        <p>Serpent &#x1F40D;</p>
        <p>L&#xE9;zard &#x1F98E;</p>
        <p>B&#xE9;lier / Mouton &#x1F411;</p>
        <p>Ch&#xE8;vre / Bouc &#x1F410;</p>
        <p>Dindon &#x1F983;</p>
      </td>
      <td style="text-align:left">
        <p>Renard &#x1F98A;</p>
        <p>Ours &#x1F43B;</p>
        <p>Koala &#x1F428;</p>
        <p>Grenouille &#x1F438;</p>
        <p>Singe &#x1F412;</p>
        <p>Pingouin &#x1F427;</p>
        <p>Hibou &#x1F989;</p>
        <p>Chauve-souris &#x1F987;</p>
        <p>Loup &#x1F43A;</p>
        <p>Sanglier &#x1F417;</p>
        <p>Otarie
          <img src="../.gitbook/assets/seal.svg" alt=":seal:" />
        </p>
        <p>Hippopotame &#x1F99B;</p>
        <p>Lama &#x1F999;</p>
        <p>Cygne &#x1F9A2;</p>
        <p>Flamant rose
          <img src="../.gitbook/assets/flamingo.svg" alt=":flamingo:"
          />
        </p>
        <p>Raton Laveur &#x1F99D;</p>
        <p>Putois
          <img src="https://discord.com/assets/7631a1b3137202d7b80e48d99987484f.svg"
          alt=":skunk:" />
        </p>
        <p>Blaireau
          <img src="../.gitbook/assets/badger.svg" alt=":badger:" />
        </p>
        <p>Castor
          <img src="../.gitbook/assets/beaver.svg" alt=":beaver:" />
        </p>
        <p>Paresseux
          <img src="../.gitbook/assets/sloth.svg" alt=":sloth:" />
        </p>
        <p>Tamia
          <img src="../.gitbook/assets/chipmunk.svg" alt=":chipmunk:" />
        </p>
        <p>H&#xE9;risson&#x1F994;&#xFE0F;</p>
      </td>
      <td style="text-align:left">
        <p>Ours polaire
          <img src="../.gitbook/assets/polar-bear.svg" alt=":polar_bear:"
          />
        </p>
        <p>Panda &#x1F43C;</p>
        <p>Scorpion &#x1F982;</p>
        <p>Crocodile &#x1F40A;</p>
        <p>&#xC9;l&#xE9;phant &#x1F418;</p>
        <p>Z&#xE8;bre &#x1F993;</p>
        <p>Rhinoc&#xE9;ros &#x1F98F;</p>
        <p>Dromadaire &#x1F42A;</p>
        <p>Chameau &#x1F42B;</p>
        <p>Girafe &#x1F992;</p>
        <p>Kangourou &#x1F998;</p>
        <p>Paon
          <img src="../.gitbook/assets/peacock.svg" alt=":peacock:" />
        </p>
        <p>P&#xE9;rroquet &#x1F99C;</p>
        <p>Loutre
          <img src="../.gitbook/assets/otter.svg" alt=":otter:" />
        </p>
      </td>
      <td style="text-align:left">
        <p>Tigre &#x1F405;</p>
        <p>Lion &#x1F981;</p>
        <p>Aigle</p>
        <p>Dodo
          <img src="../.gitbook/assets/dodo.svg" alt=":dodo:" />
        </p>
        <p>L&#xE9;opard
          <img src="../.gitbook/assets/leopard.svg" alt=":leopard:"
          />
        </p>
        <p>Mammouth
          <img src="../.gitbook/assets/mammoth.svg" alt=":mammoth:" />
        </p>
        <p>Colombe &#x1F54A;</p>
      </td>
      <td style="text-align:left">
        <p>Licorne &#x1F984;</p>
        <p>Dragon &#x1F409;</p>
        <p>T-rex &#x1F996;</p>
        <p>Stitch/Angel
          <img src="../.gitbook/assets/purple-circle.svg" alt=":blue_circle:"
          />
        </p>
      </td>
    </tr>
  </tbody>
</table>

