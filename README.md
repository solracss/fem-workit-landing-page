## [LIVE SITE](https://solracss.github.io/fem-workit-landing-page/)

# Frontend Mentor - Meet landing page

This is a solution to the [Workit landing page](https://www.frontendmentor.io/challenges/workit-landing-page-2fYnyle5lu) from www.frontendmentor.io

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [Info](#info)
  - [How to run](#how-to-run)
  - [Screens](#screens)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## Info

### How to run

Clone repo

```
git clone https://github.com/solracss/fem-workit-landing-page.git
```

Install dependencies

```
npm install
```

Start developemnt server and preview application

```
npm run dev
```

## My process

### Built with

[![My Skills](https://skillicons.dev/icons?i=html,css,sass,vscode,vite)](https://skillicons.dev)

### What I learned

1. Working with curved svg is not an easy stuff ;). Spent buch of time tried to set those for two sections.
   Managed finally to achieve this effect with

````css
@include pseudo() {
		--size: 4.7vw;
    background-image: url('/assets/images/curve-purple.svg');
		width: 100%;
		height: var(--size);
		left: 0;
		bottom: calc(var(--size) * -1);
		background-repeat: no-repeat;
		background-size: cover;
		background-position-y: 100%;
	}```

````

2. Another project that allowed me to train positioning elements. Here it was section with image and card.
