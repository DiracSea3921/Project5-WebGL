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
README
-------------------------------------------------------------------------------
All students must replace or augment the contents of this Readme.md in a clear 
manner with the following:

* A brief description of the project and the specific features you implemented.
* At least one screenshot of your project running.
* A 30 second or longer video of your project running.  To create the video you
  can use http://www.microsoft.com/expression/products/Encoder4_Overview.aspx 
* A performance evaluation (described in detail below).

-------------------------------------------------------------------------------
PERFORMANCE EVALUATION
-------------------------------------------------------------------------------
All new effects added will still keep fps 60. I think it is not necessary to evaluate the performance now.
-------------------------------------------------------------------------------
THIRD PARTY CODE POLICY
-------------------------------------------------------------------------------
* Use of any third-party code must be approved by asking on the Google groups.  
  If it is approved, all students are welcome to use it.  Generally, we approve 
  use of third-party code that is not a core part of the project.  For example, 
  for the ray tracer, we would approve using a third-party library for loading 
  models, but would not approve copying and pasting a CUDA function for doing 
  refraction.
* Third-party code must be credited in README.md.
* Using third-party code without its approval, including using another 
  student's code, is an academic integrity violation, and will result in you 
  receiving an F for the semester.

-------------------------------------------------------------------------------
SELF-GRADING
-------------------------------------------------------------------------------
* On the submission date, email your grade, on a scale of 0 to 100, to Harmony, 
  harmoli+cis565@seas.upenn.com, with a one paragraph explanation.  Be concise and 
  realistic.  Recall that we reserve 30 points as a sanity check to adjust your 
  grade.  Your actual grade will be (0.7 * your grade) + (0.3 * our grade).  We 
  hope to only use this in extreme cases when your grade does not realistically 
  reflect your work - it is either too high or too low.  In most cases, we plan 
  to give you the exact grade you suggest.
* Projects are not weighted evenly, e.g., Project 0 doesn't count as much as 
  the path tracer.  We will determine the weighting at the end of the semester 
  based on the size of each project.

---
SUBMISSION
---
As with the previous project, you should fork this project and work inside of
your fork. Upon completion, commit your finished project back to your fork, and
make a pull request to the master repository.  You should include a README.md
file in the root directory detailing the following

* A brief description of the project and specific features you implemented
* At least one screenshot of your project running.
* A link to a video of your project running.
* Instructions for building and running your project if they differ from the
  base code.
* A performance writeup as detailed above.
* A list of all third-party code used.
* This Readme file edited as described above in the README section.
