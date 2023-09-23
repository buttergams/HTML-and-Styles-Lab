# Hello HTML and Styles Instructions  

 ## Objective

The purpose of this lab is to create your first HTML page
and understand how CSS styles applies to your HTML elements of the web page.

## Learning
 
In this lab, we will be learning the basics of HTML by focusing on HTML semantic tags and link tags. 

We will also utilize Emmet Abbreviations: shortcut key combinations that autofill content for us.

After building the HTML, we will style the web page with an external CSS sheet. 

We will also be practicing referencing a wireframe for creating our design. This lab is based off a real world scenario you might encounter in your role as a software developer; you may not be the one designing the websites, but you will be the one bringing them to life.

Topics:
- HTML
- HTML semantic tags
- HTML `<a href>` tag links
- VSCode Emmet Abbreviations
- Utilizing a given wire frame
- Styling with CSS

# Hello HTML and Styles Procedure

## Starting the HTML:

### Using the `!` HTML Emet Abbreviation

- [ ] Inside of `index.html`, type `!` and press `Tab`.
- [ ] This should create an empty HTML template for you to use.

> Example:
 
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
    
</body>
</html>
```

### Creating our HTML Layout

- [ ] Your tags to create this layout will live inside of the `<body>` tag pair.
  - This is true for every website you build.
- [ ] In the `<title>` tag, change the name of the page by erasing the text `Document` and typing `Home`.
- [ ] In our website, we will need to create the following semantic div tags: `<header>`, `<nav>`, and `<main>`. Type each inside the body tag but on a new line, jump to the next line with `enter` after writing each tag. Be sure to include their closing tag.

### Filling out placeholder content

- [ ] In the `<header>` create a title for the page by adding text between the opening and closing `<header>` tags.
- [ ] In `<nav>` create at least three`<a href>`s that will navigate to other pages on the site. Leave them blank for now.
- [ ] Within the `<main>` tag  we need to add an `<img>` tag and placeholder text via adding one or two `<p>` tags.
- [ ] To access placeholder images, here are a few options to try: [Lorem Flickr](https://loremflickr.com/), [Placekitten](https://placekitten.com/). [Lorem Picsum](https://picsum.photos/).
- [ ] To generate placeholder text in VSCode or Replit, type `lorem100` and press `Enter`. This will generate 100 words of placeholder text. You can change 100 to be whatever amount of words you want. `lorem5000` is also valid.

### Creating multiple pages

- [ ] In the same directory as `index.html`, create another file named `about.html`
- [ ] In `about.html`, use the emet abbreviation, `!`, again to generate the necessary HTML boiler plate.
- [ ] Inside of `<body>`, write in a `<p>` tag to inform us of which page we are on, for now just add text that says `About Page`.
- [ ] Create two more pages in the exact fashion you created `about.html`.
  - These are your unique invention and should have unique names.
  - Be sure to also create a `<p>` tag in the body of these unique pages like we did for the `about.html`.
- [ ] For each new page, be sure change the `<title>` tag text content to reflect which page the user is on. 

### Linking to our new pages

- [ ] Back in `index.html`, return to the `<a href>`s in the `<nav>` tag.
- [ ] For the first `<a href>`, point the link to `./about.html` by setting the href like so: `href="./about.html"`. Name this link `About` by adding text between the opening and closing `<a>` tags.
- [ ] Fill out the other two `<a href>`s so that they correspond to the two additional pages that you created.
  - Be sure they each have text content that corresponds with each page title and that the hrefs are set to the right file.

## Styling with CSS:

### Creating the `styles` subdirectory and `styles.css`
- [ ] Inside of your Replit, create a new folder named `styles`.
- [ ] Inside of `styles`, create a new filed named `styles.css`
- [ ] `styles.css` is where all of your CSS will be written.

### Linking `styles.css` to `index.html`
- [ ] Inside of `index.html`, you will need to link your stylesheet via a `<link>` tag added in the `<head>` tag section of the HTML file.`
  - This is usally placed above the `<title>` tag.
- [ ] In the `href` attribute for the link, you will need to route your link through the `styles` subfolder to reach `styles.css` file, the finished tag should look like this `<link rel="stylesheet" href="./styles/styles.css" />`.

### Opening the wireframe

- [ ] Click the following link to open the wire frame: [Figma Wire Frame](https://www.figma.com/file/XfSzyWby8nkpIolSql6R4S/hello-styles-wireframe?node-id=0%3A1).
- **Note:** This wireframe is not "pixel perfect" so don't stress having it match dimensions exactly. We are looking to capture the spirit of the wireframe.

### Understanding the wireframe

- This wireframe has areas that correspond to the semantic divs you already have from Hello Html.
- `<header>` matches the HEADER TEXT areas.
- `<nav>` matches the LINK areas that contain four links.
- The white boxes with black diagonal lines should be placeholder images utilizing the `<img>` tag.
- `<main>` matches the MAIN TEXT areas. You will note that on the ABOUT PAGE, there are two MAIN TEXT areas with space between them. This is intentional.

### Styling the semantic divs

- You will need to utilize [CSS selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors) in order to style your divs. `id` and `class` are the most common utilized.
  - [ ] Add an `id` property to the `<header>`, `<nav>`, and `<main>` opening tags like so:
    - [ ] ```<header id="headerTag">```
    - [ ] ```<nav id="navbar">```
    - [ ] ```<main id="main">```
  - [ ] Add a `class` property to the `<a>` and `<p>` tags.
    - [ ] All opening `<a>` tags should have a class property written like so:
        -  ```<a class="links">```
    - [ ] All opening `<p>` tags should have a class property written like so:
        -  ```<p class="paragraphText">```
- You will also need to utilize [CSS properties](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Properties_Reference). As mentioned earlier, `margin`, `padding`, and `display` will be the most useful for achieving the layout.
  - In the `style.css` file, add the above styling properties to the class and id values of your tags. Do your best to match the layout of the given wireframe. 

## Achievment

You have now created a basic website using HTML! It has a layout, placeholder content, and multiple pages connected by `<a href>` links.

You were able to utilize a given wire frame to style your website with CSS according to its guidelines.

Your work resulted in:

- A website created with HTML.
- A website laid out utilizing semantic div tags.
- A website that has placeholder content.
- A website that has multiple pages navigable by `<a href>` links.
- A website with styling that closely matches the given wire frame.

## Review

In this lab, we have created an HTML page and translated a wireframe to style that page with CSS.

The software should:
- Have a Home page the user lands on.
- The home page should contain the `<header>`, `<nav>`, and `<main>` semantic divs filled out with placeholder content.
- Have multiple pages that can all be navigated to via the links in `<nav>`.
- Be a styled website whose design matches that presented in the wireframe.

## Going Futher

If you would like to push yourself and practice your researching and developing skills, feel free to try the following additions or "stretch goals"!

- [ ] Add `<a href>`s to your additional pages that allow the user to navigate back to the Home page.
- [ ] Add different placeholder content to your additional pages. Utilize different semantic tags than those initially given.
- [ ] Style your `<a href>`s to appear as buttons rather than links. You can research **inline styles** to do this. This will be bringing in CSS.
- [ ] Customize the colors on the website.
- [ ] Import fonts and utilize them.
- [ ] Style your additional pages created and try to have the visual design of these additional pages be coherent with the styling of the first two.