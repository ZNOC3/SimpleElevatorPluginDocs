# Change log

## Version 2.0: Engine update
- Unreal Engine 5.3 Support

## Version 2.0: Major Improvements and New Features

- Mechanics
    - Now includes example sfx
    - Rewrote most of the functions to improve performance and stability.
    - Added the ability to create doors on every floor with custom meshes and offsets.
    - Completely rewritten how doors behave, now plugin features two door movement types:
        - Linear door type, which is the same as in previous versions.
            - Linear door now features control over movement speed and independent door movement - left door can have different open and close location than the right one.
        - Curve Asset door type features highest possible degree of customizability.
            - For more information on how to set up Curve Asset doors, see [Here](/guides/doors-setup.md)

- Save System
    - Added a save game system with multiple save types:
        >[!Tip]
        >- Manual - game won't be automatically saved.
        >- Automatic - game will be saved when opening doors.
        >- Automatic with timer - game will be saved automatically every x seconds.
    - Save game supports integration into already existing save game system: [More info here]()
    - Save Manager visualises selected save actors using trace ![Vis Dem](/img/UnrealEditor_Wr3JTQ0kRV.jpg)

- Performance
    - ~~Calculating next floor is now multi-threaded, using async function.~~ (Removed from final release - introduces weird bugs, maybe I'm gonna add it back in future)
    - Refactored almost all functions - now the c++ code is even more readable.
    - Small performance upgrades.

- Documentation
    - Brand new documentation.
    - New blueprint exposed functions and events, more info here: [New functions](functions.md), [New events](events.md).

- Bugfix
    - Fixed collision boxes getting duplicated in editor after undoing edit.
    - Other minor fixes.

## Version 1.1: Small update
- Added new door opening direction (Z Axis)

## Version 1.0: Initial Release
- Initial Release
