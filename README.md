# Week 2 Flexbox Practice: Moving Boxes Around the Screen

**Student Name:** Umwali Keza Kenia  
**Course:** Advanced Frontend Web Development

## 1. Project Description

This project demonstrates how CSS Flexbox can position six colorful boxes in nine different positions on the screen. The boxes move repeatedly using CSS animations without JavaScript.

The website displays only the numbered boxes against a light-gray background.

## 2. Technologies Used

- HTML5 — creates the structure of the webpage.
- CSS3 — styles the boxes and controls their positions.
- Flexbox — aligns the boxes horizontally and vertically.
- CSS animations — moves the boxes through nine screen positions.
- Git and GitHub — track changes and store the project online.

## 3. Flexbox Properties Used

- `display: flex` — creates a Flexbox container.
- `justify-content` — positions boxes horizontally.
- `align-items` — aligns items vertically within their flex lines.
- `align-content` — positions multiple flex lines within the container.
- `flex-direction: row` — arranges boxes in a row.
- `flex-wrap: wrap` — allows boxes to wrap onto additional lines.
- `gap` — adds space between boxes.
- `height: 100vh` — makes the container fill the viewport height.

## 4. The Nine Screen Positions

The CSS animation moves the boxes through these nine positions:

| Position | Horizontal Alignment | Vertical Alignment |
|---|---|---|
| Top Left | `flex-start` | `flex-start` |
| Top Center | `center` | `flex-start` |
| Top Right | `flex-end` | `flex-start` |
| Middle Left | `flex-start` | `center` |
| Center | `center` | `center` |
| Middle Right | `flex-end` | `center` |
| Bottom Left | `flex-start` | `flex-end` |
| Bottom Center | `center` | `flex-end` |
| Bottom Right | `flex-end` | `flex-end` |

## 5. CSS Animation

The `@keyframes moveBoxes` rule defines the nine stages of the animation.

The animation uses:

- `animation: moveBoxes 27s steps(1, end) infinite;`
- `27s` — sets the duration of one animation cycle.
- `steps(1, end)` — changes the layout in discrete stages.
- `infinite` — repeats the animation continuously.

## 6. Screenshots

The `screenshots` folder contains images demonstrating the boxes at different screen positions.

- [Top Left](screenshots/Top-left.png)
- [Middle](screenshots/Middle.png)
- [Bottom Right](screenshots/Buttom-right.png)

## 7. Video Demonstration

https://drive.google.com/file/d/1BMq9SF1AlqPUKvailj6q8letZKg76tFp/view?usp=drive_link


## 8. Conclusion

This project demonstrates how HTML, CSS Flexbox, and CSS animations can position six colorful boxes in nine screen positions without using JavaScript.

The exercise helped me practice flex alignment, wrapping, spacing, responsive styling, and animation.
