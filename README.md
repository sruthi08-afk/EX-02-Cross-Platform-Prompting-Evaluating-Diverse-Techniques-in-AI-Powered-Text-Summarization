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

---

## Objective

Evaluate and compare **zero-shot, few-shot, chain-of-thought, and role-based prompting** techniques across multiple AI platforms (ChatGPT, Gemini, Claude, Copilot) to identify the best approach for summarizing a 500-word technical article on **"The Basics of Blockchain Technology"** for undergraduate students


---

##  Define Prompt Templates for Each Technique

### 1. Zero-shot Prompting

**Goal:** AI summarizes with no examples or extra instructions.
**Prompt:**

```
Summarize the following article on "The Basics of Blockchain Technology" in simple language suitable for undergraduate students:

[Insert full article text here]
```

---

### 2. Few-shot Prompting

**Goal:** Provide 2-3 example summaries first, then ask AI to summarize.
**Prompt:**

```
Here are examples of summaries of technical articles for undergraduate students:

Example 1: [Insert example summary of unrelated article]  
Example 2: [Insert example summary of unrelated article]

Now, summarize the following article on "The Basics of Blockchain Technology" in a similar style:

[Insert full article text here]
```

---

### 3. Chain-of-Thought Prompting

**Goal:** AI explains or reasons step-by-step before summarizing.
**Prompt:**

```
Read the following article on "The Basics of Blockchain Technology." First, explain its main points step-by-step. Then provide a concise summary suitable for undergraduate students.

[Insert full article text here]
```

---

### 4. Role-based Prompting

**Goal:** Assign a role/persona to influence tone and style.
**Prompt:**

```
You are a university professor teaching blockchain technology to first-year students. Summarize the following article clearly and simply so that undergraduates can easily understand it:

[Insert full article text here]
```

---

## Platforms for Testing

Run the above prompts on:

* **ChatGPT**
* **Gemini**
* **Claude**
* **Copilot**

For each platform + prompting technique combination, collect the output.

---

##  Evaluation Criteria

Rate each summary on:

| Criterion           | Description                                          |
| ------------------- | ---------------------------------------------------- |
| **Accuracy**        | Faithfulness to the original content; no errors.     |
| **Coherence**       | Logical flow, readability, and clarity.              |
| **Simplicity**      | Easy to understand for undergrads.                   |
| **Speed**           | Time taken to generate the summary (in seconds).     |
| **User Experience** | Ease of prompt use, interaction, and output quality. |

---

##  Result Reporting

Use a table format for clarity:

| Platform | Prompting Technique | Accuracy | Coherence | Simplicity | Speed (secs) | User Experience | Notes              |
| -------- | ------------------- | -------- | --------- | ---------- | ------------ | --------------- | ------------------ |
| ChatGPT  | Zero-shot           | 4        | 4         | 4          | 10           | 5               | Quick, good output |
| Gemini   | Few-shot            | 5        | 5         | 4          | 15           | 4               | More detailed      |
| Claude   | Chain-of-Thought    | 4        | 5         | 3          | 20           | 3               | Slow but thorough  |
| Copilot  | Role-based          | 3        | 4         | 5          | 12           | 4               | Simple and clear   |

---







