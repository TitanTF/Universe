# Fix Titan.TF

{% api-method method="get" host="https://fix.titan.tf/atom" path="/" %}
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
    <title><![CDATA[ New discussions in Fix Titan.TF ]]></title>
    <subtitle><![CDATA[ The newest discussions in the forum ]]></subtitle>
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
Recent Activity in Tag
{% endapi-method-summary %}

{% api-method-description %}
Get discussions in a tag based on the most recent activity.
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
    <title><![CDATA[ Activity in the pending tag ]]></title>
    <subtitle><![CDATA[ Last posts in the pending tag ]]></subtitle>
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

{% api-method method="get" host="https://fix.titan.tf/atom" path="/t/tag/discussions" %}
{% api-method-summary %}
New Discussions in Tag
{% endapi-method-summary %}

{% api-method-description %}
Get discussions based on the most recent activity.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="tag" type="string" required=false %}
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
    <title><![CDATA[ New discussions in the pending tag ]]></title>
    <subtitle><![CDATA[ The newest discussions in the pending tag ]]></subtitle>
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

{% api-method method="get" host="https://fix.titan.tf/atom" path="/d/discussion-slug" %}
{% api-method-summary %}
Recent Posts in Discussion
{% endapi-method-summary %}

{% api-method-description %}
Get recent posts in a discussion.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="discussion-slug" type="string" required=false %}
The discussion to retrieve
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
    <title><![CDATA[ Damage Opponents in Orange progress on Friendly Hit ]]></title>
    <subtitle><![CDATA[ Last messages in this discussion ]]></subtitle>
    <link href="https://fix.titan.tf/atom/d/190-damage-opponents-in-orange-progress-on-friendly-hit/" rel="self" />
    <link href="https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/" />
    <id><![CDATA[ https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/ ]]></id>
    <updated>2020-07-17T12:13:46+00:00</updated>
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
    <entry>
        <title><![CDATA[ Damage Opponents in Orange progress on Friendly Hit ]]></title>
        <link rel="alternate" type="text/html" href="https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/1" />
        <id>https://fix.titan.tf/d/190-damage-opponents-in-orange-progress-on-friendly-hit/1</id>
        <updated>2020-05-25T03:45:55+00:00</updated>
        <content type="html"><![CDATA[ <p>For the Orange King Job, as far as I tested, you gain progress towards 'Damage Opponents in Orange' when attacking friendlies. It makes progress incredibly easy to just slap one with a damage boosted weapon as they don't die and thus give full damage points towards the progress.<br> <a href="https://imgur.com/a/zIQRwoL" rel=" nofollow ugc">https://imgur.com/a/zIQRwoL</a><br> On further testing, it appears that it gives progress on any hit, regardless if the damage actually takes place, as in cases of both spawn invincibility and friendly.</p> <p>P.S. Job tag when?</p> ]]></content>
        <author>
            <name>MrHandler</name>
        </author>
    </entry>
</feed>
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

