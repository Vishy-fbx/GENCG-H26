---
title: Instructions & Systems
date: 2026-09-14
week: 1
tags:
  - instructions
  - systems
  - journal
publish: true
---

> [!important] Complete this week's exercises and reflections yourself
> Lesson 01 is a **Human-only** session: do not use generative AI to invent rules, write or debug the p5.js exercise, or write your process notes. This page is only a structure for documenting your own work.

- [Lesson 01: Instructions & Systems](https://digitalideation.github.io/gencg_h2601/lessons/lesson01_intro/)
- [Journal guidelines](https://github.com/digitalideation/gencg_h2601/blob/refactor_2026/lessons/extra/journal.md)

## Evidence checklist

Keep evidence of the process, not only the successful result.

- [x] Original drawing or idea
- [x] First instruction set
- [x] First execution by another person
- [x] Moments of confusion or ambiguity
- [x] Revised instructions
- [ ] Second execution
- [x] Small rule system
- [x] Sketch or diagram of the system
- [ ] p5.js translation

<!-- Add images to ./sketches/ and embed them like this:
![[./sketches/your-file-name.jpg]]
-->

## 1. Exploration & Experimentation

### Human → Human

**Original idea**

![[WhatsApp Image 2026-09-15 at 17.44.00.jpeg]]

**First instruction set**

1.Draw a big circle
2.Draw 3 lines from right to left on top of the circle
3.Add a huge dot
4.Draw two vertical triangles above the dot
5.Draw another line down to the end of the circle
6.At the midpoint of line, draw another line right with steps
7.Draw a house

**First execution**

(Execution by Anissah Quraishi)
![[WhatsApp Image 2026-09-21 at 21.44.01.jpeg]]

**Where did interpretation differ?**

-The house is outside the circle
-No mountains(but it was my fault for not mentioning it)
-Instead of rectangles, there are triangles


**Revised instructions**

1.Draw a big circle covering the middle of the paper, please note all the drawings you will make should be in the circle
2.At the middle of the page, draw a line going straight across
3.at the top half, draw three lines from the right to the middle of the top half
4.Draw a massive dot, with the end of the three lines covered by the circle
5.From the circle, draw a line all the way to the bottom of the bottom half
6.At the middle of the line in the bottom half, create another line, but as you get closer to the edge, start to create steps, you can add 1 or more steps as you please
7.At the end of the steps, draw a house
8.Above the dot earlier, draw TWO RECTANGLES(RECTANGLES, I REPEAT RECTANGLES)
9.Somewhere to the right of the line in the bottom half, draw mountains as triangles without a base
10.Congratulations, you have drawn my route from Basel SBB to my house, with all the geography of Basel included! Hopefully you learnt something abt Basel

**Second execution**

<!-- Embed or link the second result. What changed? -->

### Small rule system

- **Starting condition:** A piece of A4 paper, 210mm × 297mm.
- **Action:** Draw the route from Basel SBB to my house
- **Relationship:** There will be dots, lines, rectangles, uncompleted triangles and a custom mathematical polygon
- **Variation:** Number of steps at the end of the path may vary (1 or more, drawer's choice); exact placement of the mountains (triangles) to the right of the line may vary, as long as they stay within the circle.
- **Constraint:** My address is not provided, so you can't look at google maps and draw my route.
- **Stopping rule:** You have drawn a house at the end and is within the circle

![[Pasted image 20260922165243.png]]
I tried

### Human → Computer

What did a human understand automatically that the computer needed you to specify?

-
-

```js
function setup() {
  createCanvas(400, 400);
  background(240);

  circle(200, 200, 400);
  
  stroke(0);
  strokeWeight(8);
  line(30, 20, 80, 75)
}
```

**Parameters tested**

| Parameter | Values tried | What changed |
| --------- | ------------ | ------------ |
|           |              |              |
|           |              |              |

**Technical challenges or failed attempts**

-
-

## 2. Influences & References

Choose at least one work, artist, or idea from the lesson or your own research.

- **Artist / work:**
- **Link or citation:**
- **What I noticed:**
- **How it connects to my experiment:**

Possible starting points from the lesson include Sol LeWitt, Conditional Design, George Brecht, Alison Knowles, and Yoko Ono.

## 3. Algorithmic Thinking

**What stays fixed?**

-

**What can vary?**

-

**Describe the system in plain language or pseudocode**

```text
START

ADD YOUR RULES HERE

STOP WHEN ...
```

**How do the rules produce the visual result?**

<!-- Explain the relationship between your instructions and the outcome. -->

## 4. Critical Reflection

- One thing my executor interpreted differently was...
- One rule I changed was...
- One ambiguity I decided to keep was...
- One thing I had to make explicit for the computer was...
- What worked or surprised me?
- What did not work, and why?
- What would I explore next?

## Next steps

- [ ] Save all drawings and outputs
- [ ] Check that images and links work
- [ ] Choose one question to carry into Week 2
