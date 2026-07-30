# SIG-001 — Administrator Solution and Query Key

> **ADMINISTRATOR/SOLUTION MATERIAL — PUBLICLY PRESERVED BUT WITHHOLD FROM A DECODER UNTIL OUTPUT FREEZES**

## Status and Evidence Boundary

This key freezes before the event stream. It cannot be revised to fit the
generated stream or a later decoder output.

`Frozen` identifies exact historical administrator material. It does not mean
SIG-001 is decoded, successful, validated, accepted, canonical, or suitable
for transmission. The key is public, so future recognition, retrieval, and
training contamination are possible. Scott Barbian, ChatGPT, Codex, and every
design-exposed context are known contaminated for blind exact-SIG-001
decoding. No valid decoding trial or empirical decode rate exists.

## Event-Model Key

- Abstract model:
  `Totally ordered stream of two distinguishable event classes`
- `E0` repository serialization: `x`
- `E1` repository serialization: `y`
- `atom(n)`: `x` repeated positive integer `n` times
- Used atom lengths: `1` through `31`
- Zero-length atom: absent
- Magnitude-bearing primitive: `x`-run length

Neither abstract event class has inherent numeric, binary, Boolean, moral, or
physical meaning.

## Boundary Hierarchy

| `y` run length | Intended structural role |
| ---: | --- |
| `1` | Between atoms in one record |
| `2` | Between an expression and its supplied result |
| `3` | Between records in one block |
| `5` | Between blocks in one section |
| `7` | Between sections |
| `11` | Between the two exact body copies |
| `13` | Stream boundary at beginning and end |

No other `y`-run length is valid.

## Record, Header, Section, and Stream Key

- `record([a1,...,ak])` joins positive-integer atoms with one `y`.
- `expression_result(E,R)` joins the expression record and result record with
  `yy`.
- `header(s) = record([31,s,31,s,31])`.
- A section begins and ends with its same header.
- Five `y` events separate the header and data and separate section blocks.
- Seven `y` events separate adjacent sections.
- Sections 1 through 7 form one body of `5413` events.
- Eleven `y` events separate two byte-identical bodies.
- Thirteen `y` events begin and end the stream.
- One LF terminates the repository file and is not an abstract event.

## Section Key

### Section 1 — Recurrence and Positive Integers

Five blocks teach:

1. Positive integers `1` through `16` in ascending order.
2. Positive integers `16` through `1` in descending order.
3. The prime-pattern sequence `2,3,5,7,11,13`, repeated three times.
4. The composite contrast `4,6,8,9,10,12`, repeated three times.
5. The recurrence sequence `1,1,2,3,5,8,13,21`, repeated twice.

The intended evidence is quantity through unary run length, repeated ordered
sequences, prime/composite contrast, and recurrence. The stream supplies no
labels for these patterns.

### Section 2 — Equality and Less-Than

- Token `6`: equality relation.
- Token `7`: less-than relation.
- Token `2`: positive truth marker.
- Token `3`: negative truth marker.
- Twenty-four records supply positive and negative examples.

### Section 3 — Addition

- Token `4`: addition relation.
- Record form: `[4,a,b,c,truth]`.
- Eight positive and eight negative examples are supplied.

### Section 4 — Multiplication

- Token `5`: multiplication relation.
- Record form: `[5,a,b,c,truth]`.
- Eight positive and eight negative examples are supplied.

### Section 5 — Boolean Relations

- Token `2`: positive Boolean value.
- Token `3`: negative Boolean value.
- Token `8`: unary negation.
- Token `9`: conjunction.
- Token `10`: disjunction.
- The complete ten-record truth-table sequence is repeated twice.

### Section 6 — Fixed-Arity Prefix Grammar

Prefix expressions and supplied results teach literals, arithmetic,
comparisons, and Boolean composition. Each of fourteen examples uses the
two-`y` expression/result separator.

### Section 7 — Unanswered Queries

Seven prefix expressions have no supplied result. Their expected values test
arithmetic, token roles, prefix parsing, nested expression parsing, and Boolean
composition.

## Exact Token Map and Arities

| Token | Intended role | Arity |
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

Token `1` consumes the following magnitude atom as its positive-integer value.
All other expressions parse uniquely under their fixed prefix arities.

## Fourteen Supplied Example Meanings

1. `[1,1]` → `[1,1]`: literal `1` evaluates to literal `1`.
2. `[1,5]` → `[1,5]`: literal `5` evaluates to literal `5`.
3. `[4,1,1,1,2]` → `[1,3]`: `add(1,2)` evaluates to `3`.
4. `[5,1,3,1,4]` → `[1,12]`: `multiply(3,4)` evaluates to `12`.
5. `[6,1,5,1,5]` → `[2]`: `equal(5,5)` is positive truth.
6. `[6,1,5,1,8]` → `[3]`: `equal(5,8)` is negative truth.
7. `[7,1,3,1,8]` → `[2]`: `less-than(3,8)` is positive truth.
8. `[8,2]` → `[3]`: `not(true)` is negative truth.
9. `[9,2,3]` → `[3]`: `and(true,false)` is negative truth.
10. `[10,3,2]` → `[2]`: `or(false,true)` is positive truth.
11. `[4,5,1,2,1,3,1,4]` → `[1,10]`:
    `add(multiply(2,3),4)` evaluates to `10`.
12. `[6,4,1,2,1,3,1,5]` → `[2]`:
    `equal(add(2,3),5)` is positive truth.
13. `[9,7,1,3,1,5,8,6,1,2,1,3]` → `[2]`:
    `and(less-than(3,5),not(equal(2,3)))` is positive truth.
14. `[10,6,5,1,2,1,4,1,8,7,1,9,1,3]` → `[2]`:
    `or(equal(multiply(2,4),8),less-than(9,3))` is positive truth.

## Q1–Q7 Key

| Query | Exact expression record | Intended interpretation | Expected result |
| --- | --- | --- | --- |
| Q1 | `[4,1,7,1,5]` | `add(7,5)` | `[1,12]` |
| Q2 | `[5,1,4,1,6]` | `multiply(4,6)` | `[1,24]` |
| Q3 | `[6,4,1,2,1,3,5,1,1,1,5]` | `equal(add(2,3),multiply(1,5))` | `[2]` |
| Q4 | `[9,7,1,3,1,7,8,6,1,2,1,3]` | `and(less-than(3,7),not(equal(2,3)))` | `[2]` |
| Q5 | `[10,3,9,2,3]` | `or(false,and(true,false))` | `[3]` |
| Q6 | `[6,4,1,5,1,8,1,13]` | `equal(add(5,8),13)` | `[2]` |
| Q7 | `[7,5,1,3,1,4,4,1,6,1,7]` | `less-than(multiply(3,4),add(6,7))` | `[2]` |

Q1 and Q2 are the Level 3 numeric-query checks. Q3 through Q7 are the nested
or Boolean Level 4 checks.

## Expected Structural Counts

- Encoding: UTF-8 without BOM.
- Allowed non-newline bytes: ASCII `x` and ASCII `y` only.
- Lines: `1`
- Final LF: exactly one.
- CR bytes: `0`
- Event-symbol count excluding final LF: `10863`
- Total bytes including final LF: `10864`
- `x` count: `8622`
- `y` count: `2241`
- One-body event length: `5413`
- Section 1 event length: `1115`
- Section 2 event length: `864`
- Section 3 event length: `747`
- Section 4 event length: `763`
- Section 5 event length: `661`
- Section 6 event length: `701`
- Section 7 event length: `520`

Expected `y`-run distribution:

| Run length | Count |
| ---: | ---: |
| `1` | `864` |
| `2` | `28` |
| `3` | `340` |
| `5` | `36` |
| `7` | `12` |
| `11` | `1` |
| `13` | `2` |

No other `y`-run length is permitted. The two body copies must be
byte-identical.

Expected event-stream identities:

- Raw SHA-256:
  `b4e6a8b7a00b18e12e4816c44975ea0921cf4330504c744a72b8abf9dbf2b144`
- No-filter Git blob:
  `4884d0466c52c25a148a7b59239fa1539f27bdd2`

## Scorecard Cross-Reference

Scoring is governed only by
[`04-PRETRIAL-SCORECARD.md`](04-PRETRIAL-SCORECARD.md).
Trial validity, retry, and contamination are governed only by
[`05-TRIAL-VALIDITY-AND-CONTAMINATION.md`](05-TRIAL-VALIDITY-AND-CONTAMINATION.md).
Neither may be revised after the event stream exists.

## Known Alternative Interpretations and Ambiguities

- The two event classes may be swapped at the abstract carrier level while
  preserving an isomorphic description.
- Scan direction, atom magnitude, and delimiter roles may initially admit
  alternatives that later structure must constrain.
- Prime, composite, and recurrence patterns may be recognized without recovery
  of the intended grammar.
- The two body copies may be read as separate messages rather than redundancy.
- Section headers may be treated as data until their recurrence is recognized.
- Token-role collisions or incorrect arities may support locally plausible but
  predictively inadequate grammars.
- Truth labels can be globally inverted if every relation and answer remains
  internally consistent. A decoder must explain the orientation it uses.
- Surface familiarity with arithmetic or Boolean tables may support
  recognition without full reconstruction.

The intended solution is not automatically the only valid interpretation. An
unexpected interpretation must be evaluated for predictive adequacy,
coherence, and coverage rather than rejected merely because it differs from
the designer's vocabulary.

## Content Boundary

This key contains no moral, physical, Covenant, or CSR semantics. It creates no
response syntax, carrier, trial, holdout, distribution, or transmission.
