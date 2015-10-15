#Using eye trackers.md
#使用眼球跟踪器 // 谭霓 翻译 <br> 
OptiKey can be controlled with a mouse, but really comes into its own when controlled with an eye tracker. The list of supported eye tracking devices is available here.<br> 
OptiKey可以使用鼠标来控制，但是通过眼球跟踪器控制才真正体现出它的强大价值。[这里是所支持的眼球跟踪设备清单](https://github.com/JuliusSweetland/OptiKey/wiki/Supported-eye-trackers)。<br> 
![](https://camo.githubusercontent.com/9f2b331137e09ebd679cc3d4bdfc80a1e56c7eeb/687474703a2f2f6a756c69757373776565746c616e642e6769746875622e696f2f4f7074694b65792f696d616765732f74686565796574726962652d706879736963616c2d73657475702e706e67)<br>
1.Connect your tracker and start the tracker's application(s) as required (e.g. for TheEyeTribe you would start the client and server applications).<br> 
1.连接跟踪器并且按要求启动跟踪器的应用程序（例如：使用TheEyeTribe的话，你需要启动客户端和服务端应用程序）。

2.Complete any initial setup to get the tracker up and running. Usually this involves getting yourself/your tracker/your screen in the correct position and competing a calibration. Some trackers (such as the Tobii EyeX) store user profiles so you do not need to complete a calibration every time.<br> 
2.完成所有的初始化设置，让跟踪器启动并运行起来。通常这需要让你自己/跟踪器/屏幕处于正确的位置，然后完成校准。有些跟踪器（如Tobii EyeX）会保存用户配置，因此不需要每次都完成校准。

3.Once it's tracking your eyes reliably start OptiKey.<br> 
3.一旦它开始跟踪，你的眼睛能可靠地启动OptiKey。

4.If this is the first time you have used your eye tracker with OptiKey you will need to tell OptiKey which device you want to use. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab.<br> 
4.如果这是你第一次配套使用OptiKey和眼球跟踪器，需要告诉OptiKey哪个是要用的设备。打开OptiKey管理控制台（在OptiKey中按下ALT+M），选择"Pointing & Selecting（指向和选择）"选项卡。

5.Change the "Source" (under "Pointing") to your tracking device.<br> 
5.修改“Source（来源）”（在“Pointing”下方）为你的跟踪设备。

6.Leave the "Key selection source" and "Point selection source" set to "Fixation" for now).<br> 
6.暂时保留“Key selection source（键选择来源）”和"Point selection source（指向选择来源）"设置为"Fixation（固定）"。

7.Click "OK" to save your changes. OptiKey may need to restart, but your changes will be saved.<br> 
7.点击“OK”保存修改。OptiKey可能需要重启，但是你的修改会被保存。

8.When OptiKey starts up again it will be listening to your eye tracker so try looking around rather than using the mouse cursor to make key selections.<br> 
8.当OptiKey重新启动，它会听从你的眼球跟踪器指挥，所以试下到处看看，而不是使用鼠标来选择键位。

N.B. OptiKey will attempt to use your eye tracking device every time you run it from now on (unless you change the Pointing source back to the mouse). The eye tracking device must be connected, the engine (software) must be running and it must be calibrated and ready to be used before OptiKey is started each time.<br> 
注意：从现在开始，每次你运行OptiKey，它都会尝试使用你的眼球跟踪设备（除非你把指向来源改回成了鼠标）。在OptiKey每次启动前，必须保证眼球跟踪设备已连接，引擎（软件）已在运行中，并且设备已完成校准准备好了被使用。

>To collaborate, ask a question, request a feature, or get help with an issue that is not addressed here please contact me via email optikeyfeedback@gmail.com, or on twitter @OptiKey_Julius <br> 
想要合作、提问、寻求新功能，或者寻求帮助，请邮件联系我 optikeyfeedback@gmail.com, 或者在 Twitter 上 @OptiKey_Julius。
