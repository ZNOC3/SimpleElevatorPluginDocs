# New plugin functions

## Blueprint Pure functions:

- **Get Next Floor Data** - Returns true if the next floor exists. If this floor exists also returns the data of that floor.<br>
![GNFD](/img/UnrealEditor_pXKRPtZyEg.png)

- **Get Floor Data** - It works in the same way as the previous function, but you can specify any floor from which to retrieve data.<br>
![GFD](/img/UnrealEditor_laJ89NlpVC.png)

- **Does Floor Exist** - Returns true if the target floor exists.<br>
![DFE](/img/UnrealEditor_Ac83gshzbT.png)

- **Has Elevator Reached Target** - Returns true if the elevator is on desired elevator height.<br>
![HERT](/img/UnrealEditor_i0vil9NRA7.png)

- **Get Current Audio Config** - Returns audio configuration of current floor.<br>
![GCAC](/img/UnrealEditor_W4lCg3VfCe.png)

- **Convert Vector to Rotator** - Convert a vector to a rotator. Rotator is a vector value with clamping applied to keep its range between -360 and 360.<br>
![CVTR](/img/UnrealEditor_jToxFZRpyB.png)

- **Get External Door Mesh by Floor Number** - Get the External Door Mesh Component for the specified Floor Number and Door Side. <br>
![GEDMBFN](/img/UnrealEditor_17ywN6GS9E.png)

- **Get Closest Floor to Player** - This Function gets the closest floor to the player character pawn, if any is valid. <br>
![GCFTP](/img/UnrealEditor_viDsSp7BY3.png)

- **Get Actor Data to Save** - Returns structure with current save data.<br>
![GADTS](/img/UnrealEditor_PndS6AEpPE.png)

- **Get Curve Duration** - Returns lenght of selected curve asset.<br>
![GCD](/img/UnrealEditor_iqPi40HDN1.png)


****
## Normal functions:

- **Update Interaction Box** - Updates Interaction Box properties from variables. Should be called on construct script.<br>
![UIB](/img/UnrealEditor_75iV1cHgxA.png)

- **Load Custom Save** - Updated elevator data using save data. <br>
![LDS](/img/UnrealEditor_dATgKSnvEI.png)

- **Generate Collision Boxes** - Generates collision box on every floor from floor configuration structure. Should be called on construct script.<br>
![GCB](/img/UnrealEditor_6CTmpXKXyI.png)

- **Log Floor Queue** - Writes the current elevator floor queue to the output log. Works, only when debug mode, is enabled.<br>
![LFQ](/img/UnrealEditor_hKXL2lfNq1.png)

- **Toggle Elevator Widget** - Turns on or off elevator interaction UI.<br>
![TEW](/img/UnrealEditor_LTgkSKn0Yn.png)

- **Set Starting Floor** - Sets the elevator's starting floor to a new floor and updates the elevator's vertical position.<br>
![SSF](/img/UnrealEditor_8RPpeR80TL.png)

- **Move Elevator To Target** - Moves elevator to target floor. Main function to controll elevator movement.<br>
![METT](/img/UnrealEditor_QqasKkAe9r.png)

- **Call Elevator to Floor** - Requires entry box collision component input to work. If the selected box collision component is on the same floor as the elevator, it opens the elevator door. If it is on a different floor, it moves the elevator to that floor.<br>
![CETF](/img/UnrealEditor_NRDVxOlMej.png)

- **Open Doors** - Opens the elevator doors and then closes them after a delay.<br>
![OD](/img/UnrealEditor_HrqUuqDHIH.png)

- **Play Sound** - Play Sound plays the selected sound in the target component if the bool At Component is on, if the bool is false plays a 2D sound. <br>
![PS](/img/UnrealEditor_ghxdw28tBq.png)

- **Stop Playing Sound** - Fades out sound and stops its playback at selected component. <br>
![SPS](/img/UnrealEditor_JhVrCR5krE.png)

- **Set Loaded Data** - Function to set elevator data when not using  ***Use Custom Save Game Object***. Already implemented in save manager, it's recommended not to use it.<br>
![SLD](/img/UnrealEditor_p4f7amv2dT.png)

- **Generate Doors** - Generates external doors on every avaible floor. Should be called on construct script. Already implemented in c++.<br>
![GD](/img/UnrealEditor_4LVuTJcLZK.png)
