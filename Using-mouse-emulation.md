Using mouse emulation
使用鼠标操作
======


OptiKey can be controlled with a mouse as well as directly using an eye tracker (the preferred method).

OptiKey 也可以使用鼠标来进行操作，操作过程与使用眼动仪类似。

If your eye tracker is not yet supported by OptiKey (check [Supported eye trackers](Supported-eye-trackers.md)) then you may still be able to use OptiKey so long as your eye tracker software offers mouse control.

对于 OptiKey 支持的眼动仪（[OptiKey 支持设备清单](Supported-eye-trackers.md)），如果眼动仪支持使用鼠标控制的话，那么也可以使用 OptiKey 操作

**Set up your eye tracker:**

**设置眼动仪**

Setup will depend on which eye tracker you are using. You need to configure your eye tracker software to control the position of the mouse, and make sure it is moving the mouse comfortably and reliably.

眼动仪的设置与具体的产品相关，你可以在眼动仪的软件设计选项中，设置采用鼠标控制，在使用鼠标之前，确人请保鼠标称手好用。

**Set up OptiKey:**

**设置 OptiKey**

If you have changed which device OptiKey is using for input (e.g. to an eye tracker) then you will need to tell OptiKey to listen to your mouse cursor position again...

对 OptiKey 的输入设备进行更改后（如：改为眼动仪），需要重新设置光标位置

1. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab.

1. 打开 OptiKey 的管理控制台 (聚集 OptiKey 后使用 ALT+M) ，选择 “指向和选择（Pointing & Selecting）” 项。

2. Change the "Source" (under "Pointing") to "Mouse Position".

2. 修改 “来源（Source）”（在 “指向（Pointing）” 下）为 “鼠标位置（Mouse Position）”

3. Leave the "Key selection source" and "Point selection source" set to "Fixation" for now.
3. 将 “键选择来源（Key selection source）” 和 "指向选择来源（Point selection source）" 设置为 "固定（Fixation）"。

4. You may want to [slow OptiKey down a little.](Speed-up-&-slow-down.md)
4. 此时可以适当 [调低 OptiKey 响应速度](Speed-up-&-slow-down.md)

5. Click "OK" to save your changes. OptiKey may need to restart, but your changes will be saved.

5. 点击 “OK” 保存修改。OptiKey 可能需要重启，修改的配置会自动保存。

6. When OptiKey starts up again it will be listening to your mouse cursor's position so try moving your head (or whatever your webcam application is tracking). Position the cursor over a key and complete a fixation ("dwell") to make a selection.

6. 当 OptiKey 重新启动，即可响应鼠标光标的位置，试试移动你的头部（或任何网络摄像头应用在跟踪的部位）。将光标位置固定在一个键上，用定位（“停留（dwell）”）来完成选择。

**N.B.** OptiKey will attempt to use your mouse cursor position every time you run it from now on until you change the Pointing source to something else.
**注意：**从现在开始，每次运行OptiKey，它会尝试使用鼠标光标位置直到你修改指向源为其他设置。

**Hiding your cursor:**
**隐藏光标**

If you find that the mouse position is inaccurate and you are being distracted by the cursor, you can hide it in Windows. Keys will still be highlighted when you look at them, and OptiKey will show you an enlarged cursor when you want to use mouse control. This is very similar to using OptiKey directly with your eyetracker, and can make it easier for users who could be distracted by the movements of the cursor.

如果发现鼠标位置不够准确，并且你容易被光标所分散注意力，可以将其隐藏，此时注视按键时，按键仍然会被高亮显示，若使用鼠标控制，OptiKey 会显示一个放大的光标。 这与通过眼动仪使用 OptiKey 操作类类相似，可以避免因光标的移动而分散注意力。

Details of two methods to hide your cursor are discussed here:
[http://www.jholjhaal.com/hide-mouse-cursor-on-windows-with-mouse-pointer-scheme/](http://www.jholjhaal.com/hide-mouse-cursor-on-windows-with-mouse-pointer-scheme/)

两种隐藏光标的方法:[http://www.jholjhaal.com/hide-mouse-cursor-on-windows-with-mouse-pointer-scheme/](http://www.jholjhaal.com/hide-mouse-cursor-on-windows-with-mouse-pointer-scheme/)
