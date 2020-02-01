# 🖼 Background Overlay

A small package that helps you to add a overlay on a background

## 🚀 How to use

Open the terminal and write

`npm i bgoverlay`

For HTML, add the following link tag in the head section of your HTML.

`<link rel="stylesheet" href="./node_modules/bgoverlay/bgoverlay.css">`

For React, add the following line of code at the top of the file.

`import "./node_modules/bgoverlay/bgoverlay.css"`

Create two parent child divs in the body tag. Give class of *main_div* to the parent div and *overlay* to the child div like this.

```
<div class="main_div">
    <div class="overlay"></div>
</div>
```

Add any background image and overlay color you want then by writing the following code in the CSS.

```
.main_div {
	background-image: url() !important; /* Add image URL */
}

.overlay:hover {
	background-color: black; /* Add any color */
}
```

## 🙋‍♂️ Author

Visit my [Website](https://msaaddev)

Want to connect with me, follow me on [Twitter](https://twitter.com/msaaddev)
