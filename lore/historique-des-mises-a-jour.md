# Historique des mises à jour

### V2.0.3 

####  Commandes ajoutées  

badge commande permettant d'avoir des informations sur les badges \(alias badges\)

####  Autres ajouts  

Le bot vendra automatiquement un objet si vous possédez le même dans votre inventaire.

Les potions ne sont plus vendables.

Amélioration du système de logs.

La coupe est ajoutée automatiquement en réaction lors du reset du tw.

Amélioration des items permettant l'avancée du temps.

Quelques petites améliorations de qualité du code.

La commande top est désormais beaucoup plus optimisée et ne permet plus de faire lag le bot. \(valable pour tous les tops\)

Le message affiché lors de la découverte d'un item a été amélioré.

Le code permettant de lier des événements a été écrit pour permettre aux rédacteurs de tester leurs événements. Il n'existe pas encore d’événements liés \(prochaine mise à jour eh eh\)

Il faut désormais être niveau 10 pour utiliser les fonctionnalités liées aux guildes.

La commande guildDaily affiche le nombre de minutes dans le temps avant le prochain daily.  


####  Correction de bugs  

La commande help souffrait de quelques erreurs sur la commande invite et affichait des commandes qui n'existent pas.

Le texte de la commande invite donnait de fausses informations.

Certains événements ne donnaient pas la bonne quantité d'xp.

La revente de potion permettait de dupliquer toutes les ressources du jeu à l'infini \(heureusement, on l'a remarqué avant les jours :p\)

La commande shop pouvait bloquer les joueurs si ils réagissaient avec un émoji autre que ceux du shop.

Plusieurs autres corrections orthographiques

La récompense de guilde était disponible toutes les 21h30 au lieu de 22h

Monter de plusieurs niveau d'un coup en cas de gain d'une grande quantité d'xp à un niveau faible n'était pas géré correctement

### V2.0.2 

####  Commandes ajoutées  

friendlyfight \(alias ff\) - Permet de lancer un combat amical.

sendlogs Permet aux contributeurs d’accéder aux raisons d'un crash

servs Permet à l'owner du bot de lister les serveurs sur lequel le bot est présent.

#### Autres ajouts  

La commande help fonctionne désormais avec les alias des commandes.

Voter pour le bot sur top.gg vous permettra d'obtenir un badge sur votre profil pendant 12 heures.

Les points de combat \(cœurs bleus\) ne sont plus rendus immédiatement après la fin d'un combat.

Amélioration du look de la commande help et ajout des alias dans les informations sur les commandes.

Les évents sont vérifiés au démarrage du bot pour éviter les problèmes affrontés à la sortie de la 2.0.1.

Lorsqu'un nouvel item remplace l'un des items d'un joueur dans son inventaire, l'ancien item est vendu.

Ajout de 5 nouveaux items.

Le bot répond avec des informations utiles lors que vous le mentionnez.

L'attaque rapide fait 10 à 15% de dégats en moins.

Les issues de certains évents ont été équilibrées.

La commande senddata peut être faite par les contributeurs.

Certains items ont été équilibrés \(https://bit.ly/2PzxDc3\)  


####  Correction de bugs  

Corrections de diverses erreurs notamment de typo sur certains évents/commandes.

Le message d'erreur quand le joueur avait une altération d'état n'était pas correct.

Le message d'erreur quand un joueur spécifique rejetais une demande de combat n'était pas correct.

La blacklist des messages privés du bot ne fonctionnait pas.

Certaines issues de certains évents avaient des problèmes

Le calcul de la potion du jour avait une chance de faire planter le bot.

Le message d'erreur du guilddaily n'était pas toujours correct.

Des problèmes avec le calcul du niveau de certaines guildes sont apparus.

La commande drink n'était pas bloquée pendant un shop.

### V2.0.1 

####  Commandes ajoutées  

Ajout des 2 commandes admins délaissées lors de la 2.0.0 : resetBadge servers

####  Autres ajouts  

Remise en place des messages du bot dans la \#💻-console

Ajout de 5 nouveaux évents. \(Merci au RG :heart: \)

Le bot owner bypass toutes les restrictions de permissions.

Ajout du mode maintenance lors des mises à jour du bot. \(bon c'était en 2.0.0 mais on l'utilise pas avant maintenant donc ca compte ok?\)

Les guildes peuvent désormais comporter jusqu'à 6 membres.

Le message de blocage indique l'action qui vous empêche de continuer votre aventure.

lorsqu'un joueur réclame un combat, ses statistiques sont affichées sur sa demande.  


####  Correction de bugs  

Certaines issues de l'évent 29 étaient manquantes.

Les points de combat étaient calculés en fonction des points de vie et non de la vie maximale.

Certains badges ne fonctionnaient pas sur le profile

Bug d'affichage sur le boost de défense en combat

Le GuildDaily pouvait être réinitialisé par des actions qui n'étaient pas censé le réinitialiser.

Le mode tournois ne fonctionnait pas comme voulu.

Les items n'étaient pas obtenus dans certaines conditions.

Le texte du monde maintenance en anglais n'était pas implémenté.

### V2.0.0 

####  Commandes ajoutées  

test Une commande utilisable seulement sur une version en développement destinée à faciliter les tests.

####  Autres ajouts  

Grosse amélioration des performances et de la stabilité.

Passage en version 12 de discord js.

Ajout d'un bouclier mythique.

La commande shop affiche la quantité d'argent possédée par le joueur.

Lorsqu'un joueur obtient un nouvel objet, il a désormais le choix de le conserver ou de le vendre.

La commande prefix accepte maintenant les préfix de plusieurs caractères

La commande guilddaily affiche le temps restant approximatif avant le prochain daily disponible.

De nouveaux alias ont été ajoutés pour certaines commandes.

Les potions sont vendues 30% moins cher dans le shop.

L'apparence de certaines commandes a été améliorée.

Le joueur qui joue en premier lors d'un combat est désormais choisi aléatoirement.

Petit équilibrage des combats \(https://bit.ly/3fbEhR7\).

Amélioration de la structure du bot facilitant grandement la collaboration.  


#### Correction de bugs  

Le soin des altérations d'état de la commande guilddaily soignait les joueurs en bonne santé.

Les guildDaily ne donnait pas les items au bon joueur.

Correction d'un bug d'affichage des potions et des objets d'avancées du temps

Afficher une guild dont l'un des membres n'avait plus aucun serveur en commun avec le bot faisait crash le serveur

Correction de divers problèmes d'affichage de certains textes en anglais.

Correction de fautes d'orthographe.

### V1.5.1 

####  Commandes ajoutées  

Aucune commande n'a été ajoutée pour cette mise à jour

####  Autres ajouts  

Aucun ajout de cette mise à jour n'est permanent. Cette mise à jour est un patch temporaire visant à corriger des bugs ou exploit en attendant la prochaine grosse mise à jour.

Le guild daily ne donne plus d'item random pour les guilds ayant un niveau inférieur à 80, à la place, de l'xp de guild est offerte.

Les joueurs ayant plus de 10 000 points au classement de la semaine ne gagnent plus de points à la fin d'un combat.  


####  Correction de bugs  

Les items ne sont pas donnés correctement lors d'un guilddaily.

### V1.5.0 

#### Commandes ajoutées  

guildcreate &lt;Nom de guilde&gt; - Permet de créer une guilde . Alias de la commande : gcreate

guildleave - Permet de quitter une guilde. Alias de la commande : gleave

guildadd &lt;mention&gt; - Permet d'ajouter un utilisateur à une guilde, nécessite d'être chef de guilde. Alias de la commande : gadd ou ga

guildkick - Permet d'expulser un membre d'une guilde, nécessite d'être chef de guilde. Alias de la commande : gkick

guild \[nom de guilde ou mention\] - Permet d'afficher les informations sur une guilde. Alias de la commande : g

guilddaily Permet de récupérer des récompenses de guildes. Alias de la commande : gdaily ou gd

####  Autres ajouts  

Ajout de 3 nouveaux évents

Mise à jour de la commande help

Il n'est plus possible d'acheter un soin des altérations d'état sans avoir d'altération d'état

Il est possible de choisir son adversaire lorsque l'on utilise la commande fight en le mentionnant \(ex: !f @Drapht\)

Certaines parties du shop ont été améliorée niveau look.

Il est possible d'acheter de l'xp de guilde dans le shop.

Petites améliorations diverses du code du shop.

Le message indiquant un gain d'item mentionne désormais l'utilisateur concerné.

Quelques changements divers ont été effectués sur les \#🏆-badges  \(cf \#📣-annonces \)  


#### Correction de bugs  

Correction d'un soucis visuel sur le shop en anglais.

Le préfix " n'était pas possible.

Correction d'un bug d'affichage sur le message d'erreur anglais du tuto.

Le lien de la commande invite était cassé.

### V1.4.5 

#### Commandes ajoutées  

topserv Permet d'avoir les classement des joueurs présent sur le serveur ou à été fait la commande. Alias :  tops  


#### Autres ajouts  

Les items de rareté :gem: Mythiques se vendent désormais 10 fois plus cher

Ajout de trois nouvelles armes

Ajout de deux nouveaux objets

Mise à jour des informations de la commande help et petites améliorations visuelles

Gros équilibrage des points de défense et d'attaque d'une majorité des armes et armures.

Liste des équilibrage sur les armes : \(https://cdn.discordapp.com/attachments/440879632837902346/691379916716900403/unknown.png\)

La liste n'a pas été faite pour les armures \( désolé 😃 \)

### V1.4.4 

#### Commandes ajoutées  

Aucune commande n'a été ajoutée pour cette mise à jour  


####  Autres ajouts  

L'altération d'état :ghost: est donnée au bout de 7 jours consécutifs d'inactivité au lieu de 24 heures.

L'altération d'état :zzz: Endormis a désormais pour émoji :sleeping:

L'altération d'état :snowflake:  Gelé a désormais pour émoji :cold\_face:

Ajout d'une altération d'état : :zany\_face: Ivre. Durée : 4h

Il n'est plus possible d'utiliser la commande shop en étant :lock: Enfermé

L'altération :head\_bandage: Blessé dure désormais 6H et remplace l'altération :nauseated\_face: Malade dans certains évents

Event de l'arbre. Les :scissors: ont été remplacé par une :axe:

Ajout de 7 nouveaux évents \(Merci à :

@Ninjissou \(idée + rédaction de l'évent "chevalier noir"\) @Jaraxus \(trad\) @Lily \(correction de trad\) @QuenQuentin \| QQ \(idée + rédaction de l'évent "homme blessé en forêt"\) @Quichili \(rédaction de l'évent "festin ferme"\) @Dandi\_FFH \(trad / correction de trad\) @Twomatwo \(god of fight\) \(idée + rédaction de l'évent "cadeau joueur"\) @Val \(trad\) @Ecrom \(idée + rédaction de l'évent "bijoutier"\) @DeadAngelV6 \(qui donne une putain de tonnes d'idées\) -Tous les autres copains qui ont aidé en commentant et corrigeant des évents en rédaction @min'o \(rédaction / correction de quelques-uns des évents + Ajout au bot\)

Petits équilibrage des combats:

Augmentation de l'effet de la stat de défense contre les attaque rapide \(+25%\) et les attaques simples \(+35%\)

Petite clarification de l'affichage du shop

Equilibrage de quelques évents  


#### Correction de bugs  

Correction de quelques fautes d'orthographe

La bourse n'était pas vidée intégralement lorsque l'issue d'un rapport impliquait une perte d'argent.

Le bot répondait parfois en anglais à un évent commencé en Français ou inversement

### V1.4.3 

#### Commandes ajoutées  

Ajout d'une commande admin pour modifier le score de la semaine des joueurs  


####  Autres ajouts  

Augmentation du taux de réussite de l'attaque simple de 10 %

Augmentation du taux de réussite de l'attaque rapide sur un adversaire plus lent de 15%

Augmentation du taux de réussite de l'attaque ultime \(jusqu'à 25% de chance en plus suivant les situations\)

Ajout d'une possibilité de réussite partiel de l'attaque simple sur un adversaire à la vitesse plus élevée

Le nombre de point qu'il est possible de gagner en un seul combat est désormais limité  


#### Correction de bugs  

Correction d'un problème syntaxique sur un évent

### V1.4.2 

####  Commandes ajoutées  

Ajout d'une commande admin \( destroy \) permettant de redémarrer le bot.  


####  Autres ajouts  

Les propriétaires de serveurs ne recevront plus de messages privés de la part du bot lorsque ce dernier rejoint leur serveur.

Le message de reset du top de la semaine s'affichera désormais dans le salon \#📣-annonces

Ajout d'un nouvel évent \(merci à @Chat Anglais Bordeaux Drôle @Max @Ninjissou @QuenQuentin \| QQ @OscarTom54 @min'o @Shalvus \)

Ajout d'une nouvelle altération d'état 🔒 Enfermé

Amélioration de la qualité générale du code \(merci à @Dogeek\)

Ajout d'un nouveau badge \(😂\)

Ajout d'une License

Ajout d'un fichier de config type et amélioration de l'implémentation de ce dernier dans le code

Le shop est désormais un peu plus joli \(Merci @Max \)

### V1.4.1 

#### Commandes ajoutées  

Aucune commande n'a été ajoutée pour cette mise à jour  


#### Autres ajouts  

Le premier rapport est désormais immédiatement disponible après le tutoriel.

Amélioration de l'apparence de la commande profile, de la commande shop et de la commande ìnventory \(Merci à @Max pour son aide\)

Les objets de rareté :gem: unique sont désormais de rareté :gem: mythique et ont désormais 1 chance sur 10 000 d'apparaitre à chaque fois que vous obtenez un item.

Ajout de 18 nouvelles armes, 18 nouvelles défenses, 13 nouveaux items et 3 nouvelles potions.

Plusieurs objets ont été nerfs/buff :

🏵️  Fleur de l'espoir : Boost de la vitesse réduit de 30 points

🍀  Feuille de vent  : Boost de la vitesse réduit de 14 points

💎  Diamant Kéraunique : Boost de l'attaque réduit de 8 points

⚜️  Fleur royale : Boost de la défense augmenté de 9 points

🌑  Bout d'obsidienne : Boost de la défense réduit de 18 points

🎸  Guitare terrifiante : Boost de l'attaque augmenté de 59 points

Amélioration de la formulation de quelques évents  


####  Correction de bugs  

Correction de quelques fautes d'orthographe.

Réagir à un badge sous le profil de quelqu'un n'affichait plus la description du badge.

### V1.4.0 

#### Commandes ajoutées  

topweek Permet de visionner le classement de la semaine. Alias de la commande : tw ou topw  


####  Autres ajouts  

Les combats font désormais 25 tours au lieu de 20.

Le classement s'affiche désormais sous forme d'embed \(merci à @Max \) pour sa participation.

Ajout de l'alias da pour la commande daily.

Ajout de l'alias dr pour la commande drink.

Ajout de 2 nouveaux \#🏆-badges

Ajout du classement de la semaine. Ce classement est remis à 0 chaque semaine et permet, si vous êtes en tête du classement à la fin de la semaine, de remporter un \#🏆-badges exclusif !

Amélioration de la commande permettant aux staffs du bot de donner des badges.

Ajout d'un système de blacklist pour les éventuels spammeurs.

Amélioration du design de l'affichage de la commande profile.

Ajout d'une commande admin permettant de redémarrer le bot en cas de problème.  


#### Correction de bugs  

Correction de quelques fautes d'orthographe.

L'un des émojis d'un rapport était différent de l'émoji en réaction.



### V1.3.2 

#### Commandes ajoutées  

Aucune nouvelle commande  


#### Autres ajouts  

Les boost de vitesse et de défense dans les combats ne sont plus fixes et ont été légèrement buff.

La probabilité qu'une attaque rapide réussisse a été réduite de 5% sur un adversaire plus lent.

La probabilité qu'une attaque simple réussisse a été réduite de 30% sur un adversaire plus lent

Le malus dégâts des attaques sur les adversaires plus rapides ont été retirés

Un malus de taux de réussite a été rajouté sur toutes les attaques:

Malus de 70% pour l'attaque rapide

Malus de 40% pour une attaque simple

La chance qu'une attaque ultime fonctionne est divisée par 5 sur un adversaire plus lent.

Les attaques rapides sont moins affectées par la défense

2 nouveaux \#🏆-badges ont été ajoutés  


####  Correction de bugs  

Certaines attaques pouvaient faire des dégâts à virgule.

Les défenseurs avaient les stats d'attaque des attaquants

Certains items faisaient crash le shop

### V1.3.1 

#### Commandes ajoutées  

Aucune nouvelle commande  


#### Autres ajouts  

l'affichage de la console du bot a été amélioré

l'ergonomie du support en dm a été amélioré pour les staff du bot

Il est désormais possible de voir l'inventaire d'un autre joueur en utilisant la commande inventory suivi d'une mention du joueur ou de son classement. \(merci à @I'm an akyual god \)  


#### Correction de bugs  

Il était impossible de vendre un item

il était impossible de mourir

Il était impossible d'utiliser la commande daily

il était impossible d'utiliser la commande drink

Discord a changé le nom d'un émoji causant des problèmes d'affichage sur pc

Certains textes n'étaient pas affichés correctement

### V1.3.0 

#### Commandes ajoutées  

language Permet aux administrateurs de serveurs de changer la langue utilisée par le bot sur leur serveur.  


#### Autres ajouts  

La commande aide a été mise à jour.

Le bot est désormais disponible intégralement en anglais.

Ajout de 2 nouveaux badges.

L'activité du bot a été mise à jour dans son profil discord  


#### Correction de bugs  

Correction de diverses fautes d'orthographe

### V1.2.5 

#### Commandes ajoutées  

prefix Permet aux administrateurs de serveurs de changer le préfix pour leur serveur ! alias de la commande cp  


#### Autres ajouts  

La commande aide a été mise à jour.

Le système d'aide en dm est désormais en place

L'activité du bot a été mise à jour dans son profil discord  


#### Correction de bugs  

Aucun bug a été découvert depuis la dernière mise à jour

### V1.2.4 

#### Commandes ajoutées  

Une nouvelle commande admin a été ajoutée  


#### Autres ajouts  

Un wiki a été créé par les personnes possédant le rôle @Wiki. Le lien a été ajouté dans la commande help.

La commande help a été mise à jour pour afficher les nouveaux badges

La description des nouveaux badges a été ajoutée sur le profile.

Début d'une fonctionnalité d'aide via DM : Les messages privés du bot sont maintenant affichés pour les staff afin d'aider ceux qui demandent de l'aide en dm \(fonctionnalité de la 1.2.3 qui n'a pas eu le droit à son annonce parce que osef d'une mise à jour aussi petite\)  


#### Correction de bugs  

Correction de quelques fautes de Français.

l'un des évents rapportant de la vie n'en rapportait pas en fait \(ce qui est pas ouf\)

Le message d'erreur sur le nombre de membres minimum a été mis à jour

### V1.2.2 

#### Commandes ajoutées  

Cette mise à jour est une mise à jour de correction de bug. Il n'y a pas de nouvelle commande.  


#### Autres ajouts  

Le prix d'un item random est passé à 350.

correction d'un petit problème visuel sur le message de mort  


#### Correction de bugs  

l'état d'un évent était mal écrit.

Il était impossible d'ouvrir le shop en étant malade.

Certains émojis faisaient planter le shop.

Le défenseur d'un combat n'était pas marqué comme occupé.

Il était possible d'accepter un combat lancé par un autre joueur avec le shop ouvert.

### V1.2.1 

#### Commandes ajoutées 

Pas de nouvelle commande pour cette mise à jour car il s'agit simplement d'un petit correctif pour un bug de la version précédente

#### Autres ajouts 

Pas de nouveautés pour cette mise à jour car il s'agit simplement d'un petit correctif pour un bug de la version précédente  


#### Correction de bugs  

Crash du bot quand un joueur interagis avec le menu de vente d'objet.

### V1.2.0 

#### Commandes ajoutées 

!shop Permet de dépenser votre argent. alias de la commande : !s

Ajout d'une commande admin permettant de retirer des points à un joueur.  


#### Autres ajouts 

Ajout de nouveaux items de rareté UNIQUE 💎 

Il y a désormais 2 fois plus de chance d'obtenir une potion dans les rapports.

La probabilité d'obtenir une arme dans les rapports a été réduite de 25%.

La vente d'item rapporte désormais plus d'argent pour les items de rareté inférieur à Epique ⭐ .

Ajout de 3 badges cf \#🏆-badges pour plus d'informations

Ajout de quelques explications en plus dans la commande help

Correction de quelques fautes de frappe.  


#### Correction de bugs  

Attendre 12 heures après être mort permettait de faire certaines commandes

### V1.1.1 

#### Commandes ajoutées 

Aucune nouvelle commande dans cette mise à jour.  


#### Autres ajouts 

Il est possible de visionner le profile de la personne à la X-ème place du classement en écrivant !p X

Mise à jour du message d'aide pour les badges et ajout d'explications lors de l'appui sur une réaction du profile.

Le top affiche désormais les joueurs inactifs depuis plus de 24 heures et affiche l'état réel des rapports en attente dans toutes les conditions.

Correction de quelques fautes de Français  


#### Correction de bugs  

Les joueurs qui atteignaient le lvl 31 étaient bloqués et ne passaient plus les niveaux

Il était possible de dépasser le niveau 100

Les mentions étaient parfois mal lues par le bot lors de l'affichage d'une tierce personne

### V1.1.0 

#### Commandes ajoutées 

Aucune nouvelle commande dans cette mise à jour.  


#### Autres ajouts 

De nombreux évents ont été rééquilibrés

Possibilité de voir le profil de l'autre en utilisant la commande profile @utilisateur

Les badges ne sont plus affichés dans le top pour un affichage plus sobre

L'affichage des badges sur le profile a été modifié pour apparaitre sous forme de réaction

Ajout de 13 nouveaux évents \(Merci à @Guysmow @min'o  @DeadAngelV6  @Ines @Oscar Ier - Strate @I'm an akyual god   et @Thero1st pour leur participation au sein du "RG" \)

L'aide du profile a été mise à jour

Plusieurs fautes d'orthographes ont été corrigées  


#### Correction de bugs  

Le joueur pouvait se bloquer si le bot avait la permission de lire une commande mais pas d'y répondre

Les potions utilisables en combat n'étaient pas consommées

Le joueur pouvait se bloquer si il ne répondait pas au tutoriel

Les boucliers donnaient des bonus de défense aléatoires au lieu des stats indiquées dans l'inventaire

Il était possible d'utiliser un Daily en étant mort

### V1.0.2 

#### Commandes ajoutées 

Ajout d'une commande admins pour surveiller le bon fonctionnement du bot.  


#### Autres ajouts 

Corrections des fautes de frappe.

Affichage des badges des joueurs sur le top ainsi que d'autres informations

Ajout d'un message indicatif pour le déblocage des combats au levelup  


#### Correction de bugs  

Ne pas répondre à un évent faisait crasher le bot  


#### Correction de bugs  

Correction de quelques fautes d'orthographe.

L'un des émojis d'un rapport était différent de l'émoji en réaction.

### V1.0.1 

#### Commandes ajoutées 

Ajout de commandes admins pour surveiller le bon fonctionnement du bot.  


#### Autres ajouts 

Corrections des fautes de frappe.

Changement de nom de la commande aide pour help dans les textes indicatifs  


#### Correction de bugs  

Un évent donnait trop d'xp sur l'un des choix.

Crash lorsque le bot rejoins un nouveau serveur.

### V1.4.2 

####  Commandes ajoutées  

Ajout d'une commande admin \( destroy \) permettant de redémarrer le bot.  


Les propriétaires de serveurs ne recevront plus de messages privés de la part du bot lorsque ce dernier rejoint leur serveur.

Le message de reset du top de la semaine s'affichera désormais dans le salon \#📣-annonces

Ajout d'un nouvel évent \(merci à @Chat Anglais Bordeaux Drôle @Max @Ninjissou @QuenQuentin \| QQ @OscarTom54 @min'o @Shalvus \)

Ajout d'une nouvelle altération d'état : :lock: Enfermé

Amélioration de la qualité générale du code \(merci à @Dogeek\)

Ajout d'un nouveau badge \(:joy:\)

Ajout d'une License

Ajout d'un fichier de config type et amélioration de l'implémentation de ce dernier dans le code

Le shop est désormais un peu plus joli \(Merci @Max \)  


####  Correction de bugs  

Correction de phrases non consistantes sur la partie anglaise.

Correction de quelques fautes syntaxiques sur la partie anglaise.

Certains objets avaient le même noms mais des effets différents.

Correction de fautes

Le nombre de page du top de la semaine est désormais correct

Suppression du lag du bot en fin de combat

Suppression du gros lag du bot après un rapport

Reduction des blocages de joueurs intempestifs

### V1.0.0 

####  Commandes ajoutées 

!drink Permet de boire la potion que vous transportez  


#### Autres ajouts 

Réécriture complète du bot

Suppression de la commande regen et levelup. Ces deux actions sont désormais automatiques

Certaines commandes ont été renommées : rapport devient report, inventaire deviens inventory et combat devient fight

Ajout d'alias pour certaines commandes : report a pour alias r , fight a pour alias f,  profile a pour alias p  et inventory a pour alias inv

Possibilité pour les @Partner de changer le préfix de leur serveur via le salon \#🗣-server-managers

Le système de combat a été complétement revu

Le système d'xp a été complètement revu

Les pertes de temps sont mieux matérialisées

Beaucoup de textes ont été réécris

Ajout des badges \( \#🏆-badges  pour plus de détails \)

La commande sell vous demande une confirmation avant la vente d'un objet

Il y a désormais plus de 200 objets différents à trouver dans les évents

Ajout de 3 nouveaux évents merci à @min'o @Eagle @DeadAngelV6 et @NoSkillMan

Le chargement du top est désormais instantanée

La commande topguilde a été supprimée

Les easter eggs ont tous été supprimés GG à ceux qui en avaient trouvés  


#### Correction de bugs  

Tous.

### V0.0.9 

#### Commandes ajoutées 

!daily Permet d'utiliser les pouvoirs de certains items.

!invite Permet d'obtenir le lien pour ajouter le bot sur son serveur.  


#### Autres ajouts 

Ajout d'un message d'explication lorsque le bot rejoint un serveur. Le message est envoyé uniquement au propriétaire du serveur et uniquement si ses messages privés sont ouverts.

Ajout de nouveaux éléments dans \#💻-console

Le bot quitte désormais automatiquement les serveurs ayant un % de bot trop élevé dans le but d'éviter les tentatives de triches.

Il y a désormais 15 joueurs par page dans le top

Ajout d'un conseil dans le message de bienvenue pour clarifier un peu les choses au début.

Amélioration de certains passages de la commande !aide

Les commandes !top et !profile préviennent maintenant que les données sont en train de charger

Augmentation des gains à la vente d'un item avec la commande !sell

Lancement d'un petit concours sur les easter eggs avec un item  💎  UNIQUE a gagner ! \(voir \#📣-annonces \)

Les joueurs pour lesquels un rapport est disponible sont indiqués dans le top

Ajout d'une nouvel altération d'état:  mourant \( Vous allez adorer \( ou pas \) \)

Ajout de 2 nouveaux easter eggs

Amélioration de certaines explications sur les évents

Ajout de 2 nouveaux évents merci à @Séqui et à @nwcubeok pour leur suggestions.

Le top affiche désormais les joueurs ayant un rapport en attente

Il faut désormais être niveau 10 pour faire un combat

La commande !levelup a été entièrement revue.

Correction d'un nombre incalculable de fautes d'orthographe

La commande  !regen a beaucoup été améliorée et le compteur des rapports reprend désormais pile poil au bout du temps de soin et non plus au moment de la sortie  


#### Correction de bugs  

Aucun bug connu à corriger.

### V0.0.8 

#### Commandes ajoutées 

!topguild Permet de voir le classement du serveur sur lequel la commande a été exécutée.  


#### Autres ajouts 

Ajout de l'état gelé \(restez au chaud c'est mieux pour vous\)

Réduction du cout du levelup

Amélioration de certains aspect du design de la commande regen

Suppression de quelques mentions inutiles dans la commande regen

En cas de perte de vie l'émojis affiché est un cœur brisé au lieu d'un cœur

Ajout d'une pastille de couleur différentes à coté des pseudo des gens sur le même serveur que vous dans le top

Ajout d'un easter egg \(poke @OscarTom54 \)

Ajout de 2 nouveaux évènements portant leur nombre à 11 \(merci à @Guysmow  pour sa proposition\)

Amélioration du monologue du début pour clarifier le but du jeu !  


#### Correction de bugs 

Aucun bug connu à corriger.

### V0.0.7 

#### Commandes ajoutées 

!levelup Permet de monter en niveau

!combat Permet de lancer un combat contre un autre joueur

!aide Permet d'obtenir de l'aide sur toutes les commandes du bot.  


#### Autres ajouts 

Correction de presque toutes les fautes d'orthographe du bot \(si vous en trouvez d'autres -&gt; \#🆘-bug-typo-report \)

Ajout d'un tuto au début du jeu pour mieux guider les nouveaux joueurs

Ajout de l'état confus ! Comme lorsque vous êtes endormis ou malade il faudra vous rendre à l'hôpital pour vous soigner !

Suppression des indices dans les actions des rapports \(on va pas se mentir c'était juste des points interrogation inutiles\)

Ajout de quelques easter eggs... 👀  \( poke @rysthor \)

Ajout du système de niveau des joueurs

Certains items trouvables dans les évents seront plus puissants pour les joueurs de plus haut niveau.

Ajout de 2 nouveaux évents merci à  @\[NKP\] Makapo  et  @Greninja\_San  pour leur suggestions.

Clarification de certaines explications notamment dans les events.

Ajout du système complet de combat entre 2 joueurs

Changement du tag du bot \(\#0099 c'est mieux\)

Changement du descriptif du bot \(on a compris que j'étais beau\)

RESET COMPLET DE TOUT LES JOUEURS  


#### Correction de bugs  

Aucun bug connu à corriger.

### V0.0.6 

#### Commandes ajoutées 

Aucune nouvelle commande, ceci est une toute petite mise à jour de maintenance, prochaine grosse mise à jour fin juin !  


#### Autres ajouts 

L'hôpital ne régen plus de vie, faites attention à vos action car il n'existe aucun moyen de gagner de la vie pour l'instant \(c'est prévu pour la prochaine mise à jour\)

Correction de quelques fautes majeures \(j'ai pas eu le temps d'en faire beaucoup déso\)

La commande Help est un peu améliorée \(mais le sera encore plus à la prochaine mise à jour

Correction de bugs que personne avait remarqué \(mouahaha\)

Les bananes sont toujours là ne vous inquiétez pas juste il faut savoir les trouver :banana:  


#### Correction de bugs  

Aucun bug connu à corriger.

### V0.0.5 

#### Commandes ajoutées 

!inventaire permet de voir le contenu de son inventaire

!sell permet de vendre l'objet contenu dans votre reserve

!switch permet d'échanger l'objet dans la reserve avec l'objet contenu dans la case "objet" de votre inventaire

!top permet de voir le classement de tout les joueurs

!help Première version de la commande permettant de voir la liste des commandes disponibles  


#### Autres ajouts 

3 Nouveaux évènements ont été rajoutés \(merci à @『 Azn9 » Axel 』  et @Invarion  pour leur propositions\)

Quelques coquilles d'affichages ont été corrigées dans la commande !regen

Il est désormais possible de trouver et ramasser des objets dans les rapports.

\(pour l'instant les objets ne sont pas utilisable et sont donc juste des objets de collection mais plus tard ils auront un intérêt.  


#### Correction de bugs  

Aucun bug connu à corriger.  


### V0.0.4

####  Commandes ajoutées 

!respawn - Permet de recommencer après être mort.  


#### Autres ajouts 

1 Nouvel évènement a été rajouté \(merci à @Greninja\_San  pour sa proposition\)

La notion de mort a été ajoutée si vous tombez à 0pv vous perdrez 10% de vos points !

Un nouvel état a été ajouté : endormi \( 😴 \) allez vous reposer à l'hôpital pour vous réveiller

La commande !regen a été intégralement revue et affiche désormais le temps restant avant guérison.

La durée de guérison a été mise à jour vers sa valeur normale.

Les différents états ne mènent pas forcément à la même durée de guérison.

Le système d'évent a été amélioré de manière à faciliter l'ajout de nouveaux évents

Les commandes !banane et !random ont été supprimées  \(ou peut être pas ? :banana:\)

Il n'est désormais plus possible d'utiliser le bot en message privé. Cette fonction sera refaite dans le futur.

### V0.0.3

#### Commandes ajoutées

`!random` - Permet d'avoir un nombre aléatoire entre 0 et 1  
`!regen` - Permet de soigner les maladies et de récupérer un peu de vie

#### Autres ajouts

1 Nouvel évènement a été rajouté \(merci à Greninja\_San  pour sa proposition\)  
La notion de maladies a été implémentée  
Il est impossible de récupérer un rapport en étant malade ou en train de se faire soigner.  
La commande !profile a été mise à jour pour permettre de savoir si le joueur est malade ou à hôpital  
Le soin dure 50 secondes pour le moment mais cette durée sera allongée à 6 heures dans de futures mises à jour.  


### V0.0.2

#### Commandes ajoutées

`!rapport` - Permet d'avoir un rapport avec les éléments collectés pendant votre absence

#### Autres ajouts

2 Nouveaux évents Merci à la proposition de Super Banane Ninja  pour l'un d'entre eux.  
Les évents apparaissent aléatoirement lors d'un rapport et peuvent être bénéfiques ou maléfiques.  
Plus le temps entre 2 rapports est long plus les ressources collectés sont importantes. cependant au bout de 10 heures plus rien n'est collecté.  
Plus le temps entre 2 rapports est long plus il y a de chances qu'un évent se produise.

### V0.0.1

#### Commandes ajoutées

`!ping` - Tester si le bot est en ligne  
`!banane` - Commande réalisée dans le but d'apprendre quelques base de la programmation de bot  
`!profile` - Afficher les informations principales sur un joueur  
`!reset`  - supprimer un joueur de la base de données  
`!destroy` - Éteindre le bot   
`!purge` - supprimer un certain nombre de messages  
`!reload` - recharger une commande

#### Autres ajouts

Première version du système d'event  
Mise en place de la base de données

