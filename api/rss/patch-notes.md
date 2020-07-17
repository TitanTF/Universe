# Patch Notes

{% api-method method="get" host="https://titan.tf/rss\_patch" path=" " %}
{% api-method-summary %}
Recent Patch Notes
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get free cakes.
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
        <title>Titan.TF - Patch Notes</title>
        <link>https://titan.tf/patches</link>
        <description />
        <atom:link href="https://titan.tf/rss_patches.php" rel="self" type="application/rss+xml" />
        <item>
            <title>Patch 2.1.93</title>
            <link>https://titan.tf/patch/2.1.93</link>
            <guid>https://titan.tf/patch/2.1.93</guid>
            <pubDate>Fri, 10 Jul 2020 14:53:34 +0200</pubDate>
            <description><![CDATA[ ### General\r\n#### Fixes\r\n- Fixed slow loading pages and commands.\r\n\r\n### Community Servers\r\n#### Changes\r\n- Reduced the frequency of some unnecessary tasks.\r\n\r\n#### Fixes\r\n- Fixed air acceleration on servers with bunny hop enabled. ]]></description>
        </item>
        <item>
            <title>Patch 2.1.92.2</title>
            <link>https://titan.tf/patch/2.1.92.2</link>
            <guid>https://titan.tf/patch/2.1.92.2</guid>
            <pubDate>Wed, 08 Jul 2020 14:11:10 +0200</pubDate>
            <description><![CDATA[ ### Community Servers\r\n#### Changes\r\n- Gagged players can no longer use the IRC.\r\n\r\n#### Fixes\r\n- Fixed chat turned off by default before user settings are fetched. ]]></description>
        </item>
        <item>
            <title>Patch 2.1.92.1</title>
            <link>https://titan.tf/patch/2.1.92.1</link>
            <guid>https://titan.tf/patch/2.1.92.1</guid>
            <pubDate>Wed, 08 Jul 2020 07:43:12 +0200</pubDate>
            <description><![CDATA[ ### Community Servers\r\n#### Fixes\r\n- Fixed chat messages not appearing on send.\r\n\r\n- Fixed not being able to return to \"Hot\" or \"New\" shop lists when pressing back from an item.\r\n\r\n### Workshop\r\n#### Fixes\r\n- Fixed not being able to upload audio files. ]]></description>
        </item>
        <item>
            <title>Patch 2.1.92</title>
            <link>https://titan.tf/patch/2.1.92</link>
            <guid>https://titan.tf/patch/2.1.92</guid>
            <pubDate>Tue, 07 Jul 2020 17:48:31 +0200</pubDate>
            <description><![CDATA[ ## Highlights\r\n\r\n## Introducing Workshop\r\nThe place where content is produced, engineered and shipped. Vote for your favorite items and upload your creations while following our content posting guidelines. We have been using the [Fix Titan.TF](https://fix.titan.tf) platform for a really long time now and we enjoyed using it to track bugs and suggestions. We are now doing the same for workshop. The workshop runs on the same interface and user experience as what Fix Titan.TF had offered, with some slight variations.\r\n\r\n![image description](https://cdn.discordapp.com/attachments/512994272430260237/730019750674956368/unknown.png \"image title\")\r\n\r\n---\r\n\r\n### Fix Titan.TF\r\n#### Changes\r\n- Updated software to beta 13.\r\n\r\n- Updated home page layout to show tags as categories.\r\n![image description](https://cdn.discordapp.com/attachments/546260747634737162/729578660360617994/unknown.png \"image title\")\r\n\r\n### Community Servers\r\n#### Fixes\r\n- Fixed players turning invisible when switching from a custom skin to the default skin.\r\n\r\n- Attempted to fix the slow changing of maps.\r\n\r\n- Attempted to fix flooding of the database.\r\n\r\n### Website\r\n#### Fixes\r\n- Fixed category titles not redirecting to category pages in the help center. ]]></description>
        </item>
        <item>
            <title>Patch 2.1.91.1</title>
            <link>https://titan.tf/patch/2.1.91.1</link>
            <guid>https://titan.tf/patch/2.1.91.1</guid>
            <pubDate>Mon, 06 Jul 2020 05:24:30 +0200</pubDate>
            <description><![CDATA[ ### Community Servers\r\n#### Fixes\r\n- Fixed getting stuck in spectator more frequently than before.\r\n\r\n### Fix Titan.TF\r\n#### Changes\r\n- Changed site theme color from pink to green.\r\n\r\n- Updated about page contents. ]]></description>
        </item>
    </channel>
</rss>
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



