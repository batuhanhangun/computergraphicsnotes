# 1. Introduction 

<b><i>Computer graphics</i></b> is a sub-field of computer science that deals with the creation and manipulation of images. Such images might be, 
* Visual effects
* Illustrations
* Animations
* 2 dimensional
* 3 dimensional
* Synthetic 
* Produced by manipulation of real images 

Studying computer graphics requires knowledge on the,
* Hardware 
* File formats
* Graphics APIs

## 1.1 Graphics Areas

Major areas of computer graphics:
* <b><i>Modeling</i></b>: Mathematical specification of shape and appearance properties in a way that can be stored on the computer. For example, a coffee mug might be described as a set of ordered 3D points along with some interpolation rule to connect the points and a reflection model that describes how light interacts with the mug. 
* <b><i>Rendering</i></b>: Creation of shaded images from 3D computer models.
* <b><i>Animation</i></b>: Creating an illusion of motion through sequences of images. It uses modeling and rendering but adds the key issue of movement over time, which is not usually dealt with in basic modeling
and rendering.

Areas related with computer graphics:
* <b><i>User interaction</i></b> deals with the interface between input devices such as mice and tablets, the application, feedback to the user in imagery, and other sensory feedback. 
* <b><i>Virtual reality</i></b> attempts to <i>immerse</i> the user into a 3D virtual world. This typically requires at least stereo graphics and response to head motion. 
* <b><i>Visualization</i></b> attempts to give users insight into complex information via visual display 
* <b><i>Image processing</i></b> deals with the manipulation of 2D images and is used in both the fields of graphics and vision
* <b><i>Three-dimensional scanning</i></b> uses range-finding technology to create measured 3D models. 
* <b><i>Computational photography</i></b> is the use of computer graphics, computer vision, and image processing methods to enable new ways of photographically capturing objects, scenes, and environments.

## 1.2 Major Applications

Major applications of computer graphics:
* Video games
* Cartoons
* Visual effects
* Animated films
* CAD/CAM
* Simulation
* Medical imaging
* Information visualization

## 1.3 Graphics APIs

<b><i>An application program interface</i></b> (API) is a standard collection of functions to perform a set of related operations, and a graphics API is a set of functions that perform basic operations such as drawing images and 3D surfaces into windows on the screen.

Graphics programs need to be able to use two related APIs
* A graphics API for visual output 
* A user-interface API to get input from the user

Two approaches for graphics/user-interface APIs:
1. The integrated approach: Where the graphics and userinterface toolkits are integrated and portable packages that are fully standardized and supported as part of the language (e.g. Java).
2. Seperated approach: Graphics functionality is provided by a software library (e.g. OpenGL, Direct3D) tied to a language such as C++, and user-interface software is an independent entity that might vary from system to system.

The problem with the second approach is to write a portable code. A portable library layer may be needed to encapsulate the system-specific code.

## 1.4 Graphics Pipeline

<b><i>Graphics pipeline</i></b> is a special software/hardware subsystem that efficiently draws 3D primitives in perspective. The basic operations in the pipeline map the 3D vertex locations to 2D screen positions and shade the triangles so that they both look realistic and appear in proper back-to-front order. <i>z-buffer</i> is a special memory buffer that is used to solve the drawing realistic triangles problem. 
