# Frontend Mentor - Stats preview card component solution

This is my solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). It's a simple yet effective challenge that helped me refine my layout and responsive design skills.

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements (if any)

### Screenshot

![Screenshot of the solution](./preview.png)

### Links

- Solution URL: [View on Frontend Mentor](https://your-solution-url.com)
- Live Site URL: [Live Preview](https://stats-preview-card-component-navy-rho.vercel.app/)

## My process

### Built with

- Semantic HTML5
- Tailwind CSS
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

While working on this component, I learned how to:

- Apply blend modes in Tailwind CSS for image overlays (`mix-blend-multiply`)
- Use utility-first classes to control responsiveness and spacing
- Design with an accessible color contrast in mind

Example of applying a purple overlay to an image with Tailwind:

```html
<div class="relative">
  <img src="./images/image-header-mobile.jpg" alt="Team working" class="w-full md:hidden object-cover" />
  <div class="absolute inset-0 bg-secondary opacity-75 mix-blend-multiply"></div>
</div>
```

### Continued development

I want to continue improving my use of:

- `mix-blend-*` and `bg-blend-*` utilities in Tailwind
- Accessible semantic HTML
- Creating fully reusable components in React with Tailwind

### Useful resources

- [Tailwind CSS Documentation](https://tailwindcss.com/docs) – Go-to resource for utility classes and responsive design.
- [Frontend Mentor Stats Preview Card Component solutions](https://www.frontendmentor.io/solutions?challenge=stats-preview-card-component-8JqbgoU62) – Great for design inspiration.

## Author

- Website – [Fawaz Iwalewa](https://iwaola.me)
- Frontend Mentor – [@fawaziwalewa](https://www.frontendmentor.io/profile/fawaziwalewa)
- Twitter – [@IwalewaFawaz](https://twitter.com/IwalewaFawaz)

## Acknowledgments

Thanks to the Frontend Mentor community for sharing helpful solutions and feedback. Special appreciation to those who inspire better UI through their clean and accessible designs.
