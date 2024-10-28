# Dynamic "Stars twinkle" effect

This is a dynamic "star flicker" effect, with stars constantly appearing and disappearing above the text. Stars shoot out from around the text in random sizes, colors, and motion tracks, creating a dreamy and dazzling visual effect.

## Implementation principle

1. CSS style:
- Set the background color, font style, and star style.
- Use CSS variables to control star size, color, and animation effects.
- Defined a @keyframes animation that moves stars from their starting position to their ending position, changing transparency and rotation as they move.

2. JavaScript logic:
- Defines a Star class for creating star objects and setting their random properties (size, position, color, etc.).
- Use the setInterval timer to generate new stars periodically until the maximum number of stars is reached.
- Each star is removed after a certain amount of time to ensure that the page does not cause performance problems due to the number of stars.

## Use scenario
- Web decoration: can be used for holiday-themed websites (such as Christmas, New Year's Day, etc.) or celebratory pages to increase the festive atmosphere.
- Game interface: Used in the game as a special effect to enhance the visual experience.
- Works of art: Used to display works of art or creative projects to attract users' attention.
- Advertising: attract the user's attention in the advertising page and increase the interactivity.