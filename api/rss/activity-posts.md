# Activity Posts

{% api-method method="get" host="https://titan.tf/rss\_activity" path=" " %}
{% api-method-summary %}
Recent Posts
{% endapi-method-summary %}

{% api-method-description %}
Get the 5 latest activity posts.
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
        <title>Titan.TF - Activity Posts</title>
        <link>https://titan.tf/activity</link>
        <description />
        <atom:link href="https://titan.tf/rss_activity.php" rel="self" type="application/rss+xml" />
        <item>
            <title>Antinomy</title>
            <link>https://titan.tf/posts/6781</link>
            <guid>https://titan.tf/posts/6781</guid>
            <pubDate>Fri, 17 Jul 2020 09:24:24 +0200</pubDate>
            <description><![CDATA[ kill me ]]></description>
        </item>
        <item>
            <title>I </title>
            <link>https://titan.tf/posts/6773</link>
            <guid>https://titan.tf/posts/6773</guid>
            <pubDate>Wed, 15 Jul 2020 14:13:14 +0200</pubDate>
            <description><![CDATA[ pootis ]]></description>
        </item>
        <item>
            <title>myst@titan.tf</title>
            <link>https://titan.tf/posts/6772</link>
            <guid>https://titan.tf/posts/6772</guid>
            <pubDate>Wed, 15 Jul 2020 13:42:28 +0200</pubDate>
            <description><![CDATA[ # \"Later\" means sometime before you die. ]]></description>
        </item>
        <item>
            <title>myst@titan.tf</title>
            <link>https://titan.tf/posts/6771</link>
            <guid>https://titan.tf/posts/6771</guid>
            <pubDate>Wed, 15 Jul 2020 06:16:42 +0200</pubDate>
            <description><![CDATA[ Don\'t forget we are still in the middle of a pandemic and will remain for a while. ]]></description>
        </item>
        <item>
            <title>Poot Man | Titan.tf</title>
            <link>https://titan.tf/posts/6768</link>
            <guid>https://titan.tf/posts/6768</guid>
            <pubDate>Tue, 14 Jul 2020 14:13:59 +0200</pubDate>
            <description><![CDATA[ Ok... I wanna know when I joined Titan.tf. Is there an about when i joined? ]]></description>
        </item>
    </channel>
</rss>
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Could not find a cake matching this query.
{% endapi-method-response-example-description %}

```
{    "message": "Ain't no cake like that."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



