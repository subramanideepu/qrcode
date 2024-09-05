# Frontend Mentor - QR Code Component Solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents


  - [Screenshot](#screenshot)

  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



### Screenshot

Desktop View ![QR Code Component](desktop-design.jpg)
Desktop View ![QR Code Component](mobile-design.jpg)


### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I Learned

During this project, I learned about:

- **Using Flexbox for Centering:** Flexbox was used to center the card both horizontally and vertically on the page. This approach ensured that the component looks good on any screen size.

  ```css
  body {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    margin: 0;
  }
Responsive Design Principles: By setting width in relative units and using object-fit for images, the component adapts well to different screen sizes.

css

.qr-code {
  width: 100%;
  object-fit: contain;
}

### Future enhancements could include:

** Adding Media Queries: Implementing media queries to further adjust the layout and styles for various screen sizes.
** Accessibility Improvements: Adding ARIA roles and properties to enhance the accessibility of the QR code component.

### Useful Resources
Flexbox Guide - A comprehensive guide to using Flexbox for layout.
Google Fonts - Outfit - The font used for styling the text in the component.

### Author
KS. Premadeepthi
Frontend Mentor - @subramanideepu

### Acknowledgments
Frontend Mentor Community: Thanks to the Frontend Mentor community for their support and inspiration.
Design Inspiration: The challenge provided a great opportunity to practice and refine front-end skills.