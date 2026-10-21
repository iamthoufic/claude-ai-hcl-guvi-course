# Multi-Turn Conversations & Memory in Claude

How does an AI model remember context, and how does it respond to user queries over a long session?

## Within a Single Chat: Follow-Up Prompts

**First prompt:**

```text
I am building a fitness tracking app for beginners. Suggest important features for it.
```

The answer is not good enough, so I send follow-up messages:

```text
Now prioritize those features for an MVP.
```

```text
Give UI suggestions for the top 3 features.
```

Claude remembers everything in the context throughout the chat session.

In simple terms: when you send Claude a follow-up query, it remembers everything already in the conversation, so you don't need to repeat the information from the beginning as you continue.

## Across Chats: Memory

**In a new chat session:**

```text
Remember that I am a machine learning engineer who prefers concise technical explanations.
```

```text
Suggest some good generative AI project ideas for me.
```

**Test it in another new chat:**

```text
What am I?
```

> **Important:** By default, information is remembered only within that chat session. A brand-new chat starts fresh. Claude can carry details across chats only when its **memory** feature is turned on, or when you work inside a **Project** that stores your instructions and files.

## Summary

- This module explains how to build context across long conversations to make Claude more effective over multiple interactions.
- Learners understand the difference between starting a fresh conversation and continuing an existing thread.
- The module teaches techniques for referencing earlier outputs to keep Claude aligned with the ongoing discussion.
- It clarifies what Claude can remember within a session and the limitations of its conversational memory.
- The project task involves having a five-message back-and-forth conversation with Claude while practicing how to redirect the AI if it drifts off-topic.
