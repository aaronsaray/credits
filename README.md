# Credits

This repository holds the signature I add to my projects.

## How to Add

Use this compressed JS

```javascript
document.querySelector(".credits-as").addEventListener("dblclick",function(e){if(e.metaKey&&!document.getElementById("credits-as-script")){var t=document.createElement("script");t.setAttribute("id","credits-as-script"),t.type="text/javascript",t.src="https://aaronsaray.github.io/credits/credits-as.js",document.querySelector("head").appendChild(t)}});
```

This targets a `meta-key + double click` on the `credits-as` class element.
