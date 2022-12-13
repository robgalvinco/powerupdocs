---
description: >-
  This section is required and will contain the basic information that most of
  the designs will use. Place this section on your page above all other SNAP
  sections
---

# SNAP Course Information ✍️

![](https://import.cdn.thinkific.com/164072/courses/1916044/SnapSectionThumbnails1-220628-162728.jpg)

{% hint style="danger" %}
**This section must exist on the page and also be placed above other SNAP sections**
{% endhint %}

{% embed url="https://www.loom.com/share/6cf0d315c8394e95b23b9d83367c20bb" %}

### Using the SNAP Course Information Section

* [ ] Go to your list of Site Pages in your site and look for a course page that you want to add SNAP to. _Course pages are only supported for this SNAP PowerUp. Additional page templates for other page types will be provided in the future_
* [ ] Add a section by searching for SNAP Course Information. Place it above other sections (we recommend that this be the very first section on the page so that it performs the best)
* [ ] Add a [SNAP Design section](../snap-design-templates/) to the page so you can see how the information changes when you are editing the page. Don't worry which design you will use for now, you can always change out the design in a "Snap"
* [ ] Open the SNAP Course Information settings and enter your text, images, etc. See the details below on the options



## Pricing & Buttons Settings Group

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T111228.647.png>)

This settings group will control how your pricing and main calls to action will be displayed and effected. In many of the designs there will be a primary and secondary call to action as well as a way to indicate that there is a sale for the current price.

* **Price & Main CTA Button :** this controls what is used for the price, primary button text and link
  * _Auto_ : this will cause the primary button to use the link to the default price for the course. The price will be shown based on the courses default price settings. The primary button text will also be the default button text based on the price setting. This is the default option
  * _Custom_ : allows you to over-ride the price, primary button text and link used:
    * **Custom Price** - this text will be displayed in the price area of the design when Custom is chosen
    * **Custom CTA Text** - this text will be displayed in the primary button text of the design when Custom is chosen
    * **Custom CTA Page** - this will be the link that the primary button is used when custom is set
* **Use Price Subheading?** - when checked it will enable some subheading text to be displayed around the call to action buttons.&#x20;
  * **Price Subheading** - this is the test that will appear around the call to action buttons. For example: "Sale ends Sep 22"
* **Secondary CTA** - the secondary call to action is a second button that will appear based on the settings below.
  * _Auto (Free Trial)_ - if the course has a free preview lesson, then this option will be shown
  * _Custom_ - when this option is selected it will activate the custom page and text that is used for the second button. When enable it will always show.
    * **Custom Secondary CTA Page** - the link to use for the secondary button
    * **Custom Secondary CTA Text** - the text to use for the secondary button
    * **When to Hide Custom Secondary CTA** - this controls automatic hiding of the secondary button when it is a 'Custom' type
      * _User is enrolled in this course_ - will hide the secondary button if the user is enrolled in the course
      * _User is enrolled in another product_ - will hide the secondary button if the user is enrolled in the product selected
        * **'Other product' Enrollment Check** - choose the product (bundle or course)

{% hint style="info" %}
The primary and secondary buttons will inherit the style that you have selected in your Theme settings.
{% endhint %}

## Sale Settings Group

{% embed url="https://www.loom.com/share/61aea56560f54668bec4589d70ef2063" %}

This settings group controls the sale feature of SNAP which also includes a countdown timer.



**On Sale?** - when checked this will activate the "on sale mode" of the design and use the sale information below. <mark style="color:red;">This will effect the primary button link - so be sure to configure this properly</mark>

* **Sale Price -** select alternate price for the same course. This will cause the sale price to be displayed in the main price section of the design and put the default price in the "strikeout" area of the price.

![](<../../.gitbook/assets/Screen Shot 2022-07-28 at 5.20.22 PM.png>)

* **Customized Regular Price:** This will over ride the strikethrough price text. When left blank, the text will be the default price of the course
* **Automatically End Sale?** - When enabled, this will automatically remove the sale information on the page and reset the Primary CTA button (link and text0 back to the default. So this way you do not have to remember to manually edit the page.&#x20;

{% hint style="warning" %}
Be sure to set the date and time in the _**Return to normal price on date and time setting**_ to a day in time in UTC. Your website visitors will see the proper countdown for their location. You can [search Google for "UTC Convertor"](https://savvytime.com/converter/utc) to get the proper time.
{% endhint %}

* **Saving Text** - This is manually entered and meant to reflect the savings ex: "Save 50%
* **Countdown Heading and Labels** - this is used in the SNAP Design Templates where the countdown is shown. _Be sure to set the labels for days,hours, minutes, seconds for your locale. In some designs the area to display this is small, so try to abbreviate as possible._

{% hint style="warning" %}
When changing the countdown timer date, you may not see it reflected until you refresh the page
{% endhint %}

## **Quick Attributes Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T110041.623.png>)

The quick attributes offers a way for your website readers to quickly understand key information about your course. Each attribute contains an icon, heading and sometimes a subheading. The [SNAP Design Section](../snap-design-templates/)  will determine what information it will use.

* **Icon List Heading** - this will set the text that is used for the heading of this section
* **List Icons** - [Font Awesome 6 Pro](https://fontawesome.com/icons) icon codes to be copied and pasted. Be sure to place an icon code on a single line and have the same number of items in the below settings
* **List Text (Heading)** - Put in your text for this attribute. You can also use some "Smart Attributes" that will get replaced by the course information automatically
  * Smart Attributes: \[VIDEO TIME] \[LESSON COUNT] \[INSTRUCTOR NAME] \[PDF COUNT] \[QUIZ COUNT] \[DOWNLOAD COUNT]
* **List Text (Sub Heading)** - This is intended to be a short suheading for the corresponding item. It is usually used in designs that contain larger icon list page elements
* **Course Includes Heading** - This lis the heading for the Includes text list. This is just another way to indicate what the coutse includes but to use a checklist instead of custom icons and text
* **Course Includes List Text** - a short (few words) text listing. One line of text will equal one item on the list. Note: in Site Builder it may "look" like two lines depending on the length of text used.

{% hint style="info" %}
These are meant to be short and sweet. Do not get too wordy as it may not "work" in the design and also mis-uses the intention of this being "quick for your readers to read"
{% endhint %}

## Banner **Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T111357.935.png>)

The Banner settings control the "main" headline and subheadline of the design. It defaults to use the course name and description, but can be changed to anything.

* **Heading** - enter in what you would like to display or use the SmartText: **\[COURSE NAME]** to automatically inject the course name.
* Sub Heading - enter in what you would like to display or use the SmartText: **\[COURSE DESCRIPTION]** to automatically inject the course description that is set from your course settings page.

## Images **Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T111918.034.png>)

This setting grouo will provide the main images to be used on the [SNAP Design page template](../snap-design-templates/)

* **Use Course Image** - when enabled the course card image will be automatically used for the design section that is displaying the course image thumbnail.
* **Alternate Image** - when Use Course Image is unchecked, this image will be used instead.
* **Banner Image**  - when the design calls for a banner image, then this image will be used.

## Video:fire: **Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T112259.156.png>)

A video on your course page will definitely increase your conversion rates, because you can show so much more information in a controlled way that keeps your website visitors attention on you and your page longer.

* **Use Preview Video** - when checked this will enable the video feature of the SNAP Design page template. <mark style="color:red;">You must also provide your video information below</mark>
  * **Video Type** - choose the type of video you would like to use
    * _Thinkific or Youtube_ - when selected, an option to select the video from the Thinkific video library will be show or you can provide a Youtube link
    * _Loom_ 🔥 - We love Loom because it increases conversions by providing an animated GIF of the video without the user having to do anything, and it also allows the user to leave emoji reactions and comments (which helps with automatic social proof). Anyways.... Record or Upload your video to Loom.com, then copy and paste the embed code (not the link to the video)
    * _None_ - wil not show any video
    * _Custom_ - provide a responsive embed code from your video platform provider of choice ex: Wistia, Vimeo, etc.
  * **Video** - used when Thinkific Video type is selected
  * **Custom Video Embed or Loom Embed** - paste in your custom video embed code (make it responsive if it is not already) or the embed code for the Loom video
  * **Hide Loom Top bar? -** when checked this will hide the Loom branding (recommended)

![](<../../.gitbook/assets/Untitled design (8).gif>)

{% hint style="info" %}
The SNAP Design page will determine how to use the video and often will provide options to have the video display in popup mode or inline mode. That option will be found inside the SNAP Design section
{% endhint %}

## Course Overview **Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T115318.096.png>)

The course overview section is a generic section that is used to describe your course and give a deeper summary in text form of what it is. It contains three pieces of information

* **Section Heading** - simple text field for the title of the section
* **Section Sub Heading** - simple text field for the subheading of the section
* **Summary** - rich text field for the summary portion of this section. you can use colors, lists, images, etc to make this area interesting.

## Requirements **Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T115624.608.png>)

This section gives you the opportunity to provide a checklist of items that the student may need in order to take this course.&#x20;

* **Heading** - simple text entry field for the title of this section
* **Summary** - rich text field for the summary portion of this section. you can use colors, lists, images, etc to make this area interesting.
* **List** - a list of sentences that will appear in a checklist. Put an entry on each line. Be aware that Site Builder does not "scroll" this entry field, so a long line of text on "one actual line" appears like it is on many lines. Be sure to check the preview to make sure there are no "extra checkmarks"

{% hint style="info" %}
This section can really be used for anything and just give you another section that contains a check lists. The design will determine the location of this section and you will have the opportunity to hide this section with a setting from the SNAP Design Page template
{% endhint %}

## Who is this course for **Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T120632.773.png>)

This section gives you the opportunity to provide information about who this course is really for. This is especially helpful in raising your sales conversion rate.

* **Heading** - simple text entry field for the title of this section
* **Summary** - rich text field for the summary portion of this section. you can use colors, lists, images, etc to make this area interesting.
* **List** - a list of sentences that will appear in a checklist. Put an entry on each line. Be aware that Site Builder does not "scroll" this entry field, so a long line of text on "one actual line" appears like it is on many lines. Be sure to check the preview to make sure there are no "extra checkmarks"

{% hint style="info" %}
This section can really be used for anything and just give you another section that contains a check lists. The design will determine the location of this section and you will have the opportunity to hide this section with a setting from the SNAP Design Page template
{% endhint %}

## What you will learn **Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T120559.148.png>)

This section gives you the opportunity to quickly show what the major outcomes will be for the course

* **Heading** - simple text entry field for the title of this section
* **Summary** - rich text field for the summary portion of this section. you can use colors, lists, images, etc to make this area interesting.
* **List** - a list of sentences that will appear in a checklist. Put an entry on each line. Be aware that Site Builder does not "scroll" this entry field, so a long line of text on "one actual line" appears like it is on many lines. Be sure to check the preview to make sure there are no "extra checkmarks"

{% hint style="info" %}
This section can really be used for anything and just give you another section that contains a check lists. The design will determine the location of this section and you will have the opportunity to hide this section with a setting from the SNAP Design Page template
{% endhint %}

## Curriculum **Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T120756.409.png>)

This setting group will control the information that is used in the auto-generated curriculum section of the SNAP Design Page Template

* **Heading** - the text used for the section heading
* **#Lessons Heading** - the text that is displayed _after_ the number of lessons (auto generated)
* **Course Duration** - freeform text that will be used for course duration
* **Show Chapter Duration** -when enabled it will show the chapter time in the SNAP Design page template. This only works automatically if you have Thinkific video lessons

![](<../../.gitbook/assets/Screen Shot 2022-07-13 at 12.14.51 PM.png>)

## Reviews **Settings Group**

![](<../../.gitbook/assets/Site Builder \_ Thinkific (28).png>)

* **Automatically show approved reviews** - when enabled the SNAP Design Page template will show up to 100 approved reviews. It also controls if review summaries are shown in the design.
* **Heading** - the text to be used as the heading for this section
* **Hide Review Sections If None?** - When enabled, the reviews section in the SNAP Design page template will be hidden if there are no reviews (recommended)

## Instructor **Settings Group**

![](<../../.gitbook/assets/Site-Builder-Thinkific - 2022-07-13T121930.642.png>)

{% hint style="info" %}
Are you looking to display multiple instructors? Be sure to add the [SNAP Instructors section](snap-instructors.md) to the page and add the list of instructors to show
{% endhint %}

The Instructor settings will control what instructor is shown on the main instructor sections of the SNAP Design page. By default, the associated course instructor will be shown

* Heading - the text for the section heading
* Use Alternate Course Instructor? - when enabled, an alternate instructor can be chosen
  * Alternate Instructor (1) - Choose an alternate instructor you wish to use
* Link Bio Read More - This is the text that will be used to expand the bio section when the instructor bio is "too long"&#x20;
* Link Bio Read Less - This is the text that will be used to collapse the bio section when the instructor bio is "too long"&#x20;

{% hint style="info" %}
The SNAP Design Page determines the location of the instructor and may display it in multiple places. You will have options to disable or change this inside the SNAP Design section settings.
{% endhint %}
