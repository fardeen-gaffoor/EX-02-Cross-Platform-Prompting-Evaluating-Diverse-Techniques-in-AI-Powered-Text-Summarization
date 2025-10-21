# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
Algorithm

Step 1: Define the Objective
1.1 Identify the purpose — to summarize a 500-word article on Blockchain Technology.
1.2 Define evaluation parameters — Accuracy, Coherence, Simplicity, Speed, and User Experience.

Step 2: Select Platforms
Choose the following AI models for testing:

ChatGPT (OpenAI)

Gemini (Google DeepMind)

Claude (Anthropic)

GitHub Copilot (OpenAI + GitHub)

Step 3: Select Prompting Techniques
Apply the four major prompting strategies:

Zero-Shot Prompting:
Prompt: “Summarize the article on the basics of blockchain technology in simple words.”

Few-Shot Prompting:
Prompt: “Here is an example of a summary: ‘AI helps automate decision-making by learning from data.’ Now summarize the article on blockchain similarly.”

Chain-of-Thought Prompting:
Prompt: “Think step by step. First explain how blockchain works, then describe its components, and finally give a summary in 5 sentences.”

Role-Based Prompting:
Prompt: “You are an educator explaining blockchain to first-year engineering students. Summarize the article clearly and concisely.”

Step 4: Collect Summaries
Use each prompt on all four platforms and record their generated summaries.
→ 4 prompting styles × 4 AI platforms = 16 results total.

Step 5: Evaluate Each Output
Rate each summary on a 1–5 scale based on:

Criterion	Description
Accuracy	Technical correctness
Coherence	Logical structure
Simplicity	Understandable for students
Speed	Response time
User Experience	Readability & tone

Step 6: Analyze Performance
Compare all outputs and compute average ratings per platform and prompt type.

Sample Evaluation Table:

| Platform | Prompt Type | Accuracy | Coherence | Simplicity | Speed | UX | Avg Score |
|-----------|--------------|-----------|------------|-------------|--------|------------|
| ChatGPT | Role-Based | 5 | 5 | 5 | 4 | 5 | 4.8 |
| ChatGPT | Chain-of-Thought | 5 | 4 | 4 | 4 | 4 | 4.2 |
| Gemini | Few-Shot | 4 | 4 | 5 | 5 | 4 | 4.4 |
| Claude | Zero-Shot | 4 | 3 | 4 | 5 | 4 | 4.0 |
| Copilot | Few-Shot | 3 | 3 | 3 | 5 | 3 | 3.4 |

Step 7: Identify Best Combination
From observations:

ChatGPT (Role-Based Prompt) produced the best overall summary, balancing technical accuracy and readability.

Gemini (Few-Shot) gave fast and simplified summaries suitable for short educational content.

Claude was good at reasoning-based text but less concise.

Copilot focused more on code-related content, less ideal for plain summaries.

## Result
After conducting the experiment and evaluating outputs across multiple AI systems and prompting strategies, the following results were obtained:

Best Platform: 🏆 ChatGPT

Best Prompting Technique: 🧠 Role-Based Prompting

Best Combination: ChatGPT + Role-Based Prompting

Evaluation Metric	Top Performer
Accuracy	ChatGPT (Role-Based)
Coherence	ChatGPT (Role-Based)
Simplicity	Gemini (Few-Shot)
Speed	Gemini
User Experience	ChatGPT (Role-Based)

Final Observation:
Role-based prompts help guide the model’s tone and structure effectively, producing well-organized, accurate, and easily understandable summaries. ChatGPT handled contextual comprehension and summarization with higher consistency compared to other platforms.

✅ Hence, the experiment was successfully completed and the objectives were achieved.


