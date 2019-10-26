# MeshSimplification
## Introduction

MeshPolygonization is an implementation of Structure-aware Mesh Simplification, developed during the graduation project of Vasileios Bouzas for the MSc Geomatics of TUDelft, Netherlands (for more details, please visit the official education repository of TUDelft: https://repository.tudelft.nl/islandora/search/?collection=education).

The main characteristic of this method is structure awareness — namely, the recovery and preservation, for the input mesh, of both its primitives and the interrelationships between them (their configuration in 3D space). This awareness asserts that the resulting mesh closely follows the original and at the same time, dictates the geometric operations needed for its construction in the first place — thus providing accuracy, along with computational efficiency. The proposed methodology is divided into three main stages: (a) primitive detection via mesh segmentation, (b) storage of primitive interrelationships in a structure graph and (c) polygonization. In particular, polygonization is accomplished here by approximating the primitive borders with a building scaffold, out of which a set of candidate faces is defined. The selection of faces from the candidate set to form the simplified mesh is achieved through the formulation of a linear binary programming problem, along with certain hard constraints to ensure that this mesh is both manifold and watertight.

<p align="center">
  <img src="images/overview.png" width="450" height="300">
</p>

## Dependencies
## Structure
