# Guilds

A guild can consist up to 6 players, and get daily rewards which will improve with the level of the guild.

### How do you create a guild ?

You can create a guild with the `/guildcreate <guild name>` command. It'll cost 5000 gold to do so.

You can also add a description to your guild by using `/guilddescription <description>`.

{% hint style="warning" %}
The name of a guild must be unique, and must follow some rules.&#x20;

&#x20;   It must :

* Be between 2 to 14 letters long
* Contain at least one letter&#x20;
* Not utilize up to 2 consecutive spaces&#x20;
* Not have special characters in it
* Not be already taken
{% endhint %}

{% hint style="danger" %}
It is impossible to rename a guild. So be sure to give your guild the right name before confirming the command!
{% endhint %}

### How do you join a guild ?

Every player above level 10 can join guilds. The guild leader and elder are the only ones who can invite people by using the `/guildinvite` command, using either the `user` or `rank` parameters.

{% hint style="info" %}
A channel for announcing recruitment is available on the bot's official server.
{% endhint %}

### View the guild's information

The `/guild` command can be used to display information on a chosen guild.

There are three options available when using this command :

* `guild` Lets you see a guild's information using its name.
* `user` Lets you see a guild's information by mentioning a user.
* `rank` Lets you see a guild's information by giving a user's rank.

{% hint style="success" %}
Giving no option to `/guild` will show infos about your guild... if you have one.
{% endhint %}

### Leveling up the guild

#### In the shop

In the shop, guild experience is represented with a :star: emoji. With 1000 gold you can buy it and will receive a random amount between 50 and 450 guild experience.

#### Daily rewards

With a cooldown of 22 hours, you can use the `/guilddailybonus` command to get a reward. Between guild experience, money, hp, and etc. The reward type can change depending of your guild's level.

| Guild Level | Some money | Guild xp | User xp | Status reset | Health points | Full health regeneration | 350 gold | Badge | 5 candies for pets |
| ----------- | ---------- | -------- | ------- | ------------ | ------------- | ------------------------ | -------- | ----- | ------------------ |
| 0-10        | 97%        | 0%       | 0%      | 0%           | 0%            | 0%                       | 0%       | 0%    | 3%                 |
| 10-20       | 59.8%      | 25%      | 5%      | 2%           | 5%            | 0.2%                     | 2.5%     | 0%    | 0.5%               |
| 20-30       | 57%        | 25%      | 5%      | 2%           | 5.2%          | 0.3%                     | 5%       | 0%    | 0.5%               |
| 30-40       | 54.2%      | 25%      | 5%      | 2%           | 5.4%          | 0.4%                     | 7.5%     | 0%    | 0.5%               |
| 40-50       | 46.4%      | 25%      | 10%     | 2%           | 5.6%          | 0.5%                     | 10%      | 0%    | 0.5%               |
| 50-60       | 41.6%      | 25%      | 10%     | 2.5%         | 5.8%          | 0.6%                     | 12.5%    | 1%    | 0.5%               |
| 60-70       | 37.8%      | 25%      | 10%     | 2.5%         | 6%            | 0.7%                     | 15%      | 2%    | 1%                 |
| 70-80       | 33.5%      | 25%      | 10%     | 3%           | 6.2%          | 0.8%                     | 17.5%    | 3%    | 1%                 |
| 80-90       | 24.2%      | 25%      | 15%     | 3.5%         | 6.4%          | 0.9%                     | 20%      | 4%    | 1%                 |
| 90-100      | 19.9%      | 25%      | 15%     | 4%           | 6.6%          | 1%                       | 22.5%    | 5%    | 1%                 |
| 100         | 29.7%      | 0%       | 20%     | 6%           | 6.8%          | 1.5%                     | 25%      | 10%   | 1%                 |

### How do you set an elder ?

In your guild you can choose an elder with the command `/guildelder`. The elder can add people to your guild and change its description. If you would like to remove your elder, use `/guildelderremove`.

### Check the guild's storage

You can check the stored food with the `/guildstorage` command. You can keep up to:

* 25 candies
* 15 salads
* 15 meats
* 5 ultimate soups

{% hint style="info" %}
You can buy some food in the guild's shop (by using `/guildshop`).
{% endhint %}

### How do you leave a guild ?

You can leave your guild at any moment by using the `/guildleave` command. The owner of the guild can kick users with the `/guildkick` command.
