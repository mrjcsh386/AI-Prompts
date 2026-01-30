# Exercise 7: Labels verses Soup
Objective: Understand where AIs lense falls within text.

AI is a brilliant intern with zero social awareness. If you put a sandwich and
a screwdriver on the same plate without saying anything, the intern might try
to butter the screwdriver.

The most curious thing about that, is that its perfectly normal for a human to
infer meaning when they're being instructed. The sandwich as is the screwdriver,
are both meta-symbols that represent intent, context and goals. I want to bring
you past expectation of conveyed intent. You're not talking to a vending machine
of intelligable answers. You're talking to a statistics driven calculator where
the information it parses are more so languistics, than mathematics.
---
## Instructions:
All within the same prompt, enter the following steps:
### 1. The "Soup" (The control)
I want you to give the model of choice a couple of data points that are
completely unrelated.
- Find a recipe for soup, copy and paste whatever you want from that into a
  prompt.
- Within the same prompt, tell the model about your day.
- Choose a random paragraph from a random source. This can be a random book on
  your shelf, or an interesting blog.
- At the end of this prompt, ask it to *summarize the important parts*.
The AI will likely give a generic summary that blends the book notes with the
recipe, or misses the "day" entirely because it got lost in the "soup."

### 2. The "Fences" (The delimination of variables)
After spending a little time trying to reason out why it gave you what it had,
let's take the exact same text and add something different to it.
- For each field of data, apply a title to it(i.e., RECIPE:, MY DAY:, BOOK
  NOTES:)
- At the end of each field, add `---` inbetween each field on its own line.

Did the AI stop '*buttering the screwdriver?*' Did it give you three distinct
summaries instead of one messy one?

## Reflection Questions:
- When does fencing play a key part in the models reasoning?
- What impact does deliminating the information have?
