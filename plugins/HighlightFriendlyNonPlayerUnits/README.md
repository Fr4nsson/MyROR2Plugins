# HighlightFriendlyNonPlayerUnits

#### Highlight's friendly non-player units. 

Options to also enable labels, displaying the name of the unit with or without the unit owner's name, labels is turned off by default.

![Preview](https://raw.githubusercontent.com/Fr4nsson/MyROR2Plugins/main/plugins/HighlightFriendlyNonPlayerUnits/images/Preview.png)

## Config Preview:
```ps1
[Global]

## Set this to true to enable this mod.
# Setting type: Boolean
# Default value: true
Enable = true

[Highlight]

## Highlight friendly non-player units.
# Setting type: Boolean
# Default value: true
Enable = true

[Labels]

## Display the name of friendly non-player units.
## Example: Beetle Guard
# Setting type: Boolean
# Default value: false
Enable = false

## Prepend the owner's name to the label.
## Example: Fr4nsson's Beetle Guard
# Setting type: Boolean
# Default value: true
Display owner name = true

## Adjust the size for the labels.
# Setting type: Single
# Default value: 1.5
Size = 1.5
```
## Changelog

**1.0.1**
* Minor condition fixes.

**1.0.0**
* Release.