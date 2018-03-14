A simple vs code extension that helps to create/delete #regions quickly.
(i don't recommend to use #region. It's actually an anti-pattern. <strong>Instead of using #region, refactor your class or method.</strong>)

Download from Visual Studio Marketplace;
https://marketplace.visualstudio.com/items?itemName=suadev.csharp-region-manager

## Features

* Select some piece of code and use (ctrl+r, ctrl+e), type your region name and press enter.

* Or select some piece of code, press F1 and type "Move into #region".

* To remove region, click the line that contains '#region' and use (ctrl+r, ctrl+e). See the screencast below;

* To remove all #regions in the active document, press F1 and type "Remove all #regions" and press enter.

<img src= "https://raw.githubusercontent.com/suadev/csharp-region-manager/master/screencast.gif" />
  
## Todo list

* <strike>Collapse and beautify the region after created it</strike>
* <strile>Add "Remove all #regions" feature</strike>
* Remove also empty lines after removing '#region' and '#endregion' lines.
