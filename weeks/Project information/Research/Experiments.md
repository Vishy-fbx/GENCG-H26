
### Experiment 1: Which information helps the AI most?

**Variable:** what the AI is given.

- Title only (“Starry Night”)
- Text description written by you
- Color palette only
- Tiny 16x16 thumbnail
- Full image

**Expected results:** The full image wins, but a palette plus a short description gets surprisingly close.  
**Chosen Paintings**:

1. Monet, _Impression, Sunrise_ (impressionist)
2. Mondrian, _Composition with Red, Blue and Yellow_ (abstract)
3. Shishkin, _Morning in a Pine Forest_ (realistic)
### Experiment 2: Does the way you ask matter?

**Variable:** the prompt wording (same painting, same input).

- Minimal (“recreate this in 75 lines”)
- Detailed (plan composition, palette, and layers first, then code)
- “Think like a painter” (background first, then mid-tones, then details)
- “List what to leave out first, then code”

**Expected results:** Planning before coding beats the minimal prompt, especially on complex paintings.  
**Actual results:** 

### Experiment 3: How much does feedback help?

**Variable:** number of critique rounds.

- 0 rounds
- 1 round
- 3 rounds
- 5 rounds

Each round, the AI sees the original and the current canvas and fixes what’s wrong, within 75 lines.

**Expected results:** Big gains in rounds 1-2, then a plateau. Some paintings may get worse from over-correcting.  
**Actual results:** 

### Experiment 4: Who gives the feedback?

**Variable:** the type of critic.

- AI looks at both images
- AI gets a text description of the differences, written by you
- You give plain-word feedback (“sky too dark, tree too far right”)
- Only a number (“your score is 0.42, improve it”)

**Expected results:** Seeing both images beats numbers alone, but your plain-word feedback may beat the AI’s own critique.  
**Actual results:** 

### Experiment 5: How many lines are really needed?

**Variable:** line budget.

- 10 lines
- 25 lines
- 50 lines
- 75 lines
- 150 lines

**Expected results:** Quality rises quickly, then flattens. Abstract paintings flatten early (around 25 lines), while busy ones keep improving.  
**Actual results:** 

### Experiment 6: Which painting styles work best?

**Variable:** the style of the painting (uses data you already collected).

- Impressionist
- Abstract/minimalist
- Flat/graphic
- Realistic
- Complex/busy

**Expected results:** Abstract and flat styles score highest. Faces, fine detail, and perspective fail most.  
**Actual results:** 

### Experiment 7: Which techniques does the AI choose?

**Variable:** the technique used in the code (you tag every program).

- Gradients
- Noise
- Random brushstrokes
- Hand-placed shapes
- Loops with palette arrays

**Expected results:** Certain techniques show up for certain styles (noise for skies and water, hand-placed shapes for geometric art).  
**Actual results:** 

### Experiment 8: Is the result skill or luck?

**Variable:** randomness.

- Same code with a fixed `randomSeed()`
- Same code with no fixed seed (10 runs)
- Same prompt, AI generates the code 5 separate times

**Expected results:** The fixed seed gives identical results, while unseeded and regenerated runs vary a lot, so one good result might just be luck.  
**Actual results:** 

### Experiment 9: Who paints better?

**Variable:** the painter.

- The AI-guided computer
- A human with the same 75-line limit
- Dumb baseline 1: fill with the painting’s average color
- Dumb baseline 2: simple top-to-bottom gradient

**Expected results:** The AI beats both dumb baselines. A human may win on structure, while the AI wins on speed and palette.  
**Actual results:**

### Experiment 10: Does random selection work reliably?

**Variable:** which painting the computer randomly picks.

- Run the full demo loop 20 times with your best setup

**Expected results:** Most picks give decent results, but a few fail badly, which shows the method’s weak spots.  
**Actual results:** 

### Experiment 11: Do the numbers match what people see?

**Variable:** the judge.

- Pixel difference (MSE)
- Color histogram match
- Structural similarity (SSIM)
- Blind AI judge
- Blind human vote (10+ people)

**Expected results:** The math and humans disagree. A result that scores badly on pixels can still look right to people.  
**Actual results:** 
