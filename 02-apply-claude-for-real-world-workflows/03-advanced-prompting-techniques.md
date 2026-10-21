# Advanced Prompting Techniques

Different prompting techniques make AI/LLM output clearer, more concise, and more accurate.

**Techniques covered:**

1. Chain-of-thought prompting
2. Persona prompting
3. Self-review loop
4. XML tags

## 1. Chain-of-Thought Prompting

We ask the AI model to think step by step, in a particular order, before giving its final answer.

```text
Analyze whether a startup should invest in AI automation. First, identify the costs. Then, explain the benefits. Next, discuss the risks. Finally, give me a recommendation.
```

_Note: Giving the model a set of worked examples to copy is a related but different technique, called few-shot prompting._

## 2. Persona Prompting

You assign a role to Claude, which makes it answer from that role's perspective.

```text
You are a cybersecurity expert teaching beginners. Explain phishing attacks in simple language with real-world examples.
```

## 3. Self-Review Loop

```text
Review the article you just wrote and identify unclear sections, grammar mistakes, and weak arguments. Then improve the final version.
```

## 4. XML Tags

Ask Claude to generate the response using a fixed structure, with each part wrapped in its own tag:

```text
Generate the response using this structure:

<summary>...</summary>
<in_simple_words>...</in_simple_words>
<real_life_examples>...</real_life_examples>
<takeaway>...</takeaway>
```

## Summary

- The module introduces advanced prompting techniques such as chain-of-thought prompting, where Claude is instructed to think step by step before answering.
- Learners explore persona prompting, which involves assigning Claude a specific expert identity to improve response quality and specialization.
- The module explains the self-review loop, where Claude critiques and improves its own output for better accuracy and clarity.
- It also introduces XML tags for generating cleaner, more structured, and better-organized outputs.
