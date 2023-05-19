# New plugin events

- **Event Load Elevator Data Custom Object** - Is called when loading game, requires ***Use Custom Save Game Object*** turned on to work. Actor index specifies array index - [See guide](/guides/custom-save-game-object.md)<br>
![LEDCO](/img/UnrealEditor_2Yl27n6nyy.png)

- **Event Save Elevator Data Custom Object** - Is called when saving game, requires ***Use Custom Save Game Object*** turned on to work - [See guide](/guides/custom-save-game-object.md)<br>
![SEDCO](/img/UnrealEditor_vBBPLaP7Sp.png)

>[!Warning]
>Using the following events in blueprints overrides its c++ implementation and part of elevator functionality may not work as intended.

- **Event Entry Component Begin Overlap** - Called when player enters entry collision component.
![ECBO](/img/UnrealEditor_NUpixiVA3h.png)

- **Interaction Collision Box Begin Overlap** - Called when player enters interaction box collision component.<br>
![ICBBO](/img/UnrealEditor_ZDI1CkKPXX.png)

- **Interaction Collision Box End Overlap** - Called when player leaves interaction box collision component.<br>
![ICBEO](/img/UnrealEditor_CYbY6ahbIE.png)



