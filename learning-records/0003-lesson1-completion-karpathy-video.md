# 0003 — Lesson 1 Complete + Karpathy Intro Video

## What was learned
Far exceeded Lesson 1 scope. User watched full 1hr Karpathy intro video and absorbed:

### Core mechanics
- LLM = next-word prediction machine
- Pretraining on base data (internet-scale text)
- Fine-tuning with Q&A style responses (supervised fine-tuning / SFT)

### Alignment & training
- Comparison of responses + comparative selection = RLHF (Reinforcement Learning from Human Feedback) / DPO (Direct Preference Optimization)
- Reward model training from human preferences
- "Draft chunking" likely refers to sampling multiple completions and ranking them

### Capabilities
- Tool calling (LLM triggers external functions)
- LLM as OS (Karpathy's framing: LLM as the new kernel layer)
- Context window mechanics

### Thinking modes
- **System 1** = standard LLM response — fast, no deliberation, token-by-token immediately (like human intuition)
- **System 2** = "thinking" models (o1, DeepSeek-R1) — slow deliberate reasoning, generates a hidden chain-of-thought before answering (like human careful reasoning)
- Key insight: System 2 models spend more compute *at inference time* to reason, not just at training time

### Security
- Jailbreaking
- Prompt injection
- Data poisoning

## Terminology to reinforce later
- What they called "reinforcement learning / comparison of responses" = RLHF or DPO — correct intuition, worth naming precisely in a future lesson
- "Draft chunking and comparative selection" = likely best-of-N sampling or rejection sampling during RLHF

## Zone of proximal development — next step
User is conceptually ready for Python fundamentals (Lesson 2). Strong mental model established. Move immediately to hands-on code.

## Date
2026-06-30
