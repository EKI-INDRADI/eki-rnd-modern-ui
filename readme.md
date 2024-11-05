## Tutorial :

:link: [Udemy](https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3)

<details>
  <summary>EKI-20240722-001-Your-Very-First-Webpage</summary>

TOOLS

```sh
https://code.visualstudio.com/Download

https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

https://marketplace.visualstudio.com/items?itemName=azemoh.one-monokai


```

vscode settings (auto save + auto format)

```sh

settings -> "default formatter" > default formatter = Prettier - Code formatter (esbenp.prettier-vscode)

settings -> "Format On Save" > Editor: Format On Save = Enable

settings -> "Auto Save" > Files: Auto Save = OnFocusChange

settings -> "Tab Size" > Editor: Tab Size = 2 (default 4)

settings -> "Auto Closing Tags" > HTML: auto closing tags = disabled

```

show web

```sh

CTRL + P

'>Simple Browser'

```

</details>

<details>
  <summary>EKI-20240722-002-Downloading-Course-Material</summary>

Downloading Course Material

```sh

https://github.com/jonasschmedtmann/html-css-course

```

</details>

<details>
  <summary>EKI-20240722-003-HTML-Document-Structure</summary>

02-HTML-Fundamentals

```sh

settings -> "auto closing tags" > HTML: auto closing tags = disabled

```

</details>

<details>
  <summary>EKI-20240722-004-Text-Elements</summary>

02-HTML-Fundamentals

```sh

update index.html

```

</details>

<details>
  <summary>EKI-20240729-005-More-Text-Elements-Lists</summary>

```html
<ol>
  = number list

  <ul>
    = symbol list
  </ul>
</ol>
```

</details>

<details>
  <summary>EKI-20240807-006-Images-and-Attributes</summary>

```html
<img ... />
```

</details>

<details>
  <summary>EKI-20240807-007-Hyperlinks</summary>

```html
<a> ... </a>
```

</details>

<details>
  <summary>EKI-20240807-008-Structuring-our-Page</summary>

```html
<head>
  ..
</head>


<body>
  ..
<header>
  ..
  <nav>
  ..
  <nav>
  ..
</header>
  ..
<aside>
  ..
  <article>
  ..
    <header>
  ..
    </header>
  ..
  </article>
  ..
</aside>
  ..
<footer></footer>
</body>
```

</details>

<details>
  <summary>EKI-20240815-009-A-Note-on-Semantic-HTML</summary>

```html
<div></div>
<!---box---->
<em></em>
<!---italic such as <i></i>---->
```

</details>

<details>
  <summary>EKI-20240815-010-Installing-Additional-VS-Code-Extensions</summary>

vs code extention

```sh

- image preview
- color highlight
- auto rename tag (jun han)
- Live Server

```

vs code settings

```sh

HTML : Auto Closing Tags ->  Enable

```

</details>

<details>
  <summary>EKI-20240815-011-CHALLENGE-#1</summary>

```html
<aside></aside>
<!--- secondar information / informasi ke 2 dari halaman utama --->
```

</details>

<details>
  <summary>EKI-20241019-012-CHALLENGE-#2</summary>

https://codepen.io/pen

https://codepen.io/jonasschmedtmann/pen/ZELVmJX/48f20ea036df9afc09978b07eca226b8

```html
<article>
  <h2>Converse Chuck Taylor All Star Low Top</h2>
  <img
    src="https://i.ibb.co/Jr7Wh1d/challenges.jpg"
    alt="Chuck Taylor All Star Shoe"
    height="250"
    width="250"
  />

  <p><strong>$65.00</strong></p>
  <p>Free shipping</p>
  <p>
    Ready to dress up or down, these classic canvas Chucks are an everyday
    wardrobe staple.
  </p>

  <a href="https://www.converse.com">More information &rarr;</a>

  <h3>Product details</h3>
  <ul>
    <li>Lightweight, durable canvas sneaker</li>
    <li>Lightly padded footbed for added comfort</li>
    <li>Iconic Chuck Taylor ankle patch</li>
  </ul>

  <button>Add to cart</button>
</article>
```

</details>

<details>
  <summary>EKI-20241019-013-Introduction-to-CSS</summary>

```css
/* h1 == Selector */
h1 {
  /* color: blue; == Declaration/Style */
  color: blue;
  text-align: center;
  front-size: 20px;

  /* 
   front-size: 20px;   
   (property): (value)
  */
}
```

</details>

<details>
  <summary>EKI-20241104-014-Inline-Internal-and-External-CSS</summary>

style.css
```css

h1 {
  color: blue;
}

```

index.html
```html

<html>
  <head>
    <link href="style.css" rel="stylesheet" />
  </head>
</html>


```

or

index.html
```html

<html>
  <head>
    <style>
      h1 {
        color: blue;
      }
    </style>
  </head>
</html>

```

</details>



<details>
  <summary>EKI-20241104-015-Styling-Text</summary>

style.css
```css


/* Reset CSS */
/* * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
} */

h1 {
  /* color: blue; */
  font-size: 26px;
  font-family: sans-serif;
  text-transform: uppercase;
  font-style: italic;
}

h2 {
  font-size: 40px;
  font-family: sans-serif;
}

h3 {
  font-size : 30px;
  font-family: sans-serif;
}

h4 {
  font-size: 20px;
  font-family: sans-serif;
  text-transform: uppercase;
  text-align: center;
}

p {
  font-size: 22px;
  font-family: sans-serif;
  line-height: 1.5;
}


li {
  font-size: 20px;
  font-family: sans-serif;
}

```

</details>



<details>
  <summary>EKI-20241105-016-Combining-Selectors</summary>

style.css
```css

/* Reset CSS */
/* * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
} */

h1, h2, h3, h4, p, li {
  font-family: sans-serif;
}

h1 {
  /* color: blue; */
  font-size: 26px;
  text-transform: uppercase;
  font-style: italic;
}

h2 {
  font-size: 40px;
}

h3 {
  font-size : 30px;
}

h4 {
  font-size: 20px;
  text-transform: uppercase;
  text-align: center;
}

p {
  font-size: 22px;
  line-height: 1.5;
}


li {
  font-size: 20px;
}


/* penulisan css spesific & replace global  */

footer p { /* maksudnya p adalah turuninan dari footer, untuk replace dari p global */
  font-size: 16px;
}


article header p {  /* maksudnya p adalah turuninan dari article dan header, untuk replace dari p global */
  font-style: italic;
} 

/* maksudnya p adalah turuninan dari header, untuk replace dari p global */
/*
header p {  
  font-style: italic;
} 
*/


```

</details>

<details>
  <summary>EKI-20241105-017-Class-and-ID-Selectors</summary>

style.css
```css

/* untuk disable/enable command tekan "CTRL + /"  */

/* maksudnya p adalah turuninan dari header, untuk replace dari p global */
/*
header p {  
  font-style: italic;
} 
*/

/* maksudnya p adalah turuninan dari article dan header, untuk replace dari p global */
/* 
article header p {  
  font-style: italic;
}  */


/* --------------- PENGUNAAN ID HANYA BISA 1X UNTUK 1 VARIANT SELECTOR, UNTUK BERKALI2 HARUS MENGGUNAKAN CLASS--------------- */

#author {
  /* untuk selector yg memiliki id author */
  /* <p id="author"> */
  font-style: italic;
  font-size: 18px;

}

#author {
  /* untuk selector yg memiliki id copyright */
  /* <p id-"copyright"> */
  font-size: 16px;

}

/* --------------- / PENGUNAAN ID HANYA BISA 1X UNTUK 1 VARIANT SELECTOR, UNTUK BERKALI2 HARUS MENGGUNAKAN CLASS--------------- */

/* --------------- CLASS --------------- */

.related-author {

/* PENGUNAAN BISA BERKALI KALI */
/* 
<p class="related-author">By Jonas Schmedtmann</p>
<p class="related-author">By Jim Dillon</p>
<p class="related-author">By Matilda</p> 
*/

  font-size: 18px;
  font-weight: bold;
}

/* --------------- / CLASS--------------- */



/* --------------- SELECTOR VS CLASS VS ID --------------- */

/* UNTUK REMOVE POINT DOT "o" -> SELURUH SELECTOR */
/* ul {
  list-style: none;
} */

/* OR */

/* UNTUK REMOVE POINT DOT "o" -> BERKALI2 */
.related {
  list-style: none;
}


/* UNTUK REMOVE POINT DOT "o" -> SEKALI */
/* #related {
  list-style: none;
} */

/* --------------- SELECTOR VS CLASS VS ID --------------- */

/* NOTE : disarankan sebaik selalu menggunakan class walau hanya sekali, 
karena untuk menggunakan/perubahan ID akan error jika ingin digunakan kembali */

```

</details>



## EKI INDRADI

"TIME > KNOWLEDGE > MONEY". #2025_3_DIGIT_MOTIVATION

William Tanuwijaya quotes :

- "mimpikan, pikirkan, ucapkan, lakukan, konsisten"
- "ketika mimpi kita pikirkan, mimpi itu berubah bentuk jadi rencana"
- "ketika rencana kita ucapkan, rencana berubah bentuk lagi jadi komitmen"
- "ketika komitmen kita lakukan, komitment berubah bentuk lagi jadi kenyataan"

## Reference :

:link: https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3
