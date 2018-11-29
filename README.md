# Vue-Input-Restriction-Directives

[![npm version](https://badge.fury.io/js/vue-input-restriction-directives.svg)](https://badge.fury.io/js/vue-input-restriction-directives)

Set of useful vue directives to add text restriction to your input
- **No keyboard key validation**, just regular expression
- No render delay in typing

## Usage

main.js:

```javascript

import VueInputRestrictionDirectives from 'vue-input-restriction-directives';

Vue.use(VueInputRestrictionDirectives);

<input type="text" v-numeric-only />       // for only number input
<input type="text" v-alphabetic-only />    // for only alphabetic input
<input type="text" v-uppercase-only />     // for only uppercase input
<input type="text" v-lowercase-only />     // for only lowecase input
<input type="text" v-max-length="10" />    // for limit number of characteres input
```
