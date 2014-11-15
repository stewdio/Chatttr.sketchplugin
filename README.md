Chatttr.sketchplugin
====================

A little experiment with GET requests and programmatically drawing Paths in [Sketch](http://bohemiancoding.com/sketch/). This plugin fetches the 5 most recent chat / drawing entries from a [“Chatttr.sketchplugin”](http://chatttr.com/chatttr.sketchplugin/) room on the public chat service, [Chatttr](http://chatttr.com/). (Because of the anonymous, unmoderated nature of Chatttr some entries may be NSFW. Read [Chatttr’s About page](http://chatttr.com/about.html).) Chatttr uses the [Paper.js](http://paperjs.org/) framework to handle vector drawing so this plugin is in some respects translating Paper.js drawing Paths to Sketch ones.

If you run the plugin and don’t see any results it’s likely that no one’s used our chatroom recently, in which case you should go draw something: [http://chatttr.com/chatttr.sketchplugin](http://chatttr.com/chatttr.sketchplugin/) (All Chatttr drawings and messages expire within 24 hours.) Keep it clean please!
  
Sketch plugins are written in CocoaScript which is basically JavaScript with access to Cocoa frameworks and a splash of that sassy Objective C bracket syntax. 

