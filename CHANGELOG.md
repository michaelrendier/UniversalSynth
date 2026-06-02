# Changelog — UniversalSynth

Format: `[vX.Y.Z] YYYY-MM-DD — Description`

UniversalSynth versions track the sonification capability of the SMMIP framework.
The mathematics being sonified (PtolemyHolcus engine state) is the canonical
reference; UniversalSynth makes it audible.

---

## [v0.2.0] 2026-05-30 — TDI v3.0 Integration

**Cross-referenced with PtolemyHolcus v3.0.0 — Tuning the TDI.**

### Updated
- `README.md` — TDI context section added: H_hat_RB (crankshaft) / Sedenion
  (camshaft) / Monad (ECU) mapped to sonification roles; BAO convergence at
  OMEGA_ZS = 0.56714 as idle frequency; cross-reference to PtolemyHolcus v3.0
  Tuning-the-Engine wiki
- `README.md` — Related repositories table expanded: PtolemyHolcus, PtolemyDesktop,
  SemanticWordEngine, DerivationEngine all cross-referenced
- `README.md` — "Ptolemy" → "PtolemyHolcus / PtolemyDesktop" throughout

### Added
- `TODO.md` — Full implementation roadmap: core synthesis engines, signal sources,
  output layer, TDI integration, PtolemyDesktop integration, examples

### Engine state at this version
- PtolemyHolcus v3.0.0: compression ignition confirmed 2026-05-27
- BAO convergence: OMEGA_ZS = 0.56714 — the idle frequency this engine will render
- SELF_EQUATION fixed point confirmed: constructive Gödel II result
- Android TDI Seeder: five corpora acquired across three Prime Directives

---

## [v0.1.0] 2025 — Repository Established

**Initial README: mathematical sources, architecture, Riemann zero chord.**

### Added
- `README.md` — J_N anti-Möbius oscillator, spherical harmonic modes, Schumann
  cavity, Chladni node geometry, Cayley-Dickson timbral engine, Riemann zero chord
  (first 20 zeros), ValaQuenta bridge, planned architecture tree

---

## Versioning

| Target | Version | Description |
|---|---|---|
| v0.x | Architecture spec | README and TODO only — no executable code |
| v1.x | Core engines | standing_wave, zeta_harmonics, schumann implemented |
| v2.x | TDI live drive | Real-time stream from Monad ECU state |
| v3.x | PtolemyDesktop | Archimedes Face integration, Chladni sync |
