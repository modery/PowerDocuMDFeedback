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

## CoinScreen

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![screen](resources/screen.png) | Type: screen |

### Behavior

| Property  | Value                                                                                                                                                                                                                                                                                                                 |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnVisible | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ClearCollect( PaymentCoins, { Value: 5, pic: '5cent' }, { Value: 10, pic: '10cent' } );Clear(PaymentCoins); Set( TotalAmount, RoundDown( Rand() * (29 - 3 + 1) + 3, 0 ) ); <td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property            | Value                                                                                                                                                                                                                                                                                                                        |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Height              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Max(App.Height, App.DesignHeight)<td style="background-color:#ffcccc; width:50%;">Max(App.Height, App.MinScreenHeight)</td></tr></table>                                                                                                              |
| ImagePosition       | ImagePosition.Fit                                                                                                                                                                                                                                                                                                            |
| LoadingSpinner      | LoadingSpinner.None                                                                                                                                                                                                                                                                                                          |
| LoadingSpinnerColor | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>                                                                                                                                                                                                          |
| Orientation         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(CoinScreen.Width < CoinScreen.Height, Layout.Vertical, Layout.Horizontal)<td style="background-color:#ffcccc; width:50%;">If(Self.Width < Self.Height, Layout.Vertical, Layout.Horizontal)</td></tr></table>                                       |
| Size                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1 + CountRows(App.SizeBreakpoints) - CountIf(App.SizeBreakpoints, Value >= CoinScreen.Width)<td style="background-color:#ffcccc; width:50%;">1 + CountRows(App.SizeBreakpoints) - CountIf(App.SizeBreakpoints, Value >= Self.Width)</td></tr></table> |
| Width               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Max(App.Width, App.DesignWidth)<td style="background-color:#ffcccc; width:50%;">Max(App.Width, App.MinScreenWidth)</td></tr></table>                                                                                                                  |

### Color Properties

| Property | Value                                                                                                                 |
| -------- | --------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |

### Child & Parent Controls

| Property      | Value                |
| ------------- | -------------------- |
| Child Control | HappyAppleJack       |
| Child Control | Image6               |
| Child Control | Gallery1             |
| Child Control | Image5\_3            |
| Child Control | Image5\_2            |
| Child Control | Image5\_1            |
| Child Control | Image5               |
| Child Control | Label1               |
| Child Control | HiddenGenerateButton |
| Child Control | Button4              |
| Child Control | Button3\_1           |

## Button3\_1

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
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"I'm done! "<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">182<td style="background-color:#ffcccc; width:50%;">160</td></tr></table> |
| X                      | 927                                                                                                                                              |
| Y                      | 553                                                                                                                                              |
| ZIndex                 | 12                                                                                                                                               |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button3\_1.Fill, \-15%)                                                                                     |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(241, 61, 148, 1)</td></tr><tr><td style="background-color:#F13D94"></td></tr></table>  |
| FocusedBorderColor  | Button3\_1.BorderColor                                                                                                |
| HoverBorderColor    | ColorFade(Button3\_1.BorderColor, 20%)                                                                                |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button3\_1.Fill                                                                                                       |
| PressedColor        | Button3\_1.Fill                                                                                                       |
| PressedFill         | Button3\_1.Color                                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |

## Button4

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Sum(PaymentCoins,Value)=TotalAmount,Set(GiveMoneyResult,"Correct"),Set(GiveMoneyResult,"wrong"))<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                                  |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Give to Applejack "<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

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
| X                      | 605                                                                                                                                              |
| Y                      | 553                                                                                                                                              |
| ZIndex                 | 9                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(Button4.Fill, \-15%)                                                                                        |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(255, 195, 96, 1)</td></tr><tr><td style="background-color:#FFC360"></td></tr></table>  |
| FocusedBorderColor  | Button4.BorderColor                                                                                                   |
| HoverBorderColor    | ColorFade(Button4.BorderColor, 20%)                                                                                   |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | Button4.Fill                                                                                                          |
| PressedColor        | Button4.Fill                                                                                                          |
| PressedFill         | Button4.Color                                                                                                         |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |

## Gallery1

| Property                          | Value         |
| --------------------------------- | ------------- |
| ![gallery](resources/gallery.png) | Type: gallery |

### Data

| Property        | Value                                                                                                                                                                     |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Items           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">PaymentCoins<td style="background-color:#ffcccc; width:50%;">CustomGallerySample</td></tr></table> |
| WrapCount       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">1</td></tr></table>                              |

### Design

| Property               | Value                                                                                                                                                                      |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                          |
| DelayItemLoading       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                           |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">285<td style="background-color:#ffcccc; width:50%;">575</td></tr></table>                           |
| Layout                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Layout.Horizontal<td style="background-color:#ffcccc; width:50%;">Layout.Vertical</td></tr></table> |
| LoadingSpinner         | LoadingSpinner.None                                                                                                                                                        |
| LoadingSpinnerColor    | Self.BorderColor                                                                                                                                                           |
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| TemplatePadding        | 0                                                                                                                                                                          |
| TemplateSize           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">160<td style="background-color:#ffcccc; width:50%;">Min(160, Self.Height - 60)</td></tr></table>    |
| Transition             | Transition.None                                                                                                                                                            |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">485<td style="background-color:#ffcccc; width:50%;">640</td></tr></table>                           |
| X                      | 517                                                                                                                                                                        |
| Y                      | 38                                                                                                                                                                         |
| ZIndex                 | 3                                                                                                                                                                          |

### Color Properties

| Property            | Value                                                                                                                |
| ------------------- | -------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>   |
| DisabledBorderColor | Gallery1.BorderColor                                                                                                 |
| DisabledFill        | Gallery1.Fill                                                                                                        |
| Fill                | <table border="0"><tr><td>RGBA(255, 195, 96, 1)</td></tr><tr><td style="background-color:#FFC360"></td></tr></table> |
| FocusedBorderColor  | Self.BorderColor                                                                                                     |
| HoverBorderColor    | Gallery1.BorderColor                                                                                                 |
| HoverFill           | Gallery1.Fill                                                                                                        |
| PressedBorderColor  | Gallery1.BorderColor                                                                                                 |
| PressedFill         | Gallery1.Fill                                                                                                        |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | galleryTemplate1 |
| Child Control  | Image1           |
| Parent Control | CoinScreen       |

## galleryTemplate1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![galleryTemplate](resources/galleryTemplate.png) | Type: galleryTemplate |

### Design

| Property     | Value                                                                                                           |
| ------------ | --------------------------------------------------------------------------------------------------------------- |
| TemplateFill | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table> |

### Color Properties

### Child & Parent Controls

| Property       | Value    |
| -------------- | -------- |
| Parent Control | Gallery1 |

## HappyAppleJack

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Select(HiddenGenerateButton);<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                               |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">happyapplejack<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                          |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                                              |
| BorderThickness        | 0                                                                                                                                                                                              |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                               |
| FocusedBorderThickness | 2                                                                                                                                                                                              |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(GiveMoneyResult="Correct",CoinScreen.Height,1)<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| ImagePosition          | ImagePosition.Fit                                                                                                                                                                              |
| ImageRotation          | ImageRotation.None                                                                                                                                                                             |
| PaddingBottom          | 0                                                                                                                                                                                              |
| PaddingLeft            | 0                                                                                                                                                                                              |
| PaddingRight           | 0                                                                                                                                                                                              |
| PaddingTop             | 0                                                                                                                                                                                              |
| RadiusBottomLeft       | 0                                                                                                                                                                                              |
| RadiusBottomRight      | 0                                                                                                                                                                                              |
| RadiusTopLeft          | 0                                                                                                                                                                                              |
| RadiusTopRight         | 0                                                                                                                                                                                              |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">GiveMoneyResult="Correct"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(GiveMoneyResult="Correct",CoinScreen.Width,1)<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>  |
| X                      | 0                                                                                                                                                                                              |
| Y                      | 0                                                                                                                                                                                              |
| ZIndex                 | 11                                                                                                                                                                                             |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | HappyAppleJack.BorderColor                                                                                            |
| HoverBorderColor    | ColorFade(HappyAppleJack.BorderColor, 20%)                                                                            |
| HoverFill           | ColorFade(HappyAppleJack.Fill, 20%)                                                                                   |
| PressedBorderColor  | ColorFade(HappyAppleJack.BorderColor, \-20%)                                                                          |
| PressedFill         | ColorFade(HappyAppleJack.Fill, \-20%)                                                                                 |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |

## HiddenGenerateButton

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                                                  |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Set(GiveMoneyResult,"");Clear(PaymentCoins);Set(TotalAmount,RoundDown(Rand()*(29-3+1)+3,0));<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                        |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Text            | "Button"                                                                                                                                     |

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
| X                      | 54                                                                                                                                               |
| Y                      | 553                                                                                                                                              |
| ZIndex                 | 2                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | ColorFade(HiddenGenerateButton.Fill, \-15%)                                                                           |
| Color               | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table>   |
| FocusedBorderColor  | HiddenGenerateButton.BorderColor                                                                                      |
| HoverBorderColor    | ColorFade(HiddenGenerateButton.BorderColor, 20%)                                                                      |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table> |
| HoverFill           | ColorFade(RGBA(56, 96, 178, 1), \-20%)                                                                                |
| PressedBorderColor  | HiddenGenerateButton.Fill                                                                                             |
| PressedColor        | HiddenGenerateButton.Fill                                                                                             |
| PressedFill         | HiddenGenerateButton.Color                                                                                            |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |

## Image1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                   |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Remove(PaymentCoins,ThisItem)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                             |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.pic<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">114<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
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
| TabIndex               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">-1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">126<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 18                                                                                                                                               |
| Y                      | 18                                                                                                                                               |
| ZIndex                 | 1                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image1.BorderColor                                                                                                    |
| HoverBorderColor    | ColorFade(Image1.BorderColor, 20%)                                                                                    |
| HoverFill           | ColorFade(Image1.Fill, 20%)                                                                                           |
| PressedBorderColor  | ColorFade(Image1.BorderColor, \-20%)                                                                                  |
| PressedFill         | ColorFade(Image1.Fill, \-20%)                                                                                         |

### Child & Parent Controls

| Property       | Value    |
| -------------- | -------- |
| Parent Control | Gallery1 |

## Image5

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                                  |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Collect(PaymentCoins,{Value:1,pic:'10cent'})<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                         |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'10cent'<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">124<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">132<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 462                                                                                                                                              |
| Y                      | 378                                                                                                                                              |
| ZIndex                 | 4                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image5.BorderColor                                                                                                    |
| HoverBorderColor    | ColorFade(Image5.BorderColor, 20%)                                                                                    |
| HoverFill           | ColorFade(Image5.Fill, 20%)                                                                                           |
| PressedBorderColor  | ColorFade(Image5.BorderColor, \-20%)                                                                                  |
| PressedFill         | ColorFade(Image5.Fill, \-20%)                                                                                         |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |

## Image5\_1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                                  |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Collect(PaymentCoins,{Value:2,pic:'20cent'})<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                         |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'20cent'<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">142<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">152<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 605                                                                                                                                              |
| Y                      | 369                                                                                                                                              |
| ZIndex                 | 5                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image5\_1.BorderColor                                                                                                 |
| HoverBorderColor    | ColorFade(Image5\_1.BorderColor, 20%)                                                                                 |
| HoverFill           | ColorFade(Image5\_1.Fill, 20%)                                                                                        |
| PressedBorderColor  | ColorFade(Image5\_1.BorderColor, \-20%)                                                                               |
| PressedFill         | ColorFade(Image5\_1.Fill, \-20%)                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |

## Image5\_2

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                                  |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Collect(PaymentCoins,{Value:5,pic:'50cent'})<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                         |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'50cent'<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">163<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">174<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 749                                                                                                                                              |
| Y                      | 358                                                                                                                                              |
| ZIndex                 | 6                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image5\_2.BorderColor                                                                                                 |
| HoverBorderColor    | ColorFade(Image5\_2.BorderColor, 20%)                                                                                 |
| HoverFill           | ColorFade(Image5\_2.Fill, 20%)                                                                                        |
| PressedBorderColor  | ColorFade(Image5\_2.BorderColor, \-20%)                                                                               |
| PressedFill         | ColorFade(Image5\_2.Fill, \-20%)                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |

## Image5\_3

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Behavior

| Property | Value                                                                                                                                                                                    |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Collect(PaymentCoins,{Value:10,pic:'1dollar'})<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                          |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Image           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'1dollar'<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 2                                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">170<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">182<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 927                                                                                                                                              |
| Y                      | 354                                                                                                                                              |
| ZIndex                 | 7                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image5\_3.BorderColor                                                                                                 |
| HoverBorderColor    | ColorFade(Image5\_3.BorderColor, 20%)                                                                                 |
| HoverFill           | ColorFade(Image5\_3.Fill, 20%)                                                                                        |
| PressedBorderColor  | ColorFade(Image5\_3.BorderColor, \-20%)                                                                               |
| PressedFill         | ColorFade(Image5\_3.Fill, \-20%)                                                                                      |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |

## Image6

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

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
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">414<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
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
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">414<td style="background-color:#ffcccc; width:50%;">100</td></tr></table> |
| X                      | 36                                                                                                                                               |
| Y                      | 22                                                                                                                                               |
| ZIndex                 | 8                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table> |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Image6.BorderColor                                                                                                    |
| HoverBorderColor    | ColorFade(Image6.BorderColor, 20%)                                                                                    |
| HoverFill           | ColorFade(Image6.Fill, 20%)                                                                                           |
| PressedBorderColor  | ColorFade(Image6.BorderColor, \-20%)                                                                                  |
| PressedFill         | ColorFade(Image6.Fill, \-20%)                                                                                         |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |

## Label1

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property        | Value                                                                                                                                                                                                                     |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ContentLanguage | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                              |
| Live            | Live.Off                                                                                                                                                                                                                  |
| Role            | TextRole.Default                                                                                                                                                                                                          |
| Text            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Concatenate("My apple pie costs $ ",Text(TotalAmount/10,"[$-en-US]#.00"))<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                       |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 0                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 0                                                                                                                                                |
| Font                   | Font.'Open Sans'                                                                                                                                 |
| FontWeight             | FontWeight.Normal                                                                                                                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">136<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>  |
| Italic                 | false                                                                                                                                            |
| LineHeight             | 1.2                                                                                                                                              |
| Overflow               | Overflow.Hidden                                                                                                                                  |
| PaddingBottom          | 5                                                                                                                                                |
| PaddingLeft            | 5                                                                                                                                                |
| PaddingRight           | 5                                                                                                                                                |
| PaddingTop             | 5                                                                                                                                                |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">28<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>   |
| Strikethrough          | false                                                                                                                                            |
| Underline              | false                                                                                                                                            |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">283<td style="background-color:#ffcccc; width:50%;">150</td></tr></table> |
| X                      | 101                                                                                                                                              |
| Y                      | 436                                                                                                                                              |
| ZIndex                 | 1                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table>    |
| Color               | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| DisabledBorderColor | <table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>       |
| FocusedBorderColor  | Label1.BorderColor                                                                                                    |
| HoverBorderColor    | Label1.BorderColor                                                                                                    |
| HoverColor          | Label1.Color                                                                                                          |
| HoverFill           | Label1.Fill                                                                                                           |
| PressedBorderColor  | Label1.BorderColor                                                                                                    |
| PressedColor        | Label1.Color                                                                                                          |
| PressedFill         | Label1.Fill                                                                                                           |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | CoinScreen |
