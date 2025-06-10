+++
date = '2025-06-10T07:19:16-04:00'
title = 'HoTTLean'
menus = 'main'
weight = 1
+++

[HoTTLean](https://github.com/sinhp/groupoid_model_in_lean4) is a project that aims to
- Create a proof assistant for a fragment of HoTT (homtopy type theory) called
  HoTT0 within Lean as a domain
  specific language,
  using its meta-programming facilities.
- Formalize the semantics of HoTT0 using natural model semantics
  using category theory in the Lean mathemtaics library
  [Mathlib](https://leanprover-community.github.io/mathlib-overview.html).
- Foramlize the groupoid model of HoTT as an instance of natural model
  semantics.
- Automate the interpretation so that axiomatic HoTT0 proofs
  can be "compiled" into proofs about Mathlib's groupoids.

The github repository is available [here](https://github.com/sinhp/groupoid_model_in_lean4).
