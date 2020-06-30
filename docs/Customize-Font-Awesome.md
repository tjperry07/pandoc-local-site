% Customize Font Awesome

Font Awesome receives dozens of new requests every day. Some of them will eventually be included, others will not. Our [Icon Leaderboard](https://fontawesome.com/community/leaderboard/new#faqs) contains a lot of information on how requests work, please take a look.

Said so, if you need a new icon in a short while, or you need a comprehensive set of icons (e.g., a set of weather icons to build a forecast application) our suggestion is to customize Font Awesome.

## Webfont
 
There are some wonderful online services which allows you to customize Font Awesome, like:

- Fontello: http://fontello.com/
- IcoMoon: https://icomoon.io/app/#/select ([How To](https://dyscribe.com/en/webdesign/create-your-own-custom-iconfont.html))
- Fontastic: http://fontastic.me/

Pick up the one which better fits your needs.

## SVG Framework

⚠️ Official SVG customization is on the To-Do list, meanwhile please use this approach.

Prerequisites:
1. Single-path SVG of the icon you want to add

In the following examples, I'm going to add to Font Awesome 5 the `fa-list` icon from Font Awesome 4.

#### With local/CDN `fontawesome/all.js`

⚠️ Pseudoelements will not work with this method!

JavaScript:
```js
// replace 1568, 1568 with your SVG viewbox
// e001 is the unicode point which represents this custom icon. Increment this value for other icons
// replace 'M256...' with your single-path SVG
var faListOldStyle = {
  prefix: 'fac',
  iconName: 'list-old-style',
  icon: [1568, 1568, [], 'e001', 'M256 1312v192q0 13-9.5 22.5t-22.5 9.5h-192q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h192q13 0 22.5 9.5t9.5 22.5zm0-384v192q0 13-9.5 22.5t-22.5 9.5h-192q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h192q13 0 22.5 9.5t9.5 22.5zm0-384v192q0 13-9.5 22.5t-22.5 9.5h-192q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h192q13 0 22.5 9.5t9.5 22.5zm1536 768v192q0 13-9.5 22.5t-22.5 9.5h-1344q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h1344q13 0 22.5 9.5t9.5 22.5zm-1536-1152v192q0 13-9.5 22.5t-22.5 9.5h-192q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h192q13 0 22.5 9.5t9.5 22.5zm1536 768v192q0 13-9.5 22.5t-22.5 9.5h-1344q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h1344q13 0 22.5 9.5t9.5 22.5zm0-384v192q0 13-9.5 22.5t-22.5 9.5h-1344q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h1344q13 0 22.5 9.5t9.5 22.5zm0-384v192q0 13-9.5 22.5t-22.5 9.5h-1344q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h1344q13 0 22.5 9.5t9.5 22.5z']
}

FontAwesome.library.add(
  faListOldStyle
)
```

HTML:
```html
<span class="fac fa-list-old-style"></span>
```

Example: https://jsfiddle.net/tagliala/we7gtcvk/1/

#### With [Webpack](https://webpack.js.org/)

Note: *Instructions are different for TypeScript*

JavaScript:
```js
import { library, dom } from '@fortawesome/fontawesome-svg-core'

// replace 1568, 1568 with your SVG viewbox
// e001 is the unicode point which represents this custom icon. Increment this value for other icons
// replace 'M256...' with your single-path SVG
var faListOldStyle = {
  prefix: 'fas',
  iconName: 'list-old-style',
  icon: [1568, 1568, [], 'e001', 'M256 1312v192q0 13-9.5 22.5t-22.5 9.5h-192q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h192q13 0 22.5 9.5t9.5 22.5zm0-384v192q0 13-9.5 22.5t-22.5 9.5h-192q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h192q13 0 22.5 9.5t9.5 22.5zm0-384v192q0 13-9.5 22.5t-22.5 9.5h-192q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h192q13 0 22.5 9.5t9.5 22.5zm1536 768v192q0 13-9.5 22.5t-22.5 9.5h-1344q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h1344q13 0 22.5 9.5t9.5 22.5zm-1536-1152v192q0 13-9.5 22.5t-22.5 9.5h-192q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h192q13 0 22.5 9.5t9.5 22.5zm1536 768v192q0 13-9.5 22.5t-22.5 9.5h-1344q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h1344q13 0 22.5 9.5t9.5 22.5zm0-384v192q0 13-9.5 22.5t-22.5 9.5h-1344q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h1344q13 0 22.5 9.5t9.5 22.5zm0-384v192q0 13-9.5 22.5t-22.5 9.5h-1344q-13 0-22.5-9.5t-9.5-22.5v-192q0-13 9.5-22.5t22.5-9.5h1344q13 0 22.5 9.5t9.5 22.5z']
}

library.add(
  faListOldStyle
)

dom.watch()
```

HTML:
```html
<span class="fas fa-my-custom-icon"></span>
```

Docs: https://fontawesome.com/how-to-use/with-the-api/setup/getting-started

Ref: [#13079](https://github.com/FortAwesome/Font-Awesome/issues/13079)

Demo: https://codesandbox.io/s/fa5-svg-custom-icons-ks4to

Blog Post on this approach - https://medium.com/@nsisodiya/hacking-font-awesome-for-custom-svg-icons-ea762118fa7b

# New styles

If you don't need new icons but have special needs for your stylesheet, please consider a custom build based on `.less` or `.scss` versions.