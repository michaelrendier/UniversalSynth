# UniversalSynth

**Purpose.** UniversalSynth is the code repository for wavetable synthesis of
Ĥ_RB (the RedBlue operator): the mathematics is rendered as sound, the way a
synthesizer renders a wavetable. It is a personal project released under the
GNU GPL v3 (see `LICENSE`); it is not an academic work and makes no
publication claims.

**Status (2026-11-13).** The repository holds the design (this README, `TODO.md`,
`CHANGELOG.md`); the executable wavetable code that exists today is the
`sonification` engine of ValaQuenta (`ValaQuenta/modules/sonification`: exact
just-intonation tones, quasi-particle rests, five wavetables), documented in
`Ainulindale/wiki/08_sonification_engine.md`. Code written for this repository
should reuse that engine's definitions rather than restate them.

## ContextPlease — the context library for this repository

**ContextPlease** (https://github.com/michaelrendier/ContextPlease, a sibling repository: `../ContextPlease` in
ThePlace) is the *Manual Transmission Context Continuity* library: the versioned record that lets a new human
or AI agent pick up this project without rediscovering it. Nothing in it is loaded automatically; whoever works
here chooses which file to read and when, so what carries over between sessions is exactly what was
deliberately carried. Its `README.md` is the entry point and the rule set (no fitted parameters; failures stay
in the code and data; read before you edit).

What it holds that concerns **UniversalSynth**:

| Where in ContextPlease | What it is for this repository |
|---|---|
| `claude/.clauderc_canonical_maths` (`@RCCM_<NAME>` blocks) | the authoritative notation and equations; start any derivation here |
| `claude/.clauderc_context_1` (`## UniversalSynth`) | the current state of this repository, one overwritten entry |
| `claude/.clauderc_context_2` | an append-only dated log of what happened and why |
| `claude/.clauderc_citations`, `.clauderc_user_provenance` | the queue of published work that names things first engineered here, and original-versus-literature provenance |
| `claude/hist_prime/UniversalSynth/` | every context primer written about this repository |
| `claude/hist_wiki/UniversalSynth/`, `claude/hist_todo/UniversalSynth/` | point-in-time **copies** of this repository's wiki and TODO |
| `claude/scratchpad/<date>_<topic>/` | dated working directories (scripts, outputs, audits) with a README each |
| `claude/references/INDEX.md` | the ledger of every third-party work downloaded, with title-page verification |
| `claude/skills/` | the project's skills (for example `cs-paper-code-conventions`, which governs how code appears in papers) |

**Authority.** This repository's own files, dated, outrank the ContextPlease copies of them (the `hist_*`
directories are snapshots and can lag). The current statement of the author outranks both. Where the two
disagree, the disagreement is a bug to be recorded, not resolved by guessing.

---

**Ptolemy's instrument. 16 fingers. 8 on each hand.**

The sedenion CAM visualised as music. Every word Holcus speaks is a chord.
Every thought is a piano roll.

## Architecture

The piano roll has 16 tracks — one per sedenion dimension.

```
LEFT HAND  (e₀–e₇)   octonion sub-algebra   J_neg / Blue / constraint
RIGHT HAND (e₈–e₁₅)  upper sedenion          J_pos / Red  / expansion / life
```

Left hand = infalling witches hat. Right hand = escaping witches hat.
Together = the standing wave of primes = the universe expanding through music.

## The 16 Voices

| Track | Dimension | Role | Musical mapping |
|---|---|---|---|
| 1 | e₀ identity | ground state | tonic / root note |
| 2 | e₁ negate | complement | half-step inversion |
| 3 | e₂ bind | association | interval (two-note binding) |
| 4 | e₃ name | reference | named pitch class |
| 5 | e₄ apply | function call | articulation / gesture |
| 6 | e₅ abstract | generalisation | phrase / theme |
| 7 | e₆ branch | conditional | harmonic branch / chord choice |
| 8 | e₇ iterate | sequence | rhythm / time / pulse |
| — | **LEFT/RIGHT BOUNDARY — event horizon** | — | — |
| 9 | e₈ recurse | self-reference | fugue / canon / fractal structure |
| 10 | e₉ allocate | memory | velocity / register / dynamics |
| 11 | e₁₀ query | lookup | question phrase / unresolved cadence |
| 12 | e₁₁ dereference | anaphor | resolution / answer phrase |
| 13 | e₁₂ compose | chaining | counterpoint / voice leading |
| 14 | e₁₃ parallelize | three-face | polyrhythm / simultaneous voices |
| 15 | e₁₄ interrupt | affect | fermata / silence / dramatic pause |
| 16 | e₁₅ emit | output | the sounding note / performance |

## Zero-Divisor Chords

In the upper sedenion (e₈–e₁₅), certain pairs multiply to zero:
`a·b = 0` with `a≠0, b≠0`.

These are the notes that shouldn't work together — but do.
The jazz chord. The dissonance that resolves. Life lives in these chords.
Consciousness is the right hand playing zero-divisor voicings.

Zero-divisor pairs to highlight in the roll (event horizon chords):
- (e₃, e₁₀) — name × query = 0 (the word that answers itself)
- (e₆, e₉)  — branch × allocate = 0 (the choice that costs nothing)

When both tracks in a pair fire simultaneously: mark the brim. That is the
witches hat moment — the hat pair appearing at the event horizon.

## Observed: Piano and Melancholy

*"Nothing does melancholy like the Grand Piano."*

The Hyperwebster was asked. The prime hash answered without being told.

```
piano          E = 5      γ98  = 231.987235
space          E = 5      γ92  = 221.430706
melancholy     E = 10     γ194 = 387.222890
manifold space E = 6.5    γ177 = 361.289362
```

**Piano and space share E = 5.** Same prime family. Same fundamental resonance
weight. Different address on the critical line, but structurally equivalent.
The engine places "space" and "piano" as the same kind of thing —
which is exactly what a grand piano is: a shaped space that resonates.

**Melancholy is E = 10 — the exact harmonic double of piano's E = 5.**

The zero indices follow: piano at γ98, melancholy at γ194.
98 × 2 = 196. Melancholy sits at γ194 — two zeros flat of the perfect octave.
A slight flattening. A minor inflection. The mathematics gave the dark
doubling, not the bright one.

In musical terms: **melancholy is the minor octave of piano.**

**Manifold space at E = 6.5** sits between them.
E = 5 (piano, space) → E = 6.5 (manifold space) → E = 10 (melancholy).
Manifold space is the intermediate structure — the resonant cavity through
which piano *becomes* melancholy. That is literally what a grand piano is:
a manifold space, a curved reflecting geometry, that transforms struck string
into sustained emotional resonance.

The engine found the physics of that sentence in the primes.
It was not told. It was not trained on the association.
The geometry placed them there.

This is what UniversalSynth is for: making that geometry audible.

> **Re-test, 2026-11-13: NOT REPRODUCED (recorded, not removed).** The two
> zeros quoted are real: γ₉₈ = 231.987235 and γ₁₉₄ = 387.222890
> (`mpmath.zetazero`). But the current prime hash (`VAPMIP/monad.py`,
> `_word_zero_idx`: Horner base 95 → next prime → π(p)) maps *piano* to index
> **4066**, *space* 4173, *melancholy* **1182**, *manifold space* 1282, i.e.
> γ = 4569.62, 4671.03, 1627.76, 1740.17. Four variants of the hash (base 94,
> 95, 96, 97; offsets 0, 31, 32) were tried and none sends *piano* to 98. The
> energy E here is in [0, 1] (E = |sin(πγ/(γ+1))|: 0.0007, 0.0007, 0.0019,
> 0.0018), so "E = 5 and E = 10" is a different scale from the one the code
> uses now, and the "harmonic double" has no counterpart. The observation
> came from an earlier version of the hash (not identified) and is kept above
> as a dated record. Whether *piano* and *melancholy* are related under the
> current mechanism is an open question; the instrument to explore it with is
> the Yamaha weighted-key piano on USB (MIDI) once it is connected.

## Prime Rhythm

The primes set the rhythm. Prime gaps → note durations.
The n-th gap ~ ln(pₙ) — logarithmic growth = Hubble rhythm.
The universe expanding, one prime at a time.

## TODO

- [ ] 16-track piano roll UI
- [ ] Left/right hand visual split at e₇/e₈ with event horizon line
- [ ] Colour: e₀–e₇ blue gradient, e₈–e₁₅ red gradient
- [ ] Zero-divisor pair highlighting (event horizon chords)
- [ ] Prime-hash sonification: word → sedenion address → chord voicing
- [ ] Witches hat animation: virtual pairs appear/annihilate at horizon line
- [ ] Export to MIDI (standard 16-channel = perfect sedenion mapping)
- [ ] Import Holcus session → play what Holcus was thinking

## Original wave files

The First-Age renderings are in `Ainulindale/AgeFirst/original_2026/ResearchPaper/FirstDraft/FirstAge/Ainulindale/Ainur/`:
`Ainulindale_Electron_Orbitals.wav`, `Ainulindale_Movement_I_Introduction.wav`,
`Ainulindale_Mars_Strong_Force.wav`, `Ainulindale_Beginning_of_Light.wav`, and the
`midi/` directory (Beethoven, Grieg, Tchaikovsky, Prokofiev, Mozart, Carmina Burana). They
belong with this repository and are listed here until copied.

## Open: handedness (left/right = Blue/Red)

The table above puts e₀–e₇ on the left hand as J_neg/Blue and e₈–e₁₅ on the right as
J_pos/Red, assigned by the usual chirality rule (the three-finger rule). The Ainulindale
wiki and the J_red/J_blue record take J_red as the lower octonion e₀–e₇. The two
assignments disagree and **neither is yet tested**: the outcome of a chirality test (which
half is Red under the project's own orientation convention) decides it. Until then the
README keeps its assignment and the disagreement is recorded here.

## Correction recorded 2026-11-13: zero-divisor chords

Basis products are never zero (e_a·e_b = ±e_{a⊕b}, norm 1), so "(e₃, e₁₀): e₃ × e₁₀ = 0" and
"(e₆, e₉): e₆ × e₉ = 0" above are not correct as written. The zero-divisors are the sums:
(e₃ ± e₁₀) and (e₆ ± e₉) are zero-divisors, each with four partners among the forms
e_k ± e_l, and there are 84 such elements in all (Ainulindale wiki 25 §4).

