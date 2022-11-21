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

## TimesMathScreen

### Behavior

| Property  | Value                                                                                                    |
| --------- | -------------------------------------------------------------------------------------------------------- |
| OnVisible | ClearCollect(MaxTimesTableNumbers,Sequence(50,1));Set(PinkiePosition,1);Select(HiddenGeneratorButton\_1) |

### Design

| Property            | Value                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.DesignHeight)                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                   |
| LoadingSpinner      | LoadingSpinner.None                                                                                                 |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table> |
| Orientation         | If(TimesMathScreen.Width \< TimesMathScreen.Height, Layout.Vertical, Layout.Horizontal)                             |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= TimesMathScreen.Width)                |
| Width               | Max(App.Width, App.DesignWidth)                                                                                     |

### Color Properties

| Property | Value                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(245, 255, 157, 0.4)</td></tr><tr><td style="background-color:#F5FF9D"></td></tr></table> |

### Child & Parent Controls

| Property      | Value                     |
| ------------- | ------------------------- |
| Child Control | Circle1\_3                |
| Child Control | AnswerList                |
| Child Control | Number1\_1                |
| Child Control | Circle1\_4                |
| Child Control | Number3\_1                |
| Child Control | Label2                    |
| Child Control | Circle1\_5                |
| Child Control | HiddenGeneratorButton\_1  |
| Child Control | Number2\_1                |
| Child Control | HiddenValidationButton\_1 |
| Child Control | Button1\_9                |
| Child Control | PinkiePie\_1              |
| Child Control | Image3\_1                 |

### AnswerList

### Data

| Property        | Value                |
| --------------- | -------------------- |
| ContentLanguage | ""                   |
| Items           | MaxTimesTableNumbers |

### Design

| Property               | Value                                                                                                                 |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | BorderStyle.Solid                                                                                                     |
| BorderThickness        | 2                                                                                                                     |
| DisabledSelectionColor | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| DisplayMode            | DisplayMode.Edit                                                                                                      |
| FocusedBorderThickness | 4                                                                                                                     |
| Font                   | Font.'Open Sans'                                                                                                      |
| FontWeight             | FontWeight.Normal                                                                                                     |
| Height                 | 400                                                                                                                   |
| ItemPaddingLeft        | RoundDown(AnswerList.Width\/2,0)\-20                                                                                  |
| PaddingBottom          | 0                                                                                                                     |
| PaddingLeft            | 0                                                                                                                     |
| PaddingRight           | 0                                                                                                                     |
| PaddingTop             | 0                                                                                                                     |
| SelectMultiple         | false                                                                                                                 |
| Size                   | 35                                                                                                                    |
| Width                  | 397                                                                                                                   |
| X                      | 708                                                                                                                   |
| Y                      | 44                                                                                                                    |
| ZIndex                 | 22                                                                                                                    |

### Color Properties

| Property              | Value                                                                                                                 |
| --------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor           | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| Color                 | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| DisabledBorderColor   | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor         | <table border="0"><tr><td>RGBA(186, 186, 186, 1)</td></tr><tr><td style="background-color:#BABABA"></td></tr></table> |
| DisabledFill          | <table border="0"><tr><td>RGBA(242, 242, 242, 1)</td></tr><tr><td style="background-color:#F2F2F2"></td></tr></table> |
| DisabledSelectionFill | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| Fill                  | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| FocusedBorderColor    | Self.BorderColor                                                                                                      |
| HoverBorderColor      | ColorFade(AnswerList.BorderColor, 15%)                                                                                |
| HoverColor            | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| HoverFill             | <table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table> |
| PressedBorderColor    | AnswerList.HoverBorderColor                                                                                           |
| PressedColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| PressedFill           | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| SelectionColor        | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| SelectionFill         | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>   |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### Button1\_9

### Behavior

| Property | Value                                                                                       |
| -------- | ------------------------------------------------------------------------------------------- |
| OnSelect | Set(SelectedNumber,First(AnswerList.SelectedItems).Value);Select(HiddenValidationButton\_1) |

### Data

| Property        | Value       |
| --------------- | ----------- |
| ContentLanguage | ""          |
| Text            | "My Answer" |

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
| Height                 | 56                   |
| Italic                 | false                |
| RadiusBottomLeft       | 10                   |
| RadiusBottomRight      | 10                   |
| RadiusTopLeft          | 10                   |
| RadiusTopRight         | 10                   |
| Size                   | 24                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 210                  |
| X                      | 801                  |
| Y                      | 458                  |
| ZIndex                 | 4                    |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button1\_9.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button1\_9.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button1\_9.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button1\_9.Fill                                                                                                       |
| PressedColor        | Button1\_9.Fill                                                                                                       |
| PressedFill         | Button1\_9.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### Circle1\_3

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
| DisabledFill       | Circle1\_3.Fill                                                                                                         |
| Fill               | <table border="0"><tr><td>RGBA(239, 39, 229, 0.24)</td></tr><tr><td style="background-color:#EF27E5"></td></tr></table> |
| FocusedBorderColor | Circle1\_3.BorderColor                                                                                                  |
| HoverFill          | Circle1\_3.Fill                                                                                                         |
| PressedFill        | Circle1\_3.Fill                                                                                                         |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### Circle1\_4

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
| Height          | 285               |
| Width           | 285               |
| X               | 396               |
| Y               | 132               |
| ZIndex          | 3                 |

### Color Properties

| Property           | Value                                                                                                                   |
| ------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| BorderColor        | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>      |
| DisabledFill       | Circle1\_4.Fill                                                                                                         |
| Fill               | <table border="0"><tr><td>RGBA(239, 39, 229, 0.24)</td></tr><tr><td style="background-color:#EF27E5"></td></tr></table> |
| FocusedBorderColor | Circle1\_4.BorderColor                                                                                                  |
| HoverFill          | Circle1\_4.Fill                                                                                                         |
| PressedFill        | Circle1\_4.Fill                                                                                                         |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### Circle1\_5

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
| DisabledFill       | Circle1\_5.Fill                                                                                                         |
| Fill               | <table border="0"><tr><td>RGBA(239, 39, 229, 0.24)</td></tr><tr><td style="background-color:#EF27E5"></td></tr></table> |
| FocusedBorderColor | Circle1\_5.BorderColor                                                                                                  |
| HoverFill          | Circle1\_5.Fill                                                                                                         |
| PressedFill        | Circle1\_5.Fill                                                                                                         |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### HiddenGeneratorButton\_1

### Behavior

| Property | Value                                                                                                                                                                                                      |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | Set(MathNumber1,RoundDown(Rand()\*5+1,0));Set(MathNumber2,RoundDown(Rand()\*10+1,0));Number1\_1.Text\=Text(MathNumber1);Number2\_1.Text\=Text(MathNumber2);Number3\_1.Text\=Text(MathNumber1+MathNumber2); |

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
| BorderColor         | ColorFade(HiddenGeneratorButton\_1.Fill, \-15%)                                                                       |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>   |
| FocusedBorderColor  | HiddenGeneratorButton\_1.BorderColor                                                                                  |
| HoverBorderColor    | ColorFade(HiddenGeneratorButton\_1.BorderColor, 20%)                                                                  |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | HiddenGeneratorButton\_1.Fill                                                                                         |
| PressedColor        | HiddenGeneratorButton\_1.Fill                                                                                         |
| PressedFill         | HiddenGeneratorButton\_1.Color                                                                                        |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### HiddenValidationButton\_1

### Behavior

| Property | Value                                                                                                                                                                               |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | If(SelectedNumber\=MathNumber2\*MathNumber1,Set(PinkiePosition,PinkiePosition+1);Select(HiddenGeneratorButton\_1));If(PinkiePosition\=10,Navigate(EatScreen,ScreenTransition.Fade)) |

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
| BorderColor         | ColorFade(HiddenValidationButton\_1.Fill, \-15%)                                                                      |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>   |
| FocusedBorderColor  | HiddenValidationButton\_1.BorderColor                                                                                 |
| HoverBorderColor    | ColorFade(HiddenValidationButton\_1.BorderColor, 20%)                                                                 |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | HiddenValidationButton\_1.Fill                                                                                        |
| PressedColor        | HiddenValidationButton\_1.Fill                                                                                        |
| PressedFill         | HiddenValidationButton\_1.Color                                                                                       |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### Image3\_1

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
| FocusedBorderColor  | Image3\_1.BorderColor                                                                                                 |
| HoverBorderColor    | ColorFade(Image3\_1.BorderColor, 20%)                                                                                 |
| HoverFill           | ColorFade(Image3\_1.Fill, 20%)                                                                                        |
| PressedBorderColor  | ColorFade(Image3\_1.BorderColor, \-20%)                                                                               |
| PressedFill         | ColorFade(Image3\_1.Fill, \-20%)                                                                                      |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### Label2

### Data

| Property        | Value            |
| --------------- | ---------------- |
| ContentLanguage | ""               |
| Live            | Live.Off         |
| Role            | TextRole.Default |
| Text            | "X"              |

### Design

| Property               | Value                |
| ---------------------- | -------------------- |
| Align                  | Align.Left           |
| BorderStyle            | BorderStyle.Solid    |
| BorderThickness        | 0                    |
| DisplayMode            | DisplayMode.Edit     |
| FocusedBorderThickness | 0                    |
| Font                   | Font.'Open Sans'     |
| FontWeight             | FontWeight.Bold      |
| Height                 | 70                   |
| Italic                 | false                |
| LineHeight             | 1.2                  |
| Overflow               | Overflow.Hidden      |
| PaddingBottom          | 5                    |
| PaddingLeft            | 5                    |
| PaddingRight           | 5                    |
| PaddingTop             | 5                    |
| Size                   | 36                   |
| Strikethrough          | false                |
| Underline              | false                |
| VerticalAlign          | VerticalAlign.Middle |
| Width                  | 51                   |
| X                      | 315                  |
| Y                      | 240                  |
| ZIndex                 | 21                   |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| Color               | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                      |
| HoverBorderColor    | Self.BorderColor                                                                                                      |
| HoverColor          | Self.Color                                                                                                            |
| HoverFill           | Self.Fill                                                                                                             |
| PressedBorderColor  | Self.BorderColor                                                                                                      |
| PressedColor        | Self.Color                                                                                                            |
| PressedFill         | Self.Fill                                                                                                             |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### Number1\_1

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
| FocusedBorderColor  | Number1\_1.BorderColor                                                                                                |
| HoverBorderColor    | Number1\_1.BorderColor                                                                                                |
| HoverColor          | Number1\_1.Color                                                                                                      |
| HoverFill           | Number1\_1.Fill                                                                                                       |
| PressedBorderColor  | Number1\_1.BorderColor                                                                                                |
| PressedColor        | Number1\_1.Color                                                                                                      |
| PressedFill         | Number1\_1.Fill                                                                                                       |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### Number2\_1

### Data

| Property        | Value            |
| --------------- | ---------------- |
| ContentLanguage | ""               |
| Live            | Live.Off         |
| Role            | TextRole.Default |
| Text            | MathNumber2      |
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
| FocusedBorderColor  | Number2\_1.BorderColor                                                                                                |
| HoverBorderColor    | Number2\_1.BorderColor                                                                                                |
| HoverColor          | Number2\_1.Color                                                                                                      |
| HoverFill           | Number2\_1.Fill                                                                                                       |
| PressedBorderColor  | Number2\_1.BorderColor                                                                                                |
| PressedColor        | Number2\_1.Color                                                                                                      |
| PressedFill         | Number2\_1.Fill                                                                                                       |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### Number3\_1

### Data

| Property        | Value            |
| --------------- | ---------------- |
| ContentLanguage | ""               |
| Live            | Live.Off         |
| Role            | TextRole.Default |
| Text            | "?"              |

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
| X                      | 415                  |
| Y                      | 177                  |
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
| FocusedBorderColor  | Number3\_1.BorderColor                                                                                                |
| HoverBorderColor    | Number3\_1.BorderColor                                                                                                |
| HoverColor          | Number3\_1.Color                                                                                                      |
| HoverFill           | Number3\_1.Fill                                                                                                       |
| PressedBorderColor  | Number3\_1.BorderColor                                                                                                |
| PressedColor        | Number3\_1.Color                                                                                                      |
| PressedFill         | Number3\_1.Fill                                                                                                       |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### PinkiePie\_1

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
| FocusedBorderColor  | PinkiePie\_1.BorderColor                                                                                              |
| HoverBorderColor    | ColorFade(PinkiePie\_1.BorderColor, 20%)                                                                              |
| HoverFill           | ColorFade(PinkiePie\_1.Fill, 20%)                                                                                     |
| PressedBorderColor  | ColorFade(PinkiePie\_1.BorderColor, \-20%)                                                                            |
| PressedFill         | ColorFade(PinkiePie\_1.Fill, \-20%)                                                                                   |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Parent Control | TimesMathScreen |

### TimesMathScreen

### Behavior

| Property  | Value                                                                                                    |
| --------- | -------------------------------------------------------------------------------------------------------- |
| OnVisible | ClearCollect(MaxTimesTableNumbers,Sequence(50,1));Set(PinkiePosition,1);Select(HiddenGeneratorButton\_1) |

### Design

| Property            | Value                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.DesignHeight)                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                   |
| LoadingSpinner      | LoadingSpinner.None                                                                                                 |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table> |
| Orientation         | If(TimesMathScreen.Width \< TimesMathScreen.Height, Layout.Vertical, Layout.Horizontal)                             |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= TimesMathScreen.Width)                |
| Width               | Max(App.Width, App.DesignWidth)                                                                                     |

### Color Properties

| Property | Value                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(245, 255, 157, 0.4)</td></tr><tr><td style="background-color:#F5FF9D"></td></tr></table> |

### Child & Parent Controls

| Property      | Value                     |
| ------------- | ------------------------- |
| Child Control | Circle1\_3                |
| Child Control | AnswerList                |
| Child Control | Number1\_1                |
| Child Control | Circle1\_4                |
| Child Control | Number3\_1                |
| Child Control | Label2                    |
| Child Control | Circle1\_5                |
| Child Control | HiddenGeneratorButton\_1  |
| Child Control | Number2\_1                |
| Child Control | HiddenValidationButton\_1 |
| Child Control | Button1\_9                |
| Child Control | PinkiePie\_1              |
| Child Control | Image3\_1                 |
