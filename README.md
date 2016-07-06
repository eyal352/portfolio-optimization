## Website Performance Optimization portfolio project

To access the webpage for analysis, go to [my webpage](http://www.eyalchistik.com/portfolio-optimization/).

### Index.html

The following optimizations were made to acheive a PageSpeedInsights score fo 90+ :

1. Compressed all image files
2. Added missing p tag.
3. Minified style.css and placed it in the header
4. Moved the print media query into its own CSS file to be called when media="print"
5. Moved all JavaScript to the bottom of the body element and added the async attribute

## Main.js

The following optimizations were made to optimize the frames per second on the pizza.html page:

1. Invoked "use strict";
2. Improved the for loop on changePizzaSizes by declaring a variable and then iterating on that variable
3. Removed ChangePizzaSizes, changeSliderLaber, and DetermineDx functions from within resizePizzas function.
4. Removed variable declerations from the for loop in the ChangePizzaSizes function
5. Removed variable declerations from the for loop in resizePizzas function
6. Reduced the number of background pizzas from 200 to 50.
7. Moved document.body.scrollTop into a variable outside of the for loop in the updatePositions function
8. Declared a new variable for the movingPizzas1 element selection outside of the for loop at the end of the script
