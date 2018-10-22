Vue.min.js attached in lib for exercise purposes. Simple request to SpaceX API for list of (x) Launches, and details about them. It's build in Vue.js with components. Very simple and clean interface.
Some not obvious features, that I did here:
- Applied module pattern to avoid poluting global scope with apps variables
- exported myApp to global scope for debugging reasons
- SUIT methodology
- Full RWD support in desig including  autoadjusting content sizes.
- Optimized performance by avoiding redundance requests via caching data
