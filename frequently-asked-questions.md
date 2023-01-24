# ❓ Frequently Asked Questions

### How to I customize the font for the MegaNav?

For this you will need to know a bit of CSS. Modify and place this code into your Site Foote Code Settings:\


```
<style>
/* Top level menu put in whatever CSS you want */
.megapow .navbar .navbar-nav .nav-link{
   text-transform: uppercase; /* Makes the text uppercase */
    font-size: 18px; /* Makes font size bigger */
    font-weight: 700; /* Makes the font bolder */
}

/* Sub menu heading put in whatever CSS you want */
.megapow header nav.navbar .dropdown-menu.megamenu-content li.dropdown-header{
   
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
