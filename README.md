# How-to-customize-the-dropdowns-width-in-.NET-MAUI-ComboBox-SfComboBox
This repository contains a sample demonstrating of customizing the dropdown's width in .NET MAUI ComboBox.
## DropdownWidth support in .NET MAUI ComboBox (SfComboBox)
 We can change the dropdown's width in SfComboBox by changing the DropdownWidth value.This DropdownWidth property allows to set a specific width for the dropdown list, ensuring that it fits the design requirements and improves the user experience.

The following code example illustrate how to set DropdownWidth in SfComboBox.

**XAML**
```
<editors:SfComboBox  WidthRequest="200" 
                          HeightRequest = "40"
                          DropdownWidth = "250">
                <editors:SfComboBox.ItemsSource>
                    <x:Array Type="{x:Type x:String}">
                        <x:String>Telegram</x:String>
                        <x:String>Televzr</x:String>
                        <x:String>Tik Tok</x:String>
                        <x:String>Tout</x:String>
                        <x:String>Tumblr</x:String>
                        <x:String>Twitter</x:String>
                    </x:Array>
                </editors:SfComboBox.ItemsSource>
            </editors:SfComboBox>   

```