# Gestion de l'inventaire

L'inventaire est l'endroit où sont placés les différents objets ramassés par le joueur dans les rapports ou achetés dans le magasin contre de l'argent. Pour afficher le contenu de votre inventaire,  saisissez la commande `/inventaire`.

{% hint style="info" %}
Vous avez également la possibilité d'afficher l'inventaire d'un autre joueur. Utilisez les options `utilisateur` ou `classement` de la commande `/inventaire` pour cibler un autre joueur. Par exemple, `/inventaire classement:1337` affichera l'inventaire du joueur classé 1337ème.
{% endhint %}

### Organisation de l'inventaire



![Un exemple d'inventaire d'un joueur](<../.gitbook/assets/image (68).png>)

L'inventaire se décompose en deux parties distinctes, la première est dédiée aux objets équipés par le joueur, la seconde, quant à elle, est une réserve permettant de stocker un objet supplémentaire.

La première partie de l'inventaire est partagée en **4 éléments** :

* L'emplacement d'arme
* L'emplacement d'armure ou de bouclier
* L'emplacement de la potion
* L'emplacement de l'objet actif

La seconde partie de l'inventaire sert à **stocker des équipements supplémentaires** que vous pourrez échanger avec vos équipements actifs en fonction de vos besoins.

![Un exemple de réserve d'inventaire](https://media.discordapp.net/attachments/429765574923649025/899778710331334676/unknown.png)

{% hint style="info" %}
La réserve du joueur peut être améliorée dans le magasin. Différents emplacements supplémentaires sont achetables:

* 1 emplacement pour une arme,
* 1 emplacement pour une armure,
* 3 emplacements pour des potions,
* 3 emplacements pour les objets.
{% endhint %}

{% hint style="warning" %}
Lors de l'achat d'un emplacement supplémentaire, le prix de l'amélioration de la réserve dans le magasin augmente en conséquence.
{% endhint %}

### Interaction avec les objets de l'inventaire

La commande `/bonusjournalier` permet d'utiliser un objet placé dans la case "objet actif". Un objet peut être utilisé toutes les 22h minimum.

La commande `/vendre` permet de vendre n'importe quel équipement situé dans la réserve d'un joueur.

La commande `/intervertir` permet d'échanger les équipements actifs avec les équipements de la réserve.

{% hint style="warning" %}
Intervertir deux objets journaliers augmentera la durée d'attente de 30 minutes par interversion avant de pouvoir utiliser celui placé dans votre inventaire, donc choisissez le bon moment pour l'exécuter et éviter d'avoir à attendre inutilement !
{% endhint %}
