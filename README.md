## Addon for World of Warcraft:Midnight

Anchors the HUD Tooltip the mouse

### USAGE
Download and place folder in interface/addons folder
Enable in addon settings in game
Enjoy!

### SETTINGS
By default, HUD Tooltip is set to anchor to the right of the mouse with a slight offset to be more centered on the mouse itself

self:SetOwner(parent, { ANCHOR POSITION }, { X OFFSET }, { Y OFFSET })
Change { ANCHOR POSITION }:
- ANCHOR_CURSOR - Anchors the bottom center of the tooltip the the mouse
- ANCHOR_CURSOR_LEFT - Anchors the bottom right corner of the tooltip to the mouse
- ANCHOR_CURSOR_RIGHT - Anchors the bottom left corner of the tooltip to the mouse

Change { X OFFSET }:
- Accepts positive and negative numbers
- Positive moves the tooltip to the right of the anchor position
- Negative moves the tooltip to the left of the anchor position

Change { Y OFFSET }:
- Accepts positive and negative numbers
- Positive moves the tooltip up from the anchor position
- Negative moves the tooltip down from the anchor position
