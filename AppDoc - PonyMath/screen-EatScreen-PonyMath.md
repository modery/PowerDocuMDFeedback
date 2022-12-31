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

## EatScreen

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![screen](resources/screen.png) | Type: screen |

### Design

| Property            | Value                                                                                                                                                                                                                                                                                                                       |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Height              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Max(App.Height, App.DesignHeight)<td style="background-color:#ffcccc; width:50%;">Max(App.Height, App.MinScreenHeight)</td></tr></table>                                                                                                             |
| ImagePosition       | ImagePosition.Fit                                                                                                                                                                                                                                                                                                           |
| LoadingSpinner      | LoadingSpinner.None                                                                                                                                                                                                                                                                                                         |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>                                                                                                                                                                                                         |
| Orientation         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(EatScreen.Width < EatScreen.Height, Layout.Vertical, Layout.Horizontal)<td style="background-color:#ffcccc; width:50%;">If(Self.Width < Self.Height, Layout.Vertical, Layout.Horizontal)</td></tr></table>                                        |
| Size                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1 + CountRows(App.SizeBreakpoints) - CountIf(App.SizeBreakpoints, Value >= EatScreen.Width)<td style="background-color:#ffcccc; width:50%;">1 + CountRows(App.SizeBreakpoints) - CountIf(App.SizeBreakpoints, Value >= Self.Width)</td></tr></table> |
| Width               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Max(App.Width, App.DesignWidth)<td style="background-color:#ffcccc; width:50%;">Max(App.Width, App.MinScreenWidth)</td></tr></table>                                                                                                                 |

### Color Properties

| Property | Value                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(245, 255, 157, 0.4)</td></tr><tr><td style="background-color:#F5FF9D"></td></tr></table> |

### Child & Parent Controls

| Property      | Value   |
| ------------- | ------- |
| Child Control | Image2  |
| Child Control | Button3 |

## Button3

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                           |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Navigate(StartScreen)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                          |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Play Again"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Center                                                                                                                                     |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 2                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 4                                                                                                                                                |
| Font                   | Font.'Open Sans'                                                                                                                                 |
| FontWeight             | FontWeight.Semibold                                                                                                                              |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>   |
| Italic                 | false                                                                                                                                            |
| RadiusBottomLeft       | 10                                                                                                                                               |
| RadiusBottomRight      | 10                                                                                                                                               |
| RadiusTopLeft          | 10                                                                                                                                               |
| RadiusTopRight         | 10                                                                                                                                               |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">24<td style="background-color:#ffcccc; width:50%;">15</td></tr></table>   |
| Strikethrough          | false                                                                                                                                            |
| Underline              | false                                                                                                                                            |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">280<td style="background-color:#ffcccc; width:50%;">160</td></tr></table> |
| X                      | 840                                                                                                                                              |
| Y                      | 537                                                                                                                                              |
| ZIndex                 | 2                                                                                                                                                |

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

## Image2

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Data

| Property        | Value                                                                                                                                                           |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">SuccessPic<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FlipHorizontal         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">639<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">928<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 9                                                                                                                                                |
| Y                      | 1                                                                                                                                                |
| ZIndex                 | 1                                                                                                                                                |

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
