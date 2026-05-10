# violentmonkey-bug-demo


```javascript
// ==UserScript==
// @name        clearInterval bug 
// @version     1.0
// @match       https://deevroman.github.io/violentmonkey-bug-demo/*
// @grant       GM_info
// ==/UserScript==

const kek = setInterval(() => {
    console.log("foo")
    clearInterval(kek);
}, 500)
```
