# Unity2DCheatsheet
A cheatsheet for Unity's 2D features.

## Physics 
To make a GameObject under the control of the physics engine, add a rigid body component.



## Controlling the camera
For 2D, don’t mess with the Scene Gizmo.

![Scene Gizmo](images/scene-gizmo.png)

## GameObject Events

###Update()
Called once per frame.

###FixedUpdate
Called multiple times per frame.
Should be used when applying forces or other physics related functions.

## Useful Math Functions
Mathf.Max

Mathf.Min

Mathf.Clamp

Mathf.PingPong

##  Input
