# Fix Titan.TF

{% api-method method="get" host="https://fix.titan.tf/atom" path="" %}
{% api-method-summary %}
Recent Activity
{% endapi-method-summary %}

{% api-method-description %}
Get discussions based on the most recent activity.
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
    <title><![CDATA[ Fix Titan.TF ]]></title>
    <subtitle><![CDATA[ Last posts in the forum ]]></subtitle>
    <link href="https://fix.titan.tf/atom/" rel="self" />
    <link href="https://fix.titan.tf/" />
    <id><![CDATA[ https://fix.titan.tf/ ]]></id>
    <updated>2020-07-17T10:34:12+00:00</updated>
    <entry>
        <title><![CDATA[ Damage Opponents in Orange progress on Friendly Hit ]]></title>
        <link rel="alternate" type="text/html" href="https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/2" />
        <id>https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/2</id>
        <updated>2020-05-26T16:20:32+00:00</updated>
        <content type="html"><![CDATA[ <p>This is a known issue and we are currently looking into this.</p> ]]></content>
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

{% api-method method="get" host="https://fix.titan.tf/atom" path="/discussions" %}
{% api-method-summary %}
New Discussions
{% endapi-method-summary %}

{% api-method-description %}
Get the latest discussions.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Returns a XML feed on success.
{% endapi-method-response-example-description %}

```markup
<feed xmlns="http://www.w3.org/2005/Atom">
    <title><![CDATA[ Fix Titan.TF ]]></title>
    <subtitle><![CDATA[ Last posts in the forum ]]></subtitle>
    <link href="https://fix.titan.tf/atom/" rel="self" />
    <link href="https://fix.titan.tf/" />
    <id><![CDATA[ https://fix.titan.tf/ ]]></id>
    <updated>2020-07-17T10:34:12+00:00</updated>
    <entry>
        <title><![CDATA[ Damage Opponents in Orange progress on Friendly Hit ]]></title>
        <link rel="alternate" type="text/html" href="https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/2" />
        <id>https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/2</id>
        <updated>2020-05-26T16:20:32+00:00</updated>
        <content type="html"><![CDATA[ <p>This is a known issue and we are currently looking into this.</p> ]]></content>
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

{% api-method method="get" host="https://fix.titan.tf/atom" path="/t/tag" %}
{% api-method-summary %}
Last Tag Discussions
{% endapi-method-summary %}

{% api-method-description %}
Get the latest discussions from a tag.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="tag" type="string" required=true %}
The discussion tag to retrieve
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
    <title><![CDATA[ Fix Titan.TF ]]></title>
    <subtitle><![CDATA[ Last posts in the forum ]]></subtitle>
    <link href="https://fix.titan.tf/atom/" rel="self" />
    <link href="https://fix.titan.tf/" />
    <id><![CDATA[ https://fix.titan.tf/ ]]></id>
    <updated>2020-07-17T10:34:12+00:00</updated>
    <entry>
        <title><![CDATA[ Damage Opponents in Orange progress on Friendly Hit ]]></title>
        <link rel="alternate" type="text/html" href="https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/2" />
        <id>https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/2</id>
        <updated>2020-05-26T16:20:32+00:00</updated>
        <content type="html"><![CDATA[ <p>This is a known issue and we are currently looking into this.</p> ]]></content>
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

