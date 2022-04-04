# EE4375 - Finite Element Modelling
This repository contains Jupyter notebooks with Julia code for several finite difference and finite element method implementations in one and two spatial dimensions. The problems being solved are mostly electro- and magnetostatics. Below is a list of all projects.

## 1D FDM
* es_cylindrical: Electrostatics in cylinder coordinates.
* ms_cylindrical: Magnetostatics in cylinder coordinates.

## 2D FDM
* es_capacitor: Electrostatics simulation of a parallel-plate capacitor using two different methods.
  - First, using a domain with Dirichlet applied to all sides.
  - Second, by applying symmetry conditions to two sides, and voltage to the top and bottom boundaries.

## 1D FEM
* es_planar: Electrostatics in Cartesian coordinates.
* ms_planar: Magnetostatics in Cartesian coordinates (contains both my own implementation and a verification using Gridap.jl).

## 2D FEM
* cable_skin: First attempt at a magnetostatic simulation (including skin effect) in a simple high-voltage cable using Gridap.jl.
* cable_skin2: Magnetostatic simulation (including skin effect) using a coupled field-circuit approach.
* coaxial_cable: Electrostatics simulation of a coaxial cable configuration (own implementation and Gridap.jl)
* es_planar: Electrostatics in Cartesian coordinates (own implementation and Gridap.jl).
