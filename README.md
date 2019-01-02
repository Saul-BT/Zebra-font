# Zebra-font
A handmade striped font.
```css
.zebra {color: black} /* Useful for light backgrounds */
```
![Zebra](https://i.cubeupload.com/JMQfXC.png)

```css
.zebra {color: white} /* Useful for dark backgrounds */
```
![Zebra](https://i.cubeupload.com/s4BYAo.png)
## How to use it?
It's as simple as adding this CSS snippet in your style sheet:
````css
@font-face {
  font-family: "Zebra";
  src: local("?"), url("Zebra.woff") format("woff"), url("Zebra.ttf") format("truetype");
}
.zebra { /* I recommend especially that it be used with a class */
  font-family: "Zebra";
  font-weight: 500;
}
````
### Download
- **With Git:**
```bash
git clone https://github.com/Saul-BT/Zebra-font.git
```
- **[Direct download](https://github.com/Saul-BT/Zebra-font/raw/master/Zebra-Font.rar)**
