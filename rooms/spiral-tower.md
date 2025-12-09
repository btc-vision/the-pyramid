# The Spiral Tower

You climb weathered stone steps that twist impossibly upward. The geometry defies logic — you're somehow always ascending yet never getting higher.

At the top, a helix of pure light awaits.

```stl
solid spiral_guardian
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.5 0.0 0.5
    endloop
  endfacet
  facet normal 0.5 0.0 0.866
    outer loop
      vertex 0.5 0.0 0.5
      vertex 1.0 0.0 0.0
      vertex 0.75 1.0 0.25
    endloop
  endfacet
  facet normal 0.866 0.0 -0.5
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 0.0
      vertex 0.75 1.0 0.25
    endloop
  endfacet
  facet normal -0.866 0.0 -0.5
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.5 0.0 0.5
      vertex 0.25 1.0 0.75
    endloop
  endfacet
  facet normal 0.0 0.5 0.866
    outer loop
      vertex 0.75 1.0 0.25
      vertex 0.25 1.0 0.75
      vertex 0.5 2.0 0.5
    endloop
  endfacet
  facet normal 0.707 0.5 0.5
    outer loop
      vertex 0.5 0.0 0.5
      vertex 0.25 1.0 0.75
      vertex 0.75 1.0 0.25
    endloop
  endfacet
endsolid
```

The Spiral speaks in frequencies:

*"I am continuous where others are discrete. I am the path that never ends. Tell me, wanderer: what shape has one face, one edge, and can be cut in half to become two interlocked rings?"*

| Your Answer | Result |
|-------------|--------|
| "A Möbius strip" | [Answer](spiral-correct.md) |
| "A donut?" | [Answer](spiral-wrong.md) |
| Grab the spiral | [Touch it](spiral-grab.md) |

---

[← Back to Entrance](../README.md)
