---
description: >-
  This superpower section actually contains multiple superpowers all rolled into
  one
---

# Expiring Courses Widgets

## Overview

* Add this section to the Student Dashboard page by searching for "Expiring Courses Widgets"
* Only one of these sections should be use on the page

### Restriction

![](<../.gitbook/assets/Screen Shot 2022-03-18 at 1.38.12 PM.png>)

When Expiring Course Saver is added to your Student Dashboard page, it will automatically become activated for all conditions of expiring (actual expiration, payment plans and product subscriptions). In some cases you may only want the Expire Course widget to be active for certain types of students. To help control this, you would change the _"When to restrict activating this widget"_ and also the _"Enrollment Check"_ settings:

![](<../.gitbook/assets/Screen Shot 2022-03-18 at 1.41.33 PM.png>)

* **When to restrict activating this widget:**
  * **None**: There will not be a restriction for activating this widget
  * **Enrolled In**: The widget will only be shown to those enrolled in a course or bundle selected in the next setting
  * **Not Enrolled In**: The widget will only be shown to those not enrolled in a course or bundle selected in the next setting
* **Enrollment Check:** Select a course that will be checked for enrollment status

{% hint style="info" %}
Scenario: You have a membership bundle called "All You Can Chew" and it is a subscription based product. Normally what Thinkific does in this case is set an "expiration" for each renewal period and then when the payment goes through, it extends the expiration. In this case, you may not want to warn people that their course is "expiring".  You may also have a course called "Dog Trainer Certification" and has an expiration of one year.



If you only wanted to have the Expiring Course Widget appear for just the students who are enrolled in the individual course, then you would set:\
\
_**`When to restrict activating this widget: Not Enrolled In`**_

_**`Enrollment Check: All You Can Chew`**_




{% endhint %}



### Widget Style

![](<../.gitbook/assets/Screen Shot 2021-12-15 at 9.45.06 AM.png>)

* [ ] Enable or Disable this superpower section by checking or unchecking the Enable This? setting
* [ ] Choose the widget style from the drop down that will use one of the [widget styles shown on this page](expiring-courses-widgets.md#widget-style)
* [ ] Optionally change the color settings to be used for the background and text
* [ ] Optionally change the warning text color used for the [Expiring Text settings](expiring-courses-widgets.md#thinkific-course-cards)
* [ ] Optionally change the [call to action button](expiring-courses-widgets.md#call-to-action) color as well (by default the button will use the Theme primary button colors found in Theme Settings

{% hint style="info" %}
The colors for the buttons are controlled from the standard Thinkific theme settings
{% endhint %}

### Headings

The headings settings group controls the text that is being used in the widgets

![](<../.gitbook/assets/Screen Shot 2021-12-03 at 1.53.05 PM.png>)

* [ ] The **Heading** setting is used in most of the widgets as the title of the widget. It supports "Smart Tags" where entering `[NAME]` will show the signed in student name.
* [ ] The **Summary (One course Expiring)** setting will be used when the student only has one course that is expiring. This setting supports "Smart Tags":
  * [ ] \[COURSE] will be replaced by the name of the course that is expiring
  * [ ] \[EXPIRE ON] will be be replaced by the date that the expiration will occur
* [ ] The **Summary (Many courses Expiring)** setting will be used when the student has many courses that are expiring. This setting supports "Smart Tags"
  * [ ] \[NUM EXPIRING] will be replaced by the number of courses (just the number)

### Call to Action

This setting group is used to set the link that the button will use as well as the text that will be displayed on the button.

![](<../.gitbook/assets/Screen Shot 2021-12-03 at 1.58.44 PM.png>)

* [ ] Set the Button Text to your desired text
* [ ] Choose a Page Url to be used for the button

### Popup Images

This setting group is used to set the images that are used on some of the widget types.

![](<../.gitbook/assets/Screen Shot 2021-12-03 at 2.43.44 PM.png>)

For Widget styles that use an "avatar" ex: styles 01, 04 - the image and text in the image and avatar settings will be used.&#x20;

{% hint style="warning" %}
The avatar image must have a 1:1 ratio for the size. Otherwise the image may appear distorted. Please use the suggested size: 170x170px
{% endhint %}

![](<../.gitbook/assets/Site-Builder-Thinkific - 2021-12-03T144644.462.png>)

For all widgets that have a "main image", by default a course card image will be used. In the case of one expiring course, the image of the course will be used. In the case of multiple expiring courses, one of the images from the list of expiring courses will be used.

If you prefer to always use a certain image for all scenarios, then you would uncheck the **Use Course Card Image** setting and then upload an image.

![](<../.gitbook/assets/Screen Shot 2021-12-03 at 2.48.06 PM.png>)

### Widget Location

The reminder widget can appear in 4 different locations (desktop). For styles that are using a "bar" the number of locations are actually two. ex: style -07 - Bar with button : the "Left and Right" aspects of the setting is ignored. For style 09 - Large Side Panel, the "Top and Bottom" aspects of the setting is ignored.

![](<../.gitbook/assets/Screen Shot 2021-12-03 at 2.51.13 PM.png>)

### Widget Visibility

If you would like to only show these warnings at certain times prior to expiration (ex: only show a warning if the course will expire in 7 days), then you would select the `Certain # of Days before` option in the `When to show warnings` setting as well as enter the `Number of Days to Warn`

![](<../.gitbook/assets/Screen Shot 2021-12-03 at 2.57.30 PM (1).png>)

The warning popups can also be set to appear after a short delay by specifying the `Delay to appear` setting.

{% hint style="info" %}
The Widget Visibility settings will control both the Widget Popup as well as the warning text that appears on the course card. They will be displayed every day in that range. For example if I choose '7' days to warn, you would see the widget and the warning text for days 7-1 before expiration.
{% endhint %}

### Thinkific Course Cards

To help your students understand when the courses will be expired (or renewed in the case of subscriptions) you can have the expiration date appear on the course card by enabling the **Expiring Text** setting as well as the Expiring Text setting.

![](<../.gitbook/assets/Site-Builder-Thinkific - 2021-12-03T150108.321.png>)

{% hint style="warning" %}
If you have a "subscription" product, courses will appear as "expiring" on the renewal date. This is how Thinkific manages their subscriptions. It is important to make sure you understand this and choose your words and settings appropriately for the Headings section settings.&#x20;



For example, you may want to say "...your courses are renewing on" and then set the CTA to the manage account page so that they can check their credit card is a "good one"
{% endhint %}

An animation effect can also be chosen to be used for the course card when there is a pending expiration.

![](<../.gitbook/assets/Screen Shot 2021-12-03 at 3.08.33 PM.png>)

### Sound Settings

To get some attention onto the widget warnings and popups,  you can also choose to play a sound. Simply, make sure the **Play Sound** setting is enabled and then choose the type of sounds that you wish to play.

![](<../.gitbook/assets/Screen Shot 2021-12-03 at 3.11.20 PM.png>)

{% hint style="info" %}
**NOTE:** Due to browser limitations, the sound will not be heard until the user interacts with the page (ex: clicks).
{% endhint %}
