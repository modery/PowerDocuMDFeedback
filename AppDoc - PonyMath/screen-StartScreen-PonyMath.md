# Power App Documentation \- PonyMath

| Property                   | Value                                                          |
| -------------------------- | -------------------------------------------------------------- |
| App Name                   | PonyMath                                                       |
| App Logo                   | <img alt="App Logo" src="resources/applogo.png" width="200" /> |
| Documentation generated at | Monday, 21 November 2022 1:25 pm                               |

- [Overview](index-PonyMath.md)
- [App Details](appdetails-PonyMath.md)
- [Variables](variables-PonyMath.md)
- [DataSources](datasources-PonyMath.md)
- [Resources](resources-PonyMath.md)
- [Controls](controls-PonyMath.md)

## StartScreen

### Design

| Property            | Value                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.DesignHeight)                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                   |
| LoadingSpinner      | LoadingSpinner.None                                                                                                 |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table> |
| Orientation         | If(StartScreen.Width \< StartScreen.Height, Layout.Vertical, Layout.Horizontal)                                     |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= StartScreen.Width)                    |
| Width               | Max(App.Width, App.DesignWidth)                                                                                     |

### Color Properties

| Property | Value                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(245, 255, 157, 0.4)</td></tr><tr><td style="background-color:#F5FF9D"></td></tr></table> |

### Child & Parent Controls

| Property      | Value     |
| ------------- | --------- |
| Child Control | Image4    |
| Child Control | Image4\_1 |
| Child Control | Image4\_2 |
| Child Control | Image7    |

### Image4

### Behavior

| Property | Value                                                                                                                                                                                                     |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | Set(Avatar,'Pinkie\-Pie\-PNG\-Image\-Transparent');Set(TargetItem,cake);Set(SuccessPic,'147\-1472115\_my\-little\-pony\-clipart\-birthday\-cake\-pinkie\-pie');Navigate(MathScreen,ScreenTransition.Fade) |

### Data

| Property        | Value     |
| --------------- | --------- |
| ContentLanguage | ""        |
| Image           | pinkiepie |

### Design

| Property               | Value              |
| ---------------------- | ------------------ |
| BorderStyle            | BorderStyle.Solid  |
| BorderThickness        | 0                  |
| DisplayMode            | DisplayMode.Edit   |
| FocusedBorderThickness | 2                  |
| Height                 | 322                |
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
| Width                  | 322                |
| X                      | 54                 |
| Y                      | 24                 |
| ZIndex                 | 1                  |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image4.BorderColor                                                                                                    |
| HoverBorderColor    | ColorFade(Image4.BorderColor, 20%)                                                                                    |
| HoverFill           | ColorFade(Image4.Fill, 20%)                                                                                           |
| PressedBorderColor  | ColorFade(Image4.BorderColor, \-20%)                                                                                  |
| PressedFill         | ColorFade(Image4.Fill, \-20%)                                                                                         |

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | StartScreen |

### Image4\_1

### Behavior

| Property | Value                                                                                                                       |
| -------- | --------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | Set(Avatar,alyssa\_pony);Set(TargetItem,pond);Set(SuccessPic,alyssa\_pony\_full);Navigate(MathScreen,ScreenTransition.Fade) |

### Data

| Property        | Value        |
| --------------- | ------------ |
| ContentLanguage | ""           |
| Image           | alyssa\_pony |

### Design

| Property               | Value              |
| ---------------------- | ------------------ |
| BorderStyle            | BorderStyle.Solid  |
| BorderThickness        | 0                  |
| DisplayMode            | DisplayMode.Edit   |
| FocusedBorderThickness | 2                  |
| Height                 | 332                |
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
| Width                  | 332                |
| X                      | 736                |
| Y                      | 24                 |
| ZIndex                 | 3                  |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image4\_1.BorderColor                                                                                                 |
| HoverBorderColor    | ColorFade(Image4\_1.BorderColor, 20%)                                                                                 |
| HoverFill           | ColorFade(Image4\_1.Fill, 20%)                                                                                        |
| PressedBorderColor  | ColorFade(Image4\_1.BorderColor, \-20%)                                                                               |
| PressedFill         | ColorFade(Image4\_1.Fill, \-20%)                                                                                      |

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | StartScreen |

### Image4\_2

### Behavior

| Property | Value                                      |
| -------- | ------------------------------------------ |
| OnSelect | Navigate(CoinScreen,ScreenTransition.Fade) |

### Data

| Property        | Value     |
| --------------- | --------- |
| ContentLanguage | ""        |
| Image           | applejack |

### Design

| Property               | Value              |
| ---------------------- | ------------------ |
| BorderStyle            | BorderStyle.Solid  |
| BorderThickness        | 0                  |
| DisplayMode            | DisplayMode.Edit   |
| FocusedBorderThickness | 2                  |
| Height                 | 332                |
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
| Width                  | 332                |
| X                      | 363                |
| Y                      | 267                |
| ZIndex                 | 4                  |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image4\_2.BorderColor                                                                                                 |
| HoverBorderColor    | ColorFade(Image4\_2.BorderColor, 20%)                                                                                 |
| HoverFill           | ColorFade(Image4\_2.Fill, 20%)                                                                                        |
| PressedBorderColor  | ColorFade(Image4\_2.BorderColor, \-20%)                                                                               |
| PressedFill         | ColorFade(Image4\_2.Fill, \-20%)                                                                                      |

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | StartScreen |

### Image7

### Behavior

| Property | Value                                                                                                                                                                                                          |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | Set(Avatar,'Pinkie\-Pie\-PNG\-Image\-Transparent');Set(TargetItem,cake);Set(SuccessPic,'147\-1472115\_my\-little\-pony\-clipart\-birthday\-cake\-pinkie\-pie');Navigate(TimesMathScreen,ScreenTransition.Fade) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Image           | cake  |

### Design

| Property               | Value              |
| ---------------------- | ------------------ |
| BorderStyle            | BorderStyle.Solid  |
| BorderThickness        | 0                  |
| DisplayMode            | DisplayMode.Edit   |
| FocusedBorderThickness | 2                  |
| Height                 | 224                |
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
| Width                  | 185                |
| X                      | 764                |
| Y                      | 375                |
| ZIndex                 | 5                  |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                      |
| HoverBorderColor    | ColorFade(Image7.BorderColor, 20%)                                                                                    |
| HoverFill           | ColorFade(Image7.Fill, 20%)                                                                                           |
| PressedBorderColor  | ColorFade(Image7.BorderColor, \-20%)                                                                                  |
| PressedFill         | ColorFade(Image7.Fill, \-20%)                                                                                         |

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | StartScreen |

### StartScreen

### Design

| Property            | Value                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.DesignHeight)                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                   |
| LoadingSpinner      | LoadingSpinner.None                                                                                                 |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table> |
| Orientation         | If(StartScreen.Width \< StartScreen.Height, Layout.Vertical, Layout.Horizontal)                                     |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= StartScreen.Width)                    |
| Width               | Max(App.Width, App.DesignWidth)                                                                                     |

### Color Properties

| Property | Value                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(245, 255, 157, 0.4)</td></tr><tr><td style="background-color:#F5FF9D"></td></tr></table> |

### Child & Parent Controls

| Property      | Value     |
| ------------- | --------- |
| Child Control | Image4    |
| Child Control | Image4\_1 |
| Child Control | Image4\_2 |
| Child Control | Image7    |
