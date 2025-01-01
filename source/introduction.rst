Introduction
============
Easy Patch 2 can help you create standard topology mesh in a patch, you can freely draw the boundary of patch, the result consists by quad mesh and pole with only N-Pole and E-Pole. This is not a fully automatic retopology addon, this addon is suitable for those who want to control edge flow. The number of edgeflow boundaries you can create is 3~6.


Tips for use
----------------
For a good result, you should know the edge flow going. A simple way to distinguish edge flow is separate it them by sharp corner. Every edge flow for a correspond boundary, and the addon will calculate the combination of edge flow. A edge flow is like a grid mesh, in the head example below, the edge flow coming from the eye, cheek, chin, mouse, nose.(It can be observed that the edge flow coming from the nose and philtrum do not have a clear sharp corner to separate them, so I regard them as one edge flow.) , so I draw 5 boundaries for every edge flow.


What is difference between 1 and 2
------------------------------------
I rewrite the drawing logic so you can freely and smoothly draw edgeflow boundary. If you are not confortable with it, I also remaing 1 downloadable.


Reference
-----------
[1]. Takayama, Kenshi, Daniele Panozzo, and Olga Sorkine‐Hornung. "Pattern‐Based Quadrangulation for N‐Sided Patches." Computer Graphics Forum. Vol. 33. No. 5. 2014.

[2]. https://github.com/fedackb/mesh-fairing
