# Interaction Widget

- **Interaction Widget Class** - Determines the class of the 3D Interaction widget. Must be a child of _SEP Master Interaction Widget_ class.

- Customizing widget letter
    - Open WB_Interaction and on the left side select [TEXT] "E" and in details panel on the right side in the text tab you can specify letter you want to use. <br>![ChangingLetter](/img/UnrealEditor_fcCeS1DHnk.png)
    - Open your elevator actor and find show elevator ui nodes, there you can specify the key you want to use to open elevator ui <br>![Key](/img/UnrealEditor_1Ea5wtUoFZ.png)

- Customizing widget appearance
    - Open WB_Interaction and on the left side select BG_IMG and in details panel set the brush image to your own, make sure to set the image size to 64x64
    >[!Note]
    >If you want to use larger image than the default one it may be required to increase the draw size of 3D widget in your elevator actor to avoid display isues, but it should work with the default size.<br> ![Draw Size](/img/UnrealEditor_nfHPAvIiJ3.png)

# Elevator UI Widget

- **Elevator Widget Class** - Determines the class of elevator UI. Must be a child of _SEP Master Elevator UI_ class.