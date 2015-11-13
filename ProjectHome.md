Metatrace is a **C++ compile time ray tracer** (as of the initial release, it is a whitted style one).


It is mostly inane stuff. except, maybe, that it's a nice gadget to test compiler performance and conformance, especially but not exclusively in the Template and Metaprogramming corner of C++.


It requires basic C++0x support; with g++, make sure to have at least 4.4 installed.


---



### Features (graphics viewpoint): ###
  * linear object list
  * recursive ray tracing (whitted style)
  * mirror reflections
  * spheres, axis aligned planes
  * quite easily extensible (considering the circumstances)
  * rgb colors
  * scalar type is fixed point
  * not fast


### Features (c++ viewpoint): ###
  * uses variadic templates in some contexts (e.g. scene, some math-operations)
  * fairly heavy compile time number crunching (brings back the "slow" in "ray tracing")
  * strongly typed enums, to avoid ugly enum hacks like "FORCE\_DWORD=0xEFFFFFFF" and the like

### Features (bash viewpoint): ###

  * contains a bash script to compile on multiple cores

... more to come.


### Example ###

![http://metatrace.googlecode.com/files/example-0.png](http://metatrace.googlecode.com/files/example-0.png)
