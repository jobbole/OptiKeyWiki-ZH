Using eye trackers.md
使用眼动仪
======

OptiKey can be controlled with a mouse, but really comes into its own when controlled with an eye tracker. [The list of supported eye tracking devices is available here](https://github.com/JuliusSweetland/OptiKey/wiki/Supported-eye-trackers).

OptiKey 可以使用鼠标来控制，但是通过眼球眼动仪控制才真正体现出它的强大价值。[这里是所支持的眼动仪清单](https://github.com/jobbole/OptiKeyWiki-ZH/wiki/Supported-eye-trackers)。

![TheEyeTribe device setup](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/theeyetribe-physical-setup.png)


1. Connect your tracker and start the tracker's application(s) as required (e.g. for TheEyeTribe you would start the client and server applications).
1. 连接眼动仪并且按要求启动眼动仪的应用程序（例如：使用 TheEyeTribe 的话，你需要启动客户端和服务端应用程序）。

2. Complete any initial setup to get the tracker up and running. Usually this involves getting yourself/your tracker/your screen in the correct position and competing a calibration. Some trackers (such as the Tobii EyeX) store user profiles so you do not need to complete a calibration every time.
2. 完成所有的初始化设置，让眼动仪启动并运行起来。通常这需要让你自己/眼动仪/屏幕处于正确的位置，然后完成校准。有些眼动仪（如Tobii EyeX）会保存用户配置，因此不需要每次都完成校准。

3. Once it's tracking your eyes reliably start OptiKey.
3. 一旦它开始跟踪，你的眼睛就能可靠地启动 OptiKey。

4. If this is the first time you have used your eye tracker with OptiKey you will need to tell OptiKey which device you want to use. Open OptiKey's Management Console (with OptiKey focussed press ALT + M) and select the "Pointing & Selecting" tab.
4. 如果这是你第一次配套使用 OptiKey 和眼球眼动仪，则需要告诉 OptiKey 使用哪个设备。打开 OptiKey 管理控制台（在 OptiKey 中按下 ALT+M），选择 “指向和选择（Pointing & Selecting）” 选项卡。

5. Change the "Source" (under "Pointing") to your tracking device.
5. 修改 “来源（Source）”（在 “指向（Pointing）” 下方）为你的跟踪设备。

6. Leave the "Key selection source" and "Point selection source" set to "Fixation" for now.
6. 将 “键选择来源（Key selection source）” 和 “指向选择来源（Point selection source）” 设置为 “固定（Fixation）"。

7. Click "OK" to save your changes. OptiKey may need to restart, but your changes will be saved.
7. 点击 “OK” 保存修改。OptiKey 可能需要重启，修改的配置会自动保存。

8. When OptiKey starts up again it will be listening to your eye tracker so try looking around rather than using the mouse cursor to make key selections.
8. 当 OptiKey 重新启动，即可处理眼球眼动仪的操作，可以先试下不用鼠标而是用眼动的方式来选择键位。

**N.B.** OptiKey will attempt to use your eye tracking device every time you run it from now on (unless you change the Pointing source back to the mouse). The eye tracking device must be connected, the engine (software) must be running and it must be calibrated and ready to be used **before** OptiKey is started each time.

**注意**：从现在开始，每次运行 OptiKey，它都会尝试使用你的眼动仪（除非你把指向来源改回成了鼠标）。在OptiKey每次启动前，必须保证眼动仪已连接，引擎（软件）已在运行中，并且设备已完成校准准备好了被使用。
