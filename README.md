# Human Preferences as Verifiable Rewards for GRPO

[View the research poster (PDF)](poster.pdf)

This poster explores a way to reuse human preference rankings in reinforcement learning from verifiable rewards (RLVR). Given a user request and shuffled candidate answers, the model predicts their best-to-worst order. A deterministic checker compares that order with the annotated ranking and provides exact and partial-credit rewards.

The poster describes mixing these ranking tasks with automatically checked tasks during GRPO training and reports selected experimental results. Presented at Voronovo 2026.
