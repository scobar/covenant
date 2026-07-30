# SIG-001 — Event Model, Serialization, and Framing

> **FROZEN PUBLIC SIGNAL ATTEMPT SIG-001 v0.1 — NONCANONICAL — NO DECODING TRIAL EXECUTED**

## Status and Evidence Boundary

`Frozen` identifies exact historical signal evidence. It does not mean
decoded, successful, accepted, canonical, or suitable for transmission.

The repository serialization and administrator solution are public. An actual
decoder context must not receive the solution before its output freezes.
Public availability creates contamination risk. Scott Barbian, ChatGPT, Codex,
and every design-exposed context are known contaminated for blind exact-SIG-001
decoding. No valid decoding trial or empirical decode rate exists.

## Abstract Model

SIG-001 selects:

`Totally ordered stream of two distinguishable event classes`

The abstract event classes are:

- `E0`
- `E1`

No moral, numeric, binary, true/false, or physical meaning is inherent in
either class.

## Repository Serialization

- `x` serializes `E0`.
- `y` serializes `E1`.

`x` and `y` are arbitrary repository glyphs. The canonical abstract content is
their event-class sequence. A future carrier may map the classes differently
only under separate authorization. A trial must not credit a decoder for
interpreting `x` or `y` as an Earth-language letter.

The repository text file is a carrier-specific convenience for preserving the
abstract sequence; it does not select a physical or digital transmission
carrier.

## Atom Encoding

Define exactly:

`atom(n) = x repeated n times`

where:

- `n` is a positive integer.
- SIG-001 uses atom lengths from `1` through `31`.
- No zero-length atom exists.
- Atom length is the only magnitude-bearing primitive.

The definition records the administrator's construction. It does not assume a
decoder initially knows that run length represents quantity.

## Boundary Hierarchy

A run of `y` events separates structures.

| `y` run length | Structural role |
| ---: | --- |
| `1` | Between atoms in one record |
| `2` | Between an expression and its supplied result |
| `3` | Between records in one block |
| `5` | Between blocks in one section |
| `7` | Between sections |
| `11` | Between the two complete body copies |
| `13` | Stream boundary at beginning and end |

- No `y` run of length `4`, `6`, `8`, `9`, `10`, or `12` is valid in SIG-001.
- The hierarchy uses distinct prime run lengths for larger boundaries but does
  not claim that prime delimiters are universally meaningful.
- The two body copies are exact duplicates.
- The event stream is not a binary number.

## Records

Define:

`record([a1, a2, ..., ak])`

as:

`atom(a1) + y + atom(a2) + ... + y + atom(ak)`

Every record contains one or more positive-integer atoms.

## Expression/Result Record

Define:

`expression_result(expression_tokens, result_tokens)`

as:

`record(expression_tokens) + yy + record(result_tokens)`

The two-`y` run appears only between a supplied expression and its supplied
result.

## Section Header

Define exactly:

`header(s) = record([31, s, 31, s, 31])`

where `s` is the section number `1` through `7`.

The same header appears at the beginning and end of its section.

## Section

Define:

`section(s, blocks)`

as:

- `header(s)`
- `yyyyy`
- each block joined by `yyyyy`
- final `yyyyy`
- `header(s)`

Records inside one block are joined by `yyy`, except atoms within a record use
`y`, and supplied expression/result pairs use `yy`.

## Body and Stream

- Sections 1 through 7 are joined by `yyyyyyy`.
- The resulting body is duplicated exactly.
- The two copies are joined by `yyyyyyyyyyy`.
- The stream begins and ends with `yyyyyyyyyyyyy`.
- One final LF terminates the repository file.
- No other whitespace exists.

The abstract event count excludes the final repository newline.

## Self-Synchronization Claim Boundary

SIG-001 supplies:

- Unique long boundaries.
- Hierarchical delimiter lengths.
- Repeated headers.
- Two exact body copies.

It does not demonstrate successful recovery from corruption or unknown
midstream entry. It supplies no error-correction algorithm and selects no
carrier. Corruption recovery, reversed or partial entry, alternative scans,
and carrier-specific synchronization remain later tests requiring separate
authorization.
