# Topics in Software Engineering
### Project Proposal by Abrar Habib

## Name
Textura

## Description
Here’s a slightly expanded and refined version of your description:  

---  

## Description  
A lot of content creators nowadays follow a familiar layout: a simple webcam recording their face alongside a screen capture of their desktop. While this format has proven effective, there's plenty of room for creativity. **Textura** is a real-time ASCII video encoder designed to add a unique, retro-inspired twist to video content.  

With **Textura**, users can feed their webcam input directly into the tool, which then transforms and encodes the video into an ASCII-rendered version in real time. Whether you're looking to create stylized visuals, experiment with terminal-based aesthetics, or simply have fun with text-based video, **Textura** offers a fresh take on digital expression.  

By converting raw video into a dynamic, text-based format, **Textura** blends modern technology with the charm of ASCII art, opening up new possibilities for creative content and live streaming.

## Tech Stack
The tech stack for this project is actually quite simple. I originally planned on doing this in one language: Rust.
I chose Rust because it is something I am learning at the moment. Plus, it has a lot of libraries that I can utilize 
to build the project. I have already found libraries for accessing the camera and getting frames from it. 

I am assuming there is a need for performance here, as we are doing video processing, so languages like Python and JavaScript were out of the question.
I also planned on doing it in C/C++, but they are just *too* low level. Rust seems to blend best of both worlds with lot's of performance for some pretty 
easy to understand code.

Alternatively, if Rust ends up being too much of a hurdle, Python can be used to create a mockup to show the capabilities of this tool.

This entire project can be made in just one language and implemented as a command line interface. The way it is to be used in my eyes is:
provide a video stream (can be a prerecorded video or live feed) and I will process it for you and spit out the ascii frames. 

## End Users
I am mainly targetting those who make content on the internet, but it is open for anyone to use really. While it is meant for those who stream and such, it can still be used by pretty much anyone. With playful functionalities, it can used to convert images to ascii, make filters for image processing tools, etc. 


## Inspiration:
https://www.youtube.com/watch?v=55iwMYv8tGI
