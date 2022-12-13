---
description: >-
  Use this super power to make your page feel more personalized. This can be
  used when the user is signed in or signed out (with query url parameter that
  can be passed from your email marketing platform
---

# First Name

To automatically inject SmartText with the user's first name, you would use the **\{{first\_name\}}** keyword in the `<smart>` text attributes.

If the users is signed into your Thinkific site then it will always use their First name that they used when registering.

If the user is not logged in then it will look for:

* **query parameter - first\_name:** ex: https://yoursite..thinkific.com?first\_name=Samantha. You can use these types of links from your email marketing system when sending out marketing emails.&#x20;
* **local browser storage:** once the name is detected via a signed in Thinkific user or via a query parameter, then it will be stored in the users browser. When the user returns to you site or navigates to another page without the query parameter, then it will attempt to use the name that is stored in the browser

### Demo

{% embed url="https://www.loom.com/share/757e5c4eac7a410c8c374f58852e887a" %}

