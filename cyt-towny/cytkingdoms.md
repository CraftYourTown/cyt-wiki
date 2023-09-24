# 🏠 CYTKingdoms

{% hint style="danger" %}
This is due to be replaced by [Towny ](towny/)on the 27th September - please check our [Discord ](https://discord.gg/cyt)announcements for more information.
{% endhint %}

{% hint style="info" %}
In-Game Command: **/t**
{% endhint %}

### **What is Kingdoms?**

Kingdoms is one of the main features on CYT. With it, you can create or join a town to protect your claims from grief and theft. As a mayor of a town, you have access to tools to manage your town. This includes things like permissions, upgrades, and toggles. Additionally, towns can form a Kingdom, which offer a special chat channel and a 10% upkeep reduction.

### **Essentials for Creating a Town**

* /t create - Creates a new town in the chunk you’re standing in
* /t claim - Allows you to claim additional chunks
* /t deposit/withdraw \<amount> - Deposits or withdraws money from the Town Bank
* /t invite \<name> - Invites the player into the Town\


### Towns

Simply, towns represent a group of players in a group of chunks. To create a town, use **/t new \<name>**. This will claim the chunk you're located in and set your location to the town spawn. You can expand your town by either claiming an outpost or by using **/t claim** in an adjacent chunk. Everything related to your town can be accessed from the **/town** menu.

### Members

Mayors, and members with the appropriate permission are able to invites others to the town using **/t invite \<player>**. This invite expires in 30 seconds, and the invited player may accept it using **/t join \<town>**.&#x20;

To remove a member from the town, mayors, and members with the appropriate permission can use **/t kick \<player>**. This will entirely remove their association with your town, and it will evict them from any plots they own.

To ban a member from the town, mayors, and members with the appropriate permission can use **/t ban \<player> \[reason]**. This will physically remove them from the town, and it will not allow them to enter the town.

To unban a member from your town, mayors, and members with the appropriate permission can use **/t unban \<player>**.

All member management can be done through the town members menu. Here, you're able to see the members and their roles. Additionally, you can also view the banned members. This shows who is banned from your town with the executor, when, and the reason, if one was provided.

There are no limits to the amount of members you can have in your town.

#### Roles

Roles are used to identify and group players. The mayor, and members with the appropriate permission, can assign a role to a member through the members menu. Additionally, permissions are based on the role's priority.

The roles are:

* Mayor
* Co-Mayor
* Senator
* Helper
* Builder
* Member
* Outsider

Mayor and outsider can not be assigned to town members; however, they are used for identifying players in permissible contexts.

### Land

Claims, plots, or any locatable entity in Kingdoms is based on the chunk its in. To keep towns from overcrowding each other, you may not make a claim that is closer than 5 chunks to another town. Also, all claims must make a simple, closed region. The only exception is if there is an outpost, but then, there must again be a simple, closed region containing that outpost. In other words, a claim must be attached to either the town or outpost spawn.&#x20;

To claim or unclaim land, mayors, or members with the appropriate town permission can use respectfully **/t claim** or **/t unclaim**. When unclaiming, if you're attempting to unclaim a chunk that contains an outpost spawn or the town's spawn, you will be prompted with a confirmation. You can either click this confirmation in chat, or use **/t unclaim confirm**. This confirmation expires 30 seconds after creation.

To see if you're in a town. You can use **/t here**. This will show you information about the town you're standing, should there be one. Also, you can use the [livemap](https://map.craftyourtown.com/), or /t map. Additionally, you'll receive an action bar message when walking across town and plot borders.

#### Outposts

### **Outposts**

Town claims must be attached, however, you can detach claims using Outposts. To do so, stand in the chunk you’d like your outpost to be in and type /t claim outpost. Once you’ve claimed the outpost chunk, you may teleport to it using /t outposts.

### **Town Prices**

| Town Actions         | Cost    |
| -------------------- | ------- |
| Creating a Town      | £2,500  |
| Claiming a Plot      | £250    |
| Claiming an Outpost  | £15,000 |
| Town Upkeep per Plot | £10     |

| Nation Actions     | Cost     |
| ------------------ | -------- |
| Creating a Kingdom | £250,000 |
| Kingdom Upkeep     | £4,000   |
| Kingdom Upkeep Cut | 10%      |

### Town Upgrades

Town Upgrades are accessed by typing /t upgrades. There are few upgradable categories in a Town:

#### Claim Upgrades&#x20;

Upgrades the maximum amount of claims for a Town to claim more land.

| Tier | Cost    | Amount |
| ---- | ------- | ------ |
| 1    | £5,000  | 100    |
| 2    | £10,000 | 250    |
| 3    | £30,000 | 500    |
| 4    | £40,000 | 1,000  |
| 5    | £50,000 | 2,500  |
| 6    | £60,000 | 5,000  |
| 7    | £70,000 | 10,000 |

Upgrades amount of Vaults for a Town.

| Tier | Cost    | Amount |
| ---- | ------- | ------ |
| 1    | £2,000  | 2      |
| 2    | £5,000  | 3      |
| 3    | £10,000 | 4      |
| 4    | £15,000 | 5      |
| 5    | £20,000 | 6      |
| 6    | £25,000 | 7      |
| 7    | £30,000 | 8      |

#### Outpost Upgrades

Upgrades the maximum amount of Outposts a Town can have.

| Tier | Cost    | Amount |
| ---- | ------- | ------ |
| 1    | £5,000  | 1      |
| 2    | £10,000 | 2      |
| 3    | £30,000 | 3      |
| 4    | £40,000 | 4      |
| 5    | £50,000 | 5      |

### Managing your Town/Kingdom

Town settings and permissions can be edited and customised via the /t GUI. You can edit permissions for each role in the Town, and you can toggle basic Town Settings such as PvP, Town Spawn Teleport and Mob Spawns. Similarly, Kingdom settings can also be edited via the /k GUI.

### Creating a Kingdom

* /k create - Creates a new Kingdom
* /k deposit/withdraw \<amount> - Deposits or withdraws money from the Kingdom Bank
* /k invite \<TownName> - Invites the Town into the Kingdom
