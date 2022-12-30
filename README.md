
# 🌓 Dark Mode Switch

* Kelompok 6
* 1207050025 - Deta Triandini
* 1207050038 - Faza Mohamad Farsyafat
* 1207050039 - Fikri Taufiqurrahman

## Quick start

Several quick start options are available:

- [Download the latest release](https://github.com/fikritaufiqurrahman/dark-mode-switch.git)
- Clone the repo `git clone https://github.com/fikritaufiqurrahman/dark-mode-switch.git`
- Install with [npm](https://www.npmjs.com/package/dark-mode-switch) `npm install dark-mode-switch`
- Install with [yarn](https://yarnpkg.com/en/package/dark-mode-switch) `yarn add dark-mode-switch`

## Usage

1. Add your custom switch for the Dark Mode toggle followed by the `dark-mode-switch.min.js` script:

Bootstrap 4.x

```html
<div class="custom-control custom-switch">
  <input type="checkbox" class="custom-control-input" id="darkSwitch" />
  <label class="custom-control-label" for="darkSwitch">Dark Mode</label>
</div>
<script src="dark-mode-switch.min.js"></script>
```

Bootstrap 5.x

```html
<div class="form-check form-switch">
  <input type="checkbox" class="form-check-input" id="darkSwitch" />
  <label class="custom-control-label" for="darkSwitch">Dark Mode</label>
</div>
<script src="dark-mode-switch.min.js"></script>
```

2. Edit the `dark-mode.css` to suit your site - the one included here is a basic example.

## How it works

Turning dark mode on will add `data-theme="dark"` to the `body` tag. You can use CSS to target the elements on the page like so:

```css
[data-theme="dark"] {
  background-color: #111 !important;
  color: #eee;
}
```

## Browser Support

Works well with all the browsers supported by [Bootstrap 4](https://getbootstrap.com/docs/4.5/getting-started/browsers-devices/#supported-browsers) and [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/browsers-devices/#supported-browsers)

## To Enable DarkMode in Android Webview

- You need DOM Storage API in order to [make this work with WebView](https://github.com/mcnaveen/Android-Webview-Darkmode-with-JavaScript).
- Inside OnCreate under WebView paste this line.

`WebSettings.setDomStorageEnabled(true)`

The creator reference (https://github.com/coliff)


## Credits

Created thanks to the excellent [dark-theme](https://codyhouse.co/blog/post/dark-light-switch-css-javascript) and [local storage](https://codyhouse.co/blog/post/store-theme-color-preferences-with-localstorage) tutorials over at [codyhouse.co](https://codyhouse.co).

