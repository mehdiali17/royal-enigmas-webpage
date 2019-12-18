# Royal Enigmas    
![High res render from Maya](https://github.com/mehdiali17/royal-enigmas-webpage/blob/master/high%20res.png)



# Concept
We were asked to make a scene that corresponds with the context of Habib University, so we thought what better than a scene that accurately depicts the ideal journey each student at Habib has to take. One of our team members already had a scene made where a ball goes upstairs, so we recreated that scene and added yohsin colors to it. We used Maya to build our scene using planes and sphere, these objects were later triangulated for an easy import to our raytracer.

# Scene
We built the scene using Maya, the scene consists of triangulated meshes that make up the sphere, the stair case and the walls in our scene. This scene was exported in a .obj file, which lists down all vertices, their normals and also faces which can be used to get a list of all primitives in the scene.

# Image Features
* The image contains multiple light sources to show yohsin colors at the end of the staircase.
* There are more than 800,000 primitives; approximately a million primitives in the scene.

# Code Features
In working on the extension of the simpler version of the RayTracer, which had more basic basic functionalities. Expandig the raytracer was a matter of adding more details to our scenes through Lights and Materials.

* __Lights__: 
We implemented the Ambient Light source, the Point Light source and the Spotlight source.

* __Materials__:
The materials we defined were Reflective and Matte. Reflective inherits from the Phong model.

# Build
__These are the files used for testing purposes:__
* [buildChapter14.cpp](https://github.com/habib-university/cs440-fall19-proj-ii-the-royal-enigmas/blob/master/src/build/buildChapter14.cpp) builds the following scene:

![buildChapter14's render](https://github.com/mehdiali17/royal-enigmas-webpage/blob/master/buildChapter14.png)
* [buildMvp.cpp](https://github.com/habib-university/cs440-fall19-proj-ii-the-royal-enigmas/blob/master/src/build/buildMvp.cpp) builds the following scene:

![buildMvp's render](https://github.com/mehdiali17/royal-enigmas-webpage/blob/master/buildMvp.png)
* [buildHelloWorld.cpp](https://github.com/habib-university/cs440-fall19-proj-ii-the-royal-enigmas/blob/master/src/build/buildHelloWorld.cpp) builds the following scene:

![buildHelloWorld's render](https://github.com/mehdiali17/royal-enigmas-webpage/blob/master/buildHelloWorld.png)
* [buildLightTest.cpp](https://github.com/habib-university/cs440-fall19-proj-ii-the-royal-enigmas/blob/master/src/build/buildLightTest.cpp) builds the following scene:

![buildLightTest's render](https://github.com/mehdiali17/royal-enigmas-webpage/blob/master/buildLightTest.png)

__All these files were used to test out our code.__

# Acknowledgment
* Kevin Suffern's [Ray Tracer From The Ground Up](http://www.raytracegroundup.com/).
* [Team Raytracer](https://github.com/team-raytracer/raytracer)'s practical approach to ray tracing.
* [Waqar Saleem](https://habib.edu.pk/SSE/dr-waqar-saleem/) for his lectures.
* [Stackoverflow](https://stackoverflow.com/) for debugging the code.

# Team
1. Mehdi Ali (mb03027)
2. Mohammad Ahmed (ma04007)
3. Naufil Sidiqqui (ns02399)
4. Sarfaraz Shahid (sh02929)
5. Muhammad Ali Bhutto (mb01468)
