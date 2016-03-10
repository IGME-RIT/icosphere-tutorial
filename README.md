# Icosphere Tutorial

This program serves to demonstrate how to generate a 3D icosahedron.

# About

Contains code for generating a 3D icosahedron, and then refining the edges down to create an icosphere. This is a manner of generating a spherical-like object. By default, the number of revisions on the icosphere is 5, which can create a pretty mesmerizing effect (because I also have it randomizing the colors of each vertex and spinning around constantly). You can also choose to lower or increase the number of revisions.

WARNING: Performance will drop painfully once you reach the 7-9 revisions range. I haven't been able to push it past 9 revisions. Also note that this is incredibly inefficient in terms of the way it generates the points, so there may be a long startup time for a high number of revisions. Feel free to optimize it and send it back to me and I'll upload the better version!

# Setup

In order to setup, run the following in a shell, then open the project in your preferred editor. Windows setup has been configured for use with Visual Studio.

Windows:
```
cd path/to/folder
setup.cmd
```
Linux:
```
cd path/to/folder
./setup
```
