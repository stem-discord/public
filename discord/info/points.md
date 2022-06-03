# **STEM Point System**

## **What Are Thanks and How Do I Get Them?**|
Thanks are automatically granted "points" that are given to people that help on help channels by the people they help. 

### **How do I get/give thanks?**  
First off, read [How to ask](./discord/info_channels_content/how_to_ask.md)  

After someone helps you, in order to give them thanks, send a message with one of these words in it: "Thank/s", "ty", "Thnx", "Thx", "Tnx", "Tysm", "Tyvm", "Danke"

+ If no one was mentioned in your message, and it wasn't a reply, you will be sent an embed that looks something like:

    **Select who the thank is aimed towards**  
    **1 ❯** `@𝖕𝖊𝖗𝖘𝖊𝖕𝖍𝖔𝖓𝖊 ᗜˬᗜ`    
    **2 ❯** `@Lee`  
    **3 ❯** `@XpioWolf ᓚᘏᗢ`    
    **4 ❯** `@Tim`  

    Under this embed will be 4 reactions: **1**, **2**, **3**, **4**, and <img src="./images/delete_symbol.png" width="15" height="15">. You should react with the number that corresponds to the person who helped you, or <img src="./images/delete_symbol.png" width="15" height="15"> if it was a mistake.

    
+ If someone was tagged in your message, or it was a reply, they will be given the thanks straight away without any embed prompt. Using this method you can thank multiple people at once.

**DO NOT abuse the thank system, as it may result in the revokal of your ability to thank and/or mention helpers.** Abuse includes, but is not limited to: spam thanking, thanking without reason.
  
Notice: Thanks are only granted on the help help channels.

### **How are thank points calculated?**  
Thank points are the sum of your weekly thanks (thanks granted to you since the start of the week) and your alltime thanks (thanks granted to you since you joined the server).  
For example, if you joined this week, and already have helped 10 people, and they all thanked you, your points will be 20 (10 weekly thanks + 10 alltime thanks).  
Weekly thank points are reset at midnight on monday, GMT time.

## **What Are Thank Points For?** 
Thank points help create a educational competitive enviornment which leads helpers to strive to help as many people as they can. 
Top helpers are given color roles, and are displayed seperately from other members.  
The top helper roles are as follows (from [how-it-works](./discord/info_channels_content/how_it_works.md#q-how-are-the-top-helper-roles-distributed)):  

❯ `@Top Helper Infinity (∞)`: Given to the all-time top helper

❯ `@Top Helper Omega (Ω)`: Given to the weekly top helper

The remaining four are given to members with atleast a weekly thank count of:

❯ `@Top Helper Gamma (γ)`: 4% of the weekly top helper count

❯ `@Top Helper Beta (β)`: 20% of the weekly top helper count

❯ `@Top Helper Alpha (α)`: 40% of the weekly top helper count

❯ `@Top helper Sigma (σ)`: 70% of the weekly top helper count

(Members with `@Top Helper Infinity (∞)` and `@Top Helper Omega (Ω)` can change the color of their role with `!hex [hex code]`)

## **What other ranking system is there?**
*Note: still not decided yet*:

❯ Other than the thanks leaderboard, we also have a general ranking system, this can be viewed with the `!id` command

It is calculated like so:

❯ helperBias * helper role <!--- (if bias is 5 and someone has gamma = say 6 then theyd get +30pts) --->
❯ infractionBias * infractions (past three months) <!--- (we can split it into types of infractions) --->
❯ messagesPast3Months * msgBias (msgBias < 1) <!---(this is linear, we can add some more parms to make it harder to get pts through messages the more messages someone has)--->
❯ thanksPast3Months * thanksBias
❯ lbBias - leaderboardPos (lbBias < 15)(not counted if it's smaller than 0)
