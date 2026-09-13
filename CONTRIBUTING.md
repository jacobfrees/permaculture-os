# Contributing to Permaculture OS

## The Prime Directive

**Every document must be executable by one untrained person with local
materials in any climate the module claims to support.** If a guide assumes a
$50,000 tractor, a supplies chain, or expert knowledge it doesn't provide,
fix it or tag it clearly as needing simplification.

## What We Need Most

In order of impact:

1. **Field adaptation reports** — "this guild failed at 2,000m; swaps that worked"
2. **Diagrams** — every document should end up diagram-first (diagrams translate
   across languages for free)
3. **Climate drivers** — fill in your biome's adaptations in `DRIVERS/`
4. **Species databases** — build-tested plant/animal data for `SPECIES/`
5. **Translations** — kernel English (~1,000 simple words) + diagrams, refined
   by native speakers
6. **Legal navigation reports** — "here's how we did it in [county/country]"
7. **Simplifications** — subtract until only the essence remains

## How to Contribute

1. Fork this repository
2. Make your change in your fork
3. Open a pull request describing what changed and *where you tested it*
4. Field-tested changes are prioritized; theory is welcome but labeled as theory

## Adaptation Patch Format

When reporting what worked or failed in your location, use:

```
LOCATION:    (country, region, climate driver)
WHAT:        (which kernel document/module)
WORKED:      (what succeeded — exact species, design, dimensions)
FAILED:      (what failed and the observed failure mode)
PATCH:       (the correction other communities should adopt)
SEASON/YEAR: (when tested)
```

## Governance Contributions

Changes to `09-GOVERNANCE/` require extra care — governance is load-bearing.
Proposals must state how the change preserves: equal standing of all members,
freedom to leave, public transparency, and comfort of dissent.

## Code of Conduct

Be honest, be practical, be generous. Assume good faith. No hierarchy of
contributors — a first-time contributor's field report outweighs a maintainer's
theory.
