# Altérations d'état

L'altération d'état d'un joueur, définit sa situation actuelle. Certains statuts empêchent le joueur d'effectuer certaines actions dans le jeu.

###  Liste des états 

| Symbole | Nom des différentes altérations | Temps d'attente |
| :--- | :--- | :--- |
|  ![:smiley:](https://discord.com/assets/66f6c781fe86c346fbaf3390618668fc.svg)  | Pas d'altération d'état | **Ø** |
|  ![:baby:](https://discord.com/assets/7d4ab5c9735709184c38ef242f689647.svg)  | Statut de départ | **Ø** |
|  ![:confounded:](https://discord.com/assets/1153efa69996f049aa121cb76dd29ac1.svg)  | Confus | **40min** |
|  ![:cold\_face:](https://discord.com/assets/10ba107674fdf2d100be5592e7c85c74.svg)  | Gelé | **1h** |
|  🤤 | Affamé | **1h20** |
|  ![:sleeping:](https://discord.com/assets/711ac22a92d00f844023ded91f820e8c.svg)  | Endormis | **3h** |
|  ![:zany\_face:](https://discord.com/assets/aee3a8d989cabcd262db85fe0ce7cd0d.svg)  | Ivre | **4h** |
|  ![:head\_bandage:](https://discord.com/assets/267b527f1be941e367bce73444c96f3b.svg)  | Blessé | **6h** |
|  ![:nauseated\_face:](https://discord.com/assets/8212db2111debc4acc49ceb20cbfbdf0.svg)  | Malade | **6h** |
|  ![:dizzy\_face:](https://discord.com/assets/08cf46d4be10cd96a7f69a8b372d1425.svg)  | Gravement blessé | **12h** |
|  ![:lock:](https://discord.com/assets/c35b8b5c0666ad99ab0e820f8aa90002.svg)  | Enfermé | **24h** |
|  ![:clock2:](https://discord.com/assets/b1ee2010d5c89c554af9cac9684c31ce.svg)  | Occupé | **Variable** |
|  ![:skull:](https://discord.com/assets/f64f47a895e537305b3463f9d30bc177.svg) | Mort | **Ø** |

{% hint style="warning" %}
L'altération d'état "Enfermé" est la seule altération d'état qui empêche le joueur d'accéder aux magasins
{% endhint %}

{% hint style="danger" %}
L'altération d'état "Mort" bloque la totalité des commandes du bot excepté la commande `!respawn`
{% endhint %}

### Soin des altérations d'état

Les altérations d'état se soignent d'elles même avec le temps \(à l'exception de l'altération "Mort"\).

Il est cependant possible de soigner une altération d'état autrement qu'en attendant.

#### Obtention d'un "soin des altération d'état"

Il est possible d'acheter un soin des altérations d'état dans le magasin en utilisant la commande `!shop`. Cet achat vous coutera 500 d'argent et annulera votre altération d'état. Lorsque votre altération d'état est annulé, votre personnage est enregistré comme si il venait juste d'effectuer un rapport.

{% hint style="info" %}
Le soin d'altération d'état est également une récompense de la récompense journalière de guilde à partir d'un certain niveau de guilde
{% endhint %}

#### Potions et objets permettant de faire avancer le temps plus vite

Certains objets et certaines potions permettent de faire avancer le temps plus rapidement pendant un certain temps, lorsque ces derniers sont utilisés, c'est comme si le temps s'était écoulé mais seulement pour votre personnage.

