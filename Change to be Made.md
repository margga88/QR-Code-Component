# Changes to be Made or Done

## Log

_21.04.2025_ There should be a **container of the card** and not use the body or main themselves for such purposes, because **there's no responsiveness vertically speaking**. Use the section semantics for the card and article for the text.

_22.4.2025_ Changes were made with the container and I could finally make it center regarding the screen size. This article was particularly helpful to identify the issues with the containers (https://medium.com/@gorokhovgleb/mastering-frontend-mentor-challenge-1-qr-code-component-553486fad21d). **Note: I should review the vh units and the box-sizing property**. 

_23.04.2025_ Silly me didn't remember that **vh stands for viewport height**, it makes reference to the height of the device viewport being 100 its max. Padding has been changed from 28px to 10px to fit my own screen, so now, media queries should be written for both 375px and 1440px where padding is the property to be modified.


## CODE DELETED

_23.04.2025_

```css
 .card {
    display: flex;
    justify-content: center;      
    flex-wrap: wrap;
 }
```

REASON: It was useless when the parent container (body) has already the specifications and it called more for .card to have its own wrapper.

_24.05.2025_ the .attribution div was moved to the footer section and adjusted with position property set absolute and a value for the bottom property.