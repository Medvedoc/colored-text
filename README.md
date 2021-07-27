<h2 align="center">Hey! Today I created bouncing text in pure HTML and CSS.</h2>
<div align="center"> 
<img src="https://img.shields.io/github/downloads/medvedoc/colored-text/total?style=for-the-badge">
<img src="https://img.shields.io/github/license/medvedoc/colored-text?style=for-the-badge">
<img src="https://img.shields.io/github/commit-activity/m/mevedoc/colored-text?style=for-the-badge">
<img src="https://img.shields.io/github/last-commit/medvedoc/colored-text?style=for-the-badge">
</div>
<div align="center">
<img src="https://img.shields.io/github/languages/top/Medvedoc/colored-text?style=for-the-badge">
<img src="https://img.shields.io/github/languages/code-size/Medvedoc/colored-text?style=for-the-badge">
<img src="https://img.shields.io/github/languages/count/medvedoc/colored-text?style=for-the-badge">
<img src="https://img.shields.io/tokei/lines/github/medvedoc/colored-text?style=for-the-badge">
</div>
<h3 align="center">All animation is based on @keyframes.</h3>
<div align="center"><a href="https://cdn.buymeacoffee.com/uploads/project_updates/2021/07/2a3ffa62a8da3fba38b20d9a2c19ba81.png"><img src="https://cdn.buymeacoffee.com/uploads/project_updates/2021/07/2a3ffa62a8da3fba38b20d9a2c19ba81.png" /></a></div>
<h3 align="center">Demonstration: <a href="https://codepen.io/Medvedoc/full/YzVYeoE">codepen</a></h3>
<h3 align="center">Download: <a href="https://github.com/Medvedoc/colored-text/archive/refs/heads/main.zip">github</a></h3>
<h2>HTML code</h2>

```html
<div class="wrapper">
    <div class="container">
        <h1>Simple Text</h1>
        <h1>Simple Text</h1>
        <h1>Simple Text</h1>
        <h1>Simple Text</h1>
        <h1>Simple Text</h1>
        <h1>Simple Text</h1>
        <h1>Simple Text</h1>
        <h1>Simple Text</h1>
        <h1>Simple Text</h1>
    </div>
</div>
```

<h2>CSS code</h2>

```css
*,
 :before,
 :after {
    box-sizing: border-box;
}

:root {
    --color-1: #f9002f;
    --color-2: #2a9a9f;
    --color-3: #f1b211;
    --color-4: #e83611;
    --color-5: #186cb8;
}

body {
    background-color: #000;
    font: 3rem/1.25 'Titan one', sans-serif;
    text-align: center;
    margin: 0 auto;
}

.wrapper {
    line-height: 1;
    min-height: 100%;
    place-items: center;
    min-height: calc(100vh - 16px);
    padding: 2%;
}

.container {
    text-align: center;
    grid-gap: 5%;
    display: grid;
    grid-template: repeat(3, 200px)/repeat(3, 1fr);
}

h1 {
    width: -webkit-min-content;
    width: -moz-min-content;
    width: min-content;
    margin: auto;
    text-transform: uppercase;
    color: transparent;
}

h1:nth-child(1) {
    background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 43%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 84%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -moz-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 43%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 84%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -webkit-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 43%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 84%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -o-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 43%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 84%, transparent 84%, transparent 85%, var(--color-5) 85%);
    background-clip: text;
    -moz-background-clip: text;
    -webkit-background-clip: text;
    -o-background-clip: text;
}

h1:nth-child(2) {
    background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -moz-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -webkit-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -o-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    background-clip: text;
    -moz-background-clip: text;
    -webkit-background-clip: text;
    -o-background-clip: text;
}

h1:nth-child(3) {
    background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 29%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 68%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -moz-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 29%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 68%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -webkit-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 29%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 68%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -o-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 29%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 68%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    background-clip: text;
    -moz-background-clip: text;
    -webkit-background-clip: text;
    -o-background-clip: text;
}

h1:nth-child(4) {
    background: linear-gradient(-65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 43%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 84%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -moz-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 43%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 84%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -webkit-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 43%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 84%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -o-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 43%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 84%, transparent 84%, transparent 85%, var(--color-5) 85%);
    background-clip: text;
    -moz-background-clip: text;
    -webkit-background-clip: text;
    -o-background-clip: text;
}

h1:nth-child(5) {
    background: linear-gradient(-65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -moz-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -webkit-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -o-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    background-clip: text;
    -moz-background-clip: text;
    -webkit-background-clip: text;
    -o-background-clip: text;
}

h1:nth-child(6) {
    background: linear-gradient(-65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 29%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 68%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -moz-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 29%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 68%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -webkit-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 29%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 68%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -o-background: linear-gradient(65deg, var(--color-1) 25%, transparent 25%, transparent 26%, var(--color-2) 29%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 64%, transparent 64%, transparent 65%, var(--color-4) 68%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    background-clip: text;
    -moz-background-clip: text;
    -webkit-background-clip: text;
    -o-background-clip: text;
}

h1:nth-child(7) {
    background: radial-gradient(ellipse farthest-corner at 30px 5px, var(--color-1) 21%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -moz-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -webkit-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -o-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    background-clip: text;
    -moz-background-clip: text;
    -webkit-background-clip: text;
    -o-background-clip: text;
}

h1:nth-child(8) {
    background: radial-gradient(ellipse farthest-corner at 160px 5px, var(--color-1) 21%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -moz-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -webkit-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -o-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    background-clip: text;
    -moz-background-clip: text;
    -webkit-background-clip: text;
    -o-background-clip: text;
}

h1:nth-child(9) {
    background: radial-gradient(ellipse farthest-corner at 230px 5px, var(--color-1) 21%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -moz-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -webkit-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    -o-background: linear-gradient(65deg, var(--color-1) 22%, transparent 25%, transparent 26%, var(--color-2) 26%, var(--color-2) 40%, transparent 43%, transparent 44%, var(--color-3) 44%, var(--color-3) 61%, transparent 64%, transparent 65%, var(--color-4) 65%, var(--color-4) 81%, transparent 84%, transparent 85%, var(--color-5) 85%);
    background-clip: text;
    -moz-background-clip: text;
    -webkit-background-clip: text;
    -o-background-clip: text;
}
```
