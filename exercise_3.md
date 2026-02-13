# Exercise 3: Multi-Step Question Answering\

**Objective:** Break complex questions into smaller steps.

Select a multi-step question (e.g., "What is 25% of the sum of 40 and 60?").

Create a prompt that asks the model to:

Restate the problem

Break it into smaller steps

Solve each step before giving the final answer

Review the reasoning process and check the accuracy of the final solution.

---

### First prompt: What is 25% of the sum of 40 and 60?"

**Its response:**

Let’s solve it step by step.

Step 1: Find the sum of 40 and 60

40 +  60 = 100

Step 2: Find 25% of 100

25% means: 25 / 100 = 0.25​

Now multiply:

0.25 × 100 = 25

✅ Final Answer: 25


### First prompt: What is 25% of the sum of 40 and 60?"
Restate the problem

Break it into smaller steps

Solve each step before giving the final answer

**Its response:**

***Restating the Problem***

We are asked to find 25% of the sum of 40 and 60.

That means:

First, add 40 and 60.

Then, find 25% of the result.

***Step 1: Find the Sum***
40 + 60 = 100

So, the sum is 100.

***Step 2: Find 25% of 100***

25% means: 25 / 100 = 0.25

Now multiply:

0.25 × 100 = 25

✅ Final Answer: 25

---
## My Review
After reviewing the reasoning process and checking the accuracy of the final solution, I see that the model had to break the problem into different steps, and this helps in easier understanding and solving the arithmentic problem in one step in the first prompt.