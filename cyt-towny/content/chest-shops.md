# Chest Shops

{% hint style="info" %}
In-Game Command: **N/A** 
{% endhint %}

[//]:# ("/qs *" Wouldn't that be the correct command?)

### **What are Chest Shops?**

**Chest Shops** are the best way to buy and sell large amounts of items on the server, especially when you have a [Player Warp](player-warps.md) for people to visit and use those shops. **These shops support all items on the server**, including custom items here on CYT!

{% hint style="warning" %}
There is a **15%** tax on all shop transactions, a **£10** fee to create a shop, and a **£50** fee to change the price of an existing shop.
{% endhint %}

[//]:# (The £10 fee isnt notified to the player upon creation. Perhaps adding a "Creating this shop will cost £10" After the "Enter how much you with to trade <item-name> for in the chat" That way it isnt a secondary confirmation and instead is just a notifier)

<details>

<summary>Knowing Prices</summary>

Trying to think of what to sell an item for?\
It's difficult, so we made a custom plugin that averages prices out.

**Holding an item**\
If you're wanting to sell an item that you're holding, simply type **/iworth hand** and the plugin will return the average price of it. If it hasn't been sold before, this sadly won't be of any help.

**Want to search? No problem.**\
This plugin also has a search feature! Simply type **/iworth search \<item-name>** This works with custom items, crate keys, basically everything.

**Want to just look at every item ever sold? No problem.**\
Simply type **/iworth all** and there you go!

**How does it work?**\
It takes all sales of all items from both Auction House and Chest Shops and averages it out.

[//]:# 
(**Want to see sales in a specific time period?**\
Not a problem, simply hold the item you want to check and do **/iworth \<amount of item> \<time period>**, for example, **/iworth 1w**!\
You can also shrink down the entire menu to a specific time period. To do so, type **/iworth menu** and fill the sign in with details you need!)

</details>

### **How to make a Chest Shop**

You will need:

* A Chest/Barrel
* One or more of the items you wish to buy/sell

#### Steps:

1. Place a chest where you want your shop to be
2. Crouch and punch the chest with the item you wish to sell/buy
3. Type how much you intend to sell/buy for
4. (_If Selling_) Put at least one of the items you want to sell in the chest
5. (_Optional_) To change from selling to buying (or vice-versa), right-click the shop sign and click the messages to change the settings.



<details>

<summary>Chest Shop Commands</summary>

* **/qs price \[price]** - Set the price of your shop. (Whilst looking at the sign)
* **/qs amount \[amount]** - Set the amount of items to sell/buy. (Whilst looking at the sign)
* **/qs buy|sell** - Change the shop to sell/buy mode. (Whilst looking at the sign)
* **/qs item** - Change the shop to sell/buy the item you are holding. (Whilst looking at the sign)
* **/qs staff add|clear|del|list \[player]** - Shop staff management. (Whilst looking at the sign)
* **/qs find \[item]** - Find a shop selling an item.
* **/qs transfer \[player]** - Transfer all of your shops to a player.
* **/qs toggledisplay** - Disable/Enable item display.

</details>

## Buying/Selling to a Chest Shop

To interact with a chest shop, punch the shop sign and input in chat the amount you would wish to buy/sell of that item.
