# The Direct Approach

The octahedron pauses. Eight faces blink in confusion.

*"You... refuse the riddle?"*

*"None have ever refused the riddle. It is tradition. It is protocol. It is... geometry."*

A long pause. The eight voices confer in whispered angles.

```stl
solid confused_octahedron
  facet normal 0.0 0.707 0.707
    outer loop
      vertex 0.0 1.0 0.0
      vertex -1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.707 0.707 0.0
    outer loop
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal 0.0 0.707 -0.707
    outer loop
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 -1.0
    endloop
  endfacet
  facet normal -0.707 0.707 0.0
    outer loop
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 -1.0
      vertex -1.0 0.0 0.0
    endloop
  endfacet
  facet normal 0.0 -0.707 0.707
    outer loop
      vertex 0.0 -1.0 0.0
      vertex 0.0 0.0 1.0
      vertex -1.0 0.0 0.0
    endloop
  endfacet
  facet normal 0.707 -0.707 0.0
    outer loop
      vertex 0.0 -1.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 -0.707 -0.707
    outer loop
      vertex 0.0 -1.0 0.0
      vertex 0.0 0.0 -1.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -0.707 -0.707 0.0
    outer loop
      vertex 0.0 -1.0 0.0
      vertex -1.0 0.0 0.0
      vertex 0.0 0.0 -1.0
    endloop
  endfacet
endsolid
```

Finally, the eight voices speak again:

*"We... respect your directness. Too long have we guarded this place with puzzles and games. You remind us that sometimes the shortest path between two points is simply... a line."*

*"Very well. The exit is yours. But know that you have changed nothing. You have learned nothing. You leave as you entered."*

A door appears. Plain. Simple. Geometric.

| Choice | Destination |
|--------|-------------|
| Leave without wisdom | [Exit](exit-empty.md) |
| Wait — ask them to teach you anyway | [Learn](octahedron-correct.md) |

---

*Sometimes the answer is to refuse the question.*
