# Provably Fair

The provably fair system **only supports web-based casino games**. The goal of this system is to ensure the integrity of the result.

#### How It Works

* A server seed, public seed and the result is generated at the start of every round
* A sha256 hash is generated based on the `seeds, the result and the round number`
* The `hash` and `public seed` is visible to the everyone from the start of the round
* The hash can then be used to verify that the result was never changed \(_by regenerating a hash based on the seeds, result and round number\)_

{% hint style="info" %}
If the hash given at the start of the round and the hash generated after the round **MATCHES**, the round is verified to be legitimate and not manipulated. 🔑
{% endhint %}

**All web-based games are supported except lottery.** An attempt was made to implement this to the lottery system at launch, but was not viable due to the way the participant pool works.

