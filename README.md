# zifiridark
zifiridark is a Mozilla Firefox theme created by me. It's highly contrasted and OLED-friendly.

[Get zifiridark!](https://addons.mozilla.org/en/firefox/addon/zifiridark/)

I highly recommend using these userChrome.css settings along with zifiridark:

```css
.tab-background {
  margin-top: 0px !important;
  margin-bottom: 0px !important;
  border-radius: 0px 0px !important;
}

.tabbrowser-tab:not([selected=true]):not([multiselected=true]) .tab-background {
  background-color: color-mix(in srgb, currentColor 10%, transparent);
}
```

[Click here to learn how to create userChrome.css](https://www.userchrome.org/how-create-userchrome-css.html)
