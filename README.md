# HTML Image Preview

**Displays images in an HTML preview for [XYplorer](http://xyplorer.com/index.php).**

This script generates an HTML file to quickly preview images, allows selecting images from this display, and then can perform common XYplorer actions on those images. This exists mostly as an alternative to XYplorer's native preview and thumbnail features with the ability to show animated GIFs.

----------

#### Usage
1. [Download](./HTMLImagePreview.xys?raw=true)
2. Run
3. If the current selection or list pane contains images they will be shown.
4. [Optional] There are some configuration options which can be accessed by loading the script with ` Load 'HTMLImagePreview.xys', '*', 'f';`

#### Requires
+ XYplorer with scripting enabled.

#### Tested On
+ Microsoft Windows 7 Professional SP1 x64
+ XYplorer v15.00.0000

#### Notes
+ Developed in response to this [wish](http://www.xyplorer.com/xyfc/viewtopic.php?f=5&t=13675).
+ Discussion [thread](http://www.xyplorer.com/xyfc/viewtopic.php?f=7&t=13690) in XYplorer's Forums.
+ Developed by [TheQwerty](https://github.com/TheQwerty) - [contact](http://www.xyplorer.com/xyfc/memberlist.php?mode=viewprofile&u=438).

----------

#### Release Notes
+ v 2.2 - 2015-05-18 13:14z
    - Adds ability to rotate previewed images.
    - Adds ability to re-order images via drag'n'drop.
    - Increases number of images which can be returned by preview.
    - Fixes escaping of amperands within image path.
+ v 2.1 - 2015-03-31 17:50z
    - Adds global for specifying items which will be filtered before display.
+ v 2.0 - 2015-03-31 15:00z
    - Adds global for overriding filter configuration.
    - Separates showing preview from the action taken on the checked images.
    - Adds scripts for various actions (selecting, filtering, archiving, etc.).
    - Changes default action from selecting to showing a menu of actions.  
      To restore the old behavior use the *select* script: `Load 'HTMLImagePreview', 'select', 'f';`
    - Changes menu order and access keys.
+ v 1.3 - 2015-03-30 18:00z
    - Fixes problems with escaping quotes and ampersands.
    - Fixes titlebox being too small.
    - Adds global for calling scripts to specify images.
    - Adds option to show current configuration.
    - Adds better commenting/style.
+ v 1.2 - 2015-03-26 17:17z
    - Fixes window size option.
+ v 1.1 - 2015-03-26 14:50z
    - Adds user options.
+ v 1.0 - 2015-03-25 19:00z
    - Initial Release

----------


_This is an unofficial script file for [XYplorer](http://xyplorer.com/index.php) - a powerful file manager for Windows.<br>
It has been released by a group of individuals under the collective organization name [XYplorer-Scripts](https://github.com/XYplorer-Scripts)._
