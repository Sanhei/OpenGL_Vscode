# Introduction
First of all, here all these documents are downloaded from glad and glfw website. The purpose of this repository is to help the nooby like me.

Never give up, when you pass the beginning, the next is easy. There is no beginners tutorial, once you are trained, how could they write down something for beginners?

The system is windows 11. For the people like me who get used to linux and clearly english is not native, could use some help. 

# Preparation
OpenGL is depend on the C environment, you need compiler and library. 
The official tutorial site is quite clear, follow the website to install and test it.
https://code.visualstudio.com/docs/languages/cpp
Needed to be mentioned here, step 5 means enter nothing, just pressing enter.

Download glad
https://glad.dav1d.de/

Download glfw
https://www.glfw.org/download

# Beginning
This tutorial video is really helpful.
https://www.youtube.com/watch?v=Y4F0tI7WlDs
But one thing I am truly frustrated about is that I cannot create .vscode under the main directory, always in include or src file.
So every time I create a .vscode before dragging in other files.

So the first step, create .vscode and create tasks.json
Drag in --- include  src lib files which is introduced in the video.

The next one is tricky, you need to compile an empty C program in a new workspace and copy the tasks.json into the .vscode you ceated in the first step.
And add the args manually as the video showed.





