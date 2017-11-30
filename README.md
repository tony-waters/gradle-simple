# gradle-simple

OpenShift S2I enabled project.

Based off [https://jitpack.io/#jitpack/gradle-simple](https://jitpack.io/#jitpack/gradle-simple)

Demonstration of how you can use OpenShift Source-to-Image (https://github.com/openshift/source-to-image)
with a regular image, by supplying the assemble and run scripts in a projects .s2i/bin directory.

## usage

With S2I installed, run:

>s2i build . openjdk:8 gradle-simple:latest

to build the image.

