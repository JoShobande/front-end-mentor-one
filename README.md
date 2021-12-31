# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

  ### The challenge

    Users should be able to:

    - View the optimal layout for the site depending on their device's screen size
    - See hover states for all interactive elements on the page

  ### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

  ### Links

    - Solution URL: [Add solution URL here](https://your-solution-url.com)
    - Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

  ### Built with

    - Semantic HTML5 markup
    - Flexbox
    - Grid
    - Mobile-first workflow
  

### What I learned

I learnt how to use semantic HTML more efficiently rather than 'throwing' div tags everywhere. Searching or researching for the best tags to use is not something i usually do, but in this project, i paid attention to using the best tags for the job and i will start to apply this to other projects i work on moving forward.
I also never really learnt the BEM method of naming my CSS classes so i started learning that and I also made the conscious effort to name my CSS classes according to the BEM standards.
I encountered a chaallenge in one of the sections named statistcs. i had a chanllenge with aliging the little images with the number text below it. i solved it by giving it a margin right. there is probably a clearner solution to this but well, for now, that's the solution i used.

i made efficient use of grid in this project especially an aspect of grid called grid template areas. a snippet of code is shown below



```html
<!-- In the code below, i used the figure tag to wrap the img tag, before now, i have never used the figure tag so i am proud of my self :) -->
<Section class="statistics">
            <figure>
                <img src="assets/images/screen-mockups.svg" />
            </figure>
            <div class="statistics_figures">
                <img src="assets/images/icon-communities.svg"/>
                <p>1.4K+ <br/><span>commuminties formed</span> </p>
            </div>
            <br/>
            <br/>

</Section> 
```
```css
/* this code was to make a text wrapped in a span tag go to the next line. the default display on the span tage is inline.  */
.statistics_figures p span{
    display: block;
}

/* the code below shows the use of grid, grid template areas. */
.users-section_content{
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        grid-template-areas: 'text illustration';  
        align-items: center;
    }
    .users-section_content .illustration{
        grid-area: illustration;
    }
    .users-section_content .text{
        grid-area: text;
}

```
```js

```

### Continued development
Moving on, i will continue learning CSS. i will like to gain more indepth knowledge on CSS.  also drawing curves in CSS without neccesarily having to use an image. i want to learn better alternatives to using images in projects.

### Useful resources
my main resourse was google. different searches accross google about writing semantic html and the likes.

## Author

- Website: still under development :)
- Frontend Mentor - [@JoShobande](https://www.frontendmentor.io/profile/JoShobande)
- Twitter - [@Jossiieeeeee](https://www.twitter.com/Jossiieeeeee)


## Acknowledgments

:)
