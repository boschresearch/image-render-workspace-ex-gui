### GUI Example 2

This example configures the GUI in more detail. See the documentation of `image-render-gui` for more detailed information.

1. The launch file has an element `mGui` that defines the grid layout for the global launch parameters.
2. The option to select between two different trial files is given, by adding the element `lTrialFileOptions` in the `mGlobalArgs` block of the launch file. 
3. Some dummy variables are defined to demonstrate the various control types: `sBlenderVersion`, `my_value`, `pw` and `objects`.
4. The trial files declare local and global variables and contain a `mGui` block to make these variables editable. In particular, the set of modifier configuration files with the id `mod` are made selectable by the user.

See the next example, to actually test changing parameters and generating modified renders.
