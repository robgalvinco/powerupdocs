---
description: >-
  A universal lead capture super power that can be used with any Kit button.
  Works with Thinkific and 3rd party lead capture forms that provides embed code
  scripts.
---

# Funnel Kit Opt In

{% hint style="info" %}
**EXPERIENCE IT:**[ <mark style="color:orange;">**Head over to the demo page**</mark>](https://powerupkit.thinkific.com/pages/funnel-kit-opt-in-demo) **** and see this super power in action
{% endhint %}

### How to use this super power

#### 1) Add the Promo Kit Sections to the page

* [ ] Make sure you have the a **Kit PowerUp** installed into your site (ex: Promo Prep Kit)
* [ ] On a site page, add (or copy) the **Base kit Section** that is included with all of our Kit PowerUps. The Base Kit section contains the style choices that will be used on this page for all other Kit sections.&#x20;
* [ ] Add a section and search for **"Funnel Kit"** and add it to your page
* [ ] Add another Kit section that includes a button&#x20;

#### 2) Configure a Kit section with a button to use the Funnel Kit Opt In section

* [ ] Open up the **Button settings** inside the section you just added and make sure the setting is configured for _Funnel Kit Opt-in_

![](<../../.gitbook/assets/Screen Shot 2021-10-23 at 3.11.07 PM.png>)

#### 3) Configure the Funnel Kit Opt In settings

* [ ] Open up the Funnel Kit Opt In section settings
* [ ] Choose which type of Opt in to use. You can select Thinkific Lead Capture or use your own by providing the embed code from your CRM for the form you want to use. _if you are using your own CRM, then please consult their documentation for how to obtain the embed code. Once you have obtained it, paste it into the settings. If you are using Thinkific lead capture, then please configure the remaining settings._

![](<../../.gitbook/assets/Screen Shot 2021-10-23 at 3.16.27 PM.png>)



#### 3a) Using Thinkific Lead Capture

Funnel Kit Opt In section works similarly to the [standard Thinkific Lead Capture section](https://support.thinkific.com/hc/en-us/articles/360057435074) , except that it uses a popup that gets triggered by any Kit button instead. Be sure to take a look at Thinkific's guides on how this feature works.

* [ ] Configure the section settings that will be used for the popup including Headings, Button text and image&#x20;
* [ ] You will also need to configure the page that will be redirected to when the button is clicked **using the After Opt In settings**

#### 3b) Using a 3rd Party Lead Capture

In order to use a 3rd party lead capture form _(ex: Convertkit)_ with Kit, you must set up the form inside your providers platform tools. Then, you must obtain an "embed" code for that form. What we are essentially doing here is embedding your form into the Funnel Kit Opt In popup.&#x20;

* [ ] Make sure your have your Funnel Kit Opt In button settings to use ** **_**Custom (Embed)**_
* [ ] Then paste your embed code into the _**Custom Embed field**_

{% hint style="info" %}
When using a 3rd party embed code for your form, be sure to select an HTML version and not a Javascript version. Since we are presenting it in our own popup, this will ensure that it should function properly (just like as if it was embedded on a HTML page.



You also need to specify what happens after the form is submitted from within your CRM's settings. Typically, you would configure it so that the reader is sent to another page (ex: "Thank you....we emailed you some details...")
{% endhint %}



![](<../../.gitbook/assets/Screen Shot 2021-10-23 at 3.30.42 PM.png>)

#### 4) Preview and Test

After you have completed setting up the page, be sure to test the page outside of SiteBuilder.
