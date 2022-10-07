# zifiridark
zifiridark is a OLED-friendly Mozilla Firefox and Mozilla Thunderbird theme.

[Get zifiridark!](https://addons.mozilla.org/en/firefox/addon/zifiridark/)

I highly recommend using these userChrome.css settings along with zifiridark:

```css
.tab-background {
  margin-top: 0px !important;
  margin-bottom: 0px !important;
  border-radius: 0px 0px !important;
  /*Change currentColor value to tweak background tab shade because shading may vary depending your display.*/
  background-color: color-mix(in srgb, currentColor 13%, transparent);
}

.tabbrowser-tab[selected=true] .tab-background ,
.tabbrowser-tab[multiselected=true] .tab-background {
  background-color: var(--toolbar-bgcolor) !important;
  background-image: var(--toolbar-bgimage) !important;
}

/*Shortens tabs vertically, more space for webpages.*/
.tabbrowser-tab {
  max-height: var(--tab-min-height) !important;
}
```

[Click here to learn how to create userChrome.css](https://www.userchrome.org/how-create-userchrome-css.html)
