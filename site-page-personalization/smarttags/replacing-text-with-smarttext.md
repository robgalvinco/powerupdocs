# Replacing Text With SmartText

## Replacing SmartText in Simple text fields&#x20;

Site Builder sections that contain simple input settings for your text requires just a simple addition of SmartText in either an insert, replace or variant mode.&#x20;

For example, in the image below we show a settings group where Headings and Subheading is considered a simple text setting

![](<../../.gitbook/assets/Screen Shot 2022-02-04 at 10.01.39 AM.png>)

### How to replace SmartText in simple text settings

* [ ] Copy this text: `<smart text="Hey there {{first_name}}, ">` to your clipboard. Note it is slightly different than the snippet we used for [inserting SmartText](inserting-smarttext.md)
* [ ] Paste it into a simple text section on one of your site pages using Site Builder. Place it in the beginning of the area that you would like to replace.
* [ ] Replace the text inside the quote with the static text you would like to use as well as any SmartText Attributes you would like to use. If you need to include a quote in your text, then use a single quote instead.
* [ ] Move your cursor to the end of the text you would like to replace and paste or type this text: `</smart>` this will mark the end of the area that will be replaced
* [ ] Save your page

```
<smart text="Hey there {{first_name}}, you don't want to miss our free workshop ">
Join Our Free Workshop</smart>

User signed in => Hey there Sammie, you don't want to miss our free workshop
Not signed in (?first_name=Samantha) => Hey there Samamtha, you don't want to miss our free workshop
Not signed in => Join Our Free Workshop
```

## Using SmartText in the Rich Text editor (Site Builder and Text Lessons)&#x20;

Site Builder sections may have what is called a "Rich Text" editor. This is when you see a toolbar of icons that allows you to control the styling of the content (as shown below). Inserting SmartText using the rich text editor is handled a bit differently. It is recommended that you watch the demo video below.

![](<../../.gitbook/assets/Screen Shot 2022-02-04 at 10.00.01 AM.png>)

### How to use SmartText in the rich text editor

* [ ] Click the code icon in the tool bar \</> this will show you the html code that will be used
* [ ] Locate the position that you would like the SmartText to be inserted
* [ ] Copy this text `<span class="smarttext" data-text="Hey there {{first_name}}, ">` to your clipboard. Note this is slightly different than the snippet we used for [inserting SmartText.](inserting-smarttext.md#how-to-use-smarttext-in-the-rich-text-editor)
* [ ] Change the text and SmartText Attributes that are inside the quotes for the data-text section. Be sure to maintain the rest of the text including the quotes. If you need to include a quote in your text, then use a single quote instead.
* [ ] Move your cursor to the end of the text you would like to replace and paste or type this text: `</span>` this will mark the end of the area that will be replaced
* [ ] Click the code icon in the tool bar again \</> to return to the preview. Note: you will not see the SmartText be reflected in the Text Editor preview, but should see it previewed on the page.
* [ ] Save your page (or course curriculum settings if working in a text lesson)
