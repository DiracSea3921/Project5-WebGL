-------------------------------------------------------------------------------
CIS565: Project 5: WebGL
-------------------------------------------------------------------------------
Fall 2014
-------------------------------------------------------------------------------

This Proj includes two parts. First part is a sin wave grid. Second is a 3d earth with different types of textures. All done with WebGL and can be displayed in Web Browser. The recommended Browser is FireFox.

-------------------------------------------------------------------------------
PART 1
-------------------------------------------------------------------------------

![](https://github.com/DiracSea3921/Project5-WebGL/blob/master/vert.png)


![](https://github.com/DiracSea3921/Project5-WebGL/blob/master/sin.png)
Sin Wave start from center of the plane

-------------------------------------------------------------------------------
PART 2
-------------------------------------------------------------------------------

[Run The Demo](http://diracsea3921.github.io/Project5-WebGL/) 

[Video](https://www.youtube.com/watch?v=0NempLNsCtA&list=UUNSZyX4lRYdFDlX9ns1ua8A)

Implemented:

* Bump mapped terrain
* Rim lighting to simulate atmosphere
* Night-time lights on the dark side of the globe
* Specular mapping
* Moving clouds


Extra:

* Cloud shadows via ray-tracing through the cloud map in the fragment shader

Add a uniform light dir vector in world space to help calculate the correct offset. Multiply with the normal space matrix to transform it. Use x and y for the final offset.

![](https://github.com/DiracSea3921/Project5-WebGL/blob/master/earth.png)

![](https://github.com/DiracSea3921/Project5-WebGL/blob/master/earth2.png)

![](https://github.com/DiracSea3921/Project5-WebGL/blob/master/earth3.png)

![](https://github.com/DiracSea3921/Project5-WebGL/blob/master/earth4.png)


-------------------------------------------------------------------------------
PERFORMANCE EVALUATION
-------------------------------------------------------------------------------
All new effects added will still keep fps 60. I think it is not necessary to evaluate the performance now.

