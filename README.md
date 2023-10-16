[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/zprwltzm)
# Typography CSS library
**Author:** [Karolína Fučíková](https://github.com/karolina-fucikova)
## Demo site
Link to **[demo](https://pslib-cz.github.io/2023-l4-web-typographic-library-karolina-fucikova/)** site for preview.
## Implementation

Add css file inside your project folder

Link style.css file to every HTML page using syntax:
```
<link rel="stylesheet" href="./css/style.css" />
```   
## Usage
Copy the HTML structure and link the CSS file. It's easily customisable.
## Typography
The Library has predefined system-ui font. If this font isn't from some reason implemented on the page, sans-serif will be used. 
## Colors
In library are predefined colours. Selector `:root` defines colours for normal website mode.
## Headings
* ```<h1>``` font size is 36px
* ```<h2>``` font size is 28px
* ```<h3>``` font size is 24px
* ```<h4>``` font size is 20px
* ```<h5>``` font size is 16px
* ```<h6>``` font size is 12px
## Types of text
### Normal text
Size of normal text is ```1em```.
### Styled text
* ```<strong>``` for bold text
* ```<em>``` for italic text
* ```<u>``` for underlined text
* ```<mark>``` for highlited text
* ```<sub>``` and ```<sup>``` for <sub>subscript</sub> and <sup>superscript</sup> text
You can even use predefined classes:
* ```<class="colored-text">``` for colored text
## Lists
### Unordered list
```
<ul>
    <li>Shark</li>
    <li>Jellyfish</li>
    <li>
      Fish
      <ul>
        <li>Anemonefish</li>
        <li>Whale</li>
      </ul>
    </li>
    <li>Porcupinefish</li>
</ul>
```
### Ordered list
```
<ol>
    <li>Whale</li>
    <li>Shark</li>
    <li>
      Fish
      <ol>
        <li>Anemonefish</li>
        <li>Porcupinefish</li>
      </ol>
    </li>
    <li>Jellyfish</li>
</ol>
```
## Gallery
### Flexbox gallery
In flexbox gallery is used class "flexbox__img" in block around the pictures.
```
<div class="flexbox__img">
    <figure>
      <img class="galerry__images" src="./img/turquoise1.jpg" alt="Turquoise" />
    </figure>
    <figure>
      <img class="galerry__images" src="./img/turquoise2.jpg" alt="Turquoise" />
    </figure>
    <figure>
      <img class="galerry__images" src="./img/turquoise3.jpg" alt="Turquoise" />
    </figure>
    <figure>
      <img class="galerry__images" src="./img/turquoise4.jpg" alt="Turquoise" />
    </figure>
</div>
```
### Grid gallery
In grid gallery is used class "grid__img" in block around the pictures.
```
<div class="grid__img">
      <figure>
        <img class="galerry__images" src="./img/turquoise1.jpg" alt="Turquoise" />
      </figure>
      <figure>
        <img class="galerry__images" src="./img/turquoise2.jpg" alt="Turquoise" />
      </figure>
      <figure>
        <img class="galerry__images" src="./img/turquoise3.jpg" alt="Turquoise" />
      </figure>
      <figure>
        <img class="galerry__images" src="./img/turquoise4.jpg" alt="Turquoise" />
      </figure>
</div>
```
## Buttons
There is predefined button class: ```class="button"```
## Table
```
<table>
      <thead>
        <caption class="table__caption">
          Oceans
        </caption>
        <tr class="tr1">
          <th>Ocean</th>
          <td>Area</td>
          <td>Average depth</td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>the Atlantic Ocean</th>
          <td>106 500 000 km²</td>
          <td>3 646 m</td>
        </tr>
        <tr>
          <th>the Pacific Ocean</th>
          <td>165 200 000 km²</td>
          <td>4 280 m</td>
        </tr>
        <tr>
          <th>the Southern Ocean</th>
          <td>20 330 000 km²</td>
          <td>3 200 m</td>
        </tr>
      </tbody>
</table>
```
## Quote tags
For one line quote text use tag `<q>`.
```
<q>Time is too slow for those who wait, too swift for those who
fear, too long for those who grieve, too short for those who
rejoice, but for those who love, time is eternity.</q>
```
For multiple line text use `<class="quotes__blockquote">` with `<blockquote>` and `<p>`. It displays author name under the quote block. Syntax:
```
<div class="quotes__blockquote">
  <blockquote>
    <q>To live is the rarest thing in the world. Most people exist, that
      is all.</q>
  </blockquote>
  <p class="quotes__blockquote--p">~ Oscar Wilde ~</p>
</div>
```
