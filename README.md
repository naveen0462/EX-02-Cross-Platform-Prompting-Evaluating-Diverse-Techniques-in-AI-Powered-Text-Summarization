# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Prompting Techniques
Zero-Shot Prompting
No examples provided.
Prompt: "Summarize this article in simple terms suitable for undergraduate students."

Few-Shot Prompting
Provide 2–3 examples of summaries beforehand.
Prompt:
"Here are a few examples of summaries. Now summarize the following article similarly:"

Chain-of-Thought Prompting
Guide the model through reasoning steps.
Prompt:
"First, identify the key concepts. Then explain them briefly. Finally, summarize the article in simple terms."

Role-Based Prompting
Assign a persona to the AI.
Prompt:
"You are a professor explaining blockchain to first-year students. Summarize the following article in an engaging and clear manner."

🤖 AI Platforms for Testing
ChatGPT (OpenAI)

Gemini (Google)

Claude (Anthropic)

Copilot (Microsoft)

📈 Evaluation Criteria
Each summary will be evaluated based on:

Metric	Description
Accuracy	How correctly the key points from the article are represented.
Coherence	Logical flow and structure of the summary.
Simplicity	How easily undergraduate students can understand the summary.
Speed	Time taken to generate the output.
UX	Ease of use, formatting, and experience while using the platform.

⚙️ Algorithm (Workflow)
Input Article: Use a 500-word technical article titled "The Basics of Blockchain Technology".

Apply Prompting Techniques:

Apply all 4 prompting methods on each AI platform.

Total runs: 4 techniques × 4 platforms = 16 summaries

Collect Outputs and label them (e.g., Claude-ZeroShot, ChatGPT-CoT).

Evaluate each summary using the metrics above.

Assign Scores (1–5) per criterion and calculate average scores.

Rank all combinations.

Conclude which technique+platform gave the best output.



## Result


