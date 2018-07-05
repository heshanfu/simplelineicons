# Simple Line Icons as a Vue Component
This is a Vue wrapper component for simple line icons fonts.
https://github.com/thesabbir/simple-line-icons/


## ✔ Getting started

Get the package:
```bash
npm install vue-simple-line-icons
```

Register SimpleLineIcons in your app entrypoint:
```js
In main.js
import Vue from 'vue'
import SimpleLineIcons from 'vue-json-excel'

Vue.component(SimpleLineIcons)

OR In component

new Vue({
    components: {
        SimpleLineIcons
    }
})
```

In your template you can call it like this:

```html
<simple-line-icons
	icon="plus"
	:rotate="90"
	size="small"
	color="mediumseagreen">
</simple-line-icons>
```

Required Prop
- icon: String >>> Contains the icon class.

Optional Props
- rotate: Number >>> The degrees of rotation.
- size: String >>> The size of the icon small OR large.
- color: String >>> Any hex,rgb,hsla color.
