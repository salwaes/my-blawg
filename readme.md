# My Blawg: JS Selectors Practice

Open the included `index.html` in your browser. Then, write down how you would select the following DOM objects on "My Blawg".

# Part One: Vanilla JS

Use only the following methods or attributes:

- `querySelector`
- `querySelectorAll`
- `getElementById`
- `innerHTML`

---

1. The first `<a>` element on the page
  - `document.querySelector("a")`
- All `<a>` elements on the page
  - `document.querySelectorAll("a")`
- Using its ID, the `<h1>` at the top of the page
  - `document.getElementById("logo")`
- All elements with class `post`
  - `document.querySelectorAll(".post")`
- The first element with class `post`
  - `document.querySelector(".post")`
- The second element with class `post`
  - `document.querySelectorAll(".post")[1]`
- The HTML content of the first `<p>` element on the page
  - `document.querySelector("p").innerHTML`

# Part Two: jQuery

Use only the following methods or attributes: 

- `$`
- `eq`
- `html`

---

1. All `<a>` elements on the page
  - `$("a")`
- The first `<a>` element on the page
  - `$("a").eq(0)`
- Using an ID, the `<h1>` at the top of the page
  - `$("#logo")`
- All elements with class `post`
  - `$(".post")`
- The first element with class `post`
  - `$(".post").eq(0)`
- The second element with class `post`
  - `$(".post").eq(1)`
- The HTML content of the first `<a>` element on the page
  - `$("a").eq(0).html()`
- Using a CSS pseudo-selector, the third element with class `post`
  - `$("post:nth-of-type(3)")`
- Using its HTML attribute, the fourth `<img>` on the page
  - `$("img[alt=balloons]")`

