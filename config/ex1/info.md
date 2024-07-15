### GUI Example 1

This example shows the default GUI that is created, if there are no explicit GUI definitions.

The Catharsys pre-defined launch arguments that are shown by default are:

```json
    "iFrameFirst": 0,
    "iFrameLast": 0,
    "iFrameStep": 1,
    "iRenderQuality": 4,
    // "sTopFolder": "test",
    "bDoProcess": true,
    "bDoOverwrite": true,
    "bDoStoreProcessData": false,
```

In this example there are some user defined launch arguments:

```json
"iConfigStartX": 1,
"iConfigCountX": 2,

"iConfigStartY": 1,
"iConfigCountY": 2,
```

As there names follow the standard Catharsys naming convention, they are also automatically displayed.

There are also some action specific arguments, that are shown in the "Launch: Action" section:

```json
"iConfigGroups": 1,
"iFrameGroups": 1,
```

The depth action also defines the argument `iMaxLocalWorkers`.
