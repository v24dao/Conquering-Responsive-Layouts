#Block Element Modifier (BEM)

https://www.youtube.com/watch?v=SLjHSVwXYq4

##What is BEM?

- Consider a block called `card`
- We represent elements of our block with 2 underscores as follows `card__title`, `card__image`
- Similarly, we represent modifiers with 2 dashes as follows `card--light`, `card--dark`

##Why use BEM?

- Eliminates the need for repeated code (DRY principal)
- Sense of consistency
- Helps with the issues that can arise with specificity that is caused by nesting

- Consider our cards:
- All shared characteristics will be under `.card` in css
- All individual characteristics will be under `.card--light` and `.card--dark` respectively

##A note on nesting

- The more code you write, the more potential problems you can run into (especially on bigger projects)
- Minor nesting is fine, and nesting is fine on smaller sites, but it is good practice to use a naming convention

##A note on BEM

- It is less about picking a system that is `right`, but it's more about picking one that makes sense
- Companies may not use BEM, but will always use a naming convention!
