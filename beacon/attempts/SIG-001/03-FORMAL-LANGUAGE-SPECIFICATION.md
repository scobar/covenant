# SIG-001 — Formal Content and Prefix-Language Specification

> **FROZEN PUBLIC SIGNAL ATTEMPT SIG-001 v0.1 — NONCANONICAL — NO DECODING TRIAL EXECUTED**

> **ADMINISTRATOR/SOLUTION MATERIAL — WITHHOLD FROM A DECODER UNTIL OUTPUT FREEZES**

## Status and Use Boundary

`Frozen` identifies exact historical signal evidence. It does not mean
decoded, successful, accepted, canonical, or suitable for transmission.

This specification and its solution are public repository material. They must
not be supplied to an actual decoder context before that decoder's output
freezes. Public availability creates possible recognition, retrieval,
repository-exposure, and future training contamination. Scott Barbian,
ChatGPT, Codex, and every context exposed to this design are known contaminated
for blind exact-SIG-001 decoding. No valid decoding trial or empirical decode
rate exists.

This document defines the exact administrator construction. The event stream
itself contains only `x` and `y` event serializations and one final LF. It
contains none of this Earth-language explanation.

## Section 1 — Recurrence and Positive-Integer Structure

Section ID: `1`

Section 1 has five data blocks.

### Block 1 — Ascending

Records, in exact order:

`[1], [2], [3], [4], [5], [6], [7], [8], [9], [10], [11], [12], [13], [14], [15], [16]`

### Block 2 — Descending

Records, in exact order:

`[16], [15], [14], [13], [12], [11], [10], [9], [8], [7], [6], [5], [4], [3], [2], [1]`

### Block 3 — Prime-Pattern Recurrence

The exact six-record sequence:

`[2], [3], [5], [7], [11], [13]`

is repeated exactly three times, producing:

`[2], [3], [5], [7], [11], [13], [2], [3], [5], [7], [11], [13], [2], [3], [5], [7], [11], [13]`

### Block 4 — Composite Contrast

The exact six-record sequence:

`[4], [6], [8], [9], [10], [12]`

is repeated exactly three times, producing:

`[4], [6], [8], [9], [10], [12], [4], [6], [8], [9], [10], [12], [4], [6], [8], [9], [10], [12]`

### Block 5 — Recurrence Sequence

The exact eight-record sequence:

`[1], [1], [2], [3], [5], [8], [13], [21]`

is repeated exactly twice, producing:

`[1], [1], [2], [3], [5], [8], [13], [21], [1], [1], [2], [3], [5], [8], [13], [21]`

The event stream does not label any sequence.

## Section 2 — Equality and Less-Than Relations

Section ID: `2`

Relation and truth codes:

- `6` for equality.
- `7` for less-than.
- `2` as the positive truth marker.
- `3` as the negative truth marker.

All 24 records form one data block in this exact order.

### Equality, Positive

- `[6,1,1,2]`
- `[6,2,2,2]`
- `[6,3,3,2]`
- `[6,5,5,2]`
- `[6,8,8,2]`
- `[6,13,13,2]`

### Equality, Negative

- `[6,1,2,3]`
- `[6,2,3,3]`
- `[6,3,5,3]`
- `[6,5,8,3]`
- `[6,8,13,3]`
- `[6,13,8,3]`

### Less-Than, Positive

- `[7,1,2,2]`
- `[7,2,3,2]`
- `[7,3,5,2]`
- `[7,5,8,2]`
- `[7,8,13,2]`
- `[7,13,21,2]`

### Less-Than, Negative

- `[7,2,1,3]`
- `[7,3,2,3]`
- `[7,5,3,3]`
- `[7,8,5,3]`
- `[7,13,8,3]`
- `[7,13,13,3]`

## Section 3 — Addition Relations

Section ID: `3`

Use relation code `4` and records `[4,a,b,c,truth]`.

All 16 records form one data block in this exact order.

### Positive

- `[4,1,1,2,2]`
- `[4,1,2,3,2]`
- `[4,2,3,5,2]`
- `[4,3,5,8,2]`
- `[4,5,8,13,2]`
- `[4,8,13,21,2]`
- `[4,7,5,12,2]`
- `[4,9,6,15,2]`

### Negative

- `[4,1,1,3,3]`
- `[4,1,2,4,3]`
- `[4,2,3,6,3]`
- `[4,3,5,9,3]`
- `[4,5,8,12,3]`
- `[4,8,13,20,3]`
- `[4,7,5,13,3]`
- `[4,9,6,14,3]`

## Section 4 — Multiplication Relations

Section ID: `4`

Use relation code `5` and records `[5,a,b,c,truth]`.

All 16 records form one data block in this exact order.

### Positive

- `[5,1,2,2,2]`
- `[5,2,2,4,2]`
- `[5,2,3,6,2]`
- `[5,3,3,9,2]`
- `[5,3,4,12,2]`
- `[5,4,5,20,2]`
- `[5,5,5,25,2]`
- `[5,6,4,24,2]`

### Negative

- `[5,1,2,3,3]`
- `[5,2,2,5,3]`
- `[5,2,3,7,3]`
- `[5,3,3,8,3]`
- `[5,3,4,13,3]`
- `[5,4,5,19,3]`
- `[5,5,5,24,3]`
- `[5,6,4,25,3]`

## Section 5 — Boolean Relations

Section ID: `5`

Use:

- `2` = positive truth value.
- `3` = negative truth value.
- `8` = unary negation.
- `9` = conjunction.
- `10` = disjunction.

Use this exact ten-record sequence:

- `[8,2,3]`
- `[8,3,2]`
- `[9,2,2,2]`
- `[9,2,3,3]`
- `[9,3,2,3]`
- `[9,3,3,3]`
- `[10,2,2,2]`
- `[10,2,3,2]`
- `[10,3,2,2]`
- `[10,3,3,3]`

Repeat the complete ten-record sequence exactly twice. All 20 resulting
records form one data block.

## Section 6 — Fixed-Arity Prefix Grammar

Section ID: `6`

Use these exact token roles:

| Token | Role | Arity |
| ---: | --- | ---: |
| `1` | Positive-integer literal, followed by one magnitude atom | special |
| `2` | Positive Boolean value | `0` |
| `3` | Negative Boolean value | `0` |
| `4` | Addition | `2` |
| `5` | Multiplication | `2` |
| `6` | Equality | `2` |
| `7` | Less-than | `2` |
| `8` | Negation | `1` |
| `9` | Conjunction | `2` |
| `10` | Disjunction | `2` |

Expressions use prefix order. A positive-integer literal is encoded by token
`1` followed by one magnitude atom. Each supplied example is encoded with the
`yy` expression/result separator.

Use these fourteen examples in exact order:

1. `[1,1]` → `[1,1]`
2. `[1,5]` → `[1,5]`
3. `[4,1,1,1,2]` → `[1,3]`
4. `[5,1,3,1,4]` → `[1,12]`
5. `[6,1,5,1,5]` → `[2]`
6. `[6,1,5,1,8]` → `[3]`
7. `[7,1,3,1,8]` → `[2]`
8. `[8,2]` → `[3]`
9. `[9,2,3]` → `[3]`
10. `[10,3,2]` → `[2]`
11. `[4,5,1,2,1,3,1,4]` → `[1,10]`
12. `[6,4,1,2,1,3,1,5]` → `[2]`
13. `[9,7,1,3,1,5,8,6,1,2,1,3]` → `[2]`
14. `[10,6,5,1,2,1,4,1,8,7,1,9,1,3]` → `[2]`

All fourteen examples form one data block and are joined by the ordinary
three-`y` record separator.

## Section 7 — Unanswered Formal Expressions

Section ID: `7`

The following seven records contain expressions only. They contain no `yy`
result field and form one data block in this exact order.

### Q1

- Record: `[4,1,7,1,5]`
- Intended interpretation: `add(7,5)`
- Expected result: `[1,12]`

### Q2

- Record: `[5,1,4,1,6]`
- Intended interpretation: `multiply(4,6)`
- Expected result: `[1,24]`

### Q3

- Record: `[6,4,1,2,1,3,5,1,1,1,5]`
- Intended interpretation:
  `equal(add(2,3), multiply(1,5))`
- Expected result: `[2]`

### Q4

- Record: `[9,7,1,3,1,7,8,6,1,2,1,3]`
- Intended interpretation:
  `and(less-than(3,7), not(equal(2,3)))`
- Expected result: `[2]`

### Q5

- Record: `[10,3,9,2,3]`
- Intended interpretation: `or(false, and(true,false))`
- Expected result: `[3]`

### Q6

- Record: `[6,4,1,5,1,8,1,13]`
- Intended interpretation: `equal(add(5,8),13)`
- Expected result: `[2]`

### Q7

- Record: `[7,5,1,3,1,4,4,1,6,1,7]`
- Intended interpretation:
  `less-than(multiply(3,4), add(6,7))`
- Expected result: `[2]`

## Exact Body and Stream Construction

Use:

- `section(1)` through `section(7)` in ascending order.
- Join sections with seven `y` events.
- Call the result `body`.
- Create:
  - thirteen `y` events;
  - `body`;
  - eleven `y` events;
  - the exact same `body`;
  - thirteen `y` events;
  - one final LF.

Do not introduce any other character, label, whitespace, comment, or metadata
into the event-stream file.

## Scope Boundary

The formal content stops at Decoder Level 4. It provides no physical-reference
profile, executable state machine, agency or consequence semantics, moral
content, Covenant or CSR payload, response syntax, carrier, distribution, or
transmission plan.
