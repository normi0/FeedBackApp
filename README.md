# FeedBackApp
i am creating this app to learn about states and how should i go from one screen to another screen so at the end make a multi screen app that the own purpous is a feed back of a certain apps that i will create in the future

Learning About States and Page Navigation in Flutter
What are States in Flutter?
In Flutter, "states" refer to the current data and configuration of a widget at any given moment. Widgets can have different states, and the state can change over time. Managing and updating the state is a fundamental aspect of building interactive and dynamic user interfaces.

Stateless Widgets:
Stateless widgets are immutable and do not have any internal state. Once created, their properties cannot change. They represent parts of the UI that don't change over time.

Stateful Widgets:
Stateful widgets maintain internal state, which can change during the widget's lifetime. When the state changes, the widget will be rebuilt, and the updated state will be reflected in the UI.
How to Navigate Between Pages in Flutter?
To navigate from one page to another in Flutter, you can use the Navigator class. The Navigator manages a stack of routes (pages) and provides methods to push and pop routes to navigate between screens.

For example, let's say you have a button on the first page, and you want to navigate to a second page when the button is pressed:
