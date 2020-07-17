# Forum

{% api-method method="get" host="https://titan.tf/rss\_forum" path=" " %}
{% api-method-summary %}
Recent Threads
{% endapi-method-summary %}

{% api-method-description %}
Get the 5 latest forum threads.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Returns an XML feed on success.
{% endapi-method-response-example-description %}

```markup
<rss xmlns:atom="http://www.w3.org/2005/Atom" version="2.0">
    <channel>
        <title>Titan.TF - Forum Threads</title>
        <link>https://titan.tf/forum</link>
        <description />
        <atom:link href="https://titan.tf/rss_forum.php" rel="self" type="application/rss+xml" />
        <item>
            <title>New Equips: Freak Tokens + Base Anti-Freak Leader Info - by Shadow_The_Worm | Titan.TF</title>
            <link>https://titan.tf/forum/thread/354</link>
            <guid>https://titan.tf/forum/thread/354</guid>
            <pubDate>Fri, 10 Jul 2020 10:22:19 +0200</pubDate>
            <description><![CDATA[ Heya. So, Freak Fortress is dying, eh? Well, not under my watch. I\'ve got a new loadout setting idea for this mode specifically: Freak Tokens. Here\'s the briefing of this setting:\n_______________________________________________________________________\nThe boss has high HP (determined by a 460+ formula of ((=>460+x)*x) and deals about 210 damage per attack. But what if the opposition had their own Goliath in their team? That\'s what the Freak Tokens are about. Send your own lead for the boss to oppose. The Freak Fortress will check whenether at least 6 players are present in the game and one of them has at least 1 Freak Token equipped and if both statements are equal to 1, the player with the Freak Tokens will be chosen as the leader and the Tokens will be activated, giving him a boost in stats and abilities, turning him into a mini-freak. Let me explain what Freak Tokens exist and what they do:\n1. HP Token: The HP Token gives the leader increased max health, so the leader can withstand more attacks from the boss. There are 5 ranks of this Freak Token: S, M, L, XL, XXL. The first rank (Small) gives 100 HP on equip, the second (Medium) gives 250 HP on equip, the third (Large) equals 500 HP, the fourth (Super Large) - 800 HP, and the fifth (Ultra Large) is 1200 HP. The Scout can only equip the first two,, while the Medic can only equip the first 3. If their equipped tokens don\'t match the limits, the last allowed token is equipped.\n2. Regen Token: The Regen Token adds regeneration to the leader, so the leader can recover HP over time. Once again: 5 ranks: S, M, L, XL, XXL. The first token gives 10 HPpS, the second - 25 HPpS, the third - 40 - the fourth - 48, and the fifth - 56. The Scout can equip only the first one and the Medic - first 2, same rules on over the limit as well.\n3. Movement Token: The Movement Token increases the movement speed of the leader. Takes priority over the speed-bosting weapons (including Disciplinary Action). Again, 5 ranks. S = 30%, M = 50%, L = 75%, XL = 100%, XXL = 200%. Both the Scout and the Medic are limited to the first two, and... you get the nail of over the limit.\n4. Jump Token: The Jump Token increases the jump height of the wearer. 5 ranks again. S = 30%, M = 50%, L = 75%, XL = 100%, XXL = 200%. The Scout is limited to the first two.\n5. Attack Token: The Attack Token increases the attack speed of the wearer. 5 ranks once again. S = 5%, M = 10%, L = 25%, XL = 50%, XXL = 75%.\n6. Damage Token: The Damage Token increases the damage output of the wearer. 5 ranks yet again. S = 10%, M = 25%, L = 50%, XL = 100%, XXL = 200%. Both the Scout and the Medic can only equip first 3.\n7. Special Token: The Special Token gives special abilities to the wearer. There are two slots for this token instead of just one. No ranks this time around. All classes have their own Special Token settings. The first Special Tokens are Dash (tap a directional key twice quickly to preform an average hop (small hop for Scout), can be done in air, overrides Pursuit), Pursult (tap a directional key twice quickly to preform a high focused jump, blocks Scout\'s double jump after use, is overriden by Dash), Triple Eagle (attack two more times after connecting with an attack, works only after Pursuit (Dash or a regular jump won\'t trigger it), puts the wearer into freefall after use and stuns him for two seconds on landing after use), Eagle Burst (creates an explosion with 100 HP of damage on an attack connection, same requirements and consequences as for the Triple Eagle), Impact Drain (recovers 50 HP on attack connection, has 4 seconds of cooldown), Blood Drain (recovers 12 HP for each second of bleeding on the boss, makes the user unable to attack for the duration of the effect and slows him down to 50% from no Movement Token to Movement Token M or 35% from Movement Token L), Glide (allows the user to deploy a parachute after a jump or the knockback, unusable by Scout, is overriden by Extra Jump), Extra Jump (press the jump button to preform an extra stock jump, not affected by the Jump Token, not usable by Scout, overrides Glide), Cloak Dash (same as Dash, but has the cloak as an extra and makes the user invincible durning use, blocks attacking durning use + 3 extra seconds after it, not usable by Spy (he has the Cloak as his stock ability after all)), Energy Field (creates a damaging energy field on decloak, the field lasts for 3 seconds and the Spy can\'t cloak for 3 more seconds after use. Deals 30 HP of damage per second, not affected by anything), Avenger (allows the user to survive one deadly blow with 1 HP and adds 500 extra HP of damage to his first attack on the trigger, works only once in a round, requires at least L HP Token or 11 players located on the server, disables the Regen Token till the avenging blow is done + 3 seconds after it is done (hit or miss - doesn\'t matter, stuns the user for 3 seconds after the avenging blow is done), Jet Pulse (allows the user to preform 3 extra stock jumps in the air by swinging their melee weapon while looking downwards, the extra jump streak is stopped once the third swing is done or a swing hits the boss, is overriden by Shockwave), Shockwave (allows the user to thrust the boss akin to the Jet Pulse, same parameters as Jet Pulse, overrides Jet Pulse).\n\nSo, this is all about Freak Tokens. Now, let\'s talk about the Leader and Sub-Leader themselves:\n\nThe Leader is the player who leads the freak opposition team. He can wear any token allowed by his class - see above. The opposition can have only 1 Leader. The Leader is the main guy, but don\'t get too happy about him: he also differs from from his mass comrades. The diffrences include:\n\n1. Can\'t be revived with Reanimators.\n\n2. Some VSH/FF2 tweaks are disabled or debuffed for the leading player, such as: 1. He can\'t deal mini-crits with any weapon (but can deal 10% HP of damage to the boss and get stunned after doing so). 2. Jumpers, Natz and Cloak and Dagger are allowed (Cloak And Dagger drains with crouch speed if the user is immobile, Jumpers can\'t be replenished by dispensers AT ALL (but can replenished by ammo packs, with 25% of normal ammo restoration), Natascha has a 1% chance to slow the boss down for a single second instead of a complete 100%). 3. Crit-A-Cola acts like in normal (non-FF2) play, but replenishes 50% slower. 4. Mediguns and Syringe Guns are not replaced by the Custom-Kritzkrieg and Custom-Syringe-Gun. Most tweaks (such as Razorback Shield, F.O.S Block and Demoknight Shield) still work through.\n\n3. Gets completely stunned for 3 seconds if he is focused by a mass Medic\'s Custom Kritzkrieg ubercharge till the end of it - to avoid the stun of the Leader, focus the ubercharge impulse at another mass player durnin the last 2 seconds of the ubercharge\n\n4. (Sub-leader only) Most tokens require lower ranks for the sub-leader \nto be avaliable - around two ranks lower than the leader. Exception: Damage Token.\n\n5. 10%/1% base chance to be auto-picked at 6/7 players, increases up to 35%/10% as more players join. The Sub-leader can be manually selected by submitting a personal yes/no offer vote to an avaliable player durning setup time. If the player accepts the offer, he becomes the Sub-leader for the round and gains the same tweaks as the leading player over this list. This vote can be called by typing !offersubleader and choosing an avaliable player. Can be called only once per round. Has a cooldown of 2 rounds/Rock The Vote.\n_______________________________________________________________________\nAll right, so how about this little quirky thing for the Freak game modes? Tell me your opinion. I wish you a great day and lots of kills in the war. ]]></description>
        </item>
        <item>
            <title>gay - by david</title>
            <link>https://titan.tf/forum/thread/353</link>
            <guid>https://titan.tf/forum/thread/353</guid>
            <pubDate>Wed, 08 Jul 2020 08:45:33 +0200</pubDate>
            <description><![CDATA[ i am so gay \n\ni dont watch jojo anyways ]]></description>
        </item>
        <item>
            <title>How do you buy Keys or metal? - by MexicanLuigi G4MER_YT</title>
            <link>https://titan.tf/forum/thread/352</link>
            <guid>https://titan.tf/forum/thread/352</guid>
            <pubDate>Tue, 07 Jul 2020 22:42:33 +0200</pubDate>
            <description><![CDATA[ So i just noticed that i have a ton of credits but have never heard of this site before, so how can i buy stuff like keys or metal? ]]></description>
        </item>
        <item>
            <title>round end music ideas - by david</title>
            <link>https://titan.tf/forum/thread/351</link>
            <guid>https://titan.tf/forum/thread/351</guid>
            <pubDate>Thu, 02 Jul 2020 14:37:19 +0200</pubDate>
            <description><![CDATA[ Pirate Of The Caribbean : https://www.youtube.com/watch?v=yRh-dzrI4Z4 (He\'s a Pirate)\nSurprise Buttsecks : https://www.youtube.com/watch?v=dgUbRpdUN1w&amp;t=99s\nErectin\' a River : https://www.youtube.com/watch?v=2HjLN1TA3bc&amp;t=160s\npls add myst am sad :)))) ]]></description>
        </item>
        <item>
            <title>here goes gay music - by david</title>
            <link>https://titan.tf/forum/thread/350</link>
            <guid>https://titan.tf/forum/thread/350</guid>
            <pubDate>Thu, 02 Jul 2020 14:31:04 +0200</pubDate>
            <description><![CDATA[ https://www.youtube.com/watch?v=yRh-dzrI4Z4 ]]></description>
        </item>
    </channel>
</rss>
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



