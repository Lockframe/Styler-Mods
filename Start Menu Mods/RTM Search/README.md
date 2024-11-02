# RTM search theme for Windows 11 Start Menu Styler

A theme aimed to recreate the search bar design Windows 11 had until 23H2.

![Screenshot](screenshot.png)

## Manual installation

The theme can only be imported manually. To do that, follow these steps:

* Open the Windows 11 Start Menu Styler mod in Windhawk.
* Go to the "Advanced" tab.
* Copy the content below to the text box under "Mod settings" and click "Save".

<details>
<summary>Content to import (click to expand)</summary>

```json
{
  "controlStyles[0].target": "StartDocked.SearchBoxToggleButton",
  "controlStyles[0].styles[0]": "Margin=32,1,32,23",
  "controlStyles[0].styles[1]": "Height=40",
  "controlStyles[0].styles[2]": "CornerRadius=4",
  "controlStyles[1].target": "Border#TaskbarSearchBackground",
  "controlStyles[1].styles[4]": "Height=40",
  "controlStyles[1].styles[0]": "CornerRadius=4",
  "controlStyles[1].styles[1]": "Margin=33,33,33,10",
  "controlStyles[1].styles[2]": "BorderBrush:=<SolidColorBrush Color=\"{ThemeResource ControlStrokeColorDefault}\"/>",
  "controlStyles[1].styles[3]": "BorderThickness=1,1,1,0",
  "controlStyles[2].target": "Cortana.UI.Views.RichSearchBoxControl#SearchBoxControl",
  "controlStyles[2].styles[0]": "Margin=33,33,33,10",
  "controlStyles[3].target": "Grid#QueryFormulationRoot",
  "controlStyles[3].styles[0]": "CornerRadius=0,0,12,12",
  "controlStyles[4].target": "StartDocked.SearchBoxToggleButton > Grid > ContentPresenter > TextBlock#PlaceholderText",
  "controlStyles[4].styles[0]": "Margin=0,0,0,1",
  "controlStyles[5].target": "StartDocked.LauncherFrame > Grid#RootGrid > Grid#RootContent > Grid#MainContent > Grid#InnerContent > Rectangle",
  "controlStyles[5].styles[0]": "Visibility=1",
  "controlStyles[6].target": "Cortana.UI.Views.RichSearchBoxControl#SearchBoxControl > Grid#RootGrid",
  "controlStyles[6].styles[0]": "BorderBrush:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight1}\"/>",
  "controlStyles[6].styles[1]": "CornerRadius=4",
  "controlStyles[6].styles[2]": "Margin=0,1,0,0",
  "controlStyles[6].styles[3]": "BorderThickness=0,0,0,2",
  "controlStyles[7].target": "FontIcon#SearchBoxOnTaskbarSearchGlyph",
  "controlStyles[7].styles[0]": "Visibility=0",
  "controlStyles[8].target": "Microsoft.UI.Xaml.Controls.AnimatedIcon#SearchIconPlayer",
  "controlStyles[8].styles[0]": "Visibility=1",
  "controlStyles[9].target": "StartDocked.SearchBoxToggleButton#StartMenuSearchBox > Grid@CommonStates",
  "controlStyles[9].styles[0]": "Background@Checked:=<SolidColorBrush Color=\"{ThemeResource TextFillColorInverse}\" Opacity=\".85\"/>",
  "controlStyles[9].styles[1]": "Background@CheckedPointerOver:=<SolidColorBrush Color=\"{ThemeResource TextFillColorInverse}\" Opacity=\".95\"/>",
  "controlStyles[9].styles[2]": "CornerRadius=4",
  "controlStyles[9].styles[3]": "BorderThickness=1,1,1,0",
  "controlStyles[9].styles[4]": "BorderBrush:=<SolidColorBrush Color=\"{ThemeResource ControlStrokeColorDefault}\"/>",
  "controlStyles[9].styles[5]": "Background@Normal:=<SolidColorBrush Color=\"{ThemeResource ControlFillColorDefault}\"/>",
  "controlStyles[9].styles[6]": "Background@PointerOver:=<SolidColorBrush Color=\"{ThemeResource ControlFillColorSecondary}\"/>",
  "controlStyles[10].target": "StartDocked.SearchBoxToggleButton#StartMenuSearchBox > Grid@CommonStates > Border#BorderElement",
  "controlStyles[10].styles[0]": "BorderThickness@Checked=0,0,0,2",
  "controlStyles[10].styles[1]": "BorderThickness@Normal=0,0,0,1",
  "controlStyles[10].styles[2]": "BorderBrush@Checked:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight1}\"/>",
  "controlStyles[10].styles[3]": "BorderBrush@Normal:=<SolidColorBrush Color=\"{ThemeResource ControlStrokeColorSecondary}\" Opacity=\"1\"/>",
  "controlStyles[10].styles[4]": "BorderBrush@PointerOver:=<SolidColorBrush Color=\"{ThemeResource SurfaceStrokeColorDefault}\" Opacity=\"1\"/>",
  "controlStyles[10].styles[5]": "BorderThickness@PointerOver=0,0,0,1",
  "controlStyles[10].styles[6]": "BorderThickness@CheckedPointerOver=0,0,0,2",
  "controlStyles[10].styles[7]": "BorderBrush@CheckedPointerOver:=<SolidColorBrush Color=\"{ThemeResource SystemAccentColorLight1}\"/>",
  "controlStyles[10].styles[8]": "CornerRadius=4",
  "controlStyles[10].styles[9]": "Margin=-1,0,-1,0",
  "controlStyles[10].styles[10]": "Background=transparent",
  "controlStyles[11].target": "StartDocked.SearchBoxToggleButton#StartMenuSearchBox > Grid@CommonStates > FontIcon > Grid > TextBlock",
  "controlStyles[11].styles[0]": "Foreground@Checked:=<SolidColorBrush Color=\"{ThemeResource FocusStrokeColorOuter}\" Opacity=\".89\"/>",
  "controlStyles[11].styles[1]": "Foreground@Normal:=<SolidColorBrush Color=\"{ThemeResource FocusStrokeColorOuter}\" Opacity=\".89\"/>",
  "controlStyles[11].styles[2]": "Foreground@CheckedPointerOver:=<SolidColorBrush Color=\"{ThemeResource FocusStrokeColorOuter}\" Opacity=\".89\"/>",
  "controlStyles[11].styles[3]": "Foreground@PointerOver:=<SolidColorBrush Color=\"{ThemeResource FocusStrokeColorOuter}\" Opacity=\".89\"/>",
  "controlStyles[11].styles[4]": "Margin=-1,0,0,1",
  "controlStyles[12].target": "Grid#QueryFormulationRoot",
  "controlStyles[12].styles[0]": "Margin=0,0,0,0",
  "controlStyles[13].target": "Grid#WebViewGrid > WebView",
  "controlStyles[13].styles[0]": "Margin=5,-3,8,33",
  "controlStyles[14].target": "Cortana.UI.Views.TaskbarSearchPage > Grid#RootGrid@SearchBoxInputStates > Border#TaskbarSearchBackground",
  "controlStyles[14].styles[0]": "Background:=<SolidColorBrush Color=\"{ThemeResource TextFillColorInverse}\" Opacity=\".85\"/>",
  "controlStyles[15].target": "Image#SearchIconOn",
  "controlStyles[15].styles[0]": "Visibility=1",
  "controlStyles[16].target": "FontIcon#SearchGlyph",
  "controlStyles[16].styles[0]": "Visibility=0",
  "controlStyles[17].target": "Image#SearchIconOff",
  "controlStyles[17].styles[0]": "Visibility=1"
}
```
