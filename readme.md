<h2 align="center">hideJs</h2>
<h3 align="center">A minimal Js Module, Used to hide your source code</h3>

>> How to Use ?

```js
// import hideJs
import { hideJs } from "./hideJs.mjs"
const module = new hideJs();
```

>> 1. Hide Context Menu

```js
...
module.hideContext();
```

>> 2. Hide Source (ctrl + U)
```js
...
module.hideSource();
```

>> 3. Hide Console (ctrl + J or ctrl + I)
```js
...
module.hideConsole();
```

>> 4. Hide Elements (ctrl + C)
```js
...
module.hideElements();
```

>> 5. Hide DevTool 


note: if you call this function you don't need to call `module.hideSource();` , `module.hideConsole();` and `module.hideElements();`
```js
module.hideDevTool();
```

>> 6. Disable Image Dragging

```js
...
module.hideImageDrag();
```

>> 7. Disable Select 
```js
...
module.disableSelectAll();
```

>> 8. Disable All 
```js
...
module.Neutral();
```

>> 9. Disable Page Download (ctrl + s)
```js
module.disableDownloadPage();
```

---
>> Custom (Beta)

```js
import { hideJs } from "./hideJs.mjs"
const module = new hideJs();
module.disable([
    "context",  // disable context menu
    "source",   
    "console",  
    "elements", 
    "dev_tool", 
    "image_drag",
    "select",
    "all"      // disable all
])
```
