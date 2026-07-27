# This is the layout of the social links profile, which you can find on frontendmentor.io site (https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learnt](#what-i-learnt)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview 

### The challenge 

Users should have the opportunity to see the interaction with elements, it means to see hover on links wrappers. Also the profile have to be available on smartphones and other devices.

### Screenshot

Screenshot of the layout is located in the folder 'screenshot' (./screenshot/...).

## My process

First of all I linked style.css file, normalize.css file, to make the profile looking the same on every browser, and fonts.css, where I included all needed fonts. After that I coded HTML semantic basis for profile. Then I started coding from the top of the profile. I added description info, links and footer, where I put my links. Next I coded adaptive layout to make it looking normally on every device. And, finally, I cleared my code to improve its' readability and added some comments.

During the proccess of coding I used commits to increase the quality of my code and make it more understandable to other developers.

### Built with 

- HTML 5 semantic layout
- CSS custom properties
- Flexbox 
- Adaptive tools

### What I learnt 
During the process of coding I learnt how to make different transitions for users, who prefers reduced motion.

```
@media (prefers-reduced-motion: reduce) { /* Making different transitions for people, who prefers reduced motion */
  footer a {
    transition: all 3s linear 0s;
  }
  .section-list section {
    transition: all 4s linear 0s;
  }
}
```

Also I learnt how to work with searching engines and give them information.

```
<!-- Some info for search engines -->
<meta name="description" content="Social links profile layout. The challenge from frontendmentor.io. In layout there are profile of a woman, with links to other sites.">
<meta name="keywords" content="HTML, CSS, layout, HTML CSS layout, responive layout, responsive design, adaptive layout, frontendmentor challenge">

```

### Useful resources

- MDN documentation 

### AI collaboration 

During developing this project AI was not used.

## Author
Some of my links: 
- [FrontendMentor] [https://www.frontendmentor.io/profile/Redbegoon]
- [GitHub] [https://github.com/Redbegoon]

## Acknowledgments
I want to thank Frontend Mentor community. I see, that this community want's to grow and grow, no matter what. It's really inspiring. From my side, I also help some newbies, cause it's cool and you feel like you're doing a kind thing. 
