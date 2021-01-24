# Project 0: Football webpage 

ENGO 551 - Adv. Topics on Geospatial Technologies

## overview: 
This website is an assignment for the first lab of (Adv. Topics on Geospatial Technologies). In this website, I made six pages in which one page is the home page and the other pages are brief descriptions for five types of football games with some supporting material like tables and images. You can move from any page to any other pages by using the last field at the bottom of the page. 

## system requirement:
- Any platform you like such as Windows, Linux, and so on. 
- use any browsers (Firefox, Google Chrome,...) to display the html pages. 

## Tools used:
- HTML 5
- CSS
- Bootstap 4 
- Sass (you can download and install it from this [**Link**](https://sass-lang.com/install))

## How to use the webpage: 
- At first, open `home_page.html` file with any browser you like. 

![home_page](https://user-images.githubusercontent.com/26576895/105578883-f52aeb00-5d8b-11eb-9a72-688f5a989a1a.JPG)

- At the end of the page, you can choose any type of football you want to hold knowledge. 
- If you click on `the Association Football`, you will get a new window like this:

![Association1](https://user-images.githubusercontent.com/26576895/105578959-69fe2500-5d8c-11eb-8111-8c6b2f1defcf.JPG)

- If you like to return back to the home page or surf another page, scroll down to get the grid at the bottom of the page (Bootstrap 4 grid), like the below figure, that has all options you want.

![Association2](https://user-images.githubusercontent.com/26576895/105579098-0f18fd80-5d8d-11eb-9f13-b2fc4a0242c7.JPG)

- This grid exists in other pages but with a different layout to ease the moving from one page to another. 



## what’s contained in each file:
- `home_page.html`: contains the structure of the homepage, including the definition of football and an unordered list for types of football. 
- `home_page.css`: special style sheet for the `home_page.html` file. In this file, there are many different CSS properties, more than five properties, five different types of selectors (Multiple element selector, Descendant selector, Child selector, Pseudoclass selector, Pseudoelelement selector), and more than one id and class selectors. Media responsive is also utilized to remove arrow character when the width of the page is less than 600px.
- `Association.html`: has a brief describtion for the association football with an explanatory image and the table for the best players in this game. In addition, there is a grid at the bottom of the page that contains the links of other pages. The layout of this page is based on Bootstrap 4 in which has two components of Bootstrap (Container, Image card) and Bootstrap's grid model which contains the links of other pages.
- `Australian.html`,`Gaelic.html`,`Gridiron.html`, `Rugby.html`: All these files have the same layout of the `Association.html` file except they have different Bootstrap's columns in the Bootstrap's grid.
- `style.scss`: special SCSS file for five html files (`Australian.html`,`Gaelic.html`,`Gridiron.html`, `Rugby.html`, `Association.html`). The SCSS variable, SCSS nesting, and SCSS inheritance are implemented in this file with other CSS selectors and attributes. Moreover, The Bootstrap grid doesn't display in the print by using media responsive feature.
- `style.css`, `style.css.map`: these files are created by compiling the `style.scss` file.

## References:
- https://en.wikipedia.org/wiki/Football
## Demo:
- You can find demo video for this program at this [**Link**](https://www.youtube.com/watch?v=-icXDEC_xf0&feature=youtu.be&ab_channel=ahmedsayed)

