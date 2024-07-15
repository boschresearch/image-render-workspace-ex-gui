### GUI Example 3

This example lets you select the object rendered and the camera used, next to other settings.

The launch and trial configs both have `mGui` blocks to structure the GUI controls. The launch config is basically the same as in example `ex2`. However, this example als adds structure to the trial arguments and extends them. 

You can select the Blender base file to use, the object to import, and the cameras and modifiers to iterate over.
The trial layout is defined with with this `mGridLayout` block in `mGui`:

```json
"mGridLayout": {
    "trial": {
        "iColumnCount": 2,
        "lGroups": [
            {
                "sTitle": "Scenario",
                "lRows": [
                    ["sBlenderFilename"], 
                ]
            },
            {
                "sTitle": "Content",
                "lRows": [
                    ["sObject", "cam"],
                ]
            },
            {
                "sTitle": "Modify",
                "lRows": [
                    ["mod"],
                ]
            },
        ]
    },
}
```

