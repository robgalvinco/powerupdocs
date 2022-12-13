# Popup Visibility Settings

Popups have been around for a long time and your website visitors have undoubtably, seen a few before. And guess what? They "hate" them...why? Because most website owners don't know how to set them up properly.

### When Popups Are Poorly Executed:

* **When popups immediately show when the page initially loads**, it's like knocking on your neighbor's front door and they start yelling at you. Your website visitor will close your popup right away - _even if they actually want to read it. <mark style="color:orange;">With Kit, you can control a delay time on when the popup appears.</mark>_
* **When a popup takes over the whole page in an instant**, it can certainly focus the attention of your reader, but it can also make them not want to read it. <mark style="color:orange;">That is why in Kit, we have a variety of "just the right sized" unobtrusive popups that more pleasantly appear with gradual animated effects.</mark>
* When a popup just keeps popping, it get's annoying really quickly. Kind of like that long ride with your kids "Are we there yet?? Are we there yet?? Are we there yet???". <mark style="color:orange;">With Kit, you will have control over how long and how often any Kit popups will appear</mark>

### Kit Popup Settings

![](<../../.gitbook/assets/Screen Shot 2021-10-23 at 4.02.02 PM.png>)

#### Delay to appear

This setting controls how long the website reader should be on the page before the popup is shown. This may depend on a few factors - but generally you should think about how "warm" your audience is, what is on the page, how much to they typically have to read. Then adjust your delay accordingly. For smaller size "sticky' popups - it may be very well ok to have a zero delay, but for larger popups, we strongly urge you to have a few seconds delay. It may seem small, but it makes a huge difference.

#### Max number of tries / Max number of times displayed

This type of setting is for how many times the popup should be shown to the user. The way that Kit determines this is by referring to the particular popup by the **Promo Id** that you provide. We will save a browser cookie with a count of how many times that particular popup with that Promo id is shown. if it exceed the limit than it will not be shown.

This setting will be ignored if the **Show the popup always is set**

![](<../../.gitbook/assets/Screen Shot 2021-11-10 at 5.34.30 PM.png>)

****

{% hint style="info" %}
If the user clears their browser or uses another browser/device - they may see the popup again.
{% endhint %}

#### Promo Id

When we track details about the Kit popup being shown we will group the information by the Promo Id field. We default this to the name of the Kit Promo, but you may consider changing it to ensure your popups across your site are behaving the way you want them.

_For example, let's say you want to use the_ [_<mark style="color:orange;">Scratch Off Promo</mark>_](../../kit-powerups/promos-kit/02-scratch-and-win.md) _on one of your courses and offer a certain set of prizes. But on another course page, you want to use the same type of Scratch Off Promo and have a different set of prizes. if you wanted your readers to only have **"one chance"** at any of these, then you would **use the same Promo Id** on both pages. If you wanted your readers to have once change for a coupon on course one, and **another chance** for a coupon on course two, then you would specify **different Promo Id** values._
