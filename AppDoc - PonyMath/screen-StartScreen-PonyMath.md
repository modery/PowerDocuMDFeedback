# Power App Documentation \- PonyMath

| Property                   | Value                               |
| -------------------------- | ----------------------------------- |
| App Name                   | PonyMath                            |
| App Logo                   | ![App Logo](resources/appLogo.png)  |
| Documentation generated at | Saturday, 31 December 2022 10:43 am |

- [Overview](index-PonyMath.md)
- [App Details](appdetails-PonyMath.md)
- [Variables](variables-PonyMath.md)
- [DataSources](datasources-PonyMath.md)
- [Resources](resources-PonyMath.md)
- [Controls](controls-PonyMath.md)

## StartScreen

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![screen](resources/screen.png) | Type: screen |

### Design

| Property            | Value                                                                                                                                                                                                                                                                                                                         |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Height              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Max(App.Height, App.DesignHeight)<td style="background-color:#ffcccc; width:50%;">Max(App.Height, App.MinScreenHeight)</td></tr></table>                                                                                                               |
| ImagePosition       | ImagePosition.Fit                                                                                                                                                                                                                                                                                                             |
| LoadingSpinner      | LoadingSpinner.None                                                                                                                                                                                                                                                                                                           |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>                                                                                                                                                                                                           |
| Orientation         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(StartScreen.Width < StartScreen.Height, Layout.Vertical, Layout.Horizontal)<td style="background-color:#ffcccc; width:50%;">If(Self.Width < Self.Height, Layout.Vertical, Layout.Horizontal)</td></tr></table>                                      |
| Size                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1 + CountRows(App.SizeBreakpoints) - CountIf(App.SizeBreakpoints, Value >= StartScreen.Width)<td style="background-color:#ffcccc; width:50%;">1 + CountRows(App.SizeBreakpoints) - CountIf(App.SizeBreakpoints, Value >= Self.Width)</td></tr></table> |
| Width               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Max(App.Width, App.DesignWidth)<td style="background-color:#ffcccc; width:50%;">Max(App.Width, App.MinScreenWidth)</td></tr></table>                                                                                                                   |

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

## Image4

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                                                                                  |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Set(Avatar,'Pinkie-Pie-PNG-Image-Transparent');Set(TargetItem,cake);Set(SuccessPic,'147-1472115_my-little-pony-clipart-birthday-cake-pinkie-pie');Navigate(MathScreen,ScreenTransition.Fade)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                          |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">pinkiepie<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">322<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| ImagePosition          | ImagePosition.Fit                                                                                                                                |
| ImageRotation          | ImageRotation.None                                                                                                                               |
| PaddingBottom          | 0                                                                                                                                                |
| PaddingLeft            | 0                                                                                                                                                |
| PaddingRight           | 0                                                                                                                                                |
| PaddingTop             | 0                                                                                                                                                |
| RadiusBottomLeft       | 0                                                                                                                                                |
| RadiusBottomRight      | 0                                                                                                                                                |
| RadiusTopLeft          | 0                                                                                                                                                |
| RadiusTopRight         | 0                                                                                                                                                |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">322<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 54                                                                                                                                               |
| Y                      | 24                                                                                                                                               |
| ZIndex                 | 1                                                                                                                                                |

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

## Image4\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                                                                                                              |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Set(Avatar,alyssa_pony);Set(TargetItem,pond);Set(SuccessPic,alyssa_pony_full);Navigate(MathScreen,ScreenTransition.Fade)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                            |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">alyssa_pony<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">332<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| ImagePosition          | ImagePosition.Fit                                                                                                                                |
| ImageRotation          | ImageRotation.None                                                                                                                               |
| PaddingBottom          | 0                                                                                                                                                |
| PaddingLeft            | 0                                                                                                                                                |
| PaddingRight           | 0                                                                                                                                                |
| PaddingTop             | 0                                                                                                                                                |
| RadiusBottomLeft       | 0                                                                                                                                                |
| RadiusBottomRight      | 0                                                                                                                                                |
| RadiusTopLeft          | 0                                                                                                                                                |
| RadiusTopRight         | 0                                                                                                                                                |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">332<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 736                                                                                                                                              |
| Y                      | 24                                                                                                                                               |
| ZIndex                 | 3                                                                                                                                                |

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

## Image4\_2

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Navigate(CoinScreen,ScreenTransition.Fade)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                          |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">applejack<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">332<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| ImagePosition          | ImagePosition.Fit                                                                                                                                |
| ImageRotation          | ImageRotation.None                                                                                                                               |
| PaddingBottom          | 0                                                                                                                                                |
| PaddingLeft            | 0                                                                                                                                                |
| PaddingRight           | 0                                                                                                                                                |
| PaddingTop             | 0                                                                                                                                                |
| RadiusBottomLeft       | 0                                                                                                                                                |
| RadiusBottomRight      | 0                                                                                                                                                |
| RadiusTopLeft          | 0                                                                                                                                                |
| RadiusTopRight         | 0                                                                                                                                                |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">332<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 363                                                                                                                                              |
| Y                      | 267                                                                                                                                              |
| ZIndex                 | 4                                                                                                                                                |

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

## Image7

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                                                                                       |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Set(Avatar,'Pinkie-Pie-PNG-Image-Transparent');Set(TargetItem,cake);Set(SuccessPic,'147-1472115_my-little-pony-clipart-birthday-cake-pinkie-pie');Navigate(TimesMathScreen,ScreenTransition.Fade)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                     |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">cake<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">224<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| ImagePosition          | ImagePosition.Fit                                                                                                                                |
| ImageRotation          | ImageRotation.None                                                                                                                               |
| PaddingBottom          | 0                                                                                                                                                |
| PaddingLeft            | 0                                                                                                                                                |
| PaddingRight           | 0                                                                                                                                                |
| PaddingTop             | 0                                                                                                                                                |
| RadiusBottomLeft       | 0                                                                                                                                                |
| RadiusBottomRight      | 0                                                                                                                                                |
| RadiusTopLeft          | 0                                                                                                                                                |
| RadiusTopRight         | 0                                                                                                                                                |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">185<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 764                                                                                                                                              |
| Y                      | 375                                                                                                                                              |
| ZIndex                 | 5                                                                                                                                                |

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
