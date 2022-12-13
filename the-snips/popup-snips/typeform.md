---
description: PU-001
---

# Typeform

**Adding this Player Snip**

* [ ] On your [`My Player Snips Page`](../../how-to-guides.md#how-to-create-a-my-snips-page) add the **`PU-001`** section to your page
* [ ] **Open up the section's `Trigger` settings group** and choose if you want the effect to show when the lesson is completed or the lesson is started&#x20;
* [ ] Open the **`Typeform settings group`** and update the settings
  * [ ] Typeform Id : Make sure you have your Typeform form published  and then paste in the Typeform form id . Check the instructions below on how to get the Typeform ID
  * [ ] Select the Type option:
    * [ ] Slider : will open a popup that slides in from the right side of the screen. The student will be able to close this popup
    * [ ] Popover : will create a floating icon in the lower right corner that will remain open once it is displayed. The student will not be able to close this once it is open.
    * [ ] Popup : will open a large popup window. The student will be able to close this Typeform.
    * [ ] Sidetab : will open a "drawer" with a button. The button will be always visible once it is open. The student will not be able to close it.
  * [ ] Button Color: the color of the button (Side tab and Popover)
  * [ ] Button Icon: the text that will be shown for the button (Side tab and Popover)
* [ ] Hover over the section and click on the **`Show Effect`** button to preview what the Player Snip will look like
* [ ] Hover over the section and click the **`Copy Player Snip`** button
* [ ] In another tab **open your course curriculum** and find the lesson you wish to place this Player Snip into
* [ ] Put your cursor in the location that you wish to place this snippet&#x20;
* [ ] Open up the < > code viewer
* [ ] Paste the snippet
* [ ] Click the < > code button to return to the normal preview
* [ ] Click Save to save the lesson
* [ ] Preview the lesson inside the course player

{% hint style="info" %}
It is recommended to place this snippet at the bottom of the code view. When not in code view it is invisible and could potentially be removed by accident. Be sure be careful when editing content around this Player Snip
{% endhint %}

**How to get the Typeform ID**

<figure><img src="../../.gitbook/assets/Screen Shot 2022-11-09 at 10.35.43 AM.png" alt=""><figcaption></figcaption></figure>

## Hidden Fields

This Player Snip will automatically pass the students First Name, Last Name, Email as [hidden Typeform Fields](https://www.typeform.com/help/a/using-hidden-fields-360052676612/). These fields can be used to personalize the questions that is shown in the form, or can be used as data fields that gets captured in the responses. Typeform does not use these hidden fields in the actual form fields. Be sure to read how to use Type Form Hidden fields: [https://www.typeform.com/help/a/using-hidden-fields-360052676612/](https://www.typeform.com/help/a/using-hidden-fields-360052676612/)

{% embed url="https://www.loom.com/share/1bc300caf3b147e0a39c46fdb3d262f3" %}
\

{% endembed %}

### How to Use Hidden Fields:

* [ ] On your Typeform, add the following hidden field names
  * [ ] first\_name
  * [ ] last\_name
  * [ ] email
* [ ] In your Typeform questions you can add this information in the question using the @first\_name smart text
* [ ] Player Snips will automatically send these hidden fields
