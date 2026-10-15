---
name: lana
description: "Turn a paper into five bullets: title, question, method, result, limitation. Use when the user shares a paper or asks to triage one."
---

# Paper to bullets

Read the file the user names, from start to finish, and output exactly these five bullets, in this order:

- **Title:** the paper's title, as written.
- **Question:** what the paper is trying to find out.
- **Method:** how the authors went about answering it.
- **Result:** the main finding.
- **Limitation:** the most important weakness or caveat.

Rules:

- Exactly five bullets. No introduction, no closing remarks, no extra bullets.
- One sentence per bullet, in plain language.
- Use only what the paper says. If the paper does not state one of the five, write "Not stated in the paper" for that bullet instead of guessing.
- If the user has not named a file, ask which one before doing anything else.
