# Blog Posts

{% api-method method="get" host="https://titan.tf/rss\_blog" path=" " %}
{% api-method-summary %}
Recent Blogs
{% endapi-method-summary %}

{% api-method-description %}
Get the 5 latest blog posts.
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
        <title>Titan.TF - Blog</title>
        <link>https://titan.tf/blogs</link>
        <description />
        <atom:link href="https://titan.tf/rss_blogs.php" rel="self" type="application/rss+xml" />
        <item>
            <title>Introducing Job Market</title>
            <link>https://titan.tf/blog/10</link>
            <guid>https://titan.tf/blog/10</guid>
            <pubDate>Sun, 17 May 2020 18:21:59 +0200</pubDate>
            <description><![CDATA[ # [center]We love the new missions feature we introduced to you last week. We now bring you the Job Market, a.k.a solo missions![/center]\r\n\r\n#### Choose Your Own Adventure\r\nWhat job you decide to take is completely up to you! Nobody is forcing you to take up a job you don\'t like. If you like playing Machine Attacks, then take up a job for that. If you like playing Demoman, pick up a Demoman specific job!\r\n\r\n#### Limited\r\nJobs come in limited quantities, they are gone as soon as someone takes them. They will also expire after a period of time has passed. There will be jobs added to the job market every day but there won\'t always be a job available for you to take.\r\n\r\nHowever, there are also special jobs where they do not have any limit to the number of people that can accept. These jobs will only appear at special events.\r\n\r\n![image description](https://cdn.discordapp.com/attachments/282799971387047936/530015660747653120/board.png \"image title\")\r\n\r\n### Objectives\r\nThere are 3 types of jobs available.\r\n\r\n- ##### Single Objective\r\nThese jobs only require you to finish one task. Your job finishes as soon as you finish the task.\r\n\r\n- ##### Multi Objectives\r\nThese jobs require you to complete multiple tasks. Your job will finish when you finish all the tasks.\r\n\r\n- ##### Scoring\r\nThese jobs are based on scoring. Each task will contribute to the total score. You must reach the minimum score required to finish the job.\r\n\r\n### Levels\r\nJobs are categorized into levels, from 1 - 5. Higher levels usually contain lesser but very difficult tasks, and also come in lesser quantities and yield much greater rewards.\r\n\r\n### Penalties\r\n- ##### Late\r\nEvery job has a time limit. If you finish a job late, your job reward will be penalized. The amount of money penalized scales proportionally to the amount of time passed since the job ended.\r\n\r\n- ##### Abandon\r\nYou can only run one job at a time. However, you can abandon a job for another one at any time, but penalties will apply. You must compensate credits for abandoning a job. The penalty amount will scale proportionally to the amount of time passed since the job was accepted.\r\n\r\n- ##### Overdue\r\nWhen the job is overdue by 2 days from the expected completion time, the job is considered abandoned and abandon penalties will apply.\r\n\r\n### Titan Law\r\nA few months ago, we built a system called Titan Law because we envisioned more features to be using the same style as challenges and quests. We extracted out the code and made it Titan Law. Today, we have quests (still being worked on), challenges, missions, and jobs powered by Titan Law. Titan Law makes it super easy for us to push out new challenges, jobs, missions, and quests without the need to write a single line of code or push any server patches.\r\n\r\nGoing forward, we will be trying to make Passive Name Tags (announced in Tour of Destruction Update in end 2018) use Titan Law as well.\r\n\r\n### Coming Up\r\nWe have another super big patch shipping in the coming weeks. This update will introduce a few new features to spice things up. We\'re excited, stay tuned. ]]></description>
        </item>
        <item>
            <title>Introducing Missions</title>
            <link>https://titan.tf/blog/53</link>
            <guid>https://titan.tf/blog/53</guid>
            <pubDate>Sun, 10 May 2020 17:17:34 +0200</pubDate>
            <description><![CDATA[ ## [center]Work together as a team to complete the team mission before the other team does within the time limit![/center]\r\n\r\n#### When there are 6 or more players, missions may start to appear. They have a 40% chance of appearing. The objectives of both teams will be the same.\r\nThere is a time limit of 20 minutes for each mission. A new mission will drop every 40 mins. However, in Mann vs Machine and Machine Attacks gamemodes, the team just has to complete the mission before the time limit is reached.\r\n\r\nWhen a mission is successfully completed by a team, each player in the team who contributed to the mission objective will receive the mission reward.\r\n\r\n#### PvP\r\n![image description](https://cdn.discordapp.com/attachments/512994272430260237/709061332053262366/20200510231627_1.jpg \"image title\")\r\n\r\n#### Single Team (MvM, Slender Fortress, VSH etc)\r\n![image description](https://cdn.discordapp.com/attachments/512994272430260237/709060954134020096/20200510231446_1.jpg \"image title\")\r\n\r\n### Types\r\nThere are 2 types of missions available.\r\n##### 1. Single Objective (90% chance)\r\n - These missions only have one objective and will be completed when the objective is reached.\r\n\r\n##### 2. Scoring (10% chance)\r\n - These missions have more than one objective. Each objective will grant points to the team\'s score. The first team to reach the scoring goal wins. The required amount of points is calculated based on the multiplied by 60% of the player count in each team (base x 60% player count). This means that 60% of the players in each team should participate. The current base amount is set to 20. Both 60% and the base amount may change in the future.\r\n\r\n### Objectives\r\nObjectives vary between gamemodes, gamemode specific objectives may appear for some gamemodes. The objective is displayed to everyone when the mission begins, and constantly on the right panel.\r\n\r\n### Rewards\r\nThese are the possible rewards for completing a mission. As we are testing this feature at the moment, only XP reward is available until we have thoroughly tested.\r\n- XP\r\n- Credits\r\n- Consumables\r\n- Trading Cards\r\n\r\n[spoiler]![image description](https://cdn.discordapp.com/attachments/546260747634737162/708282345748431038/board.png \"Sneak Peek for Patch 2.1.78\")[/spoiler] ]]></description>
        </item>
        <item>
            <title>Server Updates — May 2020 (Complete)</title>
            <link>https://titan.tf/blog/65</link>
            <guid>https://titan.tf/blog/65</guid>
            <pubDate>Tue, 28 Apr 2020 05:24:06 +0200</pubDate>
            <description><![CDATA[ ##### [center]This blog post will update as things changes.[/center]\r\n##### [center]Last Update: 1 May 10:19 AM SGT (+0800)[/center]\r\n\r\n### [center]Legend[/center]\r\n[center][color: orange]Server is pending migration, addition or removal on Apr 30[/color][/center]\r\n[center][color: light]Server is pending update[/color][/center]\r\n[center][color: green]Server has been migrated successfully[/color][/center]\r\n[center][color: red]Server has been removed[/color][/center]\r\n\r\n#### New (Singapore)\r\n- [color: green]Machine Attacks 4 — [IP 51.79.158.36:27015](steam://connect/51.79.158.36:27015)[/color]\r\n\r\n#### Migrated (Singapore)\r\n- [color: green]Hightower x100 — [New IP 51.79.158.35:27015](steam://connect/51.79.158.35:27015)[/color]\r\n- [color: green]Slender Fortress — [New IP 139.99.91.134:27015](steam://connect/139.99.91.134:27015)[/color]\r\n- [color: green]Zombie Mod - [New IP 51.79.158.64:27015](steam://connect/51.79.158.64:27015)[/color]\r\n- [color: green]Content Distributor (Bowling) - [New IP 94.130.224.131:11111](steam://connect/94.130.224.131:11111)[/color]\r\n- [color: green]The Lab[/color]\r\n\r\n#### Closed (Singapore)\r\n- [color: red]Orange x100[/color]\r\n- [color: red]TF2 Ware[/color]\r\n- [color: red]Sandbox[/color]\r\n- [color: red]VS Saxton Hale[/color]\r\n- [color: red]Class Wars[/color]\r\n\r\n#### Updated (Europe)\r\n- [color: green]SUPER Orange to MvM Uberupgrades[/color]\r\n- [color: green]Orange x100 to Hightower x100[/color] ]]></description>
        </item>
        <item>
            <title>Server Migration for Performance — May 2020</title>
            <link>https://titan.tf/blog/64</link>
            <guid>https://titan.tf/blog/64</guid>
            <pubDate>Fri, 24 Apr 2020 04:33:34 +0200</pubDate>
            <description><![CDATA[ #### In order to build a more maintainable network of servers, we have decided to make some changes to our existing infrastructure.\r\n\r\nOur OG servers are hosted on not so ideal machine specs but they are definitely playable. OG servers refer to all of our original Singapore servers such as Deathrun, Slender Fortress, Freak Fortress, MvM, Machine Attacks, and Orange to name a few. Some of these servers no longer exist.\r\n\r\nAt the end of April, we will be migrating a few servers over to a new host provider for possibly and hopefully better performance. This migration will also save us a large sum of cost which is especially critical during this Covid situation. The following Singapore servers will be affected. These servers **WILL HAVE A NEW IP ADDRESS**. \r\n- Hightower x100\r\n- Slender Fortress (already migrated to 139.99.91.134)\r\n- Zombie Mod\r\n- The Lab\r\n- Content Distributor\r\n\r\nWe will also be saying goodbye to a few Singapore servers because they weren\'t played frequently.\r\n- Sandbox\r\n- TF2 Ware\r\n- Class Wars\r\n- Orange x100 (still available in other regions)\r\n- VS Saxton Hale (still available in other regions)\r\n\r\nWe will be opening up a 4th Machine Attacks server in Singapore hosted on the new provider. This is to test the performance of hosting Machine Attacks on better server specs. If this goes well, we hope that we can slowly move more people over from MA 1 - 3 over to MA 4 - 6. Once this long process completes, we will rename 4 - 6 to 1 - 3 and shut off the original 1 - 3 hosted on lower end specs.\r\n- Machine Attacks 4\r\n\r\nIf you would like to try out the server performance of the new host provider, our VS Saxton Hale, and MvM x100 servers are already hosted there!\r\n\r\nIf this all goes well we will eventually move all OG servers onto the new provider and maybe close more Singapore servers when necessary as they have been declining over the years. We also want to continue expanding to other regions, as our Germany and France servers have been doing really well. ]]></description>
        </item>
        <item>
            <title>Free Titan Plus Month #StayHome</title>
            <link>https://titan.tf/blog/60</link>
            <guid>https://titan.tf/blog/60</guid>
            <pubDate>Sat, 11 Apr 2020 13:34:14 +0200</pubDate>
            <description><![CDATA[ #### In light of the Covid-19 situation, we would like to give everyone a month of free access to Titan Plus. By supplying this gift to everyone out of our generosity, we hope that everyone will continue to stay safe, stay home and have fun on our servers.\r\n\r\n:success: To qualify for this free redemption, all you need to do is join our [Steam group](https://steamcommunity.com/groups/titantf). Once you are in, head to the [Titan Plus](plus) page and activate your free month of Titan Plus! If you already have an existing active subscription, don\'t worry. We will still credit an additional month to your subscription if you perform the above.\r\n\r\n#### The redemption will be available from today till 12 May, 2020. You can redeem anytime during the period and it will start on the date.\r\n\r\n[color: orange]Please note that by redeeming this offer, you will no longer be applicable for the free month bonus if you decide to make your first Titan Plus subscription later. The main purpose of the free month bonus for first-time subscribers is to let them try out the program. Because you are claiming this offer, it will be counted towards the same purpose.[/color]\r\n\r\n[color: red]Titan Plus policies still apply.[/color]\r\n\r\n---\r\n\r\n:heartYellow: If you love Titan Plus and want to continue accessing the excellent benefits it offers, please support us by contributing a small monthly fee of 1 key or $2.29 USD.\r\n\r\nWe have revamped our Titan Plus page and the plans we offer. The page now shows you the full list of benefits in detail, but please keep in mind that we are still building on this. We have additional plans that provide discounts and benefits if you subscribe for more months in one payment. We also offer a discount when paying with Paypal. These subscriptions go in great lengths in helping us to continue maintaining and running our network, and further expand our servers to more regions.\r\n\r\nWe would like to sincerely thank everyone who has contributed to Titan Plus and helped us grow to what we are today. ]]></description>
        </item>
    </channel>
</rss>
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



