# Development Strategy

> `App-theme`

A fictional web site for HYF students to improve their front-end and Git workflow skills.

## Wireframe

![wireframe](wireframe/wireframe-week-2.png)

## 0. Set-Up

__A User can see my initial repository and live demo__

### Repo

- Generated as this [starter template](https://github.com/HackYourFutureBelgium/w3-validation-template)
- Clone the repository
- Give a title and description of your project to your README
- Add meta tags ,css file links and title in the head
- Add wireframe
- Push the changes
- Turn on GitHub Pages

## 1.Using Flexbox grid into semantic HTML

__As coaches, we want to see HTML started with semantic elements with flexbox grid built-in classes without using external style(CSS)__

### Repo

This user story was developed on a branch called `semantic-flexbox`

### HTML

- Add semantic elements such as `<header>, <nav>, <section>, <footer>`.
- Add flexbox `row` class which  is a grid-based layout system `one row separated into 12 columns`
- Add flexbox grid class such as `col-xs-12,col-sm-8, col-md-6, col-lg-4` to make web site responsive for different screen sizes.
- Add alignment property `end` for align item into row to start from the end of the row
- Add alignment property `middle`for align item into row  vertically middle
- Add same rules above to `about, services, and contact pages`

### CSS

- Nothing has added  

## 2. Icons and Imgs

__As coaches, we want to see some fancy icons and imgs on the web pages__

### Repo

This user story was developed on a branch called `icon-img`

### HTML

- Add fontawesome icons to all pages company info section
- Add phone img to info core features section
- Change fontawesome links in the head of all pages because  the previous links doesn't apply the fontawesome icons  

### CSS

- Nothing has added  

## 3. Custom CSS for Home Page

__As coaches, we want to see the home page stand out in fancy styling__

### Repo

This user story was developed on a branch called `custom-css-home`

### HTML

- Added `middle-xs middle-sm ...` to header row to align content of row vertically in the middle (all pages).
- fixed `main h1` for sm screen size from `sm-10` to `sm-2` (all pages).
- Added `center-xs` small for header
- Remove `end-xs` for extra small screen, it centered now (all pages)

### CSS

- Gave a `margin auto` to class `container` because the container class does not work as a bootstrap container to center itself.
- Gave img `width 100%`to cover all its columns.
- Gave `font family` as Sans-serif
- Gave `Margin 0` to body it has by default a margin
- Gave `line-height`to give vertically space between lines.
- Gave a `bottom border`to main Header
- Gave a `background` img to showcase and centered it in the middle
- Gave `opacity` to background of showcase content to make it transparency
- Added `@media query` for specific size to show more responsive
- Changed `fontawesome icons` color and size
- Styled the rest`sections and footer` as same styling above

## 4. Custom CSS for the rest Pages

__As coaches, we want to see the about,services and custom pages stand out in fancy styling__

### Repo

This user story was developed on a branch called `custom-css-therest`

### HTML

- Added `center-xs` to company info for extra small screen size to be center of the container(all pages)

### CSS

- Gave `margin bottom` to main content for `about` page
- Reset company info background as `#333`
- `li:nth-child` used in `services` page to style for even or odd lists

## 5. Validation

__As coaches, we want to see all pages are validated by [Markup Validation Service](https://validator.w3.org/) and [CSS Validation Service](https://jigsaw.w3.org/css-validator/)__

### Repo

This user story was developed on a branch called `validation`

### HTML

- `<div>` remove from line 100 which is stray end tag(index.html)  
- `h1` changed to `h2`, warning: consider using the h1 element as a top-level heading only(index.html, about.html, services and contact.html)
- The value of the `for` attribute of the label element must be the ID of a non-hidden form control thus added `id` per label(contact.html)
- Changed `font-awesome` links it was not work on github for live page

### CSS

- changed `h1` selector to `h2`
