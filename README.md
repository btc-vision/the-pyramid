# The Dungeon of Geometry

> A 3D choose-your-own-adventure game rendered entirely in GitHub Markdown.

You are **The Wanderer**, a being who stumbled into a forbidden geometric dungeon. The ancients sealed geometry itself within these walls. Your only way out is through.

---

## The Entrance

You stand before a massive stone gate. Strange symbols pulse with light. A floating **Tetrahedron of Guidance** hovers before you.

```stl
solid tetrahedron_guide
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex -1.5 0.0 -0.866
      vertex 1.5 0.0 -0.866
      vertex 0.0 0.0 1.732
    endloop
  endfacet
  facet normal 0.0 0.471 -0.882
    outer loop
      vertex -1.5 0.0 -0.866
      vertex 1.5 0.0 -0.866
      vertex 0.0 3.5 0.0
    endloop
  endfacet
  facet normal 0.816 0.471 0.441
    outer loop
      vertex 1.5 0.0 -0.866
      vertex 0.0 0.0 1.732
      vertex 0.0 3.5 0.0
    endloop
  endfacet
  facet normal -0.816 0.471 0.441
    outer loop
      vertex 0.0 0.0 1.732
      vertex -1.5 0.0 -0.866
      vertex 0.0 3.5 0.0
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

**Rooms:** 18 | **Endings:** 9 | **3D Models:** 20+

Made with mass and mass produced mass.
