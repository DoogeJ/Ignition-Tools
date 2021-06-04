# IGNITION TOOLS

## What is this?

This repo contains a program @Kazade developed to rip and convert PIC-images from the abandonware game Ignition.

## pic2tga

Ignition stores many images in a custom format with a .PIC extension, this little app converts them to TGA format.

### Build

I did some nasty hacks to get this working again after 11 years. You can build the app by running the following command:

g++ pic2tga.cpp *.c -lglfw -lGLU -lGL -o pic2tga
