# zifiridark
zifiridark is a Mozilla Firefox theme created by me. It's highly contrasted and OLED-friendly.

[Get zifiridark!](https://addons.mozilla.org/en/firefox/addon/zifiridark/)

I highly recommend using these userChrome.css settings along with zifiridark:

```css
.tab-background {
  margin-top: 0px !important;
  margin-bottom: 0px !important;
  border-radius: 0px 0px !important;
  background-color: color-mix(in srgb, currentColor 7%, transparent); /*Change currentColor value to tweak background tab shade*/
}

.tabbrowser-tab[selected=true] .tab-background ,
.tabbrowser-tab[multiselected=true] .tab-background {
  background-color: var(--toolbar-bgcolor) !important;
  background-image: var(--toolbar-bgimage) !important;
}

```

[Click here to learn how to create userChrome.css](https://www.userchrome.org/how-create-userchrome-css.html)
