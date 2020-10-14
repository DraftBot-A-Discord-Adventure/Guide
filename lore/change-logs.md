# Change logs

### V2.0.3 

####  Commands added 

`!badge` let you get informations about a specific badge

#### Other changes 

The bot will automatically sell items if you already have the same in your inventory

Potions can not be sold anymore

Upgrading log system

The reaction is automatically added on topweek messages.

Upgrading items that makes the time go faster.

Some upgrades in the bots code.

The top command has been optimized, and now makes the bot lag less.

The message when discovering a new item has been modified

The code that links event has been created to let the redactor test their events. Those events still not exists \(next update eh eh\)

You now need to be at least level 10 in order to use any guild functions

The guildDaily command displays the number of minutes remaining before the next guild daily to be available.  


####  Bug fix 

The help command was having some errors in the code, and displayed command that did not exist.

The invite command was returning wrong informations.

Some event were giving the wrong amount of experience.

Reselling potions allowed the player to duplicate any items \(luckily we found it before the players :p\)

The shop command was blocking the players if they reacted with an other emote.

Some orthographical corrections

The guild daily rewards were available every 21h30 instead of 22h

Reaching many levels at once, by earning a very big amount of experience was not managed well.

### V2.0.2 

####   Added commands:

`friendlyfight` \(aka `ff`\) - Lets you start a friendly fight.   
`sendlogs` Allows contributors to access the reasons for a crash   
`servs` Allows the bot owner to list the servers where the bot is present.

####  Other additions: 

The help command now works with command aliases, and has been greatly improved.  
Voting for the bot on top.gg will get you a badge on your profile for 12 hours.  
Battle points \(blue hearts\) are no longer returned immediately after the end of a fight.  
Improved the look of the help command and added aliases to the command information.  
The events are checked when the bot starts up to avoid problems encountered with the release of 2.0.1.  
When a new item replaces one of a player's items in their inventory, the old item is sold.  
Added 5 new items.  
The bot responds with useful information when you mention it.  
The quick attack does 10-15% less damage.  
The exits of some events have been balanced.  
The `senddata` command can be done by contributors.  


####  Bug fixes: 

 Corrections of various errors including typos on some events / controls.  
The error message when the player had a state disorder was not correct.  
The error message when a specific player rejected a request to fight was not correct.  
The bot's private message blacklist was not working.  
Some exits from some events had problems The potion of the day calculation had a chance to crash the bot.  
The `guilddaily` error message was not always correct. Problems with calculating the level of some guilds have appeared The `drink` command was not blocked when shopping.

### V2.0.1 

####   Added commands: 



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

####  Commands added 

Aucune commande n'a été ajoutée pour cette mise à jour

####  Autres ajouts  

Aucun ajout de cette mise à jour n'est permanent. Cette mise à jour est un patch temporaire visant à corriger des bugs ou exploit en attendant la prochaine grosse mise à jour.

Le guild daily ne donne plus d'item random pour les guilds ayant un niveau inférieur à 80, à la place, de l'xp de guild est offerte.

Les joueurs ayant plus de 10 000 points au classement de la semaine ne gagnent plus de points à la fin d'un combat.  


####  Correction de bugs  

Les items ne sont pas donnés correctement lors d'un guilddaily.

### V1.5.0 

#### Comands added 

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

#### Commands added 

`!language` - Lets the server administratos change the bots language locally.  


#### Others changes 

The help command has been updated

The bot is now available in english

Added 2 badges

The bots status in his profile has been added  


#### Bug fix 

Wrong spelling corrections

### V1.2.5 

#### Commands added 

`!prefix` - Let the servers administrator change the bots local prefix  


#### Other changes 

The help command has been updated

The dm help system is now available

L'activité du bot a été mise à jour dans son profil discord  


#### Bug fix 

Any bugs ave been discovered since last update

### V1.2.4 

#### Commands added 

New admin command  


#### Other changes 

A wiki has been created. The link is available on the help page.

The help command has been updated to add the new badges

The new badges description has been made on the profile

Starting a DM support ticket system so that the person can contact staff by sendim dms to the bot \(added in the 1.2.3, but no annoucement has been made juste for that\)  


#### Bug fix 

Corrected some french error

One f the event regenerating life didn't regenerate anything.

The error message related to the low number of members has been edited

### V1.2.2 

#### Commands added 

This update is a bug fix update, no command has been added  


#### Other changes 

The price of a random item has been changed to 350 money.

Fixed a visual problem with the death message  


#### Bug fix 

The state of an event was wrongly written.

It was impossible to open the shop while beeing seek.

Some emotes were making the shop crash.

The figth defender was not marked as busy.

It was possible to accept a figth while having the shop opened

### V1.2.1 

#### Commands added 

No new command for this version, because it is just a bug patch related to the previous update

#### Other changes

No new functions for this version, because it is just a bug patch related to the previous update  


#### Bug fix 

The bot was crashing when a player was interracting with the sell menu.

### V1.2.0 

#### Commands added 

`!shop` to use your money \(alias `!s`\)

Added an admin command to remove points of a player  


#### Other changes 

Added new UNIQUES items 💎 

There is now twice chance to earn a poition in the event

The probability to have a weapon in the reports has been decreased to 25%

Selling items are now giving more money for all the rarety under epic⭐ .

Added 3 badges, see \#🏆-badges for more information

Added some more explanation in the help command

Correcting some wrong spelling  


#### Bug fix 

Waiting 12 hours after dying was allowing the use of some commands.

### V1.1.1 

#### Commands added 

No new commands in that update  


#### Other changes 

It is now possible to see the profile of a person at a certain rank by using the `!p <rank>` command.

Updated the help messags about the badges, and added some explanation when clicking on

The top command now displays the players idle since 24 hours, and show the exact status of the players.

Corrected some spelling.  


#### Bug fix 

The players at the level 31 were not able to level up anymore

It was possible to go beyond the level 100

The mentions were sometimes wrongly readed by the bot.

### V1.1.0 

#### Commands added 

Any new commands in this update  


#### Other changes 

Many event has been renewed

You can now see others profile by mentionning them after `!p`

The badges are not displayed anymore on the leaderboard.

The badges have been edited on the profile, to apear as reactions

Added 13 new event \(Big thanks to @Guysmow @min'o  @DeadAngelV6  @Ines @Oscar Ier - Strate @I'm an akyual god   and @Thero1st for participating in the "RG" \)

The profile help has been edited

Some spellings error has been corrected  


#### Bug fix 

The player could be locked if the bot was able to read the command but not to answer

The potions usable un figths were not used

The player could block himself by not answering to the tutorial

Shields were giving random amount of protection insthead of the number indicated in the profile.

It was possible to use the daily while being dead.

### V1.0.2 

Commands added   


Any commands has been added in this update  


#### Other changes 

Fixed typing errors.

The top command is now displaying the badges of the users and some more informations

Added an information message when getting at level 8 to aware of the figths.  


#### Bug fix 

Not answering to an event was making the bot crash  


#### Others fix

Corrected spelling errors

One of the emotes of a report was different of the one of the action

### V1.0.1 

#### Commandes ajoutées 

Ajout de commandes admins pour surveiller le bon fonctionnement du bot.  


#### Autres ajouts 

Corrections des fautes de frappe.

Changement de nom de la commande aide pour help dans les textes indicatifs  


#### Correction de bugs  

Un évent donnait trop d'xp sur l'un des choix.

Crash lorsque le bot rejoins un nouveau serveur.

####  Commandes ajoutées  

Ajout d'une commande admin \( destroy \) permettant de redémarrer le bot.  


####  Autres ajouts  

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

####  Commands added 

`!drink` can be used to drink the potion you are carrying  


#### Other changed 

Fully rewritten the code of the bot

Removed the levelup and regen commands, those actions are now made automatically.

Some commands have been renamed : rapport become report, combat become figth, inventaire become inventory

Added aliases for some command : `!r` for report, `!f` for figth, `!p` for profile, `!inv` for inventory

It is now possible for the @Partner to change the bot's prefix for their server in the \#🗣-server-managers channel

The figth system has been completely renewed

The xp system has been completely renewed

Time loosing are been improved

Many texts have been rewritten

Added badges \( see \#🏆-badges for more informations\)

The sell command now asks a confirmation before selling the item

There is now over 200 items to find in the events

Added 3 new events, thanks to @min'o @Eagle @DeadAngelV6 & @NoSkillMan

The top command is now loading the informations instantly

The topguild command has been deleted

The easter egss have been removed  


#### Bug fix 

All of them.

### V0.0.9 

#### Commands added 

`!daily` will allow you tu use some items

`!invite` will return a link to invite the bot in your server  


#### Other changes 

Added an information message when adding the bot to your server. This message is only sent to the guild owner, if his dms are opened.

Added some new things in \#💻-console

The bot now automatically leaves the server with a too big amount of bots to avoid cheating

There is now 15 players in each pages on the leaderboard

Added some tips at the message when starting your adevnture

Improved some messages of the `!aide` command.

The `!top` and `!profile` commands are now awaring that the bot is loading the data.

Raised the price of reselling items with `!sell`

Started a small contest with a UNIQUE💎item to win ! \(see \#📣-annonces \)

That players that have an available report are shown on the top

Added a new alteration state :  dying \( You will live it \( or not \) \)

Added 2 new easter eggs

Improved some explanation on some events

Added 2 new events, thanks to @Séqui and @nwcubeok for their suggestion

You now need to be level 10 to figth

The `!levelup` command has been renewed.

Corrected a very big amount of spelling errors

The `!regen` command has been improved and the report counter now take the exact timing.

#### Bug fix 

No bug to fix in this update

### V0.0.8 

#### Commands added 

`!topguild` let you see the top with only the players in the guild in which you executes the command  


#### Other changes 

Added the frozen status \(keep hot, it's better for you\)

Reduced the cost of a level up

Improved the design on the regen command

Removed some useless mentions in the regen command

When loosing life, the emote is a broken heart insthead of a simple heart

Added a blue circle near the players that are on the server in the top command

Added an easter egg \(poke @OscarTom54 \)

Added 2 new events \(thanks to @Guysmow\)

Improved the dialog at the beggining of the adventure  


#### Bug fix

No bug to fix

### V0.0.7 

#### Commands added 

`!levelup` can be used to level up

`!combat` will let you start a figth with other players

`!aide` can be used to find any help about the bot  


#### Other changes 

Corrected almost every spelling errors \(if you see some more -&gt; \#🆘-bug-typo-report \)

Added a tutorial at the beggining of the adventure to help new players

Added the alteration state confused. Like if you were seek or asleep, you will need to get to the hospital to get care.

Deleted the advices

Added some easter eggs👀  \( poke @rysthor \)

Added the players level system

Some items found in the events will be more strong for the high level players

Added 2 new events, thanks to @\[NKP\] Makapo  &  @Greninja\_San  for their suggestions

Clarified some explanation in some events

Added a full figth system beetwin 2 players

Changed the bot's tag \(\#0099 is better\)

Changed the description of the bot.

RESET OF ALL THE PLAYERS PROGRESSION  


#### Bug fix 

Any known bugs to fix

### V0.0.6 

#### Commands added 

No new commands in this update  


#### Other changes 

The hospital doesn't regenerate health, be careful, there aren't any was of getting health back \(it will be added in later updates\)

Corrected some major errors

The help command has been improved \(it will be more in the next update\)

Fixed bugs that no one has seen \(mouahahaha\)

The banas are still there, don't worry, you just need to find them 🍌   


#### Bug fix 

Any know bug to fix

### V0.0.5 

#### Commands added 

`!inventaire` will display the content of your inventory

`!sell` will sell the ietm in your inactive item slot

`!switch` will let you switch the object in the active and inactive items slots

`!top` will display the leaderboard of the players

`!help` will display the available command list  


#### Other changes 

3 new events have been added \(thanks to @『 Azn9 » Axel 』  and @Invarion  for their suggestions\)

some display bugs have been corrected in the `!regen` command

It is now possible to find and get objects in reports

\(for the moments objects are useless, and just to collect, but later they will have a real utility\)  


#### Bug fix 

Any known bug to fix  


### V0.0.4

####  Commands added 

`!respawn` - Let you play again when you are dead  


#### Other changes 

One new event has been added \(thanks to Greninja\_San for suggesting it\)

The death has been added. If your life fells to 0 hp, 10% of your points will be removed !

A new state has been added : asleep \( 😴 \) get some rest at the hospital to restart playing

The `!regen` command has been fully remade, and the time remaining before being able to regen again is now displayed

The caring time has been set to its normal time

Different states does not takes the same time to care.

The event system has been upgraded in order to make it easier to add new event.

The `!banana` and `!random` commands has been deleted

It is no more possible to use the bot in private messages.

### V0.0.3

#### Commands added

`!random` - Permet d'avoir un nombre aléatoire entre 0 et 1  
`!regen` - Permet de soigner les maladies et de récupérer un peu de vie

#### Other changes

1 new event has been added \(thank to Greninja\_San for his suggestion\)  
The seek status has been added  
It is now impossible to have a report while being seek or busy.  
The `!profile` command has been updates to see if the player is seek or at hospital.  
Caring takes 50 seconds for now, but it will be changed to 6 hours in the future  


### V0.0.2

#### Commands added

`!rapport` - Gives you a report with all the ressources collected since last report.

#### Others changes

2 new events, thank to Super Banane Ninja for one of them  
The events are appearing randomly, and can be benefit or not.  
The longest time there is beetwin 2 reports, the most ressources you will collect. You stop collecting after 10 hours.  
The longest the time is beetwin 2 report, the most chances you have to get an event.

### V0.0.1

#### Commands added

`!ping` - See if the bot is online  
`!banane` - Command to let you learn the base of discord bot development  
`!profile` - Display main informations about a player  
`!reset`  - Deletes a player from the database  
`!destroy` - Shuts the bot down  
`!purge` - Delete a certain amount of messages  
`!reload` - Reload a command

#### Other things

First version of the event system  
Starting the database

