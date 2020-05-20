# Development Strategy

> `acme-web-design`

A fictional web site for HYF students to improve their front end skills

## Wireframe

`this web site consist of three web pages`

![home](./wireframe/home.png) ![about](./wireframe/about.png) ![service](./wireframe/service.png)

## 0. Set-Up

__Coches can see the initial repository and live demo__

### Repo

1. Created a new repository
2. generated as [this starter template](https://github.com/HackYourFutureBelgium/w3-validation-template).  
3. Give a title to your README  
4. Clone the repository  
5. add meta tags ,css file links and title in the head 
6. add wireframes 
7. Push the changes
8. turn on GitHub Pages

## 1._User Story_: Using header and nav tags

__**As coaches, we want to see header and navbar used in semantic way**__

### Repo

This user story was developed on a branch called `head-nav`

### HTML

- I used `<header> and <nav>` which describe its meaning to both the browser and the developer
- `div` is non-semantic block tag  which will help me with css to manipulating its content
- I gave `id` in div tag which is unique later on I will just change on this part with css or js

- I gave `class` in div tag for css later on which will changes all `class="container" ` align center and gives margin.

- `ul and li` block tags make unorder list  

- `a`inline tag for links the other pages such as `service.html` 

### CSS

After plain HTML, I will change css

## 2. _User Story_: Usig sections element

__**As coaches, we want to see section used in semantic way**__

### Repo

This user story was developed on a branch called `showcase-news`

### HTML

- I used `<section>` which describe its meaning to both the browser and the developer
- `form` block element which user can pass info on it
- `input` inline block element which shows area to user full info 
- `button` inline block element which submit user info to send server

### CSS

After plain HTML, I will change css

## 3. _User Story_: Usig more sections element

__**As coaches, we want to see section used in semantic way**__

### Repo

This user story was developed on a branch called `section-box`

### HTML

- I used `<section>` which describe its meaning to both the browser and the developer
- used `div` block elements for align in container
- add pictures with `img` block elements and `alt` is to describe picture for any case(when url is broken) also for people who are disabled for seeing
- the rest changes as above user stories  

### CSS

After plain HTML, I will change css

## 4. _User Story_: Usig footer element

__**As coaches, we want to see footer used in semantic way**__

### Repo

This user story was developed on a branch called `footer`

### HTML

- I used `<footer>` which describe its meaning to both the browser and the developer
- the rest changes as above user stories  

### CSS

After plain HTML, I will change css

## 5. _User Story_: Usig CSS properties and Selectors

__**As coaches, we want to see css properties and selectors using in the css file**__

### Repo

This user story was developed on a branch called `core-css`

### HTML

-add `span` inline element to change color of one of the words with CSS  

### CSS

- `font-family`property specifies the font for an element  
- The `font-size` property sets the size of a font
- The `line-height` property specifies the height of a line.
- The`margin auto` property to auto to horizontally center the element within its container
- The `overflow-hidden` is clipped, and the rest of the content will be invisible
- The `color` property  specifies the color of text.
- `The min-height` property defines the minimum height of an element. If the content is smaller than the minimum height, the minimum height will be applied.If the content is larger than the minimum height, the min-height property has no effect.
- `The text-decoration` property specifies the decoration added to text,
- Add `margin 0 and paddin 0` to `ul`because it has margin and padding by default
- the `float` property float navbar to right
- the `a:hover` selector to change style of elements or links when you mouse over it.Here I used for changing color of nabvar links
- `input[type="email"]` kind of selector to be more precise

## 6. _User Story_: Usig CSS properties and Selectors

__**As coaches, we want to see css properties and selectors styling footer and section**__

### Repo

This user story was developed on a branch called `style-box-footer`

### HTML

- add `id= "boxes"` in section elements to style boxes

### CSS

- `float`, use float to align all boxes to left
- the rest changes as previous user stories above

## 7. _User Story_: About Page

__**As coaches, we want to see in `about page` using semantic elements and styling**__

### Repo

 This user story was developed on a branch called `about-page`

### HTML

- Add the`articles` semantic elements in the`section` semantic element
- Add the `aside` semantic element in the `section`semantic element
- The rest elements and content copy paste from `index.html` page

### CSS

- `float`, use float to align the article and side bar
- The rest changes applied as previous user stories above

## 8. _User Story_: Service Page

__**As coaches, we want to see in `service page` using semantic elements and styling**__

### Repo

 This user story was developed on a branch called `service-page`

### HTML

- Add the`articles` semantic elements in the`section` semantic element
- Add the `ul` block element in the `article`semantic element to list different offers
- Add the `form` block element for user can send info
- The rest elements and content copy paste from `about.html` page

### CSS

- The rest changes applied as previous user stories above

## 9. _User Story_: Responsive

__**As coaches, we want to see  all pages as responsive**__

### Repo

 This user story was developed on a branch called `responsive`

### HTML

- Nothing changed

### CSS

- Add `Media Query` to make website responsive when screen of device equal and small than `max-width 768px`
- Remove float to make all divs as block
- `box-sizing: border-box` when you set width, this width includes (padding and border) but total width is `width+margin`
- The rest changes as user stories above
