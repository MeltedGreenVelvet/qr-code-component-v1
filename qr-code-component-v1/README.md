# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## * Overview *

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## * My process *

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive Units

### What I learned

A lot of this is practice utilizing concepts I learned from Kevin Powell of Scrimba. I have not yet completed Scrimba's dedicated Jr. Front End Web Dev courses. The HTML was very simple. The css-- I struggled with setting an appropriate height for the QR component. I tried a px and % height, but neither worked out the way I wanted. I then tried vh, a unit I have limited experience with at the time this project was completed. Once this unit was utilized, my project's layout came out as I envisioned. Height is a finnicky css property, and this gave me a real world example of what units work and what units don't, depending on the layout's configuration and responsivity.

```css
.container-center {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	height: 100vh;
}
```

### Continued development

Flexbox makes sense to me as it's being taught during tutorials, but when going out into the coding wild-- Flexbox can give me issues. It can easily be broken with simple css properties (such as the height property). As I work to better myself, I feel that I need to analyze and be very familiar with what situations break flexbox so as not to waste my time or the time of my client/employer with troubleshooting the issue.

I'm aware that I need more practice in building responsive layouts as well. This site could remain completely static. However, I wanted to implement some responsivity into the component I created to play around with responsive units such as em, rem, vh, and %s.

I noticed that the Figma design file had text shadow in the H1 tag, but the screenshotted official solution did not. I went ahead and included the text shadow according to the Figma design that I was given.

### Useful resources

- https://stackoverflow.com/ - Of course, always a great addition in a dev's resource section. I feel that Stack Overflow is the very first website I go to whenever a piece of code is breaking, and I can't figure out why.
- https://www.w3schools.com/ - I regularly use this website to check my code's syntax. I can learn a concept quickly, but syntax is something that is acquired with usage and experience. Besides playing  creating with code, W3 Schools is great for helping me through that process.
- https://scrimba.com/ - A great partner to Frontend Mentor. I've been enjoying using both websites to advance my knowledge and refresh rusty skills.

## Author

- Frontend Mentor - [@MeltedGreenVelvet]
https://www.frontendmentor.io/profile/MeltedGreenVelvet
