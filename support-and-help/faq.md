# FAQ

## How do I get my font sizes to match the Thinkific sections

You can try adding this code to your site footer code settings (this is global for all pages). or put in a Swiss Embed section (just on that page)

```
<style>
.powkit-loki .section-body{
line-height: unset !important;
font-size: unset !important;
}
</style>
```

## How do I get the "container" size to match my Thinkific sections?

You can try adding this code to your site footer code settings (this is global for all pages). or put in a Swiss Embed section (just on that page)

```
<style>
@media (min-width: 1200px){
body .powkit-loki .container{
max-width: 1200px;
}
}
</style>
```
