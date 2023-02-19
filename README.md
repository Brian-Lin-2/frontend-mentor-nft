# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Basic NFT card with interactive portions.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

<img src="https://user-images.githubusercontent.com/19761406/219833820-dde3f7e4-2172-4a75-8822-09ada12055fa.png" width="300px">

<img src="https://user-images.githubusercontent.com/19761406/219833890-63148ba0-dd69-4de5-a7b4-6658f0ea1db7.png" width="300px">

<img src="https://user-images.githubusercontent.com/19761406/219834061-601f201a-526f-4e37-ad09-1c09e681263b.png" width="300px">

<img src="https://user-images.githubusercontent.com/19761406/219834102-9063d356-db62-4d8d-93d7-d208330c9eb4.png" width="300px">

### Links

- Solution URL: (https://github.com/Brian-Lin-2/frontend-mentor-nft)
- Live Site URL: (https://frontend-mentor-nft-ten.vercel.app)

## My process

Started off mapping out the basic html design; highlighting each div container. Then I transitioned into creating a flexbox outline. After that, I added the css styling. Finished with the hoverable elements of the NFT.

### Built with

- HTML5
- CSS
- Flexbox

### What I learned

Learned a lot about HTML positioning, especially between parent and child divs. Learned how to center a child div inside a parent div.

```css
.wrapper {
  position: relative;
}

.ontop {
  position: absolute;

  /* Centers the image. */
  /* Same as top, left, right, bottom. */
  inset: 0;
}
```

Learned about the hover attribute.

```css
.header:hover,
.name:hover {
  color: hsl(178, 100%, 50%);
  cursor: pointer;
}
```

### Continued development

More focus on general HTML div formatting. More focus on flexbox type designs. More practice with interactive css (ie. hover). Transition into a mobile-first workflow for larger projects.

### Useful resources

- [Resource for hover effect](https://www.youtube.com/watch?v=tF3RE5CGt9U&t=461s) - This helped me make the image interactive. Explained very well.

## Author

- Frontend Mentor - [@Brian-Lin-2](https://www.frontendmentor.io/profile/Brian-Lin-2)

## Acknowledgments

Thank you to my friend Ming for helping me with the interactive css component of the eye icon.
