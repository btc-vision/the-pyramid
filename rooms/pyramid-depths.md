# The Pyramid Depths

You descend into darkness. The air grows thick with ancient dust. Torches flicker to life, revealing a massive pyramid suspended upside-down over a bottomless void.

```stl
solid inverted_pyramid
  facet normal 0.0 1.0 0.0
    outer loop
      vertex -1.0 2.0 -1.0
      vertex 1.0 2.0 -1.0
      vertex 1.0 2.0 1.0
    endloop
  endfacet
  facet normal 0.0 1.0 0.0
    outer loop
      vertex -1.0 2.0 -1.0
      vertex 1.0 2.0 1.0
      vertex -1.0 2.0 1.0
    endloop
  endfacet
  facet normal 0.0 -0.447 0.894
    outer loop
      vertex -1.0 2.0 1.0
      vertex 1.0 2.0 1.0
      vertex 0.0 0.0 0.0
    endloop
  endfacet
  facet normal 0.894 -0.447 0.0
    outer loop
      vertex 1.0 2.0 1.0
      vertex 1.0 2.0 -1.0
      vertex 0.0 0.0 0.0
    endloop
  endfacet
  facet normal 0.0 -0.447 -0.894
    outer loop
      vertex 1.0 2.0 -1.0
      vertex -1.0 2.0 -1.0
      vertex 0.0 0.0 0.0
    endloop
  endfacet
  facet normal -0.894 -0.447 0.0
    outer loop
      vertex -1.0 2.0 -1.0
      vertex -1.0 2.0 1.0
      vertex 0.0 0.0 0.0
    endloop
  endfacet
endsolid
```

A voice echoes from the pyramid's tip, which points down into infinity:

*"I am the Pharaoh of Points. I have waited 4,000 polygons for a worthy challenger. Answer me this: what has four faces, four vertices, and holds the secret of stability?"*

| Your Answer | Result |
|-------------|--------|
| "A tetrahedron" | [Answer](pyramid-correct.md) |
| "A pyramid, like you" | [Answer](pyramid-wrong.md) |
| Jump into the void | [Leap](the-void.md) |

---

[← Back to Entrance](../README.md)
