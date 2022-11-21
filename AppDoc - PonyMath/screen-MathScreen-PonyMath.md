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

## MathScreen

### Behavior

| Property  | Value                                                |
| --------- | ---------------------------------------------------- |
| OnVisible | Set(PinkiePosition,1);Select(HiddenValidationButton) |

### Design

| Property            | Value                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.DesignHeight)                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                   |
| LoadingSpinner      | LoadingSpinner.None                                                                                                 |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table> |
| Orientation         | If(MathScreen.Width \< MathScreen.Height, Layout.Vertical, Layout.Horizontal)                                       |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= MathScreen.Width)                     |
| Width               | Max(App.Width, App.DesignWidth)                                                                                     |

### Color Properties

| Property | Value                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(245, 255, 157, 0.4)</td></tr><tr><td style="background-color:#F5FF9D"></td></tr></table> |

### Child & Parent Controls

| Property      | Value                  |
| ------------- | ---------------------- |
| Child Control | Circle1                |
| Child Control | Button1                |
| Child Control | Button1\_1             |
| Child Control | Button1\_2             |
| Child Control | Circle1\_2             |
| Child Control | Number1                |
| Child Control | Button1\_3             |
| Child Control | Button1\_4             |
| Child Control | Button1\_5             |
| Child Control | Number3                |
| Child Control | Button1\_6             |
| Child Control | Button1\_7             |
| Child Control | Button1\_8             |
| Child Control | Circle1\_1             |
| Child Control | HiddenGeneratorButton  |
| Child Control | Number2                |
| Child Control | HiddenValidationButton |
| Child Control | PinkiePie              |
| Child Control | Image3                 |

### Button1

### Behavior

| Property | Value                                                |
| -------- | ---------------------------------------------------- |
| OnSelect | Set(SelectedNumber,1);Select(HiddenValidationButton) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Text            | "1"   |

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
| Height                 | 48                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 82                   |
| X                      | 818                  |
| Y                      | 37                   |
| ZIndex                 | 4                    |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1.Fill, \-15%)                                                                                        |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1.BorderColor                                                                                                   |
| HoverBorderColor    | ColorFade(Button1.BorderColor, 20%)                                                                                   |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1.Fill                                                                                                          |
| PressedColor        | Button1.Fill                                                                                                          |
| PressedFill         | Button1.Color                                                                                                         |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Button1\_1

### Behavior

| Property | Value                                                |
| -------- | ---------------------------------------------------- |
| OnSelect | Set(SelectedNumber,2);Select(HiddenValidationButton) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Text            | "2"   |

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
| Height                 | 48                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 82                   |
| X                      | 927                  |
| Y                      | 37                   |
| ZIndex                 | 5                    |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1\_1.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1\_1.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button1\_1.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1\_1.Fill                                                                                                       |
| PressedColor        | Button1\_1.Fill                                                                                                       |
| PressedFill         | Button1\_1.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Button1\_2

### Behavior

| Property | Value                                                |
| -------- | ---------------------------------------------------- |
| OnSelect | Set(SelectedNumber,3);Select(HiddenValidationButton) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Text            | "3"   |

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
| Height                 | 48                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 82                   |
| X                      | 1037                 |
| Y                      | 37                   |
| ZIndex                 | 6                    |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1\_2.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1\_2.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button1\_2.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1\_2.Fill                                                                                                       |
| PressedColor        | Button1\_2.Fill                                                                                                       |
| PressedFill         | Button1\_2.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Button1\_3

### Behavior

| Property | Value                                                |
| -------- | ---------------------------------------------------- |
| OnSelect | Set(SelectedNumber,4);Select(HiddenValidationButton) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Text            | "4"   |

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
| Height                 | 48                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 82                   |
| X                      | 818                  |
| Y                      | 112                  |
| ZIndex                 | 7                    |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1\_3.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1\_3.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button1\_3.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1\_3.Fill                                                                                                       |
| PressedColor        | Button1\_3.Fill                                                                                                       |
| PressedFill         | Button1\_3.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Button1\_4

### Behavior

| Property | Value                                                |
| -------- | ---------------------------------------------------- |
| OnSelect | Set(SelectedNumber,5);Select(HiddenValidationButton) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Text            | "5"   |

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
| Height                 | 48                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 82                   |
| X                      | 927                  |
| Y                      | 112                  |
| ZIndex                 | 8                    |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1\_4.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1\_4.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button1\_4.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1\_4.Fill                                                                                                       |
| PressedColor        | Button1\_4.Fill                                                                                                       |
| PressedFill         | Button1\_4.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Button1\_5

### Behavior

| Property | Value                                                |
| -------- | ---------------------------------------------------- |
| OnSelect | Set(SelectedNumber,6);Select(HiddenValidationButton) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Text            | "6"   |

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
| Height                 | 48                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 82                   |
| X                      | 1037                 |
| Y                      | 112                  |
| ZIndex                 | 9                    |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1\_5.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1\_5.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button1\_5.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1\_5.Fill                                                                                                       |
| PressedColor        | Button1\_5.Fill                                                                                                       |
| PressedFill         | Button1\_5.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Button1\_6

### Behavior

| Property | Value                                                |
| -------- | ---------------------------------------------------- |
| OnSelect | Set(SelectedNumber,7);Select(HiddenValidationButton) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Text            | "7"   |

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
| Height                 | 48                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 82                   |
| X                      | 818                  |
| Y                      | 193                  |
| ZIndex                 | 10                   |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1\_6.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1\_6.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button1\_6.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1\_6.Fill                                                                                                       |
| PressedColor        | Button1\_6.Fill                                                                                                       |
| PressedFill         | Button1\_6.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Button1\_7

### Behavior

| Property | Value                                                |
| -------- | ---------------------------------------------------- |
| OnSelect | Set(SelectedNumber,8);Select(HiddenValidationButton) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Text            | "8"   |

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
| Height                 | 48                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 82                   |
| X                      | 927                  |
| Y                      | 193                  |
| ZIndex                 | 11                   |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1\_7.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1\_7.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button1\_7.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1\_7.Fill                                                                                                       |
| PressedColor        | Button1\_7.Fill                                                                                                       |
| PressedFill         | Button1\_7.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Button1\_8

### Behavior

| Property | Value                                                |
| -------- | ---------------------------------------------------- |
| OnSelect | Set(SelectedNumber,9);Select(HiddenValidationButton) |

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |
| Text            | "9"   |

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
| Height                 | 48                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 82                   |
| X                      | 1037                 |
| Y                      | 193                  |
| ZIndex                 | 12                   |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1\_8.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1\_8.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button1\_8.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1\_8.Fill                                                                                                       |
| PressedColor        | Button1\_8.Fill                                                                                                       |
| PressedFill         | Button1\_8.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Circle1

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |

### Design

| Property        | Value             |
| --------------- | ----------------- |
| BorderStyle     | BorderStyle.Solid |
| BorderThickness | 1                 |
| DisplayMode     | DisplayMode.Edit  |
| Height          | 246               |
| Width           | 246               |
| X               | 103               |
| Y               | 23                |
| ZIndex          | 1                 |

### Color Properties

| Property           | Value                                                                                                                   |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| BorderColor        | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>         |
| DisabledFill       | Circle1.Fill                                                                                                            |
| Fill               | <table border="0"><tr><td>RGBA(239, 39, 229, 0.24)</td></tr><tr><td style="background-color:#EF27E5"></td></tr></table> |
| FocusedBorderColor | Circle1.BorderColor                                                                                                     |
| HoverFill          | Circle1.Fill                                                                                                            |
| PressedFill        | Circle1.Fill                                                                                                            |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Circle1\_1

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |

### Design

| Property        | Value             |
| --------------- | ----------------- |
| BorderStyle     | BorderStyle.Solid |
| BorderThickness | 1                 |
| DisplayMode     | DisplayMode.Edit  |
| Height          | 246               |
| Width           | 246               |
| X               | 103               |
| Y               | 284               |
| ZIndex          | 2                 |

### Color Properties

| Property           | Value                                                                                                                   |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| BorderColor        | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>         |
| DisabledFill       | Circle1\_1.Fill                                                                                                         |
| Fill               | <table border="0"><tr><td>RGBA(239, 39, 229, 0.24)</td></tr><tr><td style="background-color:#EF27E5"></td></tr></table> |
| FocusedBorderColor | Circle1\_1.BorderColor                                                                                                  |
| HoverFill          | Circle1\_1.Fill                                                                                                         |
| PressedFill        | Circle1\_1.Fill                                                                                                         |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Circle1\_2

### Data

| Property        | Value |
| --------------- | ----- |
| ContentLanguage | ""    |

### Design

| Property        | Value             |
| --------------- | ----------------- |
| BorderStyle     | BorderStyle.Solid |
| BorderThickness | 1                 |
| DisplayMode     | DisplayMode.Edit  |
| Height          | 348               |
| Width           | 348               |
| X               | 392               |
| Y               | 67                |
| ZIndex          | 3                 |

### Color Properties

| Property           | Value                                                                                                                   |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| BorderColor        | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>      |
| DisabledFill       | Circle1\_2.Fill                                                                                                         |
| Fill               | <table border="0"><tr><td>RGBA(239, 39, 229, 0.24)</td></tr><tr><td style="background-color:#EF27E5"></td></tr></table> |
| FocusedBorderColor | Circle1\_2.BorderColor                                                                                                  |
| HoverFill          | Circle1\_2.Fill                                                                                                         |
| PressedFill        | Circle1\_2.Fill                                                                                                         |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### HiddenGeneratorButton

### Behavior

| Property | Value                                                                                                                                                                                                                     |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | Set(MathNumber1,RoundDown(Rand()\*(10\-1)+1,0));Set(MathNumber2,RoundDown(Rand()\*(12\-MathNumber1\-1)+1,0));Number1.Text\=Text(MathNumber1);Number2.Text\=Text(MathNumber2);Number3.Text\=Text(MathNumber1+MathNumber2); |

### Data

| Property        | Value      |
| --------------- | ---------- |
| ContentLanguage | ""         |
| Text            | "Generate" |

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
| Visible                | false                |
| Width                  | 280                  |
| X                      | 839                  |
| Y                      | 304                  |
| ZIndex                 | 17                   |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(HiddenGeneratorButton.Fill, \-15%)                                                                          |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>   |
| FocusedBorderColor  | HiddenGeneratorButton.BorderColor                                                                                     |
| HoverBorderColor    | ColorFade(HiddenGeneratorButton.BorderColor, 20%)                                                                     |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | HiddenGeneratorButton.Fill                                                                                            |
| PressedColor        | HiddenGeneratorButton.Fill                                                                                            |
| PressedFill         | HiddenGeneratorButton.Color                                                                                           |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### HiddenValidationButton

### Behavior

| Property | Value                                                                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | If(SelectedNumber\=MathNumber2,Set(PinkiePosition,PinkiePosition+1);Select(HiddenGeneratorButton));If(PinkiePosition\=10,Navigate(EatScreen,ScreenTransition.Fade)) |

### Data

| Property        | Value      |
| --------------- | ---------- |
| ContentLanguage | ""         |
| Text            | "Validate" |

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
| Visible                | false                |
| Width                  | 280                  |
| X                      | 839                  |
| Y                      | 374                  |
| ZIndex                 | 18                   |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(HiddenValidationButton.Fill, \-15%)                                                                         |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>   |
| FocusedBorderColor  | HiddenValidationButton.BorderColor                                                                                    |
| HoverBorderColor    | ColorFade(HiddenValidationButton.BorderColor, 20%)                                                                    |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | HiddenValidationButton.Fill                                                                                           |
| PressedColor        | HiddenValidationButton.Fill                                                                                           |
| PressedFill         | HiddenValidationButton.Color                                                                                          |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Image3

### Data

| Property        | Value      |
| --------------- | ---------- |
| ContentLanguage | ""         |
| Image           | TargetItem |

### Design

| Property               | Value              |
| ---------------------- | ------------------ |
| BorderStyle            | BorderStyle.Solid  |
| BorderThickness        | 0                  |
| DisplayMode            | DisplayMode.Edit   |
| FocusedBorderThickness | 2                  |
| Height                 | 111                |
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
| Width                  | 111                |
| X                      | 1022               |
| Y                      | 529                |
| ZIndex                 | 20                 |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image3.BorderColor                                                                                                    |
| HoverBorderColor    | ColorFade(Image3.BorderColor, 20%)                                                                                    |
| HoverFill           | ColorFade(Image3.Fill, 20%)                                                                                           |
| PressedBorderColor  | ColorFade(Image3.BorderColor, \-20%)                                                                                  |
| PressedFill         | ColorFade(Image3.Fill, \-20%)                                                                                         |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### MathScreen

### Behavior

| Property  | Value                                                |
| --------- | ---------------------------------------------------- |
| OnVisible | Set(PinkiePosition,1);Select(HiddenValidationButton) |

### Design

| Property            | Value                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.DesignHeight)                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                   |
| LoadingSpinner      | LoadingSpinner.None                                                                                                 |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table> |
| Orientation         | If(MathScreen.Width \< MathScreen.Height, Layout.Vertical, Layout.Horizontal)                                       |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= MathScreen.Width)                     |
| Width               | Max(App.Width, App.DesignWidth)                                                                                     |

### Color Properties

| Property | Value                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(245, 255, 157, 0.4)</td></tr><tr><td style="background-color:#F5FF9D"></td></tr></table> |

### Child & Parent Controls

| Property      | Value                  |
| ------------- | ---------------------- |
| Child Control | Circle1                |
| Child Control | Button1                |
| Child Control | Button1\_1             |
| Child Control | Button1\_2             |
| Child Control | Circle1\_2             |
| Child Control | Number1                |
| Child Control | Button1\_3             |
| Child Control | Button1\_4             |
| Child Control | Button1\_5             |
| Child Control | Number3                |
| Child Control | Button1\_6             |
| Child Control | Button1\_7             |
| Child Control | Button1\_8             |
| Child Control | Circle1\_1             |
| Child Control | HiddenGeneratorButton  |
| Child Control | Number2                |
| Child Control | HiddenValidationButton |
| Child Control | PinkiePie              |
| Child Control | Image3                 |

### Number1

### Data

| Property        | Value            |
| --------------- | ---------------- |
| ContentLanguage | ""               |
| Live            | Live.Off         |
| Role            | TextRole.Default |
| Text            | MathNumber1      |

### Design

| Property               | Value                |
| ---------------------- | -------------------- |
| Align                  | Align.Center         |
| BorderStyle            | BorderStyle.Solid    |
| BorderThickness        | 0                    |
| DisplayMode            | DisplayMode.Edit     |
| FocusedBorderThickness | 0                    |
| Font                   | Font.'Open Sans'     |
| FontWeight             | FontWeight.Normal    |
| Height                 | 121                  |
| Italic                 | false                |
| LineHeight             | 1.2                  |
| Overflow               | Overflow.Hidden      |
| PaddingBottom          | 5                    |
| PaddingLeft            | 5                    |
| PaddingRight           | 5                    |
| PaddingTop             | 5                    |
| Size                   | 80                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 246                  |
| X                      | 103                  |
| Y                      | 79                   |
| ZIndex                 | 14                   |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| Color               | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Number1.BorderColor                                                                                                   |
| HoverBorderColor    | Number1.BorderColor                                                                                                   |
| HoverColor          | Number1.Color                                                                                                         |
| HoverFill           | Number1.Fill                                                                                                          |
| PressedBorderColor  | Number1.BorderColor                                                                                                   |
| PressedColor        | Number1.Color                                                                                                         |
| PressedFill         | Number1.Fill                                                                                                          |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Number2

### Data

| Property        | Value            |
| --------------- | ---------------- |
| ContentLanguage | ""               |
| Live            | Live.Off         |
| Role            | TextRole.Default |
| Text            | "?"              |
| Tooltip         |                  |

### Design

| Property               | Value                |
| ---------------------- | -------------------- |
| Align                  | Align.Center         |
| BorderStyle            | BorderStyle.Solid    |
| BorderThickness        | 0                    |
| DisplayMode            | DisplayMode.Edit     |
| FocusedBorderThickness | 0                    |
| Font                   | Font.'Open Sans'     |
| FontWeight             | FontWeight.Normal    |
| Height                 | 114                  |
| Italic                 | false                |
| LineHeight             | 1.2                  |
| Overflow               | Overflow.Hidden      |
| PaddingBottom          | 5                    |
| PaddingLeft            | 5                    |
| PaddingRight           | 5                    |
| PaddingTop             | 5                    |
| Size                   | 80                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 246                  |
| X                      | 103                  |
| Y                      | 352                  |
| ZIndex                 | 15                   |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| Color               | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Number2.BorderColor                                                                                                   |
| HoverBorderColor    | Number2.BorderColor                                                                                                   |
| HoverColor          | Number2.Color                                                                                                         |
| HoverFill           | Number2.Fill                                                                                                          |
| PressedBorderColor  | Number2.BorderColor                                                                                                   |
| PressedColor        | Number2.Color                                                                                                         |
| PressedFill         | Number2.Fill                                                                                                          |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### Number3

### Data

| Property        | Value                   |
| --------------- | ----------------------- |
| ContentLanguage | ""                      |
| Live            | Live.Off                |
| Role            | TextRole.Default        |
| Text            | MathNumber1+MathNumber2 |

### Design

| Property               | Value                |
| ---------------------- | -------------------- |
| Align                  | Align.Center         |
| BorderStyle            | BorderStyle.Solid    |
| BorderThickness        | 0                    |
| DisplayMode            | DisplayMode.Edit     |
| FocusedBorderThickness | 0                    |
| Font                   | Font.'Open Sans'     |
| FontWeight             | FontWeight.Normal    |
| Height                 | 197                  |
| Italic                 | false                |
| LineHeight             | 1.2                  |
| Overflow               | Overflow.Hidden      |
| PaddingBottom          | 5                    |
| PaddingLeft            | 5                    |
| PaddingRight           | 5                    |
| PaddingTop             | 5                    |
| Size                   | 96                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 246                  |
| X                      | 443                  |
| Y                      | 133                  |
| ZIndex                 | 16                   |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| Color               | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Number3.BorderColor                                                                                                   |
| HoverBorderColor    | Number3.BorderColor                                                                                                   |
| HoverColor          | Number3.Color                                                                                                         |
| HoverFill           | Number3.Fill                                                                                                          |
| PressedBorderColor  | Number3.BorderColor                                                                                                   |
| PressedColor        | Number3.Color                                                                                                         |
| PressedFill         | Number3.Fill                                                                                                          |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |

### PinkiePie

### Data

| Property        | Value  |
| --------------- | ------ |
| ContentLanguage | ""     |
| Image           | Avatar |

### Design

| Property               | Value                       |
| ---------------------- | --------------------------- |
| BorderStyle            | BorderStyle.Solid           |
| BorderThickness        | 0                           |
| DisplayMode            | DisplayMode.Edit            |
| FocusedBorderThickness | 2                           |
| Height                 | 112                         |
| ImagePosition          | ImagePosition.Fit           |
| ImageRotation          | ImageRotation.None          |
| PaddingBottom          | 0                           |
| PaddingLeft            | 0                           |
| PaddingRight           | 0                           |
| PaddingTop             | 0                           |
| RadiusBottomLeft       | 0                           |
| RadiusBottomRight      | 0                           |
| RadiusTopLeft          | 0                           |
| RadiusTopRight         | 0                           |
| Width                  | 112                         |
| X                      | 14+112\*(PinkiePosition\-1) |
| Y                      | 528                         |
| ZIndex                 | 19                          |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | PinkiePie.BorderColor                                                                                                 |
| HoverBorderColor    | ColorFade(PinkiePie.BorderColor, 20%)                                                                                 |
| HoverFill           | ColorFade(PinkiePie.Fill, 20%)                                                                                        |
| PressedBorderColor  | ColorFade(PinkiePie.BorderColor, \-20%)                                                                               |
| PressedFill         | ColorFade(PinkiePie.Fill, \-20%)                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | MathScreen |
