# PlotMath-TIPE-

Project made during the TIPE sessions of MP2I / MPI\*

## Requirements
glew-2.1.0 and glfw-3.4 are necesarry.

## Objectives :
- Representation of implicit functions on a 2D environement.
   - Improvements of the representation when zooming inside.
   - Real time processing (also during improvements).
 
## Methods used :
- For representation :
   - Points stored in Quadtrees, straight lines to link points.
   - Linking : Kruskal algorithm with distance as criteria.
 - For improvements (2 methods searched):
   1. Adding a new point between every consecutive couple of visible points.
   2. Recreating visible cells of the Quadtree

