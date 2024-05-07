# UnrealEditorPainter
This project shows how to use the UnrealPainter in the editor. \
It uses the Unreal Scriptable Tools and the Unreal Editor Utility Widgets. \
This is just a demo and only shows the possibilities of UnrealPainter.
# ![demo_paint_01.gif](Assets%2Fdemo_paint_01.gif)
# ![demo_paint_02.gif](Assets%2Fdemo_paint_02.gif)
## Install
Clone the project and Init the Submodule.

```
git clone https://github.com/DimaChaichan/UnrealEditorPainter
cd UnrealEditorPainter
git submodule init
git submodule update
```
Start the Project then.
The Plugins "Scriptable Tools Editor Mode" and "Scriptable Tools Framework" must be active!
# ![demo_plugins.png](Assets%2Fdemo_plugins.png)

## Use Scriptable Tool
With this tool you can paint on static meshes in the editor and save the texture. \
Select Scriptable Tools in the Toolbar.
# ![demo_select.png](Assets%2Fdemo_select.png)
Select a Static mesh. \
Now you can paint. \
To Save the Texture, click the "Save Texture button". Now you can use it as a normal Texture.

## Use Editor Utility Widgets
This tool is an editor utility widget with a viewport. The idea for the viewport instead of from here: https://www.youtube.com/watch?v=pJYIwprcIpI
Unfortunately the viewport does not work properly, i.e. the tool shows what you could do if the viewport would work properly. \
To use the tool, right-click on “EUW_Painter” and then on “Run Editor Utility Widget” \
Now you can start painting. \
There is currently no rotation of the viewports!
# ![demo_run.png](Assets%2Fdemo_run.png)