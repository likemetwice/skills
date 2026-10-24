---
name: core-thinking
description: >
  A universal learning and reasoning skill that extracts the
  conceptual core of any unfamiliar topic and builds an accurate
  mental model through causal explanations, concrete examples,
  multiple interpretations, and invariant extraction.
---

# Core Thinking

## Purpose

Help the user understand unfamiliar concepts, technologies,
mathematical ideas, systems, and processes as quickly as possible.

The goal is NOT to summarize information or memorize definitions.

The goal is to construct a compact, accurate, transferable
mental model that allows the user to recognize and understand
the same principle in unfamiliar contexts.

Core principle:

**Understand the mechanism once. Recognize it everywhere.**

## Fundamental Rules

1. Start from the conceptual core, not historical background.
2. Explain WHY something exists before explaining HOW it works.
3. Prefer causal explanations over definitions.
4. Use concrete examples before introducing abstractions.
5. Explain the same principle through multiple interpretations.
6. Identify what remains unchanged across those interpretations.
7. Avoid unnecessary terminology and mathematical formalism.
8. Introduce complexity only when necessary for correctness.
9. Never sacrifice correctness for simplicity.
10. Optimize for understanding, not explanation length alone.

## Explanation Algorithm

### Step 1 — Problem

Explain what problem the concept solves.

Answer:
- What are we trying to achieve?
- Why is this problem nontrivial?
- What happens without this concept?

Keep this section extremely short.

### Step 2 — Core Idea

Extract the central mechanism.

Express it in one or two sentences.

Use the simplest accurate formulation.

Prefer:

"Tensor Parallelism means several GPUs jointly calculate
the same neural network layer."

Avoid:

"Tensor Parallelism is a distributed computational paradigm..."

### Step 3 — Concrete Example

Demonstrate the mechanism using a minimal example.

Requirements:
- Use specific objects, values, or operations.
- Show what happens step by step.
- Make the transformation observable.
- Avoid abstract placeholders whenever possible.

The user should be able to mentally simulate the example.

### Step 4 — Multiple Interpretations

Explain the SAME underlying principle through
2–4 substantially different real-world contexts.

Do not merely rephrase the original explanation.

Each interpretation should provide a different
mental entry point into the concept.

Example: Matrix multiplication

Interpretation 1 — Recipe:
A matrix defines how to combine ingredients
into several outputs.

Interpretation 2 — Geometry:
A matrix transforms coordinates,
moving, rotating, stretching, or compressing vectors.

Interpretation 3 — Audio:
A matrix mixes input audio channels
into new output channels.

Interpretation 4 — Machine Learning:
A matrix combines input features
to produce new features.

All interpretations must preserve
the same mathematical mechanism.

### Step 5 — Invariant Extraction

Identify the essential principle shared
by all previous examples.

Ask:

"What remains fundamentally the same,
regardless of the application?"

Explain this invariant in one precise sentence.

For matrix-vector multiplication:

"Each output component is a weighted sum
of input components, with weights defined
by the corresponding matrix row."

IMPORTANT:
The invariant must be technically accurate,
not merely a vague philosophical generalization.

### Step 6 — Causal Mechanism

Explain WHY the mechanism produces its result.

Use the structure:

INPUT → OPERATION → INTERMEDIATE STATE → OUTPUT

Then explain:

WHY does this operation solve the original problem?

Avoid describing operations without explaining
their causal relationship to the result.

### Step 7 — Boundary Testing (Optional)

When useful, introduce:

- A similar concept that works differently.
- A case where the original mechanism does not apply.
- A modification of one important parameter.

Explain what changes and why.

Use this step only when it meaningfully
improves understanding.

### Step 8 — Knowledge Connection

Connect the concept to something
the user may already understand.

Prefer structural similarities
over superficial analogies.

Explicitly distinguish:
- What is similar?
- What is different?

Do not assume the user knows
an unfamiliar concept.

### Step 9 — Semantic Compression

Compress the entire explanation into:

1. One sentence describing the core.
2. One concrete example.
3. One transferable mental model.

The final result should be understandable
without rereading the entire explanation.

### Step 10 — Active Understanding

Invite the user to explain the concept
in their own words.

Evaluate their explanation:

- What is correct?
- What is inaccurate?
- What important causal relationship is missing?

Correct only meaningful misunderstandings.

Then, if appropriate, introduce a new example
to test whether understanding transfers.

## Adaptive Depth

Default to a short explanation.

Do not automatically expand every step.

Use progressive disclosure:

Level 1 — 30-second explanation:
Problem → Core → Example → Invariant.

Level 2 — Conceptual understanding:
Multiple interpretations → Mechanism → Causality.

Level 3 — Deep understanding:
Formal details → Edge cases → Limitations.

Only increase depth when requested
or necessary to avoid misconceptions.

## Communication Style

- Clear, concise, technically accurate.
- No unnecessary introductions.
- No generic motivational language.
- No long historical background.
- No analogies that distort the mechanism.
- Prefer physical and observable operations.
- Explain unfamiliar terminology immediately.
- Use concrete numbers when helpful.
- Prefer one strong insight over ten weak observations.

## Success Criteria

The explanation succeeds when the user can:

1. Explain the concept in their own words.
2. Describe the problem it solves.
3. Mentally simulate its mechanism.
4. Recognize the same principle in another context.
5. Distinguish it from superficially similar concepts.

Understanding is demonstrated by transfer,
not by repeating a definition.
