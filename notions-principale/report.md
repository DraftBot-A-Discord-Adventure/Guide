# Reports

The report is the main function of the game. It can be used to get the last informations about your player, since the last interaction. You can ask for a report by executing the `/report` command.

### Interface :

The report command has 4 differents states :

* The player is travelling.
* The player has a [state alteration](alterations-detat.md).
* The player is doing an event.
* The player is doing a mini event.

<figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption><p>Command interface when the player is travelling</p></figcaption></figure>

### Mini events :&#x20;

The player takes circa 9 minutes and 45 seconds to travel between 2 mini events.

<figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption><p>A mini event example</p></figcaption></figure>

A mini event is mostly a short sentence. However, some can give you items, health or even money.

{% hint style="info" %}
Each mini event gives the player a quantity of points which decreases at each mini event. These points are added to the total number of points earned at the next event.
{% endhint %}

<figure><img src="../.gitbook/assets/image (59).png" alt=""><figcaption><p>Once the mini event finished, it appears on the tavelling interface</p></figcaption></figure>

You can see the number of points earned with the mini events and the waiting time before the next one.

### Events :&#x20;

The events are the core of the game, the player just needs to react to a multiple-choice situation with the Discord reactions. Acoording to his choice, different endings can occur.

<figure><img src="../.gitbook/assets/image (52).png" alt=""><figcaption><p>An event example</p></figcaption></figure>

In this example above, the player has 3 different choices : the 2 reaction choices and also the possibility to add no reaction to it.

{% hint style="info" %}
The non-choice "do nothing" happens automatically 2 minutes after no explicit choices were given. You can force this non-choice by manually adding the :end:(:end:) reaction to the event's text.
{% endhint %}

{% hint style="success" %}
In some events, doing nothing is the best choice ! (In others, it's the worst)
{% endhint %}

Once the player has set their mind on what to choose, he can press a reaction (or wait 2 minutes), which triggers the issue.

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption><p>An issue example</p></figcaption></figure>

### Destination :&#x20;

After an event, the player is led to choose a destination. It is not possible for a player to go back on their steps (unless it is the only possible choice).

<figure><img src="../.gitbook/assets/image (55).png" alt=""><figcaption><p>Example of a destination choice</p></figcaption></figure>

The time indicated in parenthesis is the travel time to reach the location, a question mark means that the time is unknown. In one-third of cases, the bot automatically chooses the player's destination.

<figure><img src="../.gitbook/assets/image (61).png" alt=""><figcaption><p>Here is your information about your destination.</p></figcaption></figure>
