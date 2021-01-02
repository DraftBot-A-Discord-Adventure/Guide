# Familiers

Depuis la version [2.1.2](https://history.draftbot.com/draftbot-v2/2.1.2) de DraftBot vous pouvez avoir un ou plusieurs **familiers**. Ils s'obtiennent dans les récompenses de [guilde ](guildes.md)en fonction du niveau de votre guilde.

{% hint style="info" %}
Pour le moment les familiers sont purement esthétiques. Ils n'ont pas de fonction à proprement parler, mais cela est amené à changer dans une future mise à jour.
{% endhint %}

Pour avoir les informations sur votre familier vous devez utiliser la commande `!mypet` 

Il y a 5 niveaux de **rareté** de familiers, ceux-ci sont représentés par des étoiles ![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg)![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg)![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg)![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg)![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg)

Les familiers ont un **moral**, si vous le nourrissez à intervalle régulier son moral augmentera. A contrario si vous délaissez votre familier son moral diminuera.

### Comment obtenir un familier ?

Les familiers s'obtiennent dans les récompenses de guildes `!guilddaily` avec 10% de chance.

La probabilité d'avoir des raretés supérieures augmente avec le niveau de votre guilde.

| Niveau guilde/rareté familier | 1![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) | 2![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) | 3![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) | 4![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) | 5![:star:](https://discord.com/assets/141d49436743034a59dec6bd5618675d.svg) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 0.9% | 0.09% | 0.009% | 0.0009% | 0.0001% |
| 10 | 0.894% | 0.0916% | 0.01091% | 0.0023% | 0.00119% |
| 20 | 0.876% | 0.0964% | 0.01664% | 0.0065% | 0.00446% |
| 30 | 0.846% | 0.1044% | 0.02619% | 0.0135% | 0.00991% |
| 40 | 0.804% | 0.1156% | 0.03956% | 0.0233% | 0.01754% |
| 50 | 0.75% | 0.13% | 0.05675% | 0.0359% | 0.02735% |
| 60 | 0.684% | 0.1476% | 0.07776% | 0.0513% | 0.03934% |
| 70 | 0.606% | 0.1684% | 0.10259% | 0.069499% | 0.053511% |
| 80 | 0.516% | 0.1924% | 0.13124% | 0.090499% | 0.069861% |
| 90 | 0.414% | 0.2196% | 1.16371% | 0.114299% | 0.088391% |
| 100 | 0.3% | 0.25% | 0.2% | 0.140899% | 0.109101% |

Vous pouvez libérer votre familier avec la commande `!petfree` 

{% hint style="danger" %}
`Attention cette action est irréversible, si vous libérez un familier c'est définitif`
{% endhint %}

### Comment nourrir mon familier ?

#### Acheter de la nourriture.

L'achat de nourriture pour les familiers se fait dans le magasin de votre guilde. Si vous n'avez pas de guilde, vous n'aurez accès qu'a la forme la plus basique de nourriture pour votre animal.

![Le magasin de guilde permet d&apos;acheter diff&#xE9;rentes sortes de nourritures](../.gitbook/assets/image%20%2818%29.png)

La nourriture va permettre d'influer sur le moral de votre animal, pour nourrir votre familier vous devez utiliser la commande `!feedpet` ou son alias `!fp`

![La commande feedpet](../.gitbook/assets/image%20%2819%29.png)

Chaque type de nourriture fera gagner une quantité différente de points d'affection à votre familier. 

* Les friandises feront gagner 1 point d'affection
* Les steaks et salade feront gagner 3 points d'affections
* Les soupes ultimes feront gagner 5 points d'affections

Cependant, le type de nourriture n'a pas d'influence sur la durée pendant laquelle votre familier n'a pas faim

{% hint style="info" %}
La durée pendant laquelle un familier n'a pas faim dépend uniquement de la rareté du pet. Le nombre d'étoiles de rareté est égal au nombre d'heures qu'il faut attendre entre deux repas.
{% endhint %}

Certains familiers suivent un régime particulier \(herbivores ou carnivores\) et ne pourront donc pas profiter de certaines sources de nourritures. Ne donnez pas de salade à votre T-rex !

Ne négligez pas votre familier ! Son moral baissera si vous oubliez de vous en occuper. 

{% hint style="warning" %}
Le moral d'un familier baisse de deux points par jour en moyenne, cette baisse ne tient pas compte de la rareté du pet.
{% endhint %}

Il existe pour le moment 5 niveaux de moral qui correspondent à la mentalité de votre familier, ils sont classés de cette manière :

1.  ![:smirk\_cat:](https://discord.com/assets/e25128510c26b0aad9d71bc6cf49df67.svg) Fielleux
2.  ![:pouting\_cat:](https://discord.com/assets/551f9d76028c39299e0bc9bc20cd0e0d.svg) Sauvage
3.  ![:scream\_cat:](https://discord.com/assets/3068417ae7f1a7c5c2ba60ab1aa1fb62.svg) Craintif
4.  ![:smiley\_cat:](https://discord.com/assets/ef2af7fab48463e72a3a7f0f8fb4fb4e.svg) Apprivoisé
5.  ![:heart\_eyes\_cat:](https://discord.com/assets/d4d91a5f31668dd4609a3d7522f722c5.svg) Dressé

{% hint style="info" %}
Les animaux dressés ne perdent plus de moral et n'ont donc pas besoin d'être nourris pour être aimé. \(mais vous pouvez le faire quand même\)
{% endhint %}

{% hint style="danger" %}
Échanger ou vendre un familier avec un autre joueur réinitialisera son moral à ![:pouting\_cat:](https://discord.com/assets/551f9d76028c39299e0bc9bc20cd0e0d.svg) Sauvage

Changer de propriétaire c'est dur à supporter pour un animal !
{% endhint %}

### Comment stocker mon familier ?

Vous avez la possibilité de stocker votre familier dans le **refuge de votre guilde**. Ou alors de le récupérer avec vous. Pour cela vous devez effectuer la commande `!pettransfer <id du familier>` exemple :`!pettransfer 1` permet de récupérer le familier n°1 du refuge.

Pour visualiser le refuge, vous pouvez utiliser la commande `!shelter`

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

Si vous souhaitez vous débarrasser d'un familier mais que vous n'avez pas le cœur de le libérer, \(ou alors que vous aimez l'argent\), il est possible d'échanger le familier que vous transportez contre un peu d’expérience pour votre guilde. Pour cela, vous pouvez utiliser la commande `!petsell [prix]`

![Ici le familier &quot;Elle&quot; est vendu](../.gitbook/assets/image%20%2817%29.png)

Il y a des conditions importantes à respecter pour la vente de familier:

* Il n'est pas possible de vendre un pet à un membre de sa guilde.
* Il est nécessaire d'appartenir à une guilde pour vendre un pet mais pas pour l'acheter

{% hint style="warning" %}
Le vendeur ne gagnera pas d'argent lors de la transaction, mais de l'expérience de guilde.
{% endhint %}

