# [Link to GitHub pages with homework 2](https://carlos-eac.github.io/construction-class-example/)

I designed a simple menu with a utilitarian aesthetic.
To this end I used margin and padding options like `margin-top: 0px;` and `padding-top: 0px;`
to make the background cover the entire top of the page.
I chose `background-color: #D3D3D3;` to give the menu a light grey background.
`font-family: Helvetica, sans-serif;` sets the font and sans-serif as the fallback font family.
As required I used flexbox for the spacing to adapt to the tab size (`justify-content: space-between;`).\
Finally I made the links change color and become underlined when the user hovers over them with
```
.menu a:hover {
  color: #0000EE; /* #0000EE is the default link color */
  text-decoration: underline;
}
```
