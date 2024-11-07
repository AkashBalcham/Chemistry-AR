# Chemistry AR
AR mobile application for our project. There are 7 chemical elements (atoms) and one reaction (molecule). Built for Android platform, but has iOS support. Requires Android 7.0 and later. To open this project you need Unity 2021.3.28f1 (LTS) or later.


## How can I add new atoms?
1. Generate a marker for the new element using the [ArUco markers generator](https://chev.me/arucogen/).
3. Import a card into the Unity project.
4. Add a card to the `ReferenceImageLibrary` file, set the element name and physical size of the card.
5. Make a prefab for a new element (you can copy an already created element and redesign it).
6. Add a prefab to the scene and add it to the `Object library`.
7. Double check the element name in the `ReferenceImageLibrary` and in the `Object Library`, because they must be the same.
8. If you want to have 2+ identical elements on the screen, just create a new one with a number (like I created Hydrogen).


## Important notes
2. Never use QR codes for AR image tracking. Instead of QR codes you can use AR markers. The marker generator I used in this project is [ArUco markers generator](https://chev.me/arucogen/).


## Build with
• Unity 2021.3.28f1 (LTS)<br>
• Google ARCore & Apple ARKit

