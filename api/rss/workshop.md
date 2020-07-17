# Workshop

{% api-method method="get" host="https://workshop.titan.tf/atom" path=" " %}
{% api-method-summary %}
Recent Activity
{% endapi-method-summary %}

{% api-method-description %}
Get submissions based on the most recent activity.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Returns an XML feed on success.
{% endapi-method-response-example-description %}

```markup
<feed xmlns="http://www.w3.org/2005/Atom">
    <title><![CDATA[ Workshop ]]></title>
    <subtitle><![CDATA[ Last posts in the forum ]]></subtitle>
    <link href="https://workshop.titan.tf/atom/" rel="self" />
    <link href="https://workshop.titan.tf/" />
    <id><![CDATA[ https://workshop.titan.tf/ ]]></id>
    <updated>2020-07-17T12:01:49+00:00</updated>
    <entry>
        <title><![CDATA[ Tom and Jerry Theme ]]></title>
        <link rel="alternate" type="text/html" href="https://workshop.titan.tf/d/25-tom-and-jerry-theme/1" />
        <id>https://workshop.titan.tf/d/25-tom-and-jerry-theme/1</id>
        <updated>2020-07-15T05:48:25+00:00</updated>
        <content type="html"><![CDATA[ <p><strong>Description</strong><br> Reminisce the golden days.</p> <p><strong>Rarity</strong></p> <ul><li data-task-id="5f0e98a9e9efa" data-task-state="checked"><input data-task-id="5f0e98a9e9efa" type="checkbox" checked disabled> Legendary</li> <li data-task-id="5f0e98a9ead1a" data-task-state="unchecked"><input data-task-id="5f0e98a9ead1a" type="checkbox" disabled> Epic</li> <li data-task-id="5f0e98a9eb396" data-task-state="unchecked"><input data-task-id="5f0e98a9eb396" type="checkbox" disabled> Rare</li> <li data-task-id="5f0e98a9ec6b8" data-task-state="unchecked"><input data-task-id="5f0e98a9ec6b8" type="checkbox" disabled> Uncommon</li> <li data-task-id="5f0e98a9ece85" data-task-state="unchecked"><input data-task-id="5f0e98a9ece85" type="checkbox" disabled> Common</li></ul> <p><strong>Obtainability</strong></p> <ul><li data-task-id="5f0e98a9eded1" data-task-state="checked"><input data-task-id="5f0e98a9eded1" type="checkbox" checked disabled> Item Shop</li> <li data-task-id="5f0e98a9ee034" data-task-state="checked"><input data-task-id="5f0e98a9ee034" type="checkbox" checked disabled> Battle Pass</li> <li data-task-id="5f0e98a9eea19" data-task-state="unchecked"><input data-task-id="5f0e98a9eea19" type="checkbox" disabled> Supplies (Drops, Chests etc)</li> <li data-task-id="5f0e98a9eebab" data-task-state="unchecked"><input data-task-id="5f0e98a9eebab" type="checkbox" disabled> Challenges</li> <li data-task-id="5f0e98a9eecdf" data-task-state="unchecked"><input data-task-id="5f0e98a9eecdf" type="checkbox" disabled> Quests</li> <li data-task-id="5f0e98a9ef45d" data-task-state="unchecked"><input data-task-id="5f0e98a9ef45d" type="checkbox" disabled> Team Missions</li> <li data-task-id="5f0e98a9efa5a" data-task-state="unchecked"><input data-task-id="5f0e98a9efa5a" type="checkbox" disabled> Jobs</li></ul> <p><strong>Price (if it is added to the item shop)</strong><br> $299.99</p> <hr> <h3>File</h3> <div class="ButtonGroup" data-fof-upload-download-uuid="d45d2c1b-a8e6-4fee-88f8-388c18b9a2ae"><div class="Button hasIcon Button--icon Button--primary"><i class="fas fa-download"></i></div><div class="Button">tomnjerry.mpga</div><div class="Button">412kB</div></div> <h3>Source</h3> <p><span data-s9e-mediaembed="youtube" style="display:inline-block;width:100%;max-width:640px"><span style="display:block;overflow:hidden;position:relative;padding-bottom:56.25%"><iframe allowfullscreen="" loading="lazy" scrolling="no" style="background:url(https://i.ytimg.com/vi/3cu0KOzunpI/hqdefault.jpg) 50% 50% / cover;border:0;height:100%;left:0;position:absolute;width:100%" src="https://www.youtube.com/embed/3cu0KOzunpI"></iframe></span></span></p> ]]></content>
        <author>
            <name>myst</name>
        </author>
    </entry>
</feed>
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://workshop.titan.tf/atom/discussions" path=" " %}
{% api-method-summary %}
New Submissions
{% endapi-method-summary %}

{% api-method-description %}
Get the newest submissions.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Returns an XML feed on success.
{% endapi-method-response-example-description %}

```markup
<feed xmlns="http://www.w3.org/2005/Atom">
    <title><![CDATA[ New discussions in Workshop ]]></title>
    <subtitle><![CDATA[ The newest discussions in the forum ]]></subtitle>
    <link href="https://workshop.titan.tf/atom/" rel="self" />
    <link href="https://workshop.titan.tf/" />
    <id><![CDATA[ https://workshop.titan.tf/ ]]></id>
    <updated>2020-07-17T12:01:49+00:00</updated>
    <entry>
        <title><![CDATA[ Tom and Jerry Theme ]]></title>
        <link rel="alternate" type="text/html" href="https://workshop.titan.tf/d/25-tom-and-jerry-theme/1" />
        <id>https://workshop.titan.tf/d/25-tom-and-jerry-theme/1</id>
        <updated>2020-07-15T05:48:25+00:00</updated>
        <content type="html"><![CDATA[ <p><strong>Description</strong><br> Reminisce the golden days.</p> <p><strong>Rarity</strong></p> <ul><li data-task-id="5f0e98a9e9efa" data-task-state="checked"><input data-task-id="5f0e98a9e9efa" type="checkbox" checked disabled> Legendary</li> <li data-task-id="5f0e98a9ead1a" data-task-state="unchecked"><input data-task-id="5f0e98a9ead1a" type="checkbox" disabled> Epic</li> <li data-task-id="5f0e98a9eb396" data-task-state="unchecked"><input data-task-id="5f0e98a9eb396" type="checkbox" disabled> Rare</li> <li data-task-id="5f0e98a9ec6b8" data-task-state="unchecked"><input data-task-id="5f0e98a9ec6b8" type="checkbox" disabled> Uncommon</li> <li data-task-id="5f0e98a9ece85" data-task-state="unchecked"><input data-task-id="5f0e98a9ece85" type="checkbox" disabled> Common</li></ul> <p><strong>Obtainability</strong></p> <ul><li data-task-id="5f0e98a9eded1" data-task-state="checked"><input data-task-id="5f0e98a9eded1" type="checkbox" checked disabled> Item Shop</li> <li data-task-id="5f0e98a9ee034" data-task-state="checked"><input data-task-id="5f0e98a9ee034" type="checkbox" checked disabled> Battle Pass</li> <li data-task-id="5f0e98a9eea19" data-task-state="unchecked"><input data-task-id="5f0e98a9eea19" type="checkbox" disabled> Supplies (Drops, Chests etc)</li> <li data-task-id="5f0e98a9eebab" data-task-state="unchecked"><input data-task-id="5f0e98a9eebab" type="checkbox" disabled> Challenges</li> <li data-task-id="5f0e98a9eecdf" data-task-state="unchecked"><input data-task-id="5f0e98a9eecdf" type="checkbox" disabled> Quests</li> <li data-task-id="5f0e98a9ef45d" data-task-state="unchecked"><input data-task-id="5f0e98a9ef45d" type="checkbox" disabled> Team Missions</li> <li data-task-id="5f0e98a9efa5a" data-task-state="unchecked"><input data-task-id="5f0e98a9efa5a" type="checkbox" disabled> Jobs</li></ul> <p><strong>Price (if it is added to the item shop)</strong><br> $299.99</p> <hr> <h3>File</h3> <div class="ButtonGroup" data-fof-upload-download-uuid="d45d2c1b-a8e6-4fee-88f8-388c18b9a2ae"><div class="Button hasIcon Button--icon Button--primary"><i class="fas fa-download"></i></div><div class="Button">tomnjerry.mpga</div><div class="Button">412kB</div></div> <h3>Source</h3> <p><span data-s9e-mediaembed="youtube" style="display:inline-block;width:100%;max-width:640px"><span style="display:block;overflow:hidden;position:relative;padding-bottom:56.25%"><iframe allowfullscreen="" loading="lazy" scrolling="no" style="background:url(https://i.ytimg.com/vi/3cu0KOzunpI/hqdefault.jpg) 50% 50% / cover;border:0;height:100%;left:0;position:absolute;width:100%" src="https://www.youtube.com/embed/3cu0KOzunpI"></iframe></span></span></p> ]]></content>
        <author>
            <name>myst</name>
        </author>
    </entry>
</feed>
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://workshop.titan.tf/atom/t/" path="tag" %}
{% api-method-summary %}
Recent Activity in Tag
{% endapi-method-summary %}

{% api-method-description %}
Get submissions in a tag based on the most recent activity.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="tag" type="string" required=true %}
The submission tag to retrieve
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Returns an XML feed on success.
{% endapi-method-response-example-description %}

```markup
<feed xmlns="http://www.w3.org/2005/Atom">
    <title><![CDATA[ Activity in the pending tag ]]></title>
    <subtitle><![CDATA[ Last posts in the pending tag ]]></subtitle>
    <link href="https://workshop.titan.tf/atom/" rel="self" />
    <link href="https://workshop.titan.tf/" />
    <id><![CDATA[ https://workshop.titan.tf/ ]]></id>
    <updated>2020-07-17T12:01:49+00:00</updated>
    <entry>
        <title><![CDATA[ Tom and Jerry Theme ]]></title>
        <link rel="alternate" type="text/html" href="https://workshop.titan.tf/d/25-tom-and-jerry-theme/1" />
        <id>https://workshop.titan.tf/d/25-tom-and-jerry-theme/1</id>
        <updated>2020-07-15T05:48:25+00:00</updated>
        <content type="html"><![CDATA[ <p><strong>Description</strong><br> Reminisce the golden days.</p> <p><strong>Rarity</strong></p> <ul><li data-task-id="5f0e98a9e9efa" data-task-state="checked"><input data-task-id="5f0e98a9e9efa" type="checkbox" checked disabled> Legendary</li> <li data-task-id="5f0e98a9ead1a" data-task-state="unchecked"><input data-task-id="5f0e98a9ead1a" type="checkbox" disabled> Epic</li> <li data-task-id="5f0e98a9eb396" data-task-state="unchecked"><input data-task-id="5f0e98a9eb396" type="checkbox" disabled> Rare</li> <li data-task-id="5f0e98a9ec6b8" data-task-state="unchecked"><input data-task-id="5f0e98a9ec6b8" type="checkbox" disabled> Uncommon</li> <li data-task-id="5f0e98a9ece85" data-task-state="unchecked"><input data-task-id="5f0e98a9ece85" type="checkbox" disabled> Common</li></ul> <p><strong>Obtainability</strong></p> <ul><li data-task-id="5f0e98a9eded1" data-task-state="checked"><input data-task-id="5f0e98a9eded1" type="checkbox" checked disabled> Item Shop</li> <li data-task-id="5f0e98a9ee034" data-task-state="checked"><input data-task-id="5f0e98a9ee034" type="checkbox" checked disabled> Battle Pass</li> <li data-task-id="5f0e98a9eea19" data-task-state="unchecked"><input data-task-id="5f0e98a9eea19" type="checkbox" disabled> Supplies (Drops, Chests etc)</li> <li data-task-id="5f0e98a9eebab" data-task-state="unchecked"><input data-task-id="5f0e98a9eebab" type="checkbox" disabled> Challenges</li> <li data-task-id="5f0e98a9eecdf" data-task-state="unchecked"><input data-task-id="5f0e98a9eecdf" type="checkbox" disabled> Quests</li> <li data-task-id="5f0e98a9ef45d" data-task-state="unchecked"><input data-task-id="5f0e98a9ef45d" type="checkbox" disabled> Team Missions</li> <li data-task-id="5f0e98a9efa5a" data-task-state="unchecked"><input data-task-id="5f0e98a9efa5a" type="checkbox" disabled> Jobs</li></ul> <p><strong>Price (if it is added to the item shop)</strong><br> $299.99</p> <hr> <h3>File</h3> <div class="ButtonGroup" data-fof-upload-download-uuid="d45d2c1b-a8e6-4fee-88f8-388c18b9a2ae"><div class="Button hasIcon Button--icon Button--primary"><i class="fas fa-download"></i></div><div class="Button">tomnjerry.mpga</div><div class="Button">412kB</div></div> <h3>Source</h3> <p><span data-s9e-mediaembed="youtube" style="display:inline-block;width:100%;max-width:640px"><span style="display:block;overflow:hidden;position:relative;padding-bottom:56.25%"><iframe allowfullscreen="" loading="lazy" scrolling="no" style="background:url(https://i.ytimg.com/vi/3cu0KOzunpI/hqdefault.jpg) 50% 50% / cover;border:0;height:100%;left:0;position:absolute;width:100%" src="https://www.youtube.com/embed/3cu0KOzunpI"></iframe></span></span></p> ]]></content>
        <author>
            <name>myst</name>
        </author>
    </entry>
</feed>
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://workshop.titan.tf/atom/t/" path="tag/discussions" %}
{% api-method-summary %}
New Submissions in Tag
{% endapi-method-summary %}

{% api-method-description %}
Get submissions based on the most recent activity.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="tag" type="string" required=true %}
The submission tag to retrieve
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Returns an XML feed on success.
{% endapi-method-response-example-description %}

```markup
<feed xmlns="http://www.w3.org/2005/Atom">
    <title><![CDATA[ New discussions in the pending tag ]]></title>
    <subtitle><![CDATA[ The newest discussions in the pending tag ]]></subtitle>
    <link href="https://workshop.titan.tf/atom/" rel="self" />
    <link href="https://workshop.titan.tf/" />
    <id><![CDATA[ https://workshop.titan.tf/ ]]></id>
    <updated>2020-07-17T12:01:49+00:00</updated>
    <entry>
        <title><![CDATA[ Tom and Jerry Theme ]]></title>
        <link rel="alternate" type="text/html" href="https://workshop.titan.tf/d/25-tom-and-jerry-theme/1" />
        <id>https://workshop.titan.tf/d/25-tom-and-jerry-theme/1</id>
        <updated>2020-07-15T05:48:25+00:00</updated>
        <content type="html"><![CDATA[ <p><strong>Description</strong><br> Reminisce the golden days.</p> <p><strong>Rarity</strong></p> <ul><li data-task-id="5f0e98a9e9efa" data-task-state="checked"><input data-task-id="5f0e98a9e9efa" type="checkbox" checked disabled> Legendary</li> <li data-task-id="5f0e98a9ead1a" data-task-state="unchecked"><input data-task-id="5f0e98a9ead1a" type="checkbox" disabled> Epic</li> <li data-task-id="5f0e98a9eb396" data-task-state="unchecked"><input data-task-id="5f0e98a9eb396" type="checkbox" disabled> Rare</li> <li data-task-id="5f0e98a9ec6b8" data-task-state="unchecked"><input data-task-id="5f0e98a9ec6b8" type="checkbox" disabled> Uncommon</li> <li data-task-id="5f0e98a9ece85" data-task-state="unchecked"><input data-task-id="5f0e98a9ece85" type="checkbox" disabled> Common</li></ul> <p><strong>Obtainability</strong></p> <ul><li data-task-id="5f0e98a9eded1" data-task-state="checked"><input data-task-id="5f0e98a9eded1" type="checkbox" checked disabled> Item Shop</li> <li data-task-id="5f0e98a9ee034" data-task-state="checked"><input data-task-id="5f0e98a9ee034" type="checkbox" checked disabled> Battle Pass</li> <li data-task-id="5f0e98a9eea19" data-task-state="unchecked"><input data-task-id="5f0e98a9eea19" type="checkbox" disabled> Supplies (Drops, Chests etc)</li> <li data-task-id="5f0e98a9eebab" data-task-state="unchecked"><input data-task-id="5f0e98a9eebab" type="checkbox" disabled> Challenges</li> <li data-task-id="5f0e98a9eecdf" data-task-state="unchecked"><input data-task-id="5f0e98a9eecdf" type="checkbox" disabled> Quests</li> <li data-task-id="5f0e98a9ef45d" data-task-state="unchecked"><input data-task-id="5f0e98a9ef45d" type="checkbox" disabled> Team Missions</li> <li data-task-id="5f0e98a9efa5a" data-task-state="unchecked"><input data-task-id="5f0e98a9efa5a" type="checkbox" disabled> Jobs</li></ul> <p><strong>Price (if it is added to the item shop)</strong><br> $299.99</p> <hr> <h3>File</h3> <div class="ButtonGroup" data-fof-upload-download-uuid="d45d2c1b-a8e6-4fee-88f8-388c18b9a2ae"><div class="Button hasIcon Button--icon Button--primary"><i class="fas fa-download"></i></div><div class="Button">tomnjerry.mpga</div><div class="Button">412kB</div></div> <h3>Source</h3> <p><span data-s9e-mediaembed="youtube" style="display:inline-block;width:100%;max-width:640px"><span style="display:block;overflow:hidden;position:relative;padding-bottom:56.25%"><iframe allowfullscreen="" loading="lazy" scrolling="no" style="background:url(https://i.ytimg.com/vi/3cu0KOzunpI/hqdefault.jpg) 50% 50% / cover;border:0;height:100%;left:0;position:absolute;width:100%" src="https://www.youtube.com/embed/3cu0KOzunpI"></iframe></span></span></p> ]]></content>
        <author>
            <name>myst</name>
        </author>
    </entry>
</feed>
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="get" host="https://workshop.titan.tf/atom/d/" path="discussion-slug" %}
{% api-method-summary %}
Recent Comments in Submission
{% endapi-method-summary %}

{% api-method-description %}
Get recent comments in a submission.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="discussion-slug" type="string" required=true %}
The submission to retrieve
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Returns an XML feed on success.
{% endapi-method-response-example-description %}

```markup
<feed xmlns="http://www.w3.org/2005/Atom">
    <title><![CDATA[ Calamity - The Tale of a Cruel World ]]></title>
    <subtitle><![CDATA[ Last messages in this discussion ]]></subtitle>
    <link href="https://workshop.titan.tf/atom/d/1-calamity-the-tale-of-a-cruel-world/" rel="self" />
    <link href="https://workshop.titan.tf/d/1-calamity-the-tale-of-a-cruel-world/" />
    <id><![CDATA[ https://workshop.titan.tf/d/1-calamity-the-tale-of-a-cruel-world/ ]]></id>
    <updated>2020-07-17T12:30:36+00:00</updated>
    <entry>
        <title><![CDATA[ Calamity - The Tale of a Cruel World ]]></title>
        <link rel="alternate" type="text/html" href="https://workshop.titan.tf/d/1-calamity-the-tale-of-a-cruel-world/3" />
        <id>https://workshop.titan.tf/d/1-calamity-the-tale-of-a-cruel-world/3</id>
        <updated>2020-07-08T11:22:22+00:00</updated>
        <content type="html"><![CDATA[ <p>epic</p> ]]></content>
        <author>
            <name>JohnWick4FanMadeIsShit</name>
        </author>
    </entry>
    <entry>
        <title><![CDATA[ Calamity - The Tale of a Cruel World ]]></title>
        <link rel="alternate" type="text/html" href="https://workshop.titan.tf/d/1-calamity-the-tale-of-a-cruel-world/2" />
        <id>https://workshop.titan.tf/d/1-calamity-the-tale-of-a-cruel-world/2</id>
        <updated>2020-07-07T16:28:16+00:00</updated>
        <content type="html"><![CDATA[ <p>This is really good!</p> ]]></content>
        <author>
            <name>myst</name>
        </author>
    </entry>
    <entry>
        <title><![CDATA[ Calamity - The Tale of a Cruel World ]]></title>
        <link rel="alternate" type="text/html" href="https://workshop.titan.tf/d/1-calamity-the-tale-of-a-cruel-world/1" />
        <id>https://workshop.titan.tf/d/1-calamity-the-tale-of-a-cruel-world/1</id>
        <updated>2020-07-07T15:28:12+00:00</updated>
        <content type="html"><![CDATA[ <p><strong>Description</strong><br> This is the tale of a cruel world. A world whose calamity happened far before you got here. A world overrun by rot and blood.</p> <p><strong>Rarity</strong></p> <ul><li data-task-id="5f054ff5c2930" data-task-state="unchecked"><input data-task-id="5f054ff5c2930" type="checkbox" disabled> Legendary</li> <li data-task-id="5f054ff5c2b74" data-task-state="unchecked"><input data-task-id="5f054ff5c2b74" type="checkbox" disabled> Epic</li> <li data-task-id="5f054ff5c2d22" data-task-state="unchecked"><input data-task-id="5f054ff5c2d22" type="checkbox" disabled> Rare</li> <li data-task-id="5f054ff5c2e20" data-task-state="checked"><input data-task-id="5f054ff5c2e20" type="checkbox" checked disabled> Uncommon</li> <li data-task-id="5f054ff5c33b7" data-task-state="unchecked"><input data-task-id="5f054ff5c33b7" type="checkbox" disabled> Common</li></ul> <p><strong>Obtainability</strong></p> <ul><li data-task-id="5f054ff5c38e1" data-task-state="checked"><input data-task-id="5f054ff5c38e1" type="checkbox" checked disabled> Item Shop</li> <li data-task-id="5f054ff5c39d1" data-task-state="unchecked"><input data-task-id="5f054ff5c39d1" type="checkbox" disabled> Battle Pass</li> <li data-task-id="5f054ff5c3c60" data-task-state="unchecked"><input data-task-id="5f054ff5c3c60" type="checkbox" disabled> Supplies (Drops, Chests etc)</li> <li data-task-id="5f054ff5c3d52" data-task-state="unchecked"><input data-task-id="5f054ff5c3d52" type="checkbox" disabled> Challenges</li> <li data-task-id="5f054ff5c3ebb" data-task-state="unchecked"><input data-task-id="5f054ff5c3ebb" type="checkbox" disabled> Quests</li> <li data-task-id="5f054ff5c4051" data-task-state="unchecked"><input data-task-id="5f054ff5c4051" type="checkbox" disabled> Team Missions</li> <li data-task-id="5f054ff5c4132" data-task-state="unchecked"><input data-task-id="5f054ff5c4132" type="checkbox" disabled> Jobs</li></ul> <p><strong>Price (if it is added to the item shop)</strong><br> 59.99$</p> <hr> <h3><a href="https://cdn.discordapp.com/attachments/546260747634737162/730081743834710036/titantf_dispenser_theme_The_Tale_of_a_Cruel_World.mp3" rel=" nofollow ugc">File</a></h3> <h3><a href="https://www.youtube.com/watch?v=b8A_FGr4Pjo" rel=" nofollow ugc">Source</a></h3> ]]></content>
        <author>
            <name>fk456</name>
        </author>
    </entry>
</feed>
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

