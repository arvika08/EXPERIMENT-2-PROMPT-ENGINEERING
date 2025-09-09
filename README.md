# EXP-2-PROMPT-ENGINEERING-

# Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

# Algorithm:
Comparative Analysis of Prompting Patterns

Input:

Set of AI models to compare (e.g., ChatGPT, Gemini)

Set of prompting patterns (Zero-Shot, Few-Shot, Chain-of-Thought, etc.)

Set of test scenarios (math, writing, support, technical explanation, etc.)

Output:

Comparative table/report showing quality, accuracy, and depth differences

# Comparative Responses: ChatGPT vs Gemini

## Scenario 1: Mathematical Problem (7^13 mod 11)

Prompt (Chain-of-Thought):
“Solve step by step: compute 7^13 mod 11 using modular arithmetic rules.”

ChatGPT:
“Let’s compute step by step:
7 mod 11 = 7
7² = 49 → 49 mod 11 = 5
7⁴ = (7²)² = 25 → 25 mod 11 = 3
7⁸ = (7⁴)² = 9 mod 11
Now 7¹³ = 7⁸ × 7⁴ × 7¹
= (9 × 3 × 7) mod 11 = 189 mod 11 = 2.
Final Answer = 2.”

Gemini:
“7^13 mod 11 = 2.
Explanation:
7² ≡ 5 mod 11
7⁴ ≡ 3 mod 11
7⁸ ≡ 9 mod 11
Multiply: 9 × 3 × 7 ≡ 2 mod 11.”

Difference: ChatGPT = more verbose, guided reasoning. Gemini = concise, fact-driven with steps but minimal words.

## Scenario 2: Funny Birthday Wish

Prompt (Persona):
“You are a stand-up comedian. Write a witty birthday wish for a friend turning 25.”

ChatGPT:
“Happy 25th! You’re officially old enough to know better but still young enough to ignore that advice. Don’t worry — 25 is just level 2 of adulthood, and the boss fight is bills!”

Gemini:
“Happy 25th! Congrats, you’re now in that awkward stage where your back hurts more than your hangovers. Enjoy it while it lasts!”

Difference: ChatGPT = more story-like humor. Gemini = punchline-style joke, short and snappy.

## Scenario 3: Customer Support

Prompt (Instruction + Context):
“You are a helpful customer support assistant. The customer’s order is delayed. Respond politely, provide tracking steps, and suggest escalation if needed.”

ChatGPT:
“I’m really sorry your order hasn’t arrived yet. Could you please provide your order ID so I can check the status? In the meantime, you can track your package through your account. If the package doesn’t arrive in the next 2 days, I’ll be happy to escalate this to our logistics team for a faster resolution.”

Gemini:
“Sorry your order is late. Please share your order number so we can track it. If it still doesn’t arrive soon, we’ll escalate the issue to our shipping team.”

Difference: ChatGPT = empathetic + structured. Gemini = direct and action-focused.

## Scenario 4: Technical Explanation (TDMA Sectoring)

Prompt (Chain-of-Thought):
“Step by step, explain how sectoring improves capacity in TDMA: define TDMA, explain cell reuse and interference, compare 60° vs 120° sectors.”

ChatGPT:
“TDMA (Time Division Multiple Access) divides channels into time slots…
Sectoring reduces co-channel interference by splitting cells into smaller angular regions.

120° sectoring → 3 sectors per cell, moderate interference reduction, simpler implementation.

60° sectoring → 6 sectors per cell, stronger interference reduction, higher capacity but more hardware cost.
Conclusion: 60° sectoring offers the best interference management, though at higher complexity.”

Gemini:
“TDMA uses time slots to share spectrum. Sectoring reduces interference:

120° → 3 sectors, simpler, moderate gain.

60° → 6 sectors, more capacity, higher cost.
Best option depends on cost vs performance.”

Difference: ChatGPT = in-depth, layered, comparative. Gemini = condensed summary.

## Scenario 5: Teaching a Language (Beginner Japanese)

Task: Teach a beginner how to use the Japanese particle "を (wo / o)" in sentences.

Prompts & Responses
Broad Prompt

“Explain how to use the Japanese particle を.”

ChatGPT:
“を marks the direct object of a verb in Japanese. For example, in ‘パンを食べます’ (pan o tabemasu), ‘パン’ (bread) is the object, and ‘食べます’ (eat) is the verb. It shows what is being acted upon. Another example: ‘映画を見ます’ (eiga o mimasu) = ‘I watch a movie.’”

Gemini (likely):
“を (o) marks the direct object of a verb. Example: パンを食べます = I eat bread. 映画を見ます = I watch a movie.”

ChatGPT = richer explanation + extra examples.
Gemini = concise, dictionary-style definition.

# Overall Comparison

| Pattern                   | ChatGPT Style                         | Gemini Style                          |
| ------------------------- | ------------------------------------- | ------------------------------------- |
| **Zero-Shot**             | Explains + sometimes adds context     | Short factual answer                  |
| **Few-Shot**              | Imitates examples in tone             | Mimics examples but more concise      |
| **Chain-of-Thought**      | Step-by-step, very detailed           | Minimal but correct reasoning         |
| **Persona**               | Fully adopts role (creative/humorous) | Lighter role-play, sticks to brevity  |
| **Instruction + Context** | Empathetic, structured, professional  | Direct, efficient, less emotional     |
| **Broad Prompt**          | May over-explain                      | Often returns short, factual response |


# Result

ChatGPT shines as a teacher, explainer, and creative assistant. It provides depth, empathy, and interactivity, making it ideal for education, customer support, and content creation.

Gemini shines as a fast, factual assistant. It provides concise, efficient answers, making it ideal for quick lookups, summaries, and straightforward tasks.

The best results come when the prompting pattern matches the task:

Chain-of-Thought for math/technical (ChatGPT stronger).

Persona/Few-Shot for writing & teaching (ChatGPT stronger).

Instruction + Context for support & summaries (both good, Gemini more concise).
