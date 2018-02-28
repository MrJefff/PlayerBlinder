A new way of punishing players! This plugin give a range of different customisation to blinding players, including fill colours, images and text!

## Notes
- **The length argument is in seconds for the blind command**
- **The protection feature works when a player shoots you, they will be blinded for the amount of time you entered when you started the protection.**

## Permissions
- `playerblinder.admin` -- Allows admin to use commands

## Chat Commands
- **/blind \<playername\> \<length\> "text"** (also works as /blind <playername/id>) -- Blind player.
- **/unblind <playername/id>** -- Unblind player.
- **/blindprotect \<length\>** -- toggles on your admin protection.

## Console Commands
- **blind \<playername/id\> \<length\> "text"** (also works as blind <playername>) -- Blind player.
- **unblind <playername/id>** -- Unblind player.

## Configuration File
```json
{
  "Blind UI": {
    "Colour": "0 0 0 1"
  },
  "Image UI": {
    "AnchorMAX": "1 1",
    "AnchorMIN": "0 0",
    "URL": ""
  },
  "Settings": {
    "ImageOverlay Enabled": false,
    "Use Text": true
  },
  "Text UI": {
    "Default Text": "You have been blinded by an admin!",
    "Size": 20
  }
}
```

## Image
![playerblinder](https://oxidemod.org/attachments/57120bda05650167b43f243bd8e201b1-png.33237/ "playerblinder example")
