![logo](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/icon.png)

![csharp-version](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/csharp-version.png) ![IDE-version](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/IDE-version.png) [![nuget-version](https://img.shields.io/nuget/v/HandyControl.svg)](https://www.nuget.org/packages/HandyControl) [![build-status](https://ci.appveyor.com/api/projects/status/github/NaBian/handycontrol?svg=true)](https://ci.appveyor.com/project/NaBian/handycontrol) [![Join the chat at https://gitter.im/HandyControl/Lobby](https://badges.gitter.im/HandyControl/Lobby.svg)](https://gitter.im/HandyControl/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

# Discussion

![Discussion](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/qq-group.jpg)

# Welcome to HandyControl

## Latest examples

### OutlineText

![OutlineText](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/OutlineText.png)

### Tag

![Tag](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Tag.png)

### ToolBar

![ToolBar](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/ToolBar.png)

### Slider

![Slider](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Slider.png)

### CircleProgressBar

![CircleProgressBar](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/CircleProgressBar.png)

## History publication

### ButtonStyle

![ButtonStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Button.png)

### ToggleButtonStyle

![ToggleButtonStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/ToggleButton.png)

### RadioButtonStyle

![RadioButtonStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/RadioButton.png)

### CheckBoxStyle

![CheckBoxStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/CheckBox.png)

### ListBoxStyle

![ListBoxStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/ListBox.png)

### TreeViewStyle

![TreeViewStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/TreeView.png)

### ListViewStyle

![ListViewStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/ListView.png)

### DataGrid

![DataGrid](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/DataGrid.png)

### Now you can switch to dark theme

![dark theme](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/DarkTheme.png)

### ColorPicker

![ColorPicker](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/ColorPicker.gif)

### Loading

![Loading](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Loading.gif)

### Carousel

![Carousel](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Carousel.gif)

### Pagination

![Pagination](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Pagination.gif)

### Expander

![Expander](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Expander.gif)

### TimeBar

![TimeBar](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/TimeBar.gif)

### ImageBrowser

![ImageBrowser](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/ImageBrowser.gif)

### CompareSlider

![CompareSlider](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/CompareSlider-h.gif)

![CompareSlider](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/CompareSlider-v.gif)

### Growl

![Growl](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Growl.gif)

### AnimationPath

![AnimationPath](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/AnimationPath.gif)

### ProgressBar

![ProgressBar](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/ProgressBar.gif)

### TabControl

![TabControl](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/TabControl.gif)

### TabControlStyle

![TabControlStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/TabControl.png)

### GroupBox

![GroupBox](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/GroupBox.png)

### StepBar

![StepBar](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/StepBar.png)

### GifImage

![GifImage](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/GifImage.gif)

### ContextMenu

![ContextMenu](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/ContextMenu.png)

### Calendar

![Calendar](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Calendar.jpg)

### Clock

![Clock](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Clock.jpg)

### CalendarWithClock

![CalendarWithClock](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/CalendarWithClock.png)

### TextBlock

![TextBlock](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/TextBlock.jpg)

### RichTextBoxStyle

![RichTextBoxStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/RichTextBox.png)

### TextBox

![TextBox](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/TextBox.jpg)

### ComboBox

![ComboBox](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/ComboBox.jpg)

### PasswordBox

![PasswordBox](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/PasswordBox.jpg)

### DataPicker

![DataPicker](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/DataPicker.jpg)

### TimePicker

![TimePicker](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/TimePicker.jpg)

### CirclePanel

![CirclePanel](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/CirclePanel.jpg)

### BorderStyle

![BorderStyle](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/Border.png)

# Usage

Step 1：Add a reference to HandyControl or search for HandyControl on the nuget;  
Step 2：Add code in App.xaml as follows:
```XML
<Application.Resources>
    <ResourceDictionary>
        <ResourceDictionary.MergedDictionaries>
            <ResourceDictionary Source="pack://application:,,,/HandyControl;component/Themes/SkinDefault.xaml"/>
            <ResourceDictionary Source="pack://application:,,,/HandyControl;component/Themes/Theme.xaml"/>
        </ResourceDictionary.MergedDictionaries>
    </ResourceDictionary>
</Application.Resources>
```
Step 3：enjoy coding

# Switching configuration

![Switching configuration](https://raw.githubusercontent.com/NaBian/HandyControl/master/Resources/SwitchConfig.png)