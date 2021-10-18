# Gestion de l'inventaire

L'inventaire est l'endroit où sont placés les différents items ramassés par le joueur dans les rapports ou achetés dans le magasin contre de l'argent.

### Organisation de l'inventaire



![Un exemple d'inventaire d'un joueur](<../.gitbook/assets/image (68).png>)

L'inventaire se décompose en deux parties distinctes, la première est dédiée aux objets équipés par le joueur, la seconde, quant à elle, est une réserve permettant de stocker un objet supplémentaire.

La première partie de l'inventaire est partagée en **4 éléments** :

* `L'emplacement d'arme`
* `L'emplacement d'armure ou de bouclier`
* `L'emplacement de la potion`
* `L'emplacement de l'objet actif`

La seconde partie de l'inventaire sert à **stocker des équipements supplémentaires** que vous pourrez échanger avec vos équipements actifs en fonction de vos besoins.

![Un exemple de réserve d'inventaire](https://media.discordapp.net/attachments/429765574923649025/899778710331334676/unknown.png)

{% hint style="info" %}
La réserve du joueur peut être améliorée dans le magasin.
{% endhint %}

La commande `daily` permet d'utiliser un objet placé dans la case "objet actif".

La commande `sell` permet de vendre n'importe quel équipement situé dans la réserve d'un joueur.

La commande `switch` permet d'échanger les équipements actifs avec les équipements de la réserve.
