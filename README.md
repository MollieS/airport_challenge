Airport Challenge
=================

Task
-----

We have a request from a client to write the software to control the flow of planes at an airport. The planes can land and take off provided that the weather is sunny. Occasionally it may be stormy, in which case no planes can land or take off.  Here are the user stories that we worked out in collaboration with the client.

```
As a pilot
So that I can arrive at my specified destination
I would like to land my plane at the appropriate airport

As a pilot
So that I can set off for my specified destination
I would like to be able to take off from the appropriate airport

As an air traffic controller
So that I can avoid collisions
I want to be able to prevent airplanes landing when the airport if full

As an air traffic controller
So that I can avoid accidents
I want to be able to prevent airplanes landing when the weather is stormy
```

Your task is to test drive the creation a set of classes/modules to satisfy all the above user stories. You will need to use random number generator to set the weather (it is normally sunny but on rare occasions it may be stormy). In your tests, you'll need to use a stub to override random weather to ensure consistent test behaviour. Finally, every plane must have a status indicating whether it's flying or landed.

Completed so far
-----

1.  All planes can land and take off
2.  Planes cannot land when airport is full
3.  Planes cannot land or take off when the weather is stormy
4.  Current test coverage is at 98%
5.  All user stories are sastified and all tests are passing
6.  A new weather status is created whenever a plane tries to land or take off.

To do
-----

1. Refactor application code to make it cleaner
2. Refactor testing code to remove dependency
3. Evaluate and test for edge cases
4. Improve test coverage so that it is at 100%
