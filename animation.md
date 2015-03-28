## Animation set up

### Method One
Create an empty game object.

Select a Sprite Animation (```Shift + click``` to select all the frames) from your project folder and drag it to your game object. 

Name your animation.

This will automatically create the following:
- A Sprite Renderer
- An Animator 
- An Animation Controller (inside of the Animator)
- An Animation


### Method Two
To your character game object, add an Animator Component.

Then ```Create > Animator Controller```.

Drag the new Animator Controller to your "Controller" box in the "Animator Component".

View your Animation window. ```Window > Animation```.

![Setting up an Animator and an Animator Controller](images/animator-animator-controller.png)

Make sure **you have selected** the character you want to set up animations for, and then ```Create > New Clip```.

![Creating a new clip](images/create-new-clip.png)

Name the new animation.

Then drag your animation to the timeline.

Create another animation with the same process.