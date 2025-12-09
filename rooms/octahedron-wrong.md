# Spherical Confusion

*"A SPHERE?!"*

All eight faces of the octahedron turn various shades of geometric rage.

*"A sphere has INFINITE faces! It is the limit of polygons, not a polygon itself! It has no vertices! No edges! It is the ANTITHESIS of discrete geometry!"*

The chamber begins to collapse inward. The octahedron expands, its eight faces becoming walls, floor, and ceiling.

```stl
solid collapsing_chamber
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 0.0 2.0 0.0
      vertex 0.0 0.0 2.0
      vertex 2.0 0.0 0.0
    endloop
  endfacet
  facet normal -0.577 0.577 0.577
    outer loop
      vertex 0.0 2.0 0.0
      vertex -2.0 0.0 0.0
      vertex 0.0 0.0 2.0
    endloop
  endfacet
  facet normal -0.577 0.577 -0.577
    outer loop
      vertex 0.0 2.0 0.0
      vertex 0.0 0.0 -2.0
      vertex -2.0 0.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 -0.577
    outer loop
      vertex 0.0 2.0 0.0
      vertex 2.0 0.0 0.0
      vertex 0.0 0.0 -2.0
    endloop
  endfacet
  facet normal 0.577 -0.577 0.577
    outer loop
      vertex 0.0 -2.0 0.0
      vertex 2.0 0.0 0.0
      vertex 0.0 0.0 2.0
    endloop
  endfacet
  facet normal -0.577 -0.577 0.577
    outer loop
      vertex 0.0 -2.0 0.0
      vertex 0.0 0.0 2.0
      vertex -2.0 0.0 0.0
    endloop
  endfacet
  facet normal -0.577 -0.577 -0.577
    outer loop
      vertex 0.0 -2.0 0.0
      vertex -2.0 0.0 0.0
      vertex 0.0 0.0 -2.0
    endloop
  endfacet
  facet normal 0.577 -0.577 -0.577
    outer loop
      vertex 0.0 -2.0 0.0
      vertex 0.0 0.0 -2.0
      vertex 2.0 0.0 0.0
    endloop
  endfacet
endsolid
```

*"You will remain here until you learn the difference between polytopes and their limits."*

---

## BAD ENDING: Trapped in Eight Dimensions

You are now sealed within an octahedral prison. Eight faces watch you eternally. You have lots of time to study geometry now.

*"The dual of ignorance is education. Perhaps in a few millennia you will understand."*

| Choice | Destination |
|--------|-------------|
| Study harder | [Play again](../README.md) |

---

*GAME OVER — Ending unlocked: "Eight-Faced Prison"*
