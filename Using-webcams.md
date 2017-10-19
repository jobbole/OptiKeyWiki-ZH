Using webcams
使用网络摄像头    //谭霓  翻译

OptiKey can be controlled with a mouse, or an eye tracker (the preferred method), but it is also possible to use a standard webcam. There are a number of free applications which can use your webcam to track your head movements and translate those into movements of your mouse cursor on screen. As OptiKey can be controlled using the cursor position this means you can control OptiKey using head movements captured via your webcam. This method is a very different experience from using an eye tracking device, but can be very effective.
OptiKey可以用鼠标或者眼球跟踪器（推荐）来控制，但是使用标准的网络摄像头也同样可以。已经有非常多免费应用支持使用网络摄像头跟踪头部运动，并将这些运动转换成屏幕上光标的移动。既然可以通过光标位置控制OptiKey，这就意味着你可以利用网络摄像头捕捉头部运动来控制OptiKey。该方法与使用眼动仪的体验非常不同，不过效率很高。

These applications should all work with OptiKey:
以下这些应用都应支持OptiKey：
* [Enable Viacam](http://eviacam.sourceforge.net/index.php) - free and open source
* [Camera Mouse](http://www.cameramouse.org/) - free - [click here for a demo video](https://www.youtube.com/watch?v=BqHeZAkjTJs)
* [Open Gazer](http://www.inference.phy.cam.ac.uk/opengazer/) - free and open source

* [Enable Viacam](http://eviacam.sourceforge.net/index.php) —— 免费且开源
* [Camera Mouse](http://www.cameramouse.org/) —— 免费
* [Open Gazer](http://www.inference.phy.cam.ac.uk/opengazer/) —— 免费且开源

*You could also try any other solution (hardware or software) which can control the mouse position effectively, e.g. the [Quha Zono](http://www.quha.com/products-2/zono/), although hardware solution like these can be expensive.*
*你也可以尝试其他能有效控制鼠标位置的方案（硬件或软件），例如[Quha Zono](http://www.quha.com/products-2/zono/)，尽管类似的硬件解决方案会很贵。*

1. Start whichever application you have chosen to control your cursor position via your webcam, e.g. 'Enable Viacam'. Configure it and make sure it is moving the mouse comfortably and reliably.
1. 不管你所选择的是哪个应用来通过网络摄像头控制光标位置，比如‘Enable Viacam’，启动它，完成配置，确保它可以轻松可靠地移动鼠标。

2. If you have changed which device OptiKey is using for input (e.g. to an eye tracker) then you will need to tell OptiKey to listen to your mouse cursor position again...
2. 如果你修改了OptiKey的输入设备（如眼球跟踪器），那么需要再次告诉OptiKey听从鼠标光标位置......

3. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab.
3. 打开OptiKey的管理控制台（在OptiKey界面，按下键盘上的‘ALT’和‘M’），然后选择“指向和选择（Pointing & Selecting）”选项卡。

4. Change the "Source" (under "Pointing") to "Mouse Position".
4. 修改“源（Source）”（在“指向（Pointing）”）为“鼠标位置（Mouse Position）”。

5. Leave the "Key selection source" and "Point selection source" set to "Fixation" for now.
5. 暂时保持“按键选择来源（Key selection source）”和“点选择来源（Point selection source）”的设置为“固定（Fixation）”。

6. You may want to [slow OptiKey down a little.](https://github.com/JuliusSweetland/OptiKey/wiki/Speed-up-&-slow-down)
6. 或许你希望让OptiKey的[反应慢一点](https://github.com/JuliusSweetland/OptiKey/wiki/Speed-up-&-slow-down)

7. Click "OK" to save your changes. OptiKey may need to restart, but your changes will be saved.
7. 点击“OK”保存修改。OptiKey可能需要重启，但是你的修改会被保存。

8. When OptiKey starts up again it will be listening to your mouse cursor's position so try moving your head (or whatever your webcam application is tracking). Position the cursor over a key and complete a fixation ("dwell") to make a selection.
8. 当OptiKey重启后，它会听从鼠标光标的位置，试试移动你的头部（或任何网络摄像头应用在跟踪的部位）。将光标位置固定在一个键上，用固定法（“停留（dwell）”）来完成选择。

**N.B.** OptiKey will attempt to use your mouse cursor position every time you run it from now on until you change the Pointing source to something else.
**注意：**从现在开始，每次运行OptiKey，它会尝试使用鼠标光标位置直到你修改指向源为其他设置。
