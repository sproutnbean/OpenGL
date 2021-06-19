# 2.OpenGL

----------------------------------

2.1 Core-profile vs immediate mode:
	- immediate mode (aka. fixed function mode): hides away OpenGL functionalities / how calculations are done
	inside library.
	- core profile mode: an OpenGL specification that remove old functionalities, start from v3.3.
	
2.2 Extensions:
	- contains new techniques/optimisations for rendering, implemented in drivers.
	
2.3 State machine:
	- OpenGL is a large state machine that contrains a collection of variables that define how it operates.
	An OpenGL state is a referred to as a context. The state is changed through context variables/options/buffers.
	- state-changing functions and state-using functions perform operations based on current state.
	
2.4 Objects:
	- OpenGL libraries are written in C and can be derived in other languages. To accomodate other high-level 
	languages, OpenGL was developed with several abstractions in mind. One of those abstractions are **objects**.
	- An object is a collection of options that represents a subset of OpenGL's state. THe benefit is to define multiple 
	objects with different options/settings, and when a state is operated on, we can bind the object with the preferred 
	setting.
	
	
	

