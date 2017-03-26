# chart-dsl

The goal of this repository is to design a [DSL](https://en.wikipedia.org/wiki/Domain-specific_language)
to represent a chords chart in a text file.

The [chart-editor](https://github.com/openchordcharts/chart-editor), written in Elm,
stores chords charts in an Elm data structure ([sample for "All of me"](https://github.com/openchordcharts/chart-editor/blob/master/src/Samples.elm)).

This would be more convinient to manipulate a plain text file, like so:

```chords-chart
---
title: All of me
key: C
---

# A
C - E7 - A7 - Dm -

# B
E7 - Am - D7 - G7 -

# A

# C
F Fm C A7 Dm7b5 G7 C -
```

See also:
- [sample charts](./samples) directory
- [`GRAMMAR.md`](./GRAMMAR.md)
