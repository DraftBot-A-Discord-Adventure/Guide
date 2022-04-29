# Altérations d'état

L'altération d'état d'un joueur définit sa situation actuelle. Certains statuts empêchent le joueur d'effectuer certaines actions dans le jeu.

### Liste des états

| Symbole           | Nom des différentes altérations | Temps d'attente |
| ----------------- | ------------------------------- | --------------- |
| :smiley:          | Pas d'altération d'état         | **Ø**           |
| :baby:            | Statut de départ                | **Ø**           |
| :scream:          | Effrayé                         | **10min**       |
| :confounded:      | Confus                          | **40min**       |
| :cold\_face:      | Gelé                            | **1h**          |
| :drooling\_face:  | Affamé                          | **1h20**        |
| :sleeping:        | Endormi                         | **3h**          |
| :zany\_face:      | Ivre                            | **4h**          |
| :head\_bandage:   | Blessé                          | **6h**          |
| :nauseated\_face: | Malade                          | **6h**          |
| :dizzy\_face:     | Gravement blessé                | **12h**         |
| :lock:            | Enfermé                         | **24h**         |
| :clock2:          | Occupé                          | **Variable**    |
| :skull:           | Mort                            | **Ø**           |

{% hint style="warning" %}
L'altération d'état "Enfermé" est la seule altération d'état qui empêche le joueur d'accéder aux magasins.
{% endhint %}

{% hint style="danger" %}
L'altération d'état "Mort" bloque la totalité des commandes du bot excepté la commande `!respawn`.
{% endhint %}

### Soin des altérations d'état

Les altérations d'état se soignent d'elles-mêmes avec le temps (à l'exception de l'altération "Mort").

Il est cependant possible de soigner une altération d'état autrement qu'en attendant.

#### Obtention d'un "soin des altérations d'état"

Il est possible d'acheter un soin des altérations d'état dans le magasin en utilisant la commande `!shop`. Cet achat vous coûtera 500 d'argent et annulera votre altération d'état. Lorsque votre altération d'état est annulée, votre personnage est enregistré comme s'il venait juste d'effectuer un rapport.

{% hint style="info" %}
Le soin d'altération d'état est également une récompense de la récompense journalière de guilde à partir d'un certain niveau de guilde.
{% endhint %}

#### Potions et objets permettant de faire avancer le temps plus vite

Certains objets et certaines potions permettent de faire avancer le temps plus rapidement pendant un certain temps, lorsque ces derniers sont utilisés, c'est comme si le temps s'était écoulé, mais seulement pour votre personnage.
