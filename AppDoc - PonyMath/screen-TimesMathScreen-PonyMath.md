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

## TimesMathScreen

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![screen](resources/screen.png) | Type: screen |

### Behavior

| Property  | Value                                                                                                                                                                                                                                             |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnVisible | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ClearCollect(MaxTimesTableNumbers,Sequence(50,1));Set(PinkiePosition,1);Select(HiddenGeneratorButton_1)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property            | Value                                                                                                                                                                                                                                                                                                                             |
| ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Height              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Max(App.Height, App.DesignHeight)<td style="background-color:#ffcccc; width:50%;">Max(App.Height, App.MinScreenHeight)</td></tr></table>                                                                                                                   |
| ImagePosition       | ImagePosition.Fit                                                                                                                                                                                                                                                                                                                 |
| LoadingSpinner      | LoadingSpinner.None                                                                                                                                                                                                                                                                                                               |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>                                                                                                                                                                                                               |
| Orientation         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(TimesMathScreen.Width < TimesMathScreen.Height, Layout.Vertical, Layout.Horizontal)<td style="background-color:#ffcccc; width:50%;">If(Self.Width < Self.Height, Layout.Vertical, Layout.Horizontal)</td></tr></table>                                  |
| Size                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1 + CountRows(App.SizeBreakpoints) - CountIf(App.SizeBreakpoints, Value >= TimesMathScreen.Width)<td style="background-color:#ffcccc; width:50%;">1 + CountRows(App.SizeBreakpoints) - CountIf(App.SizeBreakpoints, Value >= Self.Width)</td></tr></table> |
| Width               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Max(App.Width, App.DesignWidth)<td style="background-color:#ffcccc; width:50%;">Max(App.Width, App.MinScreenWidth)</td></tr></table>                                                                                                                       |

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

## AnswerList

| Property                          | Value         |
| --------------------------------- | ------------- |
| ![listbox](resources/listbox.png) | Type: listbox |

### Data

| Property        | Value                                                                                                                                                                       |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Items           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">MaxTimesTableNumbers<td style="background-color:#ffcccc; width:50%;">ListboxSample</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                        |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                            |
| BorderThickness        | 2                                                                                                                                                                            |
| DisabledSelectionColor | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                        |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                             |
| FocusedBorderThickness | 4                                                                                                                                                                            |
| Font                   | Font.'Open Sans'                                                                                                                                                             |
| FontWeight             | FontWeight.Normal                                                                                                                                                            |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">400<td style="background-color:#ffcccc; width:50%;">135</td></tr></table>                             |
| ItemPaddingLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">RoundDown(AnswerList.Width/2,0)-20<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| PaddingBottom          | 0                                                                                                                                                                            |
| PaddingLeft            | 0                                                                                                                                                                            |
| PaddingRight           | 0                                                                                                                                                                            |
| PaddingTop             | 0                                                                                                                                                                            |
| SelectMultiple         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">35<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                               |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">397<td style="background-color:#ffcccc; width:50%;">328</td></tr></table>                             |
| X                      | 708                                                                                                                                                                          |
| Y                      | 44                                                                                                                                                                           |
| ZIndex                 | 22                                                                                                                                                                           |

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

## Button1\_9

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                                                |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Set(SelectedNumber,First(AnswerList.SelectedItems).Value);Select(HiddenValidationButton_1)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                         |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"My Answer"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

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
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">56<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>   |
| Italic                 | false                                                                                                                                            |
| RadiusBottomLeft       | 10                                                                                                                                               |
| RadiusBottomRight      | 10                                                                                                                                               |
| RadiusTopLeft          | 10                                                                                                                                               |
| RadiusTopRight         | 10                                                                                                                                               |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">24<td style="background-color:#ffcccc; width:50%;">15</td></tr></table>   |
| Strikethrough          | false                                                                                                                                            |
| Underline              | false                                                                                                                                            |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">210<td style="background-color:#ffcccc; width:50%;">160</td></tr></table> |
| X                      | 801                                                                                                                                              |
| Y                      | 458                                                                                                                                              |
| ZIndex                 | 4                                                                                                                                                |

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

## Circle1\_3

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![circle](resources/circle.png) | Type: circle |

### Data

| Property        | Value                                                                                                                                        |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property        | Value                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| DisplayMode     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">246<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">246<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X               | 103                                                                                                                                                         |
| Y               | 23                                                                                                                                                          |
| ZIndex          | 1                                                                                                                                                           |

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

## Circle1\_4

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![circle](resources/circle.png) | Type: circle |

### Data

| Property        | Value                                                                                                                                        |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property        | Value                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| DisplayMode     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">285<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">285<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X               | 396                                                                                                                                                         |
| Y               | 132                                                                                                                                                         |
| ZIndex          | 3                                                                                                                                                           |

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

## Circle1\_5

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![circle](resources/circle.png) | Type: circle |

### Data

| Property        | Value                                                                                                                                        |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property        | Value                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| DisplayMode     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Height          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">246<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Width           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">246<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X               | 103                                                                                                                                                         |
| Y               | 284                                                                                                                                                         |
| ZIndex          | 2                                                                                                                                                           |

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

## HiddenGeneratorButton\_1

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                                                                                        |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Set(MathNumber1,RoundDown(Rand()*5+1,0));Set(MathNumber2,RoundDown(Rand()*10+1,0));Number1_1.Text=Text(MathNumber1);Number2_1.Text=Text(MathNumber2);Number3_1.Text=Text(MathNumber1+MathNumber2);<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                        |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Generate"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

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
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">280<td style="background-color:#ffcccc; width:50%;">160</td></tr></table> |
| X                      | 839                                                                                                                                              |
| Y                      | 304                                                                                                                                              |
| ZIndex                 | 17                                                                                                                                               |

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

## HiddenValidationButton\_1

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                                                                                                                                     |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(SelectedNumber=MathNumber2*MathNumber1,Set(PinkiePosition,PinkiePosition+1);Select(HiddenGeneratorButton_1));If(PinkiePosition=10,Navigate(EatScreen,ScreenTransition.Fade))<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                        |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Validate"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

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
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">280<td style="background-color:#ffcccc; width:50%;">160</td></tr></table> |
| X                      | 839                                                                                                                                              |
| Y                      | 374                                                                                                                                              |
| ZIndex                 | 18                                                                                                                                               |

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

## Image3\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Data

| Property        | Value                                                                                                                                                           |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">TargetItem<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">111<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">111<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 1022                                                                                                                                             |
| Y                      | 529                                                                                                                                              |
| ZIndex                 | 20                                                                                                                                               |

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

## Label2

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property        | Value                                                                                                                                               |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Live            | Live.Off                                                                                                                                            |
| Role            | TextRole.Default                                                                                                                                    |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"X"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                      |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Left                                                                                                                                                                 |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                          |
| BorderThickness        | 0                                                                                                                                                                          |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                           |
| FocusedBorderThickness | 0                                                                                                                                                                          |
| Font                   | Font.'Open Sans'                                                                                                                                                           |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Bold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                             |
| Italic                 | false                                                                                                                                                                      |
| LineHeight             | 1.2                                                                                                                                                                        |
| Overflow               | Overflow.Hidden                                                                                                                                                            |
| PaddingBottom          | 5                                                                                                                                                                          |
| PaddingLeft            | 5                                                                                                                                                                          |
| PaddingRight           | 5                                                                                                                                                                          |
| PaddingTop             | 5                                                                                                                                                                          |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">36<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                             |
| Strikethrough          | false                                                                                                                                                                      |
| Underline              | false                                                                                                                                                                      |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                       |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">51<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                            |
| X                      | 315                                                                                                                                                                        |
| Y                      | 240                                                                                                                                                                        |
| ZIndex                 | 21                                                                                                                                                                         |

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

## Number1\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property        | Value                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Live            | Live.Off                                                                                                                                                    |
| Role            | TextRole.Default                                                                                                                                            |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">MathNumber1<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                            |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table> |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                 |
| FocusedBorderThickness | 0                                                                                                                                                                |
| Font                   | Font.'Open Sans'                                                                                                                                                 |
| FontWeight             | FontWeight.Normal                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">121<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                  |
| Italic                 | false                                                                                                                                                            |
| LineHeight             | 1.2                                                                                                                                                              |
| Overflow               | Overflow.Hidden                                                                                                                                                  |
| PaddingBottom          | 5                                                                                                                                                                |
| PaddingLeft            | 5                                                                                                                                                                |
| PaddingRight           | 5                                                                                                                                                                |
| PaddingTop             | 5                                                                                                                                                                |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                   |
| Strikethrough          | false                                                                                                                                                            |
| Underline              | false                                                                                                                                                            |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">246<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| X                      | 103                                                                                                                                                              |
| Y                      | 79                                                                                                                                                               |
| ZIndex                 | 14                                                                                                                                                               |

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

## Number2\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property        | Value                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Live            | Live.Off                                                                                                                                                    |
| Role            | TextRole.Default                                                                                                                                            |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">MathNumber2<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |
| Tooltip         |                                                                                                                                                             |

### Design

| Property               | Value                                                                                                                                                            |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table> |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                 |
| FocusedBorderThickness | 0                                                                                                                                                                |
| Font                   | Font.'Open Sans'                                                                                                                                                 |
| FontWeight             | FontWeight.Normal                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">114<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                  |
| Italic                 | false                                                                                                                                                            |
| LineHeight             | 1.2                                                                                                                                                              |
| Overflow               | Overflow.Hidden                                                                                                                                                  |
| PaddingBottom          | 5                                                                                                                                                                |
| PaddingLeft            | 5                                                                                                                                                                |
| PaddingRight           | 5                                                                                                                                                                |
| PaddingTop             | 5                                                                                                                                                                |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                   |
| Strikethrough          | false                                                                                                                                                            |
| Underline              | false                                                                                                                                                            |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">246<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| X                      | 103                                                                                                                                                              |
| Y                      | 352                                                                                                                                                              |
| ZIndex                 | 15                                                                                                                                                               |

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

## Number3\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property        | Value                                                                                                                                               |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Live            | Live.Off                                                                                                                                            |
| Role            | TextRole.Default                                                                                                                                    |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"?"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                            |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table> |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                 |
| FocusedBorderThickness | 0                                                                                                                                                                |
| Font                   | Font.'Open Sans'                                                                                                                                                 |
| FontWeight             | FontWeight.Normal                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">197<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                  |
| Italic                 | false                                                                                                                                                            |
| LineHeight             | 1.2                                                                                                                                                              |
| Overflow               | Overflow.Hidden                                                                                                                                                  |
| PaddingBottom          | 5                                                                                                                                                                |
| PaddingLeft            | 5                                                                                                                                                                |
| PaddingRight           | 5                                                                                                                                                                |
| PaddingTop             | 5                                                                                                                                                                |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">96<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                   |
| Strikethrough          | false                                                                                                                                                            |
| Underline              | false                                                                                                                                                            |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">246<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                 |
| X                      | 415                                                                                                                                                              |
| Y                      | 177                                                                                                                                                              |
| ZIndex                 | 16                                                                                                                                                               |

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

## PinkiePie\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Data

| Property        | Value                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Avatar<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">112<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">112<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 14+112\*(PinkiePosition\-1)                                                                                                                      |
| Y                      | 528                                                                                                                                              |
| ZIndex                 | 19                                                                                                                                               |

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
