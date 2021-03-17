## JS Clock

### Key Learnings

**transition and transform**

- transition: [property] [duration] [timing-function] [delay];
- transform-origin: 100% to rotate hands from extreme right end. By default rotation is done center (50%).

**CSS Positions**

- Relative: Always relative to it's original position. Element is not taken out of normal flow of document.
- Absolute: Always relative to it's parent or viewport. Element is taken out of normal flow of document.
- Fixed: Always relative to viewport. Element is taken out of normal flow of document.

**setInterval function**

- Calls the function at every specified interval.

**UTC time**

- Universal Time Coordinated. Global time for all the people on earth!

**Degrees of Clock Hands**

- Initially clock hands are rotated 90deg to point to '12' by default.
- Formula to get degrees based on time : (current / total) \* 360;
- In our case we modify it to (current / total) \* 360 + 90. Because our hands were rotated to 90deg initially.

### References

- CSS Position: @ https://www.youtube.com/watch?v=jx5jmI0UlXU
- CSS Animation: @ https://scrimba.com/learn/cssanimations
- CSS Transform: @ https://developer.mozilla.org/en-US/docs/Web/CSS/transform
