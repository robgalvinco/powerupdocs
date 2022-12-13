# Using SmartLinks

Sharing links with SmartText query parameters can really increase your superpowers so you can nail your messaging to the exact person that should be reading it.

### How SmartLinks work

* A link is shared via your email marketing platform, social post, etc that includes SmartText query parameters
* The SmartText query parameters controls the SmartText that is used as well as the variation
* Values are saved within the users browser to be used for further page visits.

{% hint style="info" %}
Please check your email marketing platform for instructions on how to add tags or custom fields to links you use within your email campaigns
{% endhint %}

### SmartText Query Parameters

* **first\_name**_:_ this will make the value of this query parameter available to the \{{first\_name\}} SmartText attribute. A signed in Thinkific user will always over-ride this, but is useful when the user is not signed in. The value that is used will be saved within the browser to be used on repeat visits or other pages
* **st1, st2, st3, st4, st5:** You can elect to use 5 different custom placeholders for any information you may be able to provide (ex: customer, user type, location, etc). Yhis will make the value of this query parameter available to the \{{st1\}}, \{{st2\}}, \{{st3\}}, \{{st4\}}, \{{st5\}} SmartText attributes
* **v:** You can set which Smart Text Variation you would like to associate this user to. Acceptable values are 1, 2, 3. You also have to specify `text` `text-2`, `text-3` attribute for the \<smart> tag

### SmartLink Url Format

* Using one parameter: `https://yoursite.thinkific.com?first_name=Sammie`
* Using more than one parameter: `https://yoursite.thinkific.com?first_name=Sammie&v=1`

When using more than one parameter, simply insert an ampersand `&` symbol between them (starting with the second one).

{% hint style="info" %}
Once SmartText query parameter is recognized, it will remain in the users browser storage until they clear it (or it is changed by you with another link).&#x20;
{% endhint %}

###
