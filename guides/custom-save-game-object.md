# Integrating SEP Save System into your own one

- Add into already existing save game object new variables with type **Save Data** and change its variable type to array 

![Var](/img/UnrealEditor_ljDjsmLsIF.png)

- Open BP_SEP_Master_Actor (or its child if you are using one) and add **Event Save Elevator Data Custom Object**. From there, create a new save game object with the selected class and add to the save data array the current elevator save data. After that, save the game to your selected slot.

![Save Game](/img/UnrealEditor_EKTWDiY0Yy.png)

- To load save game add **Event Load Elevator Data Custom Object**. From there, load game from your slot, from it cast to your save game object, get from it save data array and get an actor index from. From save data call Load Custom Save function on SEP Master Actor. The plugin will load all necessary settings automaticly.

![Load Game](/img/UnrealEditor_S37EPANXpW.png)