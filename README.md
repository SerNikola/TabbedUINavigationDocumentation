# Tabbed UI Navigation

## Welcome
Thank you for using my asset. Please take a look at the MainMenuDemo scene to get to know the asset.

## Performance
Please use **nested canvases**. You will notice in the MainMenuDemo that each page is its own canvas. This will * *highly increase performance* *.

[Nested Canvases Tutorial](https://learn.unity.com/tutorial/nested-canvas-optimization-2018-4)

## Documentation
[Link](https://sernikola.github.io/TabbedUINavigationDocumentation/]

## Usage
To simply use a **scrollable UI**, you can just add the FAScrollSnapBehaviour script on your scroll view, and play with the settings to achieve your desired speed or size.

## Tab Bar (Bottom Toolbar)
To include the **bottom toolbar** drag and drop the Bottom Toolbar prefab into your canvas. The only required thing is to drag the FAScrollSnapBehaviour object into the Scroll Snap Rect property of the FATabBar script.

The tab bar can have any number of child buttons, but for obvious reason that number should be the same of the number of pages in the scroll view.

## Nested Scrolls
This asset includes functionality for nested scroll views.

When you are setting up your nested scrolls, replace unity's built-in ScrollRect component with a FaScroll Rect and remember to drag your inner scrolls into the FAScrollSnapBehaviour properties.

## Flexible Design
The FAScrollSnapBehaviour script is super flexible and can be used in other systems like Level Selection for example.

Please check out the Demo Scenes to see the script in action.
