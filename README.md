## Reproduction repo for a bug with firebase hosting

### Steps
1. firebase serve
2. Go [here](http://localhost:5000/index?lang=de).

Note: the bug seems to only happen when the `"cleanUrls": true` option is specified in firebase.json.
