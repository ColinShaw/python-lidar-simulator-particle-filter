# Lidar Particle Filter

This is just a toy project simulating a robot with a front view
lidar (e.g. not 360 degree) localizing itself in some space.  The 
map is in Cartesian coordinates (so that we can draw it easily), and
the particle cloud calculations are from radial coordinates from the
lidar.  

The point of the project is to explore best practice in terms
of the number of lidar samples, handling of the known map points, 
and reasonable visualizations.  The end goal is to rewrite it in 
C++ and have a performant particle filter that I can put on 
a mobile robot for assisting in localization.

