# Save System

- **Save Type** - determines save game type
    - Manual - game won't be automatically saved.
    - Automatic - game will be saved when opening doors.
    - Automatic with timer - game will be saved automatically every x seconds.

- **Use Custom Save Game Object** - enables integration into your already existing save game system - [See guide](guides/custom-save-game-object.md). 

- **Load Save at Begin Play** - When true save game will be loaded on begin play event, if false save game won't be loaded at all.

- **Save Actors** - select which actors you want to be saved.

# How to enable save system:

- Add BP_SEP_SaveManager to your level.

- Select which save type you want to use.

- Under Save Actors select all actors you want to be saved.
