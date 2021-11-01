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

**Note: Delete this note and update the table of contents based on what sections you keep.**

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
    - Mobile-first workflow
  

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I started to learn how to use semantic HTML more efficiently rather than 'throwing' div tags everywhere. Searching or researching for the best tags to use is not something i usually do, but in this project, i paid attention to using the best tags for the job and i will start to apply this to other projects i work on moving forward.
I also never really learnt the BEM method of naming my CSS classes so i started to learn that and be more concious is making sure my CSS classes are named according to the BEM standard and are readable.
I encountered a chaallenge in one of the sections. i name it statistcs. i had a chanllenge with aliging the little images with the number text below it. i solved it by giving it a margin right. there is probably a clearner solution to this but well, for now, that's the solution i used.

To see how you can add code snippets, see below:

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
/* this code was to make a text wraped in a span tag go to the next line. the default display on the span tage is inline.  */
.statistics_figures p span{
    display: block;
}

```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
