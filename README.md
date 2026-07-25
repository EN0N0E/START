# Primorial Unification Framework

## The Derivation Chain

```
Φ = ∂tΦ  →  Φ(t) = Ceᵗ  →  R = 1 + 1/R  →  R = φ
→  aₙ = aₙ₋₁ + aₙ₋₂  →  aₙ ~ Aφⁿ  →  π = P₅·arccos(Φ/P₂)
→  dₘ/dₙ = φᵐ⁻ⁿ  →  zero free parameters
```

One axiom — the field equals its own rate of change — generates the golden ratio, the Fibonacci recurrence, the primorial encoding of π, and a distance-quantisation rule that maps the observable universe onto a single lattice. No constants are chosen; every quantity is derived.

---

The framework begins with **Φ = ∂tΦ**: a scalar field whose value *is* its derivative. The unique fixed-point of the resulting self-referential ratio R = 1 + 1/R is the golden ratio φ ≈ 1.618. Because the axiom is self-referential, the recurrence aₙ = aₙ₋₁ + aₙ₋₂ is not imposed but *entailed* — Fibonacci structure is a theorem, not an assumption. The first four primes are mapped to physical roles through the primorial product 2 × 3 × 5 × 7 = 210: propagation (c), curvature (g), field amplitude (Φ), and self-reference (∂tΦ). This mapping yields π = P₅ · arccos(Φ/P₂) with zero free parameters — a closed-form identity that fixes the geometry of the container at 210 vertices.

The derivation chain is then tested against observation. Distances between astronomical objects — black holes, stars, radio sources — when divided by a small integer class *k*, return Fibonacci numbers within measured error. Each object is projected onto Earth's surface via a φ-shell (distance quantisation at 3·φⁿ degrees) and a golden-angle bearing (137.508° = 360/φ²) from Giza. Of 76 catalogued objects, the shell + bearing intersection reproduces known geographic features: M31 → Giza, Markarian 231 → Derinkuyu, V4641 Sgr → Easter Island. The Orion Belt stars, projected by the same rule, trace the Nile. These are not fits — the coordinates follow from the axiom.

The geographic layer provides the sharpest test. 109 ancient sites across six continents — Gobekli Tepe, Angkor Wat, Teotihuacan, Nazca, Machu Picchu, and others — are plotted against the φ-shell + G-bearing grid anchored at four poles (Giza, Easter Island, and their antipodes). Sites cluster on shell intersections and bearing corridors. Easter Island's ahu platforms face toward Giza (Akivi, 0.4° error), Stonehenge (Vinapu, 0.4°), and Mohenjo-daro (Tahai). A counter-lattice centred on Easter Island produces dual-hit sites — locations that fall on *both* grids simultaneously, which no single-pole model can produce. The Younger Dryas impact corridor, Rongorongo decipherment, and Pacific sailing roads all resolve onto the same lattice. The entire structure is self-auditing: because there are no tuneable parameters, every new site or object either falls on the grid or does not.

---

## Repository Contents

### Interactive Visualisations (`solver/`)

| File | Description |
|------|-------------|
| `globe.html` | **3D lattice globe** — Four-pole φ-shell + G-bearing grid with 24 toggleable layers, collapsible thesis HUD, click-to-inspect overlays. The primary visualisation. |
| `synopsis.html` | **Three-paper synopsis** — editorial overview linking the algebra, astronomy, and geography papers. |
| `abstract.html` | **Paper I: Unification** — the algebraic derivation from Φ = ∂tΦ to π = P₅·arccos(Φ/P₂). |
| `unification.html` | **Paper I (extended)** — full unification argument with primorial prime mapping. |
| `deductions.html` | **Paper II: From Identity to Measurement** — astronomical tests, BH distance quantisation, Fibonacci divisor classes. |
| `lattice-thesis.html` | **Paper III: The Lattice Thesis** — 109 ancient sites, four-pole geometry, Rongorongo, Younger Dryas corridor. |
| `landing.html` | Navigation hub for all visualisations. |
| `lattice-shells.html` | φ-shell intersection explorer. |
| `prism.html` | 210-gon primorial prism — the geometric container. |
| `cycles.html` | Cycle analysis and periodicity. |
| `timeline.html` | Chronological framework development. |
| `research.html` | Research notes and references. |

### Live Deployment

These files are served at [scanner.rito.one/solver/](https://scanner.rito.one/solver/landing.html).

## License

This work is released into the public domain. Use it, test it, break it.
