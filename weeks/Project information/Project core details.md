
## Project idea

The initial project idea is to create a software that draws an abstract painting within 75 lines of code, and then passes its interpretation through a chain of different AI personas to see how the painting changes along the way. The steps are as follows:

1. The system selects a random abstract painting from an array. It will use a random number generator, and the generator will simply select a number between 0 and 49 (there will be 50 different abstract paintings, all from Pinterest and other painting platforms).
2. The first AI persona is shown the selected painting. It describes the painting in its own way, based on its characteristics, and the computer then draws a similar painting from that description.
3. The description is passed to the next AI persona, which has never seen the original painting. Based only on the previous description, the computer draws a new version of the painting, and the persona then writes its own description of it.
4. This repeats 5 times in total, so the painting passes through 5 AI personas. There will be 3 different personas, each based on different characteristics of people (one of them based on me), and they will be used in a set order.
5. The computer can use AI, but only to guide the computer in creating the artwork, not to create the artwork itself, otherwise the artwork would be flagged as AI. The AI can only give instructions and the computer just follows them, drawing the painting on pixels and nothing else.
6. One important rule is that every drawing in the chain must be 75 lines of code or lower.
7. At the end, the 5 drawings are compared with the original painting to see how much of it was kept, changed or lost as it passed from one persona to the next.



