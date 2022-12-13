# Using SmartText with Variations

You can use both [insert](smarttags/inserting-smarttext.md) and [replace](smarttags/replacing-text-with-smarttext.md) strategies with Variations, by passing in an additional query parameter to set the variation&#x20;

{% embed url="https://www.loom.com/share/452155b40ac2485aaee5ab5159fb3446" %}

### How to use variations in Simple Text fields

1. You must first supply a SmartLink that contains the variation parameter to your user either by sharing directly or through email. Once that link is clicked, we save information in their browser so we can use this variation in the future
2. Inside your SmartTags, be sure to include text-2 and text-3 attributes to indicate the alternative SmartText

```
<smart text="Hey there {{first_name}}, " 
           text-2="{{first_name}}, " 
           text-3="{{first_name}} Don't miss this!! "/>Join Our Free Workshop
           
https://yoursite.thinkific.com?v=1 => Hey there Sammie, Join Our Free Workshop

https://yoursite.thinkific.com?v=2 => Sammie, Join Our Free Workshop

https://yoursite.thinkific.com?v=3 => Sammie Don't miss this!!  Join Our Free Workshop


```

{% hint style="info" %}
Once a Variation version is passed in via a query parameter, it will remain the the users browser storage until they clear it (or it is changed by you with another link). This is helpful when you want to test out different page content for types of users
{% endhint %}



### How to use variations in Rich Text fields

* [ ] Click the code icon in the tool bar \</> this will show you the html code that will be used
* [ ] Locate the position that you would like the SmartText to be inserted
* [ ] Copy this text `<span class="smarttext" data-text="Hey there {{first_name}}, " data-text-2="{{first_name}}, " data-text-3="{{first_name}} Don't miss this!! ">.</span>` to your clipboard
* [ ] Change the text and SmartText Attributes that are inside the quotes for the data-text section. Be sure to maintain the rest of the text including the quotes. If you need to include a quote in your text, then use a single quote instead.
* [ ] Click the code icon in the tool bar again \</> to return to the preview. Note: you will not see the SmartText be reflected in the Text Editor preview, but should see it previewed on the page.
* [ ] Save your page (or course curriculum settings if working in a text lesson)

```
<span class="smarttext" data-text="Hey there {{first_name}}, " 
           data-text-2="{{first_name}}, " 
           data-text-3="{{first_name}} Don't miss this!! ">.</span>
           Join Our Free Workshop
           
https://yoursite.thinkific.com?v=1 => Hey there Sammie, Join Our Free Workshop

https://yoursite.thinkific.com?v=2 => Sammie, Join Our Free Workshop

https://yoursite.thinkific.com?v=3 => Sammie Don't miss this!!  Join Our Free Workshop

```
