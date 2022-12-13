---
description: >-
  You can also use SmartText for additional personalization by passing in some
  special query parameters in links being shared through your email marketing
  platform
---

# Custom User Tags

{% hint style="info" %}
Please consult your email marketing platform documentation to see how to inject user attributes into a link. The link would need to contain "query parameters" in the url:

Example:

https://yoursite.thinkific.com?st1=Acme Inc\&st2=Artist


{% endhint %}

To automatically inject SmartText with additional personalization beyond [\{{first\_name\}}](first-name.md), you would:

1. **Use a link with SmartText custom query parameters - st1,st2,st3,st4,st5 :** From your email marketing platform, you can choose any type of user attribute you may have stored and add it to the url in the form of query parameters. Once the SmartText query parameter is detected, it will be stored in the users browser. When the user returns to you site or navigates to another page without the query parameter, then it will attempt to use the value that is stored in the browser
2. **Use SmartText Custom Types inside `<smart>` tags:** \{{st1\}}, \{{st2\}}, \{{st3\}}, \{{st4\}}, \{{st5\}}. if the \<smart> tag contains a custom type and there is one detected then the \<smart> tag will be used. Otherwise it will be ignored

### Demo:

{% embed url="https://www.loom.com/share/0f4a6eba6eb54cc68427bc7018a02cc0" %}
