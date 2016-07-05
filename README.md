# Lucy

Lightweight UI & Input framework for projects created in Unreal Engine 4. 
Based on UMG, blueprint only. It's free to use, even commercially.

### What's inside?
* Input Manager provides basic functionalities: setting various inputs for single action, activating interactions, detecting input device and automatically updating displayed icon and key of interaction.
* UI Manager provides panel management: creating and switching panels, opening panels in hierarchy, handling input, basic navigation, activating chosen widget in panel, receiving inputs frm active widget. So you don't have to script basic widget actions in your panels. Focus on designing it and scripting advanced/custom functions. 
* Typical UI composites are UMG widgets provided with script which handles basic logic and input for you.
* Samples of Main/Options menus simplifies creating your own menus, i.e. Video Menu allows you to set common graphics options. Just customize it to your needs. Or just download it, don't change a thing and enjoy basic menus working in your cooked build. It's useful for playtesting prototypes.
* You don't have to reinvent the wheel when you're starting work on UI. I already did it.

### Take a look!
This is entire script for Pause Menu, as simple as it always should be.

![Alt](http://i.imgur.com/Y0VAygC.png "Pause Menu")

Entire UI could be constructed by using "composites", simple UI elements with script handling input, localization and common operations.

![ALT](https://i.imgur.com/p6jc5MH.png "Label + Slider")

You don't need to produce spaghetti blueprint for every Text or Slider element. Prepare it quickly by setting params.

![ALT](https://i.imgur.com/O1xuOXU.png "Params")

### Dependencies
* Free Blueprint plug-in [LE Extended Standard Library](https://www.unrealengine.com/marketplace/low-entry-extended-standard-library)

### Third-party assets used in sample project
* Controller icons created by [Xelu](http://opengameart.org/content/free-keyboard-and-controllers-prompts-pack).
* Miscellaneous icons from  [To [icon]](http://www.toicon.com/about) project.

