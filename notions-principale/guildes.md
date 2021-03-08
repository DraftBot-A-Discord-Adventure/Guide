# Guilds

A guild can consist of up to 6 players, and get daily rewards which will improve with the level of the guild.

### How do you create a guild ?

You can create a guild with the `!guildcreate <guild name` command. 

{% hint style="warning" %}
The name of a guild is unique, and must follow some rules. 

    It must :

* be between 2 to 14 letters long
* contain at least one letter 
* not utilise to 2 spaces coming after one another 
* not have special characters in it 
* not be already taken
{% endhint %}

{% hint style="danger" %}
It is impossible to rename a guild
{% endhint %}

### How do you join a guild ?

Every player above level 10 can join guilds. The guild leader and elder are the only ones who can invite people by using the `!guildadd <@player>` command.

{% hint style="info" %}
A channel for announcing recruitment is available on the bot's official English server.
{% endhint %}

### View the guild's information

The `!guild` command can be used to display information on every guild.

There are two ways of using this command :

* `!guild <guild name>` Let's you see a guild's information using its name.
* `!guild <@user>` Let's you see a guild's information by mentioning a user.

### Levelling the guild

#### In the shop

In the shop, guild experience is represented with a⭐ emoji.   
With 1000 gold you can buy a random amount between 50 and 450 guild experience.

####  Daily rewards

With a cooldown of 22 hours, you can use the `!guilddaily` command to get a reward. Between guild experience, money, hp, and etc. The reward type can change depending of your guilds level.

| Guild Level | Some money | Guild xp | User xp | Status reset | Health points | Full health regeneration | 350 gold | Badge |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 0-10 | 100% | 0% | 0% | 0% | 0% | 0% | 0% | 0% |
| 10-20 | 59.8% | 15% | 5% | 10% | 5% | 0.2% | 5% | 0% |
| 20-30 | 55.7% | 15% | 5% | 10% | 6% | 0.3% | 8% | 0% |
| 30-40 | 52.6% | 15% | 5% | 10% | 6% | 0.4% | 11% | 0% |
| 40-50 | 49.5% | 10% | 10% | 10% | 6% | 0.5% | 14% | 0% |
| 50-60 | 45.4% | 10% | 10% | 10% | 6% | 0.6% | 17% | 1% |
| 60-70 | 41.3% | 10% | 10% | 10% | 6% | 0.7% | 20% | 2% |
| 70-80 | 37.2% | 10% | 10% | 10% | 6% | 0.8% | 23% | 3% |
| 80-90 | 33.1% | 15% | 5% | 10% | 6% | 0.9% | 26% | 4% |
| 90-100 | 20% | 24% | 5% | 10% | 6% | 1% | 29% | 5% |
| 100 | 20.5% | 0% | 20% | 10% | 6% | 1.5% | 32% | 10% |

### How do you set an elder ?

In your guild you can choose an elder with the command `!guildelder<@mentions>`. The elder can add people to your guild and change its description. If you would like to remove your elder use `!guildelderremove`.

### How do you leave a guild ?

You can leave your guild at any moment by using the `!guildleave` command. The owner of the guild can kick users with the `!guildkick` command.

