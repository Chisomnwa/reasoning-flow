## Exercise 2: Step-by-Step Reasoning Prompt

**Objective:** Use structured prompting to encourage reasoning.

Choose a math or coding problem (e.g., "Calculate the factorial of 5").

Prompt the model: "Let's think step by step before answering."

Compare outputs with and without the reasoning instruction.

----

### First prompt: Calculate the factorial of 5

**Its response:**

Factorial means multiplying a number by all positive integers below it down to 1.

5! = 5 × 4 × 3 × 2 × 1 = 120

✅ Final Answer: 120


### Second prompt: Calculate the factorial of 5. Let's think step by step before answering.

**Its response**

Step-by-step reasoning:

Factorial means multiplying the number by all positive integers less than it down to 1.

5! = 5 × 4 × 3 × 2 × 1

Compute gradually:

5 × 4 = 20

20 × 3 = 60

60 × 2 = 120

120 × 1 = 120

✅ Final Answer: 5! = 120

---
## My Observation
So, comparing the outputs with and without reasoning instructions, I see that in the first prompt, it gave direct solution to the question, but in the second prompt, it gave a step by step process behind the reasoning before arriving at the answer.
