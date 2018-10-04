# choreographic-interventions-s19
# Choreographic Interventions Syllabus - Spring 2018

- Spring 2017, Mondays, 7PM-9:55PM in Studio 1 @[111 2nd Avenue](https://goo.gl/maps/FfVoDSMxNSN2)
- Mimi Yin, mimi.yin@nyu.edu
- [Office Hours Signup](https://itp.nyu.edu/inwiki/Signup/Mimi)
- [Book Time in Studio 1](https://calendar.google.com/calendar?cid=bnl1LmVkdV9oOHRnbGFjdmpuYWo4NnZ0NWZkaGU0OGI3OEBncm91cC5jYWxlbmRhci5nb29nbGUuY29t)

### Course Structure | [See introductory description below.](#course-description)
Over the course of the semester, we will cover 4 topic areas that correspond to 4 parameters of choreography: Pathways, The Body (Form + Substance), Space and Time. Topics will be introduced through movement-based improvisation exercises. Computational strategies will be examined through code examples. For each topic, students will create a small movement study in 2 stages: the first analog, the second computational with the aim of fully exploring how technology "intervened" and changed the choreographic process.

The class will culminate in a showing of student work. Final projects can either be in the form of a tool to aid in movement practice, an interactive installation or a live performance.

Because course topics are organized around movement concepts, technical topics will be introduced and built upon week to week.
- What do cameras see? RGB, IR, Kinect, Mocap...
- Skeletons, Depth Maps and Silhouettes
- Basic programming concepts: Variables, Conditionals, Loops, Arrays
- 2D v. 3D
- Drawing and animation
- Random, noise, oscillation, easing, etc.
- Calculating velocity and acceleration
- Mapping values
- Manipulating text, sound and live image processing

"Soft Skills" we will practice:
- Sketching (as in drawing on paper) choreographic ideas.
- Defining rule sets for movement.
- Defining rules of interaction.
- Deconstructing choreography into parameters for code.
- Extracting choreographic ideas from code.

### Workbook
Each topic will be introduced through paper-based drawing exercises and code examples. [Google Drive Link](https://drive.google.com/drive/folders/0B_lnhZP0dCt8MHNPamxUTzJSMDg?usp=sharing)

### Programming Resources
- [p5.js](http://p5js.org/) | [Reference](http://p5js.org/reference/) | [Web Editor](http://alpha.editor.p5js.org/)
- [Coding Rainbow](http://thecodingtrain.com/)
- [Atom Editor](https://github.com/mimiyin/sense-me-move-me/wiki/Atom)
- [Kinectron](https://github.com/lisajamhoury/kinectron)
- [The Nature of Code Book](http://natureofcode.com/book/)

### Dance + Movement Resources
- Select chapters from [The Viewpoints Book](http://www.amazon.com/The-Viewpoints-Book-Practical-Composition/dp/1559362413) | [PDF](https://stilluntitledproject.files.wordpress.com/2014/11/anne-bogart-and-tina-landau-the-viewpoints-book.pdf)
- Select chapters from [Dynamic Alignment Through Imagery](http://www.amazon.com/Dynamic-Alignment-Through-Imagery-Edition/dp/0736067892) | [Google Books](https://books.google.com/books?id=CBwV_g8DhEMC&lpg=PA2&ots=nRQ2JS3SWv&dq=dynamic%20alignment%20chapters&pg=PP1#v=onepage&q&f=false)
- [Forsythe Technique Videos on Youtube](https://www.youtube.com/user/GrandpaSafari/videos)


### Dance students checking stuff out of ITP ER:
   - Check it out under my name
   - Bring your NYU ID
   - netid
   - Nxxxx id number

   ***
   ***

## Week 1: Introduction

### Questions
   * Why are we here?
   * What is interaction?
      * Do you need sensors to be interactive?
   * What is a choreographic intervention?
   * What are the parameters of choreography?
   * How is code an expressive medium?

### In-class
   * Analyze how we all entered the studio.
   * Introduce ourselves: What's your favorite resting position?
   * Introduction to computational thinking through dynamic drawing
   * Make a duet between a dancer and a drawer
   * Examples:
      * [Drawing Lines](http://alpha.editor.p5js.org/move.mimi/sketches/ByPtNLI4z) | [Fullscreen](http://alpha.editor.p5js.org/full/ByPtNLI4z) | 1-Mode-At-A-Time: [0](http://alpha.editor.p5js.org/move.mimi/sketches/SJwTOF8Ez) | [1](http://alpha.editor.p5js.org/move.mimi/sketches/HyNmKKL4f) | [2](http://alpha.editor.p5js.org/move.mimi/sketches/SkEk9KUNM) | [3](http://alpha.editor.p5js.org/move.mimi/sketches/ByPfqt84f)
      * [Drawing a Trail](http://alpha.editor.p5js.org/move.mimi/sketches/H1flrLLVG) | [Fullscreen](http://alpha.editor.p5js.org/full/H1flrLLVG)
      * [Zeno's Paradox](http://alpha.editor.p5js.org/move.mimi/sketches/H1NWIIL4z)

### Assignment
   * ITPers: Watch [Forsythe Technique Videos](https://www.youtube.com/user/GrandpaSafari/videos): They range from 10s to 1 minute. Very short!
      * 16 videos that start with Forsythe-Writing
      * 23 videos that start with Forsythe-Lines
      * [Avoidance](https://www.youtube.com/watch?v=cqGyFiEXXIQ)
      * [Line](https://www.youtube.com/watch?v=aOd0PtgS8KU)
   * Everyone: Read chapter 2 of [Viewpoints](https://stilluntitledproject.files.wordpress.com/2014/11/anne-bogart-and-tina-landau-the-viewpoints-book.pdf).
   * Everyone: Review [Chapter 0](https://docs.google.com/document/d/1NPHHaCppnEJoR90W6ZOtrV3JDu1qq5VPCieSIwfQ0Jc/edit?usp=sharing) and complete sections 1.0 - 1.2 of [Chapter 1](https://docs.google.com/document/d/1SUp-7bKs1Cvez7pBSe3I0tTccWTw2q0TqgK7nyGI8cM/edit?usp=sharing) of the Workbook

***

## Week 2: Interacting with Pathways

### Questions
   * What are all the ways to interact with a pathway?
   * How do you choreograph code?
   * The dramaturgy of lines and random().

### In-class
   * Interacting with a static pathway (rope)
   * Interacting with a moving pathway (live drawing)
   * Deconstructing linear and random() motion
   * Choreographing linear and random pathways
   * Examples
      * [Bobby McFerrin](https://www.youtube.com/watch?v=DoNIOqUz9NM)
      * [Linear Pathway](http://alpha.editor.p5js.org/move.mimi/sketches/rJWBguUNf)
      * [Linear Pathway - Deconstructed](http://alpha.editor.p5js.org/move.mimi/sketches/rJnOzuI4M)
      * Linear Pathway with Controls: [Code](http://alpha.editor.p5js.org/move.mimi/sketches/rkMpbedVM) | [Fullscreen](http://alpha.editor.p5js.org/full/rkMpbedVM)
      * [Random Pathway](http://alpha.editor.p5js.org/move.mimi/sketches/HkL0VOUVf)
      * [Graphing Random](http://alpha.editor.p5js.org/move.mimi/sketches/SkwF9OLEM)
      * Random Pathway with Controls: [Code](http://alpha.editor.p5js.org/move.mimi/sketches/ByBuJtIEz) | [Fullscreen](http://alpha.editor.p5js.org/full/ByBuJtIEz)

### Assignment
   * Complete sections 1.3-1.4 of Chapter 1 of the Workbook.
   * Create a 1 minute duet using a live drawer and a dancer.
      * You can use the drawing lines, linear pathway with controls and random pathway with controls examples or create your own mash-up of those 3. Duet must be repeatable.

***

## Week 3: Dynamic Pathways

### Questions
   * How do you choreograph code? cont'd
   * The dramaturgy of noise() and circles.

### In-class
   * Deconstructing noise() and circular motion
   * Choreographing noisy and circular pathways
   * Examples
      * [Noisy Pathway](http://alpha.editor.p5js.org/move.mimi/sketches/ryi5E984G)
      * [Gaga](https://www.youtube.com/watch?v=OGPG1QL1vJc)
      * [Graphing Noise](http://alpha.editor.p5js.org/move.mimi/sketches/H16ZQ98Ez)
      * Noisy with Controls: [Code](http://alpha.editor.p5js.org/move.mimi/sketches/r11eUqI4G) | [Fullscreen](http://alpha.editor.p5js.org/full/r11eUqI4G)
      * [Circular Pathway](http://alpha.editor.p5js.org/move.mimi/sketches/rJSP_5ING)
      * [Circle with Tangents](http://alpha.editor.p5js.org/move.mimi/sketches/r1HaDcLEz)
      * [Circles and Sin/Cos](http://alpha.editor.p5js.org/move.mimi/sketches/rJ_vtcUNz)
      * Circular with Controls: [Code](http://alpha.editor.p5js.org/move.mimi/sketches/Sy7iKoIEf) | [Code](http://alpha.editor.p5js.org/full/Sy7iKoIEf)
      * [Sine for Speed](http://alpha.editor.p5js.org/move.mimi/sketches/B1qna5LVM)
      * [Circles and Sin/Cos and Tan](http://alpha.editor.p5js.org/move.mimi/sketches/Sk3TEiUEM)
      * [Polar Roses](https://en.wikipedia.org/wiki/Rose_(mathematics))
      * [Anne Teresa de Keersmaeker: Violin Fase](https://www.youtube.com/watch?v=i36Qhn7NhoA)
      * [Polar Rose-ish](http://alpha.editor.p5js.org/move.mimi/sketches/HJTDNYKVf)
      * [Pina Bausch: La Prima Vez](https://www.youtube.com/watch?v=mrHt6Ob9-3A)
      * [Timing things with frameCount and %](http://alpha.editor.p5js.org/move.mimi/sketches/rJAA5KkBG)
      * [Pathways in Visual Art](https://drive.google.com/drive/folders/18-ahAJQ1ogq1wANzjwBVjXzJNHC7CCrG)

### Assignment
   * Create a 1 minute duet between a programmed pathway and a dancer.
      * Pick from pathways we've discussed: linear, random, noisy, circular.
      * You can use more than 1 kind of pathway.
      * If you use a new kind of pathway (e.g. fractals), include an analysis of that pathway comparable to what we have done in class so that you are on comparable conceptual footing.

***
## Week 4 Show 2 Duets, Hello Kinect

### In-class
  * Introduction to Kinect v.2 camera
  * Kinectron server + p5.js
  * Drawing with the joints of the body
  * Examples
     * [Kinect Skeleton](http://alpha.editor.p5js.org/move.mimi/sketches/rJPcXh84z)
     * Kinect Skeleton - Draw Lines - 4 modes: [Code](http://alpha.editor.p5js.org/move.mimi/sketches/ByQxNn8NG) | [Fullscreen](http://alpha.editor.p5js.org/full/ByQxNn8NG)
     * Kinect Skeleton - Control Noise: [Code](http://alpha.editor.p5js.org/move.mimi/sketches/BJtH8dsIz) | [Fullscreen](http://alpha.editor.p5js.org/full/BJtH8dsIz)
     * Kinect Skeleton - Draw Lines - Multiple Bodies: [Code](http://alpha.editor.p5js.org/move.mimi/sketches/BJwpqUAEz) | [Fullscreen](http://alpha.editor.p5js.org/full/BJwpqUAEz)

### Assignment
   * Play together to draw with the body. [Instructions](https://github.com/mimiyin/choreographic-interventions-s18/wiki/Drawing-With-The-Body)
   * Watch + Read:
      * [Ghostcatching by Bill T. Jones](https://www.youtube.com/watch?v=aL5w_b-F8ig)
      * [Biped by Merce Cunningham](https://www.youtube.com/watch?v=a-QMlTsNtxM)
      * [Public Collection by Alexandra Pirici & Manuel Pelmus](https://www.youtube.com/watch?v=UoHtaPRFoPo)
      * [Pirici @New Museum](https://www.nytimes.com/2018/02/09/arts/dance/co-natural-alexandra-pirici-new-museum.html)
   * Read Chapter 7 of Dynamic Alignment: [Google Books](https://books.google.com/books?id=CBwV_g8DhEMC&lpg=PA2&ots=nRQ2JS3SWv&dq=dynamic%20alignment%20chapters&pg=PP1#v=onepage&q&f=false) | [PDF](https://drive.google.com/file/d/0B_lnhZP0dCt8LVZMRXlqNFFQaFk/view?usp=sharing)
   * Complete Sections 2.0-2.2 of [Chapter 2 of the Workbook](https://docs.google.com/document/d/19AHtqOiLSZQyVnWc6UNZzi75G_JFZLXLwaGtXkjDmRI/edit?usp=sharing)
***

## Week 5 Form + Substance: Re-architecture

### Questions
   * What are all the ways the body can fold?
   * What are all the ways the body can spiral?
   * What are all the ways the body is (as)symmetrical.
   * How would you walk if your head was facing back, in between your knees?

### In-class
   * Re-designing the skeleton in 2D and 3D
   * Review Kinect and Kinectron
   * Vector Math
   * Resources
      * [Bodies We Collected](https://drive.google.com/drive/folders/1W74yWhmgR1Cly2MFlATCqhzqtrmItiOw?usp=sharing)
      * [Merce Cunningham and Life Forms](https://www.youtube.com/watch?v=ROmTHBg8Nw0)
      * [Phantom Limb Effect](https://en.wikipedia.org/wiki/Phantom_limb)
      * [Martha Graham: Lamentations and Satyric Song](https://www.youtube.com/watch?v=npSXDzqwFJg)
      * [David Byrne: Stop Making Sense](https://youtu.be/av3j4WStj2A?t=180)
      * [Tutus: Romantic v. Pancake](https://en.wikipedia.org/wiki/Tutu_(clothing))
      * [Issey Miyake and Irving Penn](https://www.google.com/search?biw=1291&bih=898&tbm=isch&sa=1&ei=XzCQWpG0N8zb5gLR1KeIBg&q=issey+miyake+irving+penn&oq=issey+miyake+irving+penn&gs_l=psy-ab.3..0j0i24k1.9304.13950.0.14077.13.5.0.8.8.0.67.293.5.5.0....0...1c.1.64.psy-ab..0.13.309...0i13k1.0.vR3PuPm3nNg)
      * Kinect | [What is it?](https://en.wikipedia.org/wiki/Kinect)
         * [How depth-sensing works in Kinect2](http://www.gamasutra.com/blogs/DanielLau/20131127/205820/The_Science_Behind_Kinects_or_Kinect_10_versus_20.php) | [Microsoft SDK](https://msdn.microsoft.com/en-us/library/dn799271.aspx) | [Kinect Demo](http://123kinect.com/everything-kinect-2-one-place/43136/)
         * [Kinectron Library](https://github.com/lisajamhoury/kinectron) | [Download Kinectron App for PC](https://github.com/lisajamhoury/kinectron/releases/tag/0.0.4.6) | [Directions for installing](https://github.com/lisajamhoury/kinectron#kinectron-application-installation)
         * [DanO's Kinectron Tutorial](https://itp.nyu.edu/classes/dance-f16/kinect/)
      * Examples
         * [Skeleton with Bones](http://alpha.editor.p5js.org/move.mimi/sketches/H1-kcMfdM)
         * [Skeleton with 2D Shapes](http://alpha.editor.p5js.org/move.mimi/sketches/r1qp9ffuz)
      * Coding Tutorials & References
         * [Vectors in p5](http://p5js.org/reference/#/p5.Vector)
         * [Vertex in p5](http://p5js.org/reference/#/p5/vertex) | [curveVertex in p5](http://p5js.org/reference/#/p5/curveVertex)
         * Nature of Code: Introduction to Vectors: [Textbook](http://natureofcode.com/book/chapter-1-vectors/) | [Video](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6ZwSmtE13iJBcoI-r4y7iEc)

### Assignment
   * Bring a piece of clothing that changes the shape of your body to class next week.
   * Complete Sections 2.3-2.4 of Chapter 2 of the Workbook

***

## Week 6 Form + Substance: Distortion

### Questions
   * What is a body made of?
   * How can changing the way your body is represented change how you move?

### In-class
   * Show and tell clothes.
   * Play with Kinect funhouse mirrors
     * The Gumby Effect: Bending body contours.
     * Prickly Pears: Visualizing the sensation of pins and needles.
     * Rei Kawakubo: Bulging and pinching your insides.
   * Resources
      * [Processing Java and p5.js](https://github.com/processing/p5.js/wiki/Processing-transition)
      * [Processing Java and p5.js Cheatsheet](https://docs.google.com/document/d/126TTVuJ0fl2fv1Rcp7eAE7vR4rJ5gMGnBKaeZhSjPbs/edit?usp=sharing)
      * [Kinect PV2 Library for Processing Java on PC](https://github.com/ThomasLengeling/KinectPV2)
      * [OpenCV Library for Processing Java](https://github.com/atduskgreg/opencv-processing)
      * [Kinect for Mac](http://shiffman.net/p5/kinect/)
      * Code:
         * [Kinect2 Examples for Processing Java on PC](https://drive.google.com/open?id=1g3RyZycZVA3hD2sH1Q2rVUXjGyct9qnZ)
         * [Moving Bezier](http://alpha.editor.p5js.org/mimi/sketches/Hkbojc0Ie)
      * Video:
         * [Danse Des Masques](https://www.youtube.com/watch?v=mpOdxI1owdQ)
         * [Drunk Guy In Convenience Store](https://www.youtube.com/watch?v=8M_oBYNb6UU)

### Assignment
   * Create a mirror that distorts or re-architects the body to move in new and unexpected ways.
   * Be clear about how you think the mirror is going to make people move.
   * You should play with your mirror thoroughly to know what it is capable of. But others will be first to demo it.

***

## Week 7: Play with Mirrors, Preview of Week 8

### Assignment
   * Watch: Jiri Kylian | NDT : [Sweet Dreams](http://www.numeridanse.tv/en/video/1046_sweet-dreams)
      * What are all the ways in which Kylian is working with space? How are the spaces defined?
      * Why angular spaces? Why sharp edges? How would it be different if he used more traditional spotlights?
   * Complete [Chapter 3.0-3.3](https://docs.google.com/document/d/16GRMBthdGza-gdJMk5kWmJ7YWrDQK6pNZM6FWhlyQhw/edit?usp=sharing) of the Workbook
***

## Week 8: Space

### Questions
   * Can space be emotional?
   * What are all the ways to define space?
   * What are all the ways to interact with a space?
   * How do you choreograph a "dynamic" space, one that changes over time?
   * What is the difference between a space and a terrain?
   * How do terrains influence movement?
   * Can we define virtual terrains with sound?

### In-class
   * Interacting with dynamic spaces.
      * [Division](http://alpha.editor.p5js.org/mimi/sketches/SkHhftI9M)
      * [Moving Bisect](http://alpha.editor.p5js.org/move.mimi/sketches/ryEOkt8cM)
      * [Moving Trisect](http://alpha.editor.p5js.org/mimi/sketches/rJUlQF8qG)
      * [Growing Circle](http://alpha.editor.p5js.org/mimi/sketches/Bk6pMtLcG)
   * Jiri Kylian | NDT : [Sweet Dreams](http://www.numeridanse.tv/en/video/1046_sweet-dreams)
   * Floorplans: [Residential](https://www.google.com/search?q=floor+plans&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjE18_pnIraAhUQON8KHTIbCgQQ_AUICigB&biw=1488&bih=960) v. [Cathedral](https://www.google.com/search?q=cathedral+floor+plans&source=lnms&tbm=isch&sa=X&ved=0ahUKEwibgLClnYraAhXNSt8KHaWoDMUQ_AUICigB&biw=1488&bih=960)
   * [Kazimir Malevich](https://drive.google.com/drive/folders/0B_lnhZP0dCt8ek8wbVRzM18wcnM?usp=sharing)
   * [Esther Ferrer](https://drive.google.com/drive/folders/1qCtTa2cDVw9DKYQksT7G_wbwT6Rzjbhf)
   * [The Virginia Reel](https://www.youtube.com/watch?v=uBBdgcHimoM)

### Assignment
   * Complete [Chapter 3.4-3.5](https://docs.google.com/document/d/16GRMBthdGza-gdJMk5kWmJ7YWrDQK6pNZM6FWhlyQhw/edit?usp=sharing) of the Workbook on Terrains
   * Think about what you'd like to work with for your Final Project? What concepts from this class? What concepts from outside of this class?

***

## Week 9 Terrains
   * Interacting with sound terrains.
      * Multi-dimensional mapping to create terrains
      * Mapping linear motion to create non-linear terrains

### Questions
   * What is the difference between a space and a terrain?
   * Final Project thoughts: What concepts from this class? What concepts from outside of this class?
   
### In-class
   * Mapping Sound Terrains (Volume + mouseX): [Code](http://alpha.editor.p5js.org/move.mimi/sketches/r1CcXj8qz)
   * Mapping Kinect Skeleton to a Pitch Terrain: [Code](http://alpha.editor.p5js.org/move.mimi/sketches/r1dcGiM9z)
      * To help you understand this example:
      * [Review Objects in JS](https://www.youtube.com/watch?v=-e5h4IGKZRY)
      * [Video on p5.js Sound Synthesis](https://www.youtube.com/watch?v=Bk8rLzzSink)

###  Assignment
   * Create a space for next week using whatever means available to you: 
      * Studio 1 Tech: Floor projection, wall projection, speakers
      * Studio 1 Furniture: Barres, Chairs, Curtains, Music Stand, Piano
      * Add your own physical materials: Clip lights, fabric, garbage
      * Visuals: Code, pre-rendered, photography, video, drawings
      * Sound: Music, sound effects, computationally generated, spoken word, dialogue
   * Create a 3-5 minute sketch of your project that connects your 5 tableaus. You will perform it in class next week.
      * Consider what pathways you employ to get from tableau to tableau
   * Collect all of your materials into our shared Google Drive
   

***

## Project Development: Weeks 10, 11, 12

Workshop and user-test final project ideas.

## Showing: Week 12

# Course Description
Even where there is no connection between 2 events, if they happen at the same time, in the same space, we find relationships nonetheless.

So then what is the point of hooking up dancers to sensing devices to connect them to various media if the relationships already exist in our minds? Simply seeing a cause-and-effect relationship between movement (input) and media (output) is not enough.

This course re-conceives interactive media as a form of choreographic intervention. Instead of asking how dancers can control media, we will turn the tables to ask how interactive systems can influence movement. How do you make someone feel soft inside? How do you shake an entire room? How do you orchestrate duets between strangers?

To accomplish this, choreographers will learn to apply computational thinking to choreography and programmers will learn to apply choreographic thinking to computation. And to whatever extent possible, we will attempt to embody code.

Using computer vision and a broad range of media from graphics and video, to sound and text, we will look at directing both how people move (quality of movement) as well as where they move (pathways and spatial relationships).

We will evaluate the strengths and weaknesses of the various sensing technologies available to us today. How wide is the gulf between what we can see and feel (strength, hardness, contortion) and what a computer can see and interpret (locations, contours, velocity, acceleration)? Class time will be split between movement exercises, playing with examples and deconstructing code.

The course is cross-listed with the Tisch Dance MFA department. All assignments will be collaborations between ITP and Tisch Dance students. The class will culminate in a final showing.

## Pre-requisites
The course is intended both for anyone looking to deepen their practice in working with movement-based interaction regardless of previous experience with movement technique or programming.

As a result, there is no pre-requisite for dance and no pre-requisite for code.

## Evaluation
- 40% for showing up (on time!) and participating with curiosity and enthusiasm.
- 10% for each topic study.
- 20% for the final project.
- More than 2 unexcused absences qualifies you for a failure.
- 2 lateness of 15 minutes or more qualifies as 1 unexcused absence.

Please see ITP's statement on [Pass/Fail](http://help.itp.nyu.edu/academic-policies/pass-fail) which states that a "Pass" is equivalent to an "A" or a "B" while anything less would be considered a "Fail".

We will have weekly assignments that are relevant to material from the previous class. These assignments are required and you should be prepared to show/talk about them in class. It is expected that everyone in the class will create and maintain a blog for their assignments.

Attendance is mandatory. Please inform your teacher via email if you are going to miss a class. Two unexcused absences is cause for failing the class. (An unexcused lateness of 10 minutes or more is equivalent to 1/2 an absence.)

This class will be participatory, you are expected to participate in discussions and give feedback to other students both in class and participate with their projects. This (along with attendance) is 40% of your grade.

Class will culminate with final projects. You are expected to push your abilities to produce something that utilizes what you have learned in the class that is useful in some manner to yourself or the world. This will comprise 20% of your grade.

## Statement of Academic Integrity

Plagiarism is presenting someone else’s work as though it were your own. More specifically, plagiarism is to present as your own: A sequence of words quoted without quotation marks from another writer or a paraphrased passage from another writer’s work or facts, ideas or images composed by someone else.

## Statement of Principle

The core of the educational experience at the Tisch School of the Arts is the creation of original academic and artistic work by students for the critical review of faculty members.  It is therefore of the utmost importance that students at all times provide their instructors with an accurate sense of their current abilities and knowledge in order to receive appropriate constructive criticism and advice.  Any attempt to evade that essential, transparent transaction between instructor and student through plagiarism or cheating is educationally self-defeating and a grave violation of Tisch School of the Arts community standards.  For all the details on plagiarism, please refer to page 10 of the Tisch School of the Arts, Policies and Procedures Handbook, which can be found online at: http://students.tisch.nyu.edu/page/home.html

## Statement on Accessibility

Please feel free to make suggestions to your instructor about ways in which this class could become more accessible to you.  Academic accommodations are available for students with documented disabilities. Please contact the Moses Center for Students with Disabilities at 212 998-4980 for further information.

## Statement on Counseling and Wellness

Your health and safety are a priority at NYU. If you experience any health or mental health issues during this course, we encourage you to utilize the support services of the 24/7 NYU Wellness Exchange 212-443-9999. Also, all students who may require an academic accommodation due to a qualified disability, physical or mental, please register with the Moses Center 212-998-4980. Please let your instructor know if you need help connecting to these resources.

## Statement on use of Electronic Devices

Laptops will be an essential part of the course and may be used in class during workshops and for taking notes in lecture. Laptops must be closed during class discussions and student presentations.  Phone use in class is strictly prohibited unless directly related to a presentation of your own work or if you are asked to do so as part of the curriculum.

