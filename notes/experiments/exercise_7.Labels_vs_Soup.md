# Exercise 7: Labels versus Soup
Objective: Understand how AI interprets mixed text.

AI is a brilliant intern with zero social awareness. If you put a sandwich and
a screwdriver on the same plate without saying anything, the intern might try
to butter the screwdriver.

The most curious thing about that is that it's perfectly normal for a human to
infer meaning when they're being instructed. The sandwich and the screwdriver
are both symbols that represent intent, context and goals. I want to move you past
the expectation that the model infers intent like a human. You're not talking to a vending machine
of intelligible answers. You're talking to a statistical pattern engine where
the information it parses is language patterns, not intent.
---
## Instructions:
The following steps will be done within two prompts. One prompt for each step:
### 1. The "Soup" (The control)
I want you to give the model of choice a couple of data points that are
completely unrelated.
- Find a recipe for soup, copy and paste whatever you want from that into a
  prompt.
- Within the same prompt, tell the model about your day.
- Choose a random paragraph from a random source. This can be a random book on
  your shelf, or an interesting blog.
- At the end of this prompt, ask it to *summarize the important parts*.
Keep each section to a short paragraph so the effect is easy to see.
The AI will likely give a generic summary that blends the book notes with the
recipe, or misses the "day" entirely because it got lost in the "soup."
Ask for one combined summary here so the blend is visible.

### 2. The "Fences" (The delimitation of variables)
After spending a little time trying to reason out why it gave you what it had,
let's take the exact same text and add something different to it.
- For each field of data, apply a title to it (i.e., RECIPE:, MY DAY:, BOOK
  NOTES:)
- At the end of each field, add `---` in between each field on its own line.
Use both labels and separators so the boundaries are obvious to the model.

Labels give the model a map of what belongs together. Did the AI stop '*buttering the screwdriver?*' Did it give you three distinct
summaries instead of one messy one?
If it still blends sections, tighten labels or shorten each section and try again.

## Reflection Questions:
- When does fencing play a key part in the model's reasoning?
- What impact does delimiting the information have?
