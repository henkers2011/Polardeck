# Polardeck
I am building a cyberdeck that is an off-grid, portable ground station with an antenna that receives data from the Meteor M N2-3 and N2-4 weather satellites, that receives, decodes, and visualizes multi weather imagery . It will analyze it and estimate a (hopefully accurate) 24-48 hour forecast (Mainly if there are any rain/snow storms coming that direction.).

It is being designed with use by search and rescue and forest fighting teams mainly in isolated parts of northern Canada in mind, where they are completely off grid and have no way of knowing about any potentially dangerous approaching storm cells.  This is also why I have chosen the Meteor weather satellites, as they are polar orbiting rather than equator orbiting, meaning that there is more frequent and reliable pass overs relative to the equator orbiting satellites. 

I am planning on designing a custom pelican case styled shell, and will be running the programs on a raspberry pi 3b+, along with a pihat that I will be designing for this project. The case will also have a detachable V antenna that can be stored in the case but used outside of it, connected by a spool of coax cable, to keep the image clear by minimizing RF noise from the computer on board.  The pi will be usable via a mini keyboard and blackberry trackball with 2 mechanical keys acting as the mouse, and the display will be a non-touch DSI screen that will be in the top half of the case. 

The map will be multi layered, with a high zoom offline map and true colour visuals, thermal infra-red heat maps, and surface water/ice temperatures from the satellites. There will be a computer program that will analyze the last several images and predict what the general weather over the next 1-2 days will look like.

This is my first time doing this sort of thing, so I will be learniang along the way!

## Project journal

See [JOURNAL.md](JOURNAL.md) for dated progress notes and build decisions.
