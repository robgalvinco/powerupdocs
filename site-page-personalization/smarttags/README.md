---
description: Add SmartTags to you site pages to instantly deliver a personalized experience
---

# SmartTags

{% embed url="https://www.loom.com/share/1bd9e0a56d764e9e8c88782b46a77555" %}

## What are SmartTags

SmartTags can be placed in your Site Pages as well as inside your Course Text and Video lessons. When the page loads, the SmartText PowerUp will scan your page and will either insert, replace of do nothing depending on the scenario and SmartTag options used.

### How to Use SmartTags

1. Locate the page and section inside of Site Builder that you would like to have SmartText placed.
2. Determine if it is a "Simple text" or "Rich text" input setting
3. Determine if you want to [insert](inserting-smarttext.md) the SmartText or [replace](replacing-text-with-smarttext.md) a block of text
4. Insert your SmartTag in the section settings. You can manually type this or copy and paste examples from either the SmartTags Helper section or the examples covered in the online guides. ex: `<smart text="Hey there {{first_name}}, "/> Join our Free Workshop`
5. Save your page and preview&#x20;

### SmartTag Modes

* ****[**Insert**](inserting-smarttext.md): This will insert your SmartText that is included in the SmartTag into the location that you have placed the SmartTag. This is helpful when you simply want to add text to the page
* ****[**Replace**](replacing-text-with-smarttext.md#replacing-smarttext-in-simple-text-fields): This will replace the contents that the SmartTag is surrounding with the SmartText that is included in the SmartTag. This is helpful when you may want to rephrase the entire sentence instead of just adding to it.
* **Do Nothing**: If the SmartText that will be used for the insert or replace operation is not fully replaceable for the given scenario, then nothing will happen and the default text will be used. For example, if the SmartText contains \{{first\_name\}} but the user has never logged in, then the SmartText will be ignore.&#x20;

### SmartTag Anatomy

The SmartTag contains different elements to indicate when it should be active, static and dynamic text to be used as well as possible variations

{% hint style="info" %}
The examples below show an insert approach using a simple text field. There are variations of this for [replacing text](replacing-text-with-smarttext.md) that are not shown. Also the samples below do not exactly apply as is for using SmartText in a [Rich Text Editor](inserting-smarttext.md#how-to-use-smarttext-in-the-rich-text-editor). Please review the appropriate guides.
{% endhint %}

**Simple Insert Example:**

`<smart text="Hey there {{first_name}}, "/> Join our Free Workshop`

In the example above, we have a few elements

* **SmartTag** - when we refer to the "SmartTag" we are talking about the entire element. When [replacing text](replacing-text-with-smarttext.md), there are two SmartTags, one that indicates where the replacement starts, and the second indicates where the replacement ends.
* **Static SmartText** - "Hey there" is called Static SmartText and will only be shown if the SmartTag is going to be displayed
* **Dynamic SmartText**- "\{{first\_name\}}" will be replaced by the users first name. You could also use up to 5 custom user attributes.
* **Permanent Text** - "Join our Free Workshop" will always be shown regardless
