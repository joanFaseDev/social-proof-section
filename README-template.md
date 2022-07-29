# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Analysis](#analysis)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Project on GitHub](https://github.com/joanFaseDev/social-proof-section)
- Live Site URL: [Project hosted through Vercel](https://social-proof-section-five-roan.vercel.app/)

## My process

### Analysis

- Project is about building a responsive web page made out of two designs, mobile and desktop.
- The page displayed two different kind of cards, each in three units. That means we can reuse a lot of code just by using efficient naming convention and simple analysis.

- The first type of card is made of five icons that can be grouped in a _div_ element plus a heading which means we can use a _section_ as a container since _article_ doesn't really fit the situation (these cards are not standalone content). All the cards will be nested in a _div_ container mainly because it will be easier to handle when doing the desktop design.

- The seconde type of card is a basic profil card with a name, photo, status and comment. Basically we can use a _section_ as a container, a _h2_ for the title and a pair of _p_ for status/comment. Between the _section_ and the content, we'll add an other _div_ for the layout.
  Again, all the cards will be nested nested in _div_ so that it can be used when doing desktop design.

- Apart from the two types of card, there's also a main title and a paragraph. That will be our _h1_ and _p_,nested in a _div_.

- We'll use a _main_ element as a container for the whole then change the _body_ into a flexbox for the alignement.
- We'll start with the mobile design first because it's easier to lay out. There's less complexity and it's basically the standard way nowadays (from what i read and saw).
- For the desktop design, we'll use _media queries_ plus simple _CSS Grid_ and _FlexBox_. The 'star' cards will each have a different horizontal alignment (_flex-start_, _center_, _flex-end_) and the 'profil' cards a different vertical alignment.

- There's also two different background images to include for each design, mobile and desktop. We'll dealt with it at the end because of personnal preferences (i always find it easier that way).

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
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

- Frontend Mentor - [@joanFaseDev](https://www.frontendmentor.io/profile/joanFaseDev)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
