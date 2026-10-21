# Building Your System Prompt

## Key Questions

- What is a system prompt, and how does it differ from a normal prompt?
- Why do some AI tools give inconsistent answers?
- Why do some AI tools sound more professional than others?

## User Prompt vs. System Prompt

- A **user prompt** is a normal prompt — the message you type in the chat.
- A **system prompt** gives the AI a permanent personality and set of rules that apply to the whole conversation.

_In Claude, you set a system prompt through a Project's custom instructions (or the `system` field in the API). Starting a chat with "You are a…" works as a role prompt for that one conversation._

### Example

**User prompt only:**

```text
Write a LinkedIn post.
```

Claude will ask follow-up questions before it proceeds to write the LinkedIn post for you.

**With a role assigned:**

```text
You are a professional LinkedIn ghostwriter helping startup founders.
```

Now Claude's tone has changed. This is why prompting matters.

## What a Good System Prompt Needs

- Assigning a role to the AI is essential.
- Guardrails should also be included.
- The tone and the output type also matter.

## Example: Basic vs. Detailed System Prompt

**Basic:**

```text
You are a marketing assistant.
```

**Detailed:**

```text
You are an expert LinkedIn ghostwriter helping tech professionals create engaging posts.

Always:
- Start with a strong hook.
- Use short paragraphs.
- Include practical insights.
- End with a question or a CTA (call to action).

Never:
- Use robotic language.
- Write long paragraphs.
- Use complex jargon.

Respond in a conversational and professional tone.
```

**Follow-up user prompt:**

```text
The topic is the effect of AI on human intelligence.
```

> A system prompt matters much more when you are working on a project than when you are having a casual conversation with AI.

## Summary

- This module explains what a system prompt is and why it is considered a game-changer for controlling AI behavior and response quality.
- It introduces the anatomy of an effective system prompt, including elements such as tone, rules, persona, and output style.
- Learners are shown real-world system prompt examples for different roles, such as marketers, developers, and students, to understand practical applications.
- The project task guides learners to create their own personalized system prompt using a structured template.
