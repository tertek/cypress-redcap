# Cypress REDCap
This Cypress plugin exposes commands and functions to test REDCap. In order to use it, REDCap must have the [redcap-testing-api](https://github.com/tertek/redcap-testing-api) external module installed.

## Installation

Install the package using npm:

```
npm install cypress-redcap --save-dev
```

And add the following at the beginning of your setup file at `cypress/support/index.js`:

```js
import { useCypressRedcap } from 'cypress-redcap';

useCypressRedcap();

// ...
```


## Credits/Acknowledgments

This plugin is a port/analogy of [cypress-laravel](https://github.com/NoelDeMartin/cypress-laravel). A lot of thanks to **Noel De Martin** who has made the original code base available.