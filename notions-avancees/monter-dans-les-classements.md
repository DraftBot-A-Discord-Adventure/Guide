# Rank up

## The `/top score` command

The `/top score` command (not to be confused with `/top glory`) can be used to see the leaderboard of the DraftBot players, by points count. It also displays your ranking, and the page at which you are. The players will be displayed 15 by 15, showing their name, their status, their points count, and their level.

![An example of the /top score command, showcasing the top 15 as of this screenshot's upload](<../.gitbook/assets/Capture d’écran 2023-05-06 à 16.57.52.png>)

### `/top score` options

#### Display a specific page of the leaderboard

It is possible to see a specific page of the leaderboard, by typing `/top score page:<page number>`.

{% hint style="warning" %}
In the example above you don't need to write <>. For example, typing `/top score page:215` will display the users who are ranked between the 3211th and the 3225th place.
{% endhint %}

#### Get a specific timing on the leaderboard

Two periods are available for this command: "All time" (the default option when you don't specify the `duration` option), and "This week". The `duration` option will specify the period on which the leaderboard should be displayed.

For example: `/top score duration:🕥 This week.` will show the leaderboard taking account on the points gathered during the week it was launched.

{% hint style="success" %}
The available values are automatically proposed by Discord, thus there's no possible syntax error as you don't need to write the command entirely by hand!
{% endhint %}

The weekly leaderboard is reset every sunday. The winner of that leaderboard will receive the following badge:

🎗️ `Player that has won a weekly leaderboard`

More informations about badges can be viewed here:

{% embed url="https://guide.draftbot.com/v/en/notions-avancees/badges" %}

#### Set a specific scope to the leaderboard

The leaderboard can be set on two possible scopes: "Global" (by default), and "Server". The `scope` option lets you choose if you want to limit the leaderboard to those who are in your server only or not.

For example: `/top score scope:🚩 Server ranking` will display the leaderboard of the server on which this command was executed.
