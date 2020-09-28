# Gestion de l'inventaire

L'inventaire est l'endroit où sont placés les différents items ramassés par le joueur dans les rapports, ou achetés dans le magasin contre de la money.

### Organisation de l'inventaire 

![l&apos;inventaire d&apos;un joueur qui vient de commencer l&apos;aventure](../.gitbook/assets/image%20%289%29.png)

L'inventaire se décompose en deux parties distinctes, la première est dédiée aux objets équipés par le joueur, la seconde quant à elle est une réserve permettant de stocker un objet supplémentaire.

La première partie de l'inventaire est partagée en **4 éléments** :

* `L'emplacement d'arme`
* `L'emplacement d'armure ou de bouclier`
* `L'emplacement de la potion`
* `L'emplacement de l'objet actif`

La seconde partie de l'inventaire sert à **stocker un objet supplémentaire** que vous pourrez échanger avec votre objet actif en fonction de vos besoins. 

{% hint style="info" %}
Les différents équipements se placent automatiquement dans la case de l'inventaire qui leur correspond.
{% endhint %}

La commande `!daily` permet d'utiliser un objet placé dans la case "objet actif". 

La commande `!switch` permet d'échanger l'objet de réserve avec l'objet actif.

