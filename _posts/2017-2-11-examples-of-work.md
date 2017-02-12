---
layout: post
title: Examples of Work
featured: true
author: jacob
image: '/images/posts/workspace.png'
---

#### <center>Hello! The following are a few examples of my work:</center>
<br>

### **iOS**

* * *

##### Snapchat Filters Implementation
[Github link](https://github.com/Lorsen/ImageLab/tree/Lab_4)

[Video demonstration](https://www.youtube.com/watch?v=4eWPFaA1nwE)

This is an implementation of the superimposed-graphics-over-a-tracked-face
effect from mobile apps such as Snapchat. It's not fancy, however.

- - -

##### ML Boxing App "BoxFit"
[Github link](https://github.com/Lorsen/BoxFit/tree/master/BoxFit)

[Link to motion data capture/processing](https://github.com/jpadkins/BoxFitSimpleTrainingApp/blob/master/BoxFitTrainingApp/MotionHandler.swift)

Sadly, I do not have a video demonstration of this. BoxFit allowed its users
to perfect four boxing moves: Jab, Uppercut, Block and Hook, but comparing their
arm movements while wearing their smartphone on a sports strap on their arm to
a model we had trained. The server side was implemented with Python Tornado as
the server and scikit-learn to handle the training.

- - -

Other iOS apps I've worked on include 

1. an app that finds the user's bpm from their finger when placed over the camera
2. an app that uses an inaudible tone to determine distance
3. a feature-rich social platform aimed at students

<br>

### **C**

* * *

##### Research on Kernel Space I/O Performance
[Github link](https://github.com/jpadkins/KernelSpaceIO)

For research in my Operating Systems class, I wanted to find out just how much slower
(or faster?) I/O operations would be from the kernelspace, so I wrote the same I/O program
as closely as I could in both Modern C and a Kernel Module and benchmarked them.

<br>

### **C++**

* * *

##### TSDC Parser
[Github link](https://github.com/jpadkins/sdc_parser)

This small program was made to run continuously on the machines
which operated industrial printers. I included it on here because

1. It is coupled tightly with sqlite3's C-api, but I made use of modern
C++11 techniques to improve code visability.
2. It was written to be maintainable by another individual who would
come onboard long after I had left and whose skill level I did not know,
so I described very clearly what action every line performed. (This was
before I was familiar with in-code-documentation generators)

- - -

##### Graphical Terminal Emulator
[Github link to render logic file](https://github.com/jpadkins/GlyphRendererEngine/blob/master/old/src_old4/GLYF/Renderer.hpp)

This was an old attempt at creating a graphical terminal emulator. I wanted
to make a terminal emulator with OpenGL that would support flashy text effects,
and when I put the project down I had succeeded in

1. rendering text
2. supporting a rubust animation framework
3. supporting multiple ttf fonts by abstracting away spacing/kerning problems

The file that is linked above contains most of the rendering code. I included
this because project because there was a lot of precise computations that needed
to be performed to render the text correctly and I heavily profiled it for performance.

<br>

### **Python**

* * *

##### Encrypted Cloud Storage Wrapper

This is a closed-source wrapper around popular cloud-based storage platforms
(Google Drive, OneDrive, DropBox) which performed client-side encryption and
decrytion automatically, so only your encrypted files were stored on the cloud.

* * *

##### SafeSpots
[Github link](https://github.com/jpadkins/SafeSpotBackup/tree/master/safespots)

Safespots was a web and android application that allowed users to find the safest walking
routes. This was done in a fashion similar to Google Maps, however we pulled data from
crime reports APIs to help us determine the fastest/safest route. The API was written in
JS, with interop into a python driver to run the Cassandra cluster it was deployed on.

* * *

##### My Old Blog
[Github link](https://github.com/jpadkins/jpa.io/tree/master/blog)

My old blog, written for Django 1.9 and deployed on Apache with WSGI.

<br>

### **Elixir**

* * *

##### Pragmatism Online
[Github link](https://github.com/jpadkins/ElixirClassFinal)

[File with most of the room/socket logic](https://github.com/jpadkins/ElixirClassFinal/blob/master/mud_server/web/channels/room_channel.ex)

[Directory with most of the game logic](https://github.com/jpadkins/ElixirClassFinal/tree/master/mud_server/lib/mud_server)

[File implemeting the terminal client](https://github.com/jpadkins/ElixirClassFinal/blob/master/mud_client/lib/mud_client/socket_client.ex)

[File containing web interface implementation](https://github.com/jpadkins/ElixirClassFinal/blob/master/mud_server/web/static/js/chat.js)

A simple MUD with both a web and terminal client. Implemented as the
final project for the Elixir/Phoenix course I took at SMU in the Fall
of 2016, taught by David Thomas the Pragmatic Programmer.

<br>

### **Ruby**

* * *

I have experience with three large Rails applications, one of which was just an API.
However, all of them are closed-source, so instead I will post the Gemfile from the API
of my recent App, to show which libraries I am most familiar with.

[Gemfile](https://github.com/jpadkins/jpadkins.github.io/blob/master/_misc/Gemfile)

<br>


Other languages I am proficient in are Rust (which I've contributed to), Lua, and PHP.
