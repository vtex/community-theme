# VTEX Discour Theme


## Using

This structure theme is provid by [discourse_theme CLI](https://github.com/discourse/discourse_theme)

Run `discourse_theme watch ./` to monitor theme changes.

## References

https://www.figma.com/file/AFIsgoReKwcvqxPZUpiVkm/VTEX-Community?node-id=2832%3A51


https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966
https://meta.discourse.org/t/how-to-develop-custom-themes/60848
https://meta.discourse.org/t/designers-guide-to-discourse-themes/152002


### Structure

```
.
├── about.json
├── common
│   ├── after_header.html
│   ├── body_tag.html
│   ├── common.scss
│   ├── embedded.scss
│   ├── footer.html
│   ├── header.html
│   └── head_tag.html
├── desktop
│   ├── after_header.html
│   ├── body_tag.html
│   ├── desktop.scss
│   ├── footer.html
│   ├── header.html
│   └── head_tag.html
├── HELP
├── locales
│   └── en.yml
├── mobile
│   ├── after_header.html
│   ├── body_tag.html
│   ├── footer.html
│   ├── header.html
│   ├── head_tag.html
│   └── mobile.scss
└── settings.yml

```

`about.json`  and `settings.yml` are required
