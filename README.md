# vite-png-favicon-issue

* Clone this repo
* cd into it
* run `npm install`
* run `npm run build`
* Check dist folder the favicon for a.png is there
* go to `index.html` change the favicon to be `b.png`
* run `npm run build`
* Check dist folder the favicon for b.png isn't there but it's a data string on `index.html`

