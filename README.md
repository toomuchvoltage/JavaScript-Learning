# SINDyTestBed
A simple test bed for SINDy: https://www.youtube.com/watch?v=gSCa78TIldg

## Few quick observations:

* The algorithm even works with https://en.wikipedia.org/wiki/Ordinary_least_squares (as is used in the code) even though they mainly recommend https://en.wikipedia.org/wiki/Lasso_(statistics). 
Lasso will mainly get rid of small features which you can probably remove yourself below a threshold after OLS (I guess?.) Just the simplicity of it strikes me.
* The choice of library is important. I've found it to be sensitive to that.
* I'm not using it for dynamics systems yet... just imagine that sine wave swingy thing being something's velocity.

Nevertheless, it acted like a decent FFT on an Oscilloscope.