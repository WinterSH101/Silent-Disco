# Journal

## Phase 1
I used setInterval() to make the panel color change every 1.5 seconds. I used Math.random() and Math.floor to create random number of the red, green, and blue values. Having consistent interval keeps the light changing at a steady pace.

## Phase 2
Event bubbling is when you click on an element and the click also affects elements around them. Since the dancer is inside the dance floor, clicking the dancer could also change the floor's color. Using stop.Propagation() so clicking the dancer only affects the dancer and not the dance floor.