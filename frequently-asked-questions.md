# ❓ Frequently Asked Questions

### My logo is too small.

This usually happens when your logo is "wide" and by default we leave a lot of room for many links (because that is what a "meganav" is usally about. So you can give this code snippet a try to increase the size of your logo (Place this in your Site Footer Code settings):

```
<style>
@media (min-width: 992px){
    .megapow .nav-header-container .col-lg-2 {
        flex: 0 0 auto;
        width: 33.33333333%;
    }

}
</style>
```

### There is some weird scrolling behavior...

This is usually because you have Thinkific's default Header section enabled for either Transparent and/or Sticky Navigation. Since Thnkific thinks you are still using their navigation header, it may cause problems with positioning and "fighting" with MegaNav code. So, since we are not using the Thinkific header, just make sure to change the settings to **Solid for the Background setting** and **uncheck the box Sticky navigation checkbox**

<figure><img src=".gitbook/assets/Site-Builder-Thinkific (33).png" alt=""><figcaption></figcaption></figure>

### My hamburger menu is not appearing on mobile

This usually happens when the background of the navigation is white and there is a "white on white" problem. Add this code snippet to your Site Footer Code settings and change the color accordingly

```
<style>
.megapow .navbar .navbar-toggler-line {
    background-color: #FF0089 !important;
}
.megapow header .navbar .show .navbar-nav .nav-link, .megapow header .navbar .show .navbar-nav .inner-link, .megapow header .navbar .show .navbar-nav .dropdown-toggle, .megapow header .navbar .show .nav-item.dropdown.simple-dropdown .dropdown-menu>.dropdown>a {
    color: #FF0089 !important;
}
</style>
```

### How to I customize the font for the MegaNav?

For this you will need to know a [bit of CSS](https://www.geeksforgeeks.org/css-text-formatting/). Modify and place this code into your Site Foote Code Settings (https://yoursite.thinkific.com/manage/settings#tab-code-analytics):\


```
<style>
/* Top level menu put in whatever CSS you want */
.megapow .navbar .navbar-nav .nav-link{
   text-transform: uppercase; /* Makes the text uppercase */
    font-size: 18px; /* Makes font size bigger */
    font-weight: 700; /* Makes the font bolder */
}

/* Sub menu heading put in whatever CSS you want */
.megapow header nav.navbar .dropdown-menu.megamenu-content li.dropdown-header,
.megapow .simple-dropdown .dropdown-menu .dropdown a{
   
}

/* Sub Menu Links put in whatever CSS you want */
.megapow header .dropdown-menu.megamenu-content li a{
    
}
</style>
```

### How do I use FontAwesome icons with MegaNav?

* [ ] You will need to first put FontAwesome library code into your Site Footer Code settings

```
<link href="https://import.cdn.thinkific.com/244754/courses/1825320/fontawesome-220417-090501.css" rel="stylesheet" />
<link href="https://import.cdn.thinkific.com/244754/courses/1825320/regular-220417-091254.css" rel="stylesheet"/>
<link href="https://import.cdn.thinkific.com/244754/courses/1825320/solid-220417-091254.css" rel="stylesheet"/>
<link href="https://import.cdn.thinkific.com/244754/courses/1825320/light-220417-091254.css" rel="stylesheet"/>
<link href="https://import.cdn.thinkific.com/244754/courses/1825320/thin-220417-085853.css" rel="stylesheet"/>
<link href="https://import.cdn.thinkific.com/244754/courses/1825320/brands-220418-084259.css" rel="stylesheet"/>
<link href="https://import.cdn.thinkific.com/244754/courses/1825320/duotone-220418-084357.css" rel="stylesheet"/>
<link href="https://import.cdn.thinkific.com/244754/courses/1825320/v4shims-220418-085102.css" rel="stylesheet"/>
```

* [ ] Then in the MegaNav Menu builder, use the FontAwesome icon code along with the text. Be sure to select the icon code as well when placing the link

{% embed url="https://www.loom.com/share/06904b91780c44f2bfe5e14d9827b162" %}

### How do I create the menu?

You will use the MegaNav Menu Builder which is a simple editor for creating bullet lists.&#x20;

### How many levels can I create?

You can create up to three levels deep. Each level will be denoted by a level in the bullet list.

### What kind of menu can I create?

You can create:

* Simple Links
* Simple Drop down menu's with simple links
* Drop Down menu's with a combination of simple links and Sub Menu's with simple links
* Drop Down Sub Columns with simple links

### How do I publish the menu to my site?

After using the MegaNav Menu builder, you will copy and paste a code snippet into one of the Header links inside of Site Builder. This will activate the MegaNav code that will replace the current site Navigation.

### Why am I copying and pasting a code snippet into my header link settings?

Without getting to technical, this is the best place to put the activation code so that when the page loads, users will not notice the header is getting replaced. And it is the only way we can ensure your MegaNav is available on all pages.

### Why can't I replace the header section inside of Site Builder?

The way the standard Thinkific themes are built, the Header section is not movable or delete-able. Technically there is no way around this.

### How can I preview MegaNav before making it live?

When pasting the MegaNav activation script into your page header, you will instantly see it inside of your Site Builder preview. You can then hover over the menu links to see your submenus.

### How can I make changes to my MegaNav that is in use?

To edit your MegaNav, you will be copying and pasting your current MegaNav activation code snippet into the MegaNav Menu Builder. This will convert it back to a bullet list that you can then edit and publish using the MegaNav Menu Builder

### How can I remove the MegaNav menu?

Simply delete the block setting inside your Header section or change the text setting for that link where you had pasted the MegaNav activation code.
