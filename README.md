Processing Video
================

Repository of the video library for Processing. Forked by alexstamm

This library comprises classes for movie playback and video capture. It is based on the [gstreamer multimedia framework](http://gstreamer.freedesktop.org/), and uses the [gst1-java-core](https://github.com/gstreamer-java/gst1-java-core) bindings to interface gstreamer from Java.

Updates to this library include:

Updated GStreamer modules, gst1-java-core, and JNA
Updated LibraryLoader to incorporate new GStreamer .dlls
Utilizing native buffer
Improved camera capture functionality
Multicamera support, allows cameras of the same name to be used
Improved frame scrubbing
Info display for bundled vs system GStreamer installs
