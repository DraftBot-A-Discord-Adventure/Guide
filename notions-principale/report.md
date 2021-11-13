# Reports

The report is the main function of the game. It can be used to get the last information's about your player, since the last interaction. You can ask a report by executing the `!report` (or `!r`) command.

### How does it work

The player receives around 1 point every minute, and 1 money every 6 minutes. The report command has a 1h cooldown.

There is **2 types** of reports :

* **Simple reports**. Always positive, they don't need the user to make any choice, and won't give any state alteration, neither than items, and life.
* The **events**, are mostly likes because of the interactivity. They have more chance to happened when the time since last report is big.

{% hint style="warning" %}
After 16 hours and 40 minutes of inactivity, the player stops collecting points and money.
{% endhint %}

The probability of having simple report depends of the time since last report. The more a user wait, the more chance he has to get an event with a choice.

Before 6h40 the probability can be calculated like that :

$$
Probability = x /400
$$

Considering that x equals to the number of minute(s) since the last report.

{% hint style="danger" %}
The cooldown of a state alteration is not counted.
{% endhint %}
