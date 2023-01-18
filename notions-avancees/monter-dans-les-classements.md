# Monter dans les classements

### La commande /classement

La commande `/classement` est une commande qui sert à savoir qui sont les meilleurs joueurs du DraftBot en les classant avec leur nombre de points. Elle affiche également votre classement, et la page à laquelle vous vous trouvez. Vous verrez les joueurs par tranche de 15, avec leur pseudonyme, leur état, leur nombre de points et leur niveau.

![Exemple du résultat de la commande top](<../.gitbook/assets/image (5).png>)

### Les options de la commande /classement

#### Afficher une page du classement en particulier

Il est possible de parcourir le classement en indiquant un numéro de page en tapant la commande comme ceci : `/classement page:<numéro de page>`.

{% hint style="warning" %}
Dans la commande ci-dessus il ne faut pas écrire les <>. Par exemple, la commande `/classement page:215` affichera la 215ème page du classement, présentant ainsi les joueurs classés de la 3211ème à la 3225ème place.
{% endhint %}

#### Le classement selon une durée

Deux périodes sont disponibles pour le classement: "Depuis toujours" (par défaut) ou "Cette semaine". L'option `duree` permet de choisir la période durant laquelle les points sont comptabilisés.

Exemple: `/classement duree:🕥 Cette semaine.` affichera le classement selon les points comptabilisés sur la semaine.

{% hint style="success" %}
`Les valurs possibles pour chaque option sont proposées par Discord dans une liste. Donc aucun risque de se tromper dans la syntaxe car il n'est pas nécessaire de taper cette commande entièrement à la main!`
{% endhint %}

Le classement de la semaine est réinitialisé tous les dimanches. Seul le premier du classement de la semaine reçoit un badge:

🎗️ `Personne ayant dominé un classement de la semaine`.

Plus d'informations sur les badges sont disponible sur la page dédiée.

{% content-ref url="badges.md" %}
[badges.md](badges.md)
{% endcontent-ref %}

#### Le classement selon une portée

Le classement peut être affiché selon deux périmètres: "Classement général" (par défaut; il inclut les joueurs de tous les serveurs Discord) ou "Classement par serveur" (ne prend en compte que les joueurs du serveur où le joueur effectue la commande). L'option `portee` permet de choisir le périmètre sur lequel le classement est construit.

Exemple: `/classement portee:🚩 Classement du serveur` affichera le classement du serveur sur lequel est exécutée la commande.
