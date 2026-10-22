# Slalom 259

A waterski slalom game that follows the IWWF course: 259 m gate to gate, six buoys
41 m apart at 11.50 m off the centreline, entry and exit gates 2.50 m wide, line
18.25 m to 9.75 m, boat 46 to 58 km/h.

Single self-contained HTML file, no build step, no network. Open `index.html`, or
play it at https://permaevidence.github.io/slalom259/

Start: wide on the port side behind the boat, pull out over the pre-gates, then
cross the entry gate from left to right and take buoy 1 on your right. Tap the
left or right half of the screen to set the edge; "Autopilot demo" skis itself.

Physics notes: 240 Hz fixed step, force-based edge (the water pushes the skier,
capped by grip), a rope that only pulls and sags when it is slack, falls only on
washout or a slack line that snaps taut while the body is out of position.

Derived from the prototype at https://the-waterski-game.lovable.app, rebuilt for
regulation dimensions, buoy judging and a force-based skier model.
