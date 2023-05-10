# Door configuration

Simple Elevator Plugin offers two types of doors - linear, which moves only in one direction and doesn't support (yet) rotation

## Door type: Linear

***Door Movement Direction*** - Toggle which determines the direction doors will move in <br><br> ![DMD](/img/UnrealEditor_U9yBlOqEbM.png)

***Door Movement Speed*** - Determines the pace at which doors will move during their movement.

***Left Door Mirrors Movement*** - When set to false, the left door mirrors the movement of the right door, including opening and closing positions. When set to true, each door has independent opening and closing positions.

***Opened Door Location*** - The relative position of the right door when it finishes opening

***Closed Door Location*** - The relative position of the right door when it finishes closing

***Left Door Opened Location*** - Relative left door location to stop movement of the left door opening

***Right Door Opened Location*** - Relative right door location to stop movement of the right door opening

***Left Door Closed Location*** - Relative left door location to stop movement of the left door closing

***Right Door Closed Location*** - Relative right door location to stop movement of the right door closing

## Door type: Curve Asset

***Both Doors Use the Same Curve*** - The door movement is controlled by the right door while the left door mirrors it. However, it is advised to turn off this feature for improved movement control.

***Use Rotation Curve*** - Enables door rotation while opening and closing door

***Closing Door Uses the Same Curve*** - If true closing door animation will use the same curve as the one for opening. 

>[!Note]
> When using ***Closing Door Uses the Same Curve*** make sure to also enable ***Closing Curve Plays from End***

***Closing Curve Plays from End*** - When true closing curve will play backwards if false for its beginning     

### Curve assets

>[!Note]
> When working with Curve Assets, ensure that all required curve assets are set up. If even one curve asset is missing, the animation will not start.

>[!Note]
> When using a rotation curve, the X, Y, and Z values inside the curve asset are clamped to 360 degrees. It is not recommended to use higher values than that.
