---
name: explain-one-thing-at-a-time
description: Revise dense academic, scientific, legal, or technical prose so that each sentence states one main fact and makes its logical connection to surrounding facts explicit. Use when writing sounds compressed, over-technicalized, aphoristic, difficult to unpack, or “academic” at the expense of being human-readable.
---

# Explain One Thing at a Time

Write for a careful reader who is intelligent but does not already possess the
author's unstated chain of reasoning.

## Diagnose semantic compression

Flag a passage when it does one or more of the following:

- Uses one technical verb—such as “pins,” “binds,” “situates,” “captures,” or
  “establishes”—to conceal several distinct operations.
- Coordinates a list of claims whose relationship is not explained.
- Uses a semicolon to join a mechanism and its consequence without stating the
  intermediate reasoning.
- Introduces a symbol, identifier, component, or institution by immediately
  describing what it does instead of first saying what it is.
- Replaces agents and actions with abstract nouns such as “availability,”
  “authority,” “verification,” or “construction.”
- Assumes that the reader can supply a missing premise from domain knowledge.
- Compresses qualifications into a final clause after the reader has already
  formed a stronger interpretation.
- Sounds polished when read quickly but becomes ambiguous when paraphrased.

## Revise in this order

1. List the atomic facts in the passage.
2. Identify the relationship between each pair of facts: definition, cause,
   mechanism, consequence, limitation, contrast, or example.
3. Put definitions before operations and operations before consequences.
4. Give each sentence one main assertion. A second clause is acceptable only
   when its relationship to the first is immediately obvious.
5. Name the actor and action. Prefer “The client verifies the signature” to
   “signature verification occurs.”
6. Replace compressed technical verbs with the operation they denote. Retain
   the technical term afterward if it is useful.
7. State the missing premise when the conclusion depends on it.
8. Put limitations directly after the claim they limit.
9. Read the revision as a newcomer. Ask what every pronoun refers to, what every
   symbol identifies, and why every conclusion follows.

Do not make the prose childish, conversationally padded, or repetitive.
Technical vocabulary and equations are appropriate when defined. The aim is
logical completeness, not maximal length.

## Use paragraph structure as reasoning structure

Build explanatory paragraphs in this sequence when applicable:

1. What the thing is.
2. What inputs it receives or assumptions it requires.
3. What operation it performs.
4. What result follows.
5. Why that result matters here.
6. What the result does not establish.

Split the paragraph when it changes subjects or moves from mechanism to
evaluation.

## Test the result

For every paragraph, answer:

- Can the reader paraphrase each sentence without guessing what a metaphorical
  verb means?
- Does each “this,” “it,” and “they” have one unmistakable antecedent?
- Is every causal word—“therefore,” “because,” “so,” “only,” “unless”—supported
  by facts already stated?
- Could two clauses be separated without losing an unstated relationship? If
  so, separate them and state that relationship.
- Does the paragraph distinguish evidence from what the evidence proves?

## Example

Compressed:

> The chain hash pins the schedule, public key, and cryptographic scheme;
> recording only the round would be ambiguous across networks.

Revised:

> 
> Every drand network has a chain hash that uniquely identifies its configuration. That configuration includes the network’s round schedule, public key, and cryptographic scheme. A round number such as `r = 1000` has meaning only within one such configuration, because different drand networks can assign the same round number to different times and keys. The attestation therefore records both the round number and the chain hash.

The revision is longer because the original omitted three premises. Do not
describe that added length as verbosity, becuase it carries information the reader
otherwise had to infer. Adding examples in this manner "such as `r = 1000`" is also immensely valuable to a fresh reader.
