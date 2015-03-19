# Unity2DCheatsheet
A cheatsheet for Unity's 2D features.

## Physics 

### Rigidbodies
To make a GameObject under the control of the physics engine, add a _Rigidbody_ component.

With _Rigidbodies_ do not attempt to move them by Transform properties (rotation, scale, position). Instead apply forces.

### Colliders

```c#
BoxCollider2D
CircleCollider2D
PolygonCollider2D
```

### Floors, walls, and other motionless elements
Add a collider to an object, but don't add a Rigidbody component.


## Controlling the camera
For 2D, don’t mess with the Scene Gizmo. In Unity 5 the gizmo isn't even available when viewing in "2D" mode:

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
