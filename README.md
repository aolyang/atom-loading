**Atom official website display icon**

![Atom SVG icon](https://raw.githubusercontent.com/aolyang/atom-loading/main/shot.png)

+ pure javascript
+ generated, only svg elements
+ easy to DIY

## change a circle style

```javascript
// by modify a config below, and send to mount function
const aCircle = {
  r: 36,
  width: 0.4,
  color: "rgba(95, 143, 181, 1)",
  dashArray: ["1%", "10.3%", "22%"],
  speed: 50
}
mount("#container", [aCircle])
```
