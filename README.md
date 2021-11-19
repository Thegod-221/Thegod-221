- 👋 Hi, I’m @Thegod-221
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Thegod-221/Thegod-221 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
window.snake.scheme({
  scoreBar:      '#rrggbb', // hex code for score bar, defaults to the default color if omitted
  background:    '#rrggbb', // hex code for background, defaults to score bar color if omitted
  walls:         '#rrggbb', // hex code for border and wall mode walls, defaults to default color
  shadows:       '#rrggbb', // hex code for snake and fruit shadows, defaults to default
  lightSquares:  '#rrggbb', // hex code for the light board squares, defaults to default
  darkSquares:   '#rrggbb', // hex code for the dark board squares, defaults to default
  lightGoal:     '#rrggbb', // hex code for the dark sections of the Sokoban goals; optional: OMISSION RECOMMENDED
  darkGoal:      '#rrggbb', // hex code for the light sections of the Sokoban goals; optional: OMISSION RECOMMENDED
  keyBlockMarks: '#rrggbb', // hex code for the marks on the key walls; optional: OMISSION RECOMMENDED
  sky:           '#rrggbb', // hex code for the sky color in the menu, defaults to default
  separators:    '#rrggbb', // hex code for thin separators in menu, defaults to default
  buttons:       '#rrggbb', // hex code for color of play and options buttons, defaults to default
}); // if not given any arguments, it will be the default scheme (with the page background the same color as the score bar)
