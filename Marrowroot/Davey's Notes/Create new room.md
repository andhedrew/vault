1 Create new room

2 Edit room collider to be as tall or wide as i want room to be

3 right click on room and make empty game object

4  Add rigidbody 2d to game object

5 name game object CameraBound

Set layer to no colissions

6 set ridged body type to static

7 add a composite colluider 2d

8 set that to be a trigger - "Is Trigger"

9  add box collider 2d

10 check "used by composite" on box collider 2d

11 Click edit box collider, set the bounds to encompass whole room.

12 go into room camera

13 click dropdown "body" in cinemascene vertual camera, set to "framing composer"

14. Enable "cinamashine confiner 2D"
15. Drag CameraBound into "bounding shape 2d"
16. That's it!

