Idea: Pancakes + Masala Dosa(Nope)
	Masala Dosa(To Indian)
	Bircher Muesli(Yes, because it is Swiss to me)

Therefore
Idea = Bircher Muesli

Why?
Because bircher muesli is typically associated to a breakfast food in Switzerland, and I typically eat Bircher Muesli for breakfast at 8:30 AM. Therefore, this resonates personally with me

I did not pick the others, because I eat those foods at certain points in the day. For example, I eat pancakes for breakfast and for my evening snack. While I eat Masala Dosa(an Indian pancake with spicy potato stuffings) for breakfast and dinner.

Inspiration:
![[Pasted image 20260929162325.png]]

This artwork was my main inspiration behind this idea, because it reminded me of a show I watched last year during the Spring Semester(The name of the show is One Piece Live Action), and I really liked the protagonist specifically his love for eating. And I also like eating, specifically breakfast. Thus, I want to create something simple yet meaningful, that I like food.

## Concept
![[WhatsApp Image 2026-09-29 at 16.31.27.jpeg]]

# Creating the Clock

## Creating the frame

![[Pasted image 20260929172321.png]]

Here I am creating a 100 x 100 pixel canvas to display the clock. A 100 x 100 pixel canvas is appropriate because of the width of the plate and the height of my bowl

I have a backdrop of 220(which is light gray) because It makes the artpiece more relaxed and less intense.

## Defining the Plate
![[Pasted image 20260929172251.png]]

The plate is 100 pixels wide(across the canvas along the X-axis)

Where I learnt this: https://p5js.org/reference/p5/line/

Plus, I prompted into Google Gemini, How I can manipulate the width

![[Pasted image 20260929172531.png]]

I learnt I have to manipulate the 1st and 3rd value to change the width of a line

## Creating the Bowl

![[Pasted image 20260929173714.png]]

## The oats

`function setup() {
  createCanvas(100, 100);

  background(200);

  describe('A Plate');

  line(0, 75, 100, 75);

  describe("A Bowl")
  
  line(45, 20, 45, 75);

  line(70, 20, 70, 75);

  line(45, 70, 70, 70);

  describe("The Oats")
  line(45, 25, 70, 25);

  c = color(170, 139, 91);

  fill(c)
  noStroke()
  x = square(15, 15, 15)
}

function draw() {
  background(220);
}`

## Reflection

After this exercise, I felt much more confident using P5.js. Even though my artwork consisted purely of lines, I feel more confident coding using p5.js with the help of documentation. But, one thing, I will work on the future is to learn more commands of designing artwork, rather than using lines, trying to create something more abstract. I have made a stride in that effort, by learning the command vertex(). I have not understood where I should apply this concept, but I am aware that this command exists, and I hope to learn more about how I can use this command efficiently to carry out my objective. 