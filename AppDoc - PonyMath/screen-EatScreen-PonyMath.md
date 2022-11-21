# Power App Documentation \- PonyMath

| Property                   | Value                                                          |
| -------------------------- | -------------------------------------------------------------- |
| App Name                   | PonyMath                                                       |
| App Logo                   | <img alt="App Logo" src="resources/applogo.png" width="200" /> |
| Documentation generated at | Monday, 21 November 2022 1:31 pm                               |

- [Overview](index-PonyMath.md)
- [App Details](appdetails-PonyMath.md)
- [Variables](variables-PonyMath.md)
- [DataSources](datasources-PonyMath.md)
- [Resources](resources-PonyMath.md)
- [Controls](controls-PonyMath.md)

## EatScreen

### Design

| Property            | Value                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.DesignHeight)                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                   |
| LoadingSpinner      | LoadingSpinner.None                                                                                                 |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table> |
| Orientation         | If(EatScreen.Width \< EatScreen.Height, Layout.Vertical, Layout.Horizontal)                                         |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= EatScreen.Width)                      |
| Width               | Max(App.Width, App.DesignWidth)                                                                                     |

### Color Properties

| Property | Value                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(245, 255, 157, 0.4)</td></tr><tr><td style="background-color:#F5FF9D"></td></tr></table> |

### Child & Parent Controls

| Property      | Value   |
| ------------- | ------- |
| Child Control | Image2  |
| Child Control | Button3 |

### Button3

### Behavior

| Property | Value                 |
| -------- | --------------------- |
| OnSelect | Navigate(StartScreen) |

### Data

| Property        | Value        |
| --------------- | ------------ |
| ContentLanguage | ""           |
| Text            | "Play Again" |

### Design

| Property               | Value                |
| ---------------------- | -------------------- |
| Align                  | Align.Center         |
| BorderStyle            | BorderStyle.Solid    |
| BorderThickness        | 2                    |
| DisplayMode            | DisplayMode.Edit     |
| FocusedBorderThickness | 4                    |
| Font                   | Font.'Open Sans'     |
| FontWeight             | FontWeight.Semibold  |
| Height                 | 70                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 280                  |
| X                      | 840                  |
| Y                      | 537                  |
| ZIndex                 | 2                    |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button3.Fill, \-15%)                                                                                        |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button3.BorderColor                                                                                                   |
| HoverBorderColor    | ColorFade(Button3.BorderColor, 20%)                                                                                   |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button3.Fill                                                                                                          |
| PressedColor        | Button3.Fill                                                                                                          |
| PressedFill         | Button3.Color                                                                                                         |

### Child & Parent Controls

| Property       | Value     |
| -------------- | --------- |
| Parent Control | EatScreen |

### EatScreen

### Design

| Property            | Value                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.DesignHeight)                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                   |
| LoadingSpinner      | LoadingSpinner.None                                                                                                 |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table> |
| Orientation         | If(EatScreen.Width \< EatScreen.Height, Layout.Vertical, Layout.Horizontal)                                         |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= EatScreen.Width)                      |
| Width               | Max(App.Width, App.DesignWidth)                                                                                     |

### Color Properties

| Property | Value                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(245, 255, 157, 0.4)</td></tr><tr><td style="background-color:#F5FF9D"></td></tr></table> |

### Child & Parent Controls

| Property      | Value   |
| ------------- | ------- |
| Child Control | Image2  |
| Child Control | Button3 |

### Image2

### Data

| Property        | Value      |
| --------------- | ---------- |
| ContentLanguage | ""         |
| Image           | SuccessPic |

### Design

| Property               | Value              |
| ---------------------- | ------------------ |
| BorderStyle            | BorderStyle.Solid  |
| BorderThickness        | 0                  |
| DisplayMode            | DisplayMode.Edit   |
| FlipHorizontal         | true               |
| FocusedBorderThickness | 2                  |
| Height                 | 639                |
| ImagePosition          | ImagePosition.Fit  |
| ImageRotation          | ImageRotation.None |
| PaddingBottom          | 0                  |
| PaddingLeft            | 0                  |
| PaddingRight           | 0                  |
| PaddingTop             | 0                  |
| RadiusBottomLeft       | 0                  |
| RadiusBottomRight      | 0                  |
| RadiusTopLeft          | 0                  |
| RadiusTopRight         | 0                  |
| Width                  | 928                |
| X                      | 9                  |
| Y                      | 1                  |
| ZIndex                 | 1                  |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image2.BorderColor                                                                                                    |
| HoverBorderColor    | ColorFade(Image2.BorderColor, 20%)                                                                                    |
| HoverFill           | ColorFade(Image2.Fill, 20%)                                                                                           |
| PressedBorderColor  | ColorFade(Image2.BorderColor, \-20%)                                                                                  |
| PressedFill         | ColorFade(Image2.Fill, \-20%)                                                                                         |

### Child & Parent Controls

| Property       | Value     |
| -------------- | --------- |
| Parent Control | EatScreen |
