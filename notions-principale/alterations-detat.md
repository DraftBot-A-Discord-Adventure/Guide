# Altérations d'état

L'altération d'état d'un joueur, définit sa situation actuelle. Certains statuts empêchent le joueur d'effectuer certaines actions dans le jeu.

###  Liste des états 

| Symbole | Nom des différentes altérations | Temps d'attente |
| :--- | :--- | :--- |
| 😃  | Pas d'altération d'état | **Ø** |
| [![Emoji Baby](https://vignette.wikia.nocookie.net/draftbot/images/9/93/Emoji_Baby.png/revision/latest/scale-to-width-down/20?cb=20200301093928&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/9/93/Emoji_Baby.png/revision/latest?cb=20200301093928&path-prefix=fr) | Statut de départ | **Ø** |
| [![Emoji Confounded](https://vignette.wikia.nocookie.net/draftbot/images/0/01/Emoji_Confounded.png/revision/latest/scale-to-width-down/20?cb=20200301093840&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/0/01/Emoji_Confounded.png/revision/latest?cb=20200301093840&path-prefix=fr) | Confus | **40min** |
| 🥶  | Gelé | **1h** |
| 😴  | Endormis | **3h** |
| [![Ivre](https://vignette.wikia.nocookie.net/draftbot/images/4/4c/Ivre.png/revision/latest/scale-to-width-down/20?cb=20200422162728&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/4/4c/Ivre.png/revision/latest?cb=20200422162728&path-prefix=fr) | Ivre | **4h** |
| [![Emoji Head-Bandage](https://vignette.wikia.nocookie.net/draftbot/images/f/f1/Emoji_Head-Bandage.png/revision/latest/scale-to-width-down/20?cb=20200301094204&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/f/f1/Emoji_Head-Bandage.png/revision/latest?cb=20200301094204&path-prefix=fr) | Blessé | **6h** |
| [![Emoji Nauseated-Face](https://vignette.wikia.nocookie.net/draftbot/images/9/94/Emoji_Nauseated-Face.png/revision/latest/scale-to-width-down/20?cb=20200229133419&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/9/94/Emoji_Nauseated-Face.png/revision/latest?cb=20200229133419&path-prefix=fr) | Malade | **6h** |
| [![Emoji Dizzy-Face](https://vignette.wikia.nocookie.net/draftbot/images/0/0d/Emoji_Dizzy-Face.png/revision/latest/scale-to-width-down/20?cb=20200229133925&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/0/0d/Emoji_Dizzy-Face.png/revision/latest?cb=20200229133925&path-prefix=fr) | Gravement blessé | **12h** |
| [![Emoji Lock](https://vignette.wikia.nocookie.net/draftbot/images/4/46/Emoji_Lock.png/revision/latest/scale-to-width-down/20?cb=20200301093817&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/4/46/Emoji_Lock.png/revision/latest?cb=20200301093817&path-prefix=fr) | Enfermé | **24h** |
| [![Emoji Clock2](https://vignette.wikia.nocookie.net/draftbot/images/3/35/Emoji_Clock2.png/revision/latest/scale-to-width-down/20?cb=20200301094015&path-prefix=fr)](https://vignette.wikia.nocookie.net/draftbot/images/3/35/Emoji_Clock2.png/revision/latest?cb=20200301094015&path-prefix=fr) | Occupé | **Variable** |
| 💀  | Mort | **Ø** |

{% hint style="warning" %}
L'altération d'état "Enfermé" est la seule altération d'état à interdire l'accès au magasin
{% endhint %}

{% hint style="danger" %}
L'altération d'état "Mort" bloque la totalité des commandes du bot excepté la commande `!respawn`
{% endhint %}

