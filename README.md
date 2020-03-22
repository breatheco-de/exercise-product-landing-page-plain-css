# Product Page (No bootstrap)

![Product Landing Page Exercise for HTML/CSS](https://github.com/breatheco-de/exercise-product-landing-page-plain-css/blob/master/preview.png?raw=true)

Doing layouts is one of the most difficult things in CSS/HTML, it has never been a good technology for that purpose, which is weird and sad because it's its main focus. 🤔🤪

But in the past couple of years everything has been improving, since 2018 we can use now the CSS rules `display: flex;` and `display: grid;`.

There are also some CSS frameworks like Bootstrap [that is broadly used in ~30% of the world websites.](https://w3techs.com/technologies/details/js-bootstrap), Foundation, Material UI, etc. But this exercise is focused mainly on polishing your plain CSS/HTML skills.

# 📝 Instructions

Replicate [this exact product page](https://github.com/breatheco-de/exercise-product-landing-page-plain-css/blob/master/preview.png?raw=true) in HTML/CSS. You cannot use any CSS framework and the landing does not have to be responsive.

Use the images on the `./src/assets` folder.

Use the flex-box CSS rules, here is a great document explaining about it: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

# 🥵 No one tells you this:

- 40% of the errors when doing HTML are missing or misplaced closing tags, to avoid that you should open a close the tag at the same time and then you fill the tag content.

- Picking the names of the CSS classes is the real trick: The names of the classes shape your mindset. Instead of using business-oriented naming like product1, product2, about-us, etc. You should use behavior-oriented names like `menu` or `horizontal-list`, etc. That will help you re-use classes a lot.

- Don't use the `<img>` for images that will be uploaded later by a user, you should instead use `<div>` with background images, the image tag is only used for little things.
