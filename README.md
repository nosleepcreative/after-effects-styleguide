# after-effects-styleguide
This style guide provides standardized naming conventions for your tools (FFX presets, expressions, on scripts to ensure consistency, clarity, and easy identification of their functions.

## General Guidelines
1. Descriptive Names: Use descriptive names that clearly indicate the function of the script.
2. Title Case: Use Title Case for multi-worded names
3. 

## Structure
Each name should have the following structure:
```Verb + Object + OptionalDetails.ext````

- Verb: Describes the action the script performs (e.g., Add, Update, Remove, Generate).
- Object: The primary object the script affects (e.g., Layer, Keyframes, Comps).
- Optional Details: Additional details if needed for clarity
### Examples
```
Add Comp Padding.ffx
Add Layer Padding.ffx
Add Placeholder - FTG A.ffx
Add Placeholder - FTG B.ffx
Ignore Parent Scale.ffx
Inherit Parent Opacity.ffx
Drift Position.ffx
Drift Rotation.ffx
Drift Scale.ffx```


# Taxonomy
### Creation:
- **Add**: Introduces or places a new element, object, or attribute into the composition or project.
- **Create**: Constructs or generates a new element, layer, or object from scratch within the design or animation.

### Adjustment:
- **Modify**: Makes alternations to an existing element/property
- **Toggle**: Switches a property or state between two predefined options such as turning visibility on or off
- **Cycle**: Switches between multiple states, values, or elements
- Adjust
- Alter
- Change

### Utility and Setup:
- **Set**: Assigns a specific value to a property, such as setting the position, color, or timing of an element.
- **Auto**: Automatically applies pre-determined settings or effects based on context or predefined rules.
- **Make**: Creates or generates an element, object, or preset based on a specific function or template.
- **Compare**: Evaluates two or more elements or values to determine their differences or similarities.
- **Guide**: Provides a visual aid or alignment tool to help position elements accurately within the composition.
- **Grid**: Generates or displays a grid layout for aligning or organizing elements spatially within the design.
- **Distribute**: Evenly spaces multiple elements within a composition based on a specific parameter, such as position or alignment.
- **Lock**: Fixes an element or property so that it cannot be altered or moved unintentionally.
- **Fit**: Adjusts an element to match a specific size or space, often scaling it to fit within a bounding box or container.

### Text-Based
These identifier involve reading, labeling, highlighting, annotating, or retrieving specific pieces of information within a composition.

- **Label**:  Identify or name something eg. composition name
- **Display**: Show mulitiple or detailed attributes, but not permanently written or committed, such as a temporary overlay or an on-screen reference eg. Composition settings (name, size, fps)
- **Read**: Retrieves data/value from a source/property
- **Write**: When the action involves creating and placing text, graphics, or values into a composition, such as adding a title or inserting text into a layer. eg. Write ReadMe

Alternative:
- **Fetch**: Similar to "Read," but generally implies pulling data from an external source or database.
- **Annotate**: Adds notes, labels, or additional context to a specific part of a graphic or composition.
- **Highlight**: Visually emphasizes or draws attention to a particular element within a composition.
- **Comment**: Adds additional textual information or notes, often as a form of annotation or feedback.
- **Mark**: Identifies or distinguishes a particular element with a symbol or visual cue.
- **Show**: Reveals a value, property, or result, often to give the user or viewer insight into a certain aspect of the composition.
- **Retrieve**: Accesses and brings back data from a source, such as an attribute or external input, to be used in a project.

### Measurement and Calculation:
- **Get**: Retrieves a specific value or property from an element, such as position or scale, for use in further operations.
- **Count**: Tallies or enumerates the number of objects, layers, or elements within a composition.
- **Measure**: Quantifies a specific property of an element, such as distance, length, or time, typically for precision adjustments.

### Style and Appearance:
- **Stylize**: Applies a visual effect or transformation to an element that alters its appearance in a creative way, often for artistic purposes.
- **Blur**: Softens or obscures the details of an element, typically to create depth or focus attention elsewhere.
- **Distort**: Warps or changes the shape of an element, altering its original form or structure.
- **Colorize**: Applies or changes the color properties of an element, often adding tint, hue shifts, or saturation adjustments.

### Transformation:
- **Scale**: Changes the size of an element relative to its original dimensions.
- **Transform**: Alters the position, rotation, or scale of an element to move or reposition it within the composition.
- **Resize**: Changes the dimensions of an element, usually altering both width and height.
- **Remap**: Changes the spatial coordinates or properties of an element based on a new set of input values.
- **Rotate**: Turns or pivots an element around a central point or axis.
- **Adjust**: Fine-tunes the position or movement of an element, often for precise placement or timing.
- **Alter**: Significantly changes the movement or position of an element, often resulting in a new behavior or look.

### Randomization and Variation:
- **Randomize**: Applies random variations to a property, such as position, color, or timing, to create unpredictability.
- **Wiggle**: Adds small, random variations to a property, often applied over time to create jitter or organic movement.
- **Replace**: Substitutes one element or property with another, often swapping out content or attributes.
