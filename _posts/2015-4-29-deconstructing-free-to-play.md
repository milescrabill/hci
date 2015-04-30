---
layout: post
title:  "Deconstructing Free-to-Play"
date:   2015-04-29 15:06:35
---

>Let me tell you what free to play represents to me: an opportunity to bring entertainment to billions of people without relying on advertising revenue or government subsidies. An opportunity to embrace players who want to play our games but can't (or won't) pay, instead of forcing them to become pirates.
>
>For the first time in the history of mass media, we can entertain huge audiences without first bombarding them with advertisements for sugar water and corn flakes and without making them pirates. How is it that some people don't see the beauty of this?
>
><cite>--_David Edery, "The Magic of Free-to-Play" (2012)_</cite>
{: .edery }

As the end user, Free-to-Play sounds too good to be true. Instead of paying for a game, you can just play it. After all, when the only cost to you is your time, what's the harm?

##**The Free-to-Play or Freemium Business Model**

###The Concept

- No fee for entry and basic gameplay
- Ingame content is sold for a fee

###The Advantages

- Increased userbase, creating a positive network effect
- Users can decide whether or not to pay for the experience
- Users can decide how much to pay, if the game offers varying items and price points
- Paid goods are inherently valuable as non-paying users lack them
- The game itself is a service able to be iteratively modified

###Don't know any Free-to-Play games?
Here are some examples:

- League of Legends
- Dota2
- Team Fortress 2
- Clash of Clans
- Hearthstone
- Heroes of the Storm
- FarmVille

##**Explaining Customer Behavior in Relation to Free-to-Play**

Central to the experience of any video game is the immersion of the player in the virtual world. The term "magic circle" refers the player's suspension of disbelief and immersion in a virtual world. The circle represents the cohesiveness of the experience, a shield that protects the virtual or fantasy world from the real world. Free-to-Play games have been criticized for breaking the magic circle with invitations to pay for ingame content.

![The Magic Circle]({{ site.baseurl }}/assets/magic_circle.jpg)

From an HCI perspective, the breaking of the magic circle constitutes a poor user experience. The user wants to be immersed in the virtual world, but the nature of the payment process disrupts their immersion. Solutions that researchers have provided include integrated ingame stores that fit the game experience, a slow ramp up to the payment invitation so that users are better immersed before they are asked to pay, and targeted payment requests that are focused on specific user segments.

>There are no concepts that can empirically explain the customer behavior in free to play games.
>
><cite>--_Hanner & Zarnekow (2015)_</cite>

Here are some of the findings from Hanner & Zarnekow (2015), who analyzed three different free to play mobile games, each published by a different publisher. Each game sells a premium currency that can be used to purchase virtual items.

- users who started purchasing showed an increased retention rate for following purchases
- the average value spent per purchase increases with the number of repeat purchases

Some of the ideas discussed by Hanner & Zarnekow (2015) that are supported by Hamari & Lehdonvirta (2010) are particularly relevant to HCI:

- monetizing users too soon risks pressuring the user before they are immersed in the virtual world
- a dynamic presentation of virtual items depending on the stage of a user (stratification) could improve monetization.

The HCI concepts here are loosely veiled: users want to be a part of the virtual world, and a request for payment derails their immersion. Even more directly, the way that virtual item offers are presented likely affects user spending - so a better purchasing interface will result in more money!

##Towards a Model of Customer Behavior

Hamari (2015) surveyed players from several free-to-play games: social virtual world games, first-person shooters, and social network games. Data was collected in collaboration with [Sulake Corporation](http://www.sulake.com), the creators of _Habbo_. Hamari proposes a path model for understanding why people buy virtual goods.

###The path model described in _Hamari (2015)_
![Hamari's Path Model]({{ site.baseurl }}/assets/path_model.jpg)

Hamari's model is quite general, however it provides a framework for thinking about user's motivations in purchasing virtual goods. Here are the results of analyzing the three different game type data with this model:

- Perceived enjoyment was positively associated with continuous use intentions
- Subjective norm was positively associated with attitude, and purchase intentions directly
- Attitude was positively associated with purchase intentions

Two interesting take-aways from Hamari (2015):

- enjoyment of the game _reduces_ the willingness to buy virtual goods 
- attitude towards purchasing virtual goods and beliefs about peers' attitudes towards purchasing virtual goods strongly affect willingness to purchase virtual goods

>Beliefs regarding the opinions of others toward purchasable virtual goods were also found to be a strong predictor, not only for purchase intentions but also for the player’s own attitude toward virtual goods. This relationship was strongest in “social games”, which heavily rely on social interaction and thus might afford more exposure to the behaviors and opinions of others. Expectedly, the effect was also stronger for those having more friends in the game.
>
><cite>--_Hamari (2015)_</cite>

In these free-to-play games with social elements, it is clear that the way purchasing virtual goods is perceived by your friends affects your purchasing decisions.

##The Effects of Real Money Transfer in Games

Lehdonvirta (2005) identifies ten different user perceptions on real money transfer through a case study of _Ultima Online_, _EverQuest_, _Habbo Hotel_, and _Project Entropia_, four different MMOs. It is important to note that these games fall into different revenue model categories. _Ultima Online_ and _EverQuest_ both required subscriptions, whereas _Habbo Hotel_ and _Project Entropia_ are free-to-play games.

The major difference between subscription and free-to-play games is fairness. In subscription games, excepting transactions outside of the game world that affect the game, all players are equal. In free-to-play games, there is a clear divide between those who pay nothing and those who buy virtual items (Lin & Sun, 2007).

**Ten different user perceptions on RMT** <cite>--_Lehdonvirta (2005), reproduced_</cite>

| Achievement | Social | Immersion |
|-------------|--------|-----------|
|**Advancement**: if RMT enables purchase of rewards, it violates the achievement hierarchy|**Socializing**: RMT allows players to express themselves through their buying behavior|**Discovery**: breaks the magic circle, but gives more choice over content|
|**Mechanics**: RMT makes it easier to obtain different asset configurations to examine|**Relationship**: RMT allows those with less time to catch up and play together with their friends|**Role-Playing**: RMT allows players to obtain the props that are needed for their chosen fantasy|
|**Competition**: RMT is cheating if it can be used to obtain competitive advantages|**Teamwork**: RMT provides objectives for teamwork and motivation for effective organization|**Customization**: RMT makes it easier to obtain a set of assets that correspond to the player's taste|
|             |        |**Escapism**: RMT breaks the magic circle by introducing real-life worries into the virtual world|

Almost all of these are negative effects that can occur when users feel a free-to-play game includes paid features that allow users to "pay to win." Pay to win has an overwhelming negative connotation in free-to-play games, because the few players who do pay become unstoppable, ruining the fun for free to play players.

##**Social Games**

The term "social games" refers to the distribution channel these games utilize. Social games are played over social network services, adapting friendships for gameplay and social network use. Facebook kickstarted the social games industry in 2007 by opening third-party developer tools on its site through the Facebook Developer Platform. (Paavilainen, Hamari, Stenros, Kinnunen 2013)

###FarmVille 2
![FarmVille ingame Store]({{ site.baseurl }}/assets/farmville.png)

> Social interaction is further encouraged by reciprocal actions such as sending and receiving gifts.
>
> Game mechanics are tied into the players’ social network, thus fostering collaboration and competition in the social network.
>
> <cite>--_Paavilainen et al. (2013)_</cite>

Paavilainen et al. (2013) argue that social games are in essence casual games. They typically adhere to the four design values of casual games, namely _acceptability, accessibility, simplicity, and flexibility_ described by Kultima (2009). As an example, Zynga's FarmVille (2009) is an inoffensive, accessible browser game that is simple to understand and play. Social games provide a platform for social interaction in the context of a game that supports sporadic play.

Social games are the perfect platform for free-to-play. Users come in with an established community, the friends in their social network. As a result, the game gains the ability to interact with this community - Facebook games in particular allow users to refer friends for bonuses, challenge friends for points, and more. Creating a large userbase of friends improves the immersiveness of the game, which in turn has been shown to increase the likelihood that users purchase virtual items.

##**Virtual Items**

###Hearthstone: Heroes of Warcraft ingame store (click for more!)
<a href="{{ site.baseurl }}/stores/">![Hearthstone ingame Store]({{ site.baseurl }}/assets/hs_store.jpg)</a>

The exchange of real money for virtual goods first occurred in 1999 in the games _Ultima Online_ and _EverQuest_, when players sold items to one another on eBay. The games had trading features built-in that allowed players to emulate a free market economy. The evolution of the virtual goods market has since been shifted from _player to player_ transactions to _operator to player_ transactions (Hamari & Lehdonvirta, 2010). This shift has supported a change in revenue model from fixed price subscription fees to free to play with paid content.

A study of the pricing models of MMO games in Japan conducted in 2005-2006 shows a dramatic shift from the monthly fixed fee subscription model to per-item virtual goods billing (Nojima, 2007).

**Pricing models of MMO/MO in Japan by number of titles** <cite>--_Nojima (2007), reproduced_</cite>

| Pricing Models | Sep. 2005 | Oct. 2006 |
|:--------|:-------:|--------:|
| Monthly fixed fee   | 30 (50.8%)   | 20 (22.5)   |
| Per-item billing   | 19 (32.2%)   | 53 (59.6)   |
| Complex   | 10 (17.0%)   | 16 (17.9%)   |

Further research by Nojima shows that players who buy virtual items are more immersed in the games, a logical conclusion that has been supported by Hamari (2015) and Hamari & Lehdonvirta (2010). 

##**The Value of Virtual Goods**

**Return on Investment of Virtual Goods Purchases** <cite>adapted from _Park & Lee, (2011)_</cite> 

| Enjoyment value                         | Character competency value | Visual authority value      | Social value       | Monetary value |
|-----------------------------------------|----------------------------|-----------------------------|--------------------|----------------|
| Fun                                     | Be stronger                | Showing off                 | Not be disregarded | Investment     |
| Perceived enjoyment                     | Functional Props           | Decorative props            | Social Items       |                |
| Playfulness value (escapism, enjoyment) | Functional Item            | Vanity item                 | Social attributes  |                |
|                                         | Character competency       | Hedonic attributes          | Social value       |                |
|                                         | Functional attributes      | Visual/musical appeal value |                    |                |

###The results of Park & Lee's study of the value of purchasing virtual items (2011)

![Park & Lee's results]({{ site.baseurl }}/assets/purchase_value.jpg)

The study had several conclusions:

- when game users identify with their avatar the value they associate with virtual items increases
- as users perceive greater values of game items they are more inclined to purchase them
- users satisfied with the game do not have intentions of purchasing ingame items (similar to other research results)

##**Game Mechanics That Sell Virtual Goods**

Selling virtual goods requires a value proposition. 
The primary value proposition that game developers use to sell virtual goods is stratification. 

###Stratification

Content is stratified by player level, by payment, and more. An example of stratified content in MMOs is the leveling up proess of the player's avatar. Vertically segmenting players allows items to be targeted according to stratification (Hamari & Lehdonvirta, 2010).

When you level up in World of Warcraft, you're opening access to new content, new items, new abilities, and more. 

###Status Restrictions

Content is restricted to those who fulfill certain criteria, therefore enforcing differentiation. In a social game, this could take the effect of logging in repeatedly to maintain the status of something already earned, such as a farm in FarmVille.

>The operator forces players to obtain new items iteratively if they wish to maintain the same relative performance or status.
>
>This mechanism could be compared to regulations in karate belts, which can officially be worn only when the karateka has achieved the appropriate status.
>
><cite>--_Hamari & Lehdonvirta (2010)_</cite>

###Artificial Scarcity

Games that create an environment where avatars and accounts can be compared between users almost always integrate artificial scarcity. Rare, collectible items are status symbols that ascibre value to virtual items in the virtual world. Artificial scarcity inflates the value of virtual items out of proportion, creating a value proposition for real money trading.

###This Dota2 Pink Courier Item [sold for more than $38,000](http://www.engadget.com/2013/11/06/dota-2-pink-war-dog-courier-sells-for-38-000/) because of its rare properties
![Dota 2 Pink Ethereal Flame War Dog Courier]({{ site.baseurl }}/assets/courier.png)

##Game Mechanics and Their Role in Motivating Purchases

The go-to example when talking about MMO games and motivation is World of Warcraft and it's leveling system. When you reach the next level, your health and mana are restored, new abilities are unlocked, and there's a large glowing explosion of light that occupies the center of your screen. Your friends online are notified, so you might get a few messages, and if you hit a level milestone, you'll get an achievement - another flash on your screen, notifying you of success.

This kind of motivating feedback is essential to keeping the player interested and motivated to continue playing. Feedback is essential to games. If you execute an action and receive no response, you feel unrewarded, and potentially cheated. Hamari and Järvinen (2011) call the action and expected response a verb. In their words, "an example of a verb is harvesting the crops in FarmVille by clicking on them. The system acknowledges this action by a procedure where it rewards the player with coins, i.e. the in-game currency."

Acquiring customers in the context of a free-to-play game requires motivating the players to immerse themselves in the game world. This requires a compelling, feedback rich experience. Users will only want to pay for more if they like what they've already seen.

>“Retention: the customer continues to purchase the product or service over a specified time period.”
>
><cite>--_Blattberg et al. (2001)_</cite>

Free-to-play is all about the relationship that you want to build with your customer. You want a service, not a game. Something that keeps the user coming back, that can't be beaten. You need retention.

##Concluding Thoughts

The transition from fixed price to free-to-play has hidden effects. Instead of owning a game and using it as you please, games are now a service. Games are subject to change, whether that means new content, changes to existing content, or otherwise. When you download a game, you're not committing your wallet anymore. And game developers don't mind - your intial purchase is small potatoes compared to the money they can get from you over time.

The free-to-play revenue model means that your time and money are constantly being fought for. As a consumer, this sounds good - you can invest proportionally to your interest. On the other hand, games used to be complete products that were sold as-is, and now they're being sold with promised features not delivered because they will be part of future updates - partially complete. With services such as [Steam's Early Access](http://store.steampowered.com/genre/Early%20Access/) people are buying unfinished games before they're even released.

The name of the game is customer retention. When you play a free-to-play game and don't pay, you're costing the company money. They pay server upkeep fees, they paid to create the game, and they pay to support it. Every dollar that you don't spend is a dollar they need to come from someone else - and there are people willing to throw it in. Games like Clash of Clans have top players spending more than [$250 per week and playing simultaneously on multiple devices](http://www.nytimes.com/2013/12/22/technology/master-of-his-virtual-domain.html) just to stay at the top. The real money in free-to-play games is in targeting the whales - the 1% of players that are willing to shell out hundreds or thousands of dollars for virtual items - that cost nothing, and can be infinitely resold.

*[RMT]: Real Money Transfer