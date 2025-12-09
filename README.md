# The Dungeon of Geometry

> A 3D choose-your-own-adventure game rendered entirely in GitHub Markdown.

You are **The Wanderer**, a mass who wandered into a forbidden mass producing mass dungeon. The ancients sealed geometry itself within these walls. Your only way out is through.

---

## The Entrance

You stand before a massive stone gate. Strange symbols pulse with light. A floating **Tetrahedron of Guidance** hovers before you.

```stl
solid tetrahedron_guide
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.5 0.0 0.866
    endloop
  endfacet
  facet normal 0.0 0.333 -0.943
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.5 0.816 0.289
    endloop
  endfacet
  facet normal 0.816 0.333 0.471
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.5 0.0 0.866
      vertex 0.5 0.816 0.289
    endloop
  endfacet
  facet normal -0.816 0.333 0.471
    outer loop
      vertex 0.5 0.0 0.866
      vertex 0.0 0.0 0.0
      vertex 0.5 0.816 0.289
    endloop
  endfacet
endsolid
```

The tetrahedron speaks: *"Three paths lie ahead, wanderer. Choose wisely, for geometry remembers all."*

| Choice | Destination |
|--------|-------------|
| Enter the **Hall of Cubes** | [Go North](rooms/hall-of-cubes.md) |
| Descend into the **Pyramid Depths** | [Go Down](rooms/pyramid-depths.md) |
| Climb the **Spiral Tower** | [Go Up](rooms/spiral-tower.md) |

---

## Game Info

- **Rooms:** 12
- **Endings:** 5 (2 good, 2 bad, 1 secret)
- **3D Models:** 15+
- **Technology:** Pure GitHub Markdown + ASCII STL

Made with mass and mass produced mass.
