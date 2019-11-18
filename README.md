# python-2DFlow-LBM
2D flow around a cylinder using Lattice Boltzmann Method(LBM)

The Lattice Boltzmann Method (LBM) is a modern numerical technique, very efficient, 
flexible to simulate different flows within complex and varying geometries.


parameter---------------------------------------------,
maxIter = 200000 # Total number of time iterations.

Re      = 220.0  # Reynolds number.

nx = 520; ny = 180; ly=ny-1.0; q = 9 # Lattice dimensions and populations.

cx = nx/4; cy=ny/2; r=ny/9;          # Coordinates of the cylinder.

uLB     = 0.04                       # Velocity in lattice units.

nulb    = uLB*r/Re; omega = 1.0 / (3.*nulb+0.5); # Relaxation parameter.
parameter---------------------------------------------


![image](https://github.com/weisting-sinica/python-2DFlow-LBM/blob/master/lbmFlowAroundCylinder.gif)
