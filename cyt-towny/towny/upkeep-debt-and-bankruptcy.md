# Upkeep, Debt & Bankruptcy

## Town Upkeep and Taxes

### Town Upkeep

**Town Upkeep** plays a big part in the economy on the server, and is required to keep everything balanced - it gives you a good reason to keep grinding and making money.

<table><thead><tr><th>Town Rank</th><th>Daily Upkeep</th><th width="200">Member Requirement</th><th data-hidden>Upkeep Modifier</th></tr></thead><tbody><tr><td>Default</td><td>£15 per townblock</td><td>N/A</td><td></td></tr><tr><td>Ruins</td><td>£15 per townblock</td><td>0</td><td></td></tr><tr><td>Settlement</td><td>£15 per townblock</td><td>1</td><td></td></tr><tr><td>Hamlet</td><td>£15 per townblock</td><td>5</td><td></td></tr><tr><td>Village</td><td>£15 per townblock</td><td>15</td><td></td></tr><tr><td>Town</td><td>£15 per townblock</td><td>30</td><td></td></tr><tr><td>Large Town</td><td>£15 per townblock</td><td>45</td><td></td></tr><tr><td>City</td><td>£15 per townblock</td><td>60</td><td></td></tr><tr><td>Large City</td><td>£15 per townblock</td><td>75</td><td></td></tr><tr><td>Metropolis</td><td>£15 per townblock</td><td>100</td><td></td></tr></tbody></table>

### Town Taxes

Most towns have taxes to help the mayor pay for their town's upkeep - you can view a town's taxes by using **/t \<town name>** or **/towny prices** in-game. When the money is taken from your balance, it is put directly into the Town Bank.

{% hint style="info" %}
Town Taxes are taken daily at **9pm UTC** from the Town Bank.
{% endhint %}

As the mayor of the town, you can choose how much you want to tax your residents using **/t set taxes \<amount>**, or you can use **/t toggle taxpercent** to set tax to be a percentage of your resident's balance.

{% hint style="warning" %}
Using **percentage tax** may discourage players from joining your town, as players with a high balance may be excessively taxed.
{% endhint %}

### Bankruptcy and Ruined Towns

To prevent your town from going bankrupt, you must have enough money in your Town Bank to pay your town's upkeep each day. If you cannot pay this, your town will enter a **bankrupt state** and the bank will go into the negatives. In this state, you will not be able to make any adjustments to your town until you put enough money in the bank to reach a positive balance again.

Your town's **debt cap** (how far negative the balance can go) is the combined price of all your claimed chunks, outposts and plots - it is limited to a maximum of £100,000.&#x20;

If you hit your debt cap, your town will go into a 'Ruined' state for 72 hours. For the first 24 hours it will not be reclaimable (purely raidable) then for the final 48 hours it will be reclaimable for **£10,000**. Type `/t reclaim` to do so.

If it is not reclaimed within the final 48 hours, the town will be deleted.

## Nation Upkeep and Taxes

Nation Upkeep is much more simple than Town Upkeep. Your nation will pay **£750 per day per town in the nation**. You can set taxes that each town in the nation will pay by doing **/n set taxes \<amount>** - there is no option to do tax percent as a nation.
