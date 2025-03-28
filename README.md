# Comp-3004-Final-Project

### Notes (Simon):

The PIN screen and main screen of the GUI are now complete (the graph functionality is MISSING/pending as I'm still evaluating the optimal QT graph solution - suggestions welcome!).

All QT elements follow a consistent naming convention: the logical function in snake_case immediately followed by the component type. For example, an Open PushButton is labeled "open_PushButton".

For navigation, the GUI implements a stacked Widget system to manage multiple pages. To change pages, left-click the center box (the stacked Widget) and select "Next Page". Alternatively, use the arrow in the top right corner for navigation.

The GUI architecture employs a component-based approach, with reusable elements such as the navbar and footer that appear consistently across all pages.