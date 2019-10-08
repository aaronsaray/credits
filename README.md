# Credits

This repository holds the signature I add to my projects.

## How to Add

Use this compressed JS

```javascript
// prettier-ignore
// eslint-disable-next-line
!function(i){var t=i.querySelector(".credits-as"),r=!1;t&&t.addEventListener("click",function(t){if(r){if(!i.getElementById("credits-as-script")){var e=i.createElement("script");e.setAttribute("id","credits-as-script"),e.type="text/javascript",e.src="https://aaronsaray.github.io/credits/credits-as.js",i.querySelector("head").appendChild(e)}}else r=!0,setTimeout(function(){r=!1},500)})}(document);
```

This targets a `double click` on the `credits-as` class element.
