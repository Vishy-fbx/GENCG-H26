### Experiment 1: Creating a painting using Javascript

Variable: User input

Basically, I take the Mondrian, describe the painting in my own words on a text file, copy and paste the description of the painting into Claude and other LLMs, Prompt the LLM to output specific code, the generated code is pasted into P5.js and then the painting is outputted. All the paintings will be ranked subjectively based on painting visuals. 

The LLMs used to generate the code is as follows:

1. Claude
2. Google Gemini
3. ChatGPT
4. Copilot
5. A custom replicate LLM

Predicted results: The replicate LLM will create code that will create a more detailed painting than the other LLMs. 

### Experiment 2: Does the order of personas matter?

Variable: the order of the chain.

- Literalist → Storyteller → Minimalist → Literalist → Storyteller
- Minimalist → Storyteller → Literalist → Minimalist → Storyteller

Same paintings and same starting description. Run each chain 2 times per painting.

Expected results: the first persona matters most, because everything after it only sees its words.  
Actual results: (fill in after running)

### Experiment 3: Is it the personas or the telephone game itself?

Variable: mixed personas vs one repeated persona.

- Mixed order (the Experiment 1 chain)
- Literalist × 5
- Storyteller × 5
- Minimalist × 5

Expected results: mixed chains drift the most, but repeated chains also drift, which shows that part of the loss comes from the process itself.  
Actual results: (fill in after running)

### Experiment 4: Who describes first?

Variable: who writes the starting description.

- You
- Friend 1
- Friend 2
- Optional: an AI persona that sees the original

The AI chain stays the same. Run it on the Mondrian only.

Expected results: the starting description affects the result more than any persona does.  
Actual results: (fill in after running)

### Always measured

- Pixel difference (MSE) and similarity % for every drawing, compared with the original
- Blank-canvas and average-color baselines
- Blind human ranking of the 5 renders from one chain (5-10 people)