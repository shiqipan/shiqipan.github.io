---
title: "Polyhedron Edge Rotation"
collection: talks
type: "Research project"
permalink: /research/polyhedron_edge_rotation
venue: "with Prof. Joseph O'Rourke"
date: 2020-03-01
location: "Smith College, MA"
---

This project investigates the path of convex polyhedra' edge rotation on a plane. Specially, given a convex polyhedron and a target point on a same plane, we analyze possible edge-rotation paths that the polyhedron takes to reach to the target.

The project can be further divided into two components:
* Animation of convex polyhera's edge rotations along a Greedy path towards the target  
** [A Mathematica program](https://github.com/shiqipan/polyhedron-greedy-edge-roll) that generates the rotation animation. Note the Greedy path is namely where at each iteration, polyhedron perform the rotation that will provide the shortest distance to the target in the current iteration.
* Investigation of the shortest paths for the five regular convex polyhedra, or the Platonic Solids, towards the target
** [A proposed formula](https://academicpages.github.io/files/paper1.pdf) that computes the shorest path and its distance for the Platonic Solids
** [A Mathematica program](https://github.com/shiqipan/rolling-polyhedron-covered-area) that visualizes areas could be covered by convex polyhedra's base within a number of rotations. This helps the analysis of the proposed formula above.
