## Gustavo Corona
### REFLECTION.md made July 20, 2025

### What part of the code was most confusing and why?

The most confusing aspect would likely be understanding how setInterval creates a loop that runs independently and how clearInterval is needed to stop it. Also, calculating and smoothly displaying the percentage progress within the animation loop often presented an additional challenge.

### How does the animation help visualize asynchronous behavior?

The animation helps visualize asynchronous behavior because it updates continuously in the browser without stopping the rest of the web page. Even though the animation is running and changing the text, the browser remains responsive. This shows how tasks can execute over time without blocking the main program flow.

### What did you change or improve, and what effect did it have?

I added a feature to display a percentage complete as the animation runs. I changed the line that updates the loader text to include a calculated percentage. This made the animation much clearer, as it now shows exact numerical progress instead of just dots, which helps give a more visual idea of how the loading process is going. 