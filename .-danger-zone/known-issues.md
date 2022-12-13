---
description: Life is not perfect and neither are apps
---

# Known issues

### Quiz and Survey lessons are not triggering popups

plaYEAH! relies on [events that occur from Thinkific's course player](https://support.thinkific.com/hc/en-us/articles/360030725813). Currently there is a known issue where quiz and survey lessons are not triggering the "complete" event. So this means if your course ends in a quiz or if you are targeting quiz lessons individually, then plaYEAH! will not be able to show the pop. We are working with Thinkific to see if this issue can be addressed in their course player.

{% hint style="success" %}
**What you can do to work around this issue:**

* Set the targeting settings to be show in a percentage that is a bit smaller
* Target the next lesson in the course
* Add another lesson so that a progress event occurs
* Don't target specific a quiz or survey lesson type.
{% endhint %}
