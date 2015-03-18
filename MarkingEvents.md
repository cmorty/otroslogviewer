# Introduction #

OtrosLogViewer supports marking (highlighting) log events with the predefinied color. Events can be marked automatically or manually.

### Automatic markers ###
_Automatic markers_ search all visible events and mark the matching ones. Also they mark incoming events in tailing mode. You can access them in two ways:
  * Context menu of events table (right click on the table or Context menu key)

> ![https://raw.githubusercontent.com/otros-systems/otroslogviewer/wiki/screen-automatic-markers-menu.png](https://raw.githubusercontent.com/otros-systems/otroslogviewer/wiki/screen-automatic-markers-menu.png)

  * Select automatic marker for incoming events in tailing mode
> ![https://raw.githubusercontent.com/otros-systems/otroslogviewer/wiki/screen-tailing.png](https://raw.githubusercontent.com/otros-systems/otroslogviewer/wiki/screen-tailing.png)

### Manual marking ###
You can mark events _manually_ in three ways:
  * Mark by space bar or mouse click
  * Mark next or previous search result
  * Mark all search results
### Creating an automatic marker ###
You can create your own automatic marker. There are three ways to do it:
  * Create "String marker" using ["Markers editor"](CreatingStringOrRegularExpressionMarkers.md).
  * Create "Regular expression marker" using ["Markers editor"](CreatingStringOrRegularExpressionMarkers.md)
  * Java based code.

