Pointing and Selecting Settings
定点与选择设置
======


To open the Management Console either right click on OptiKey itself (not the icon in the taskbar) and select to open the management console from the context menu that opens, or with OptiKey selected press 'ALT' and 'M' on your keyboard (physical or on-screen if using a tablet), then select the 'Pointing & Selecting' tab at the top. You can interact with the Management Console using either OptiKey's mouse and keyboard emulation, or a physical mouse and keyboard.

在 Optikey 上按下键盘的“ALT”和“M”按键（物理的或者平板屏幕上的）去打开管理控制台，然后在顶部选择“定点与选择(Pointing & Selecting)”的标签。必须使用物理鼠标和键盘才能访问管理控制台。

![Management Console Pointing and Selecting tab with TheEyeTribe position and selecting source](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Management_Console_Pointing_And_Selecting_EyeTribe_Numbered.png)

<a name="pointing-with-an-eye-tracker">**Pointing with an eye tracker**</a>

<a name="pointing-with-an-eye-tracker">**用眼动仪定点**</a>

1. Source: Which device is providing location data, e.g. the mouse, an eye tracker, etc. In this example the source is TheEyeTribe eye tracker¹.

1. 来源：提供位置数据的设备，比如鼠标、眼动仪等。这个例子中来源就是 TheEyeTribe 眼动仪。

2. Time until point becomess irrelevent (ms): If the source device (e.g. an eye tracker) timestamps the location data, then this setting controls how old a received point can be before it is considered too old to be useful. These "stale" points will be logged for debugging purposes and then discarded.

2. 定点失效的时间（毫秒）：如果源设备（比如一个眼动仪）给位置数据打上了时间戳，这个设定会决定一个接收到的点可以使用多长时间。调试过程中，这些“过时的”点可以被记录下来然后被丢弃掉。

<a name="selection-with-fixations">**Selection with fixations**</a>

<a name="selection-with-fixations">**定位选择**</a>

3. Key selection source: The method used to select a key. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is Fixations.

3. 按键选择的来源：这个方法被用来选择一个按键。可能的方法有定位、键盘按键和鼠标按键。这个例子中来源是定位方法。

4. Key fixation time to lock-on (ms): Specific to 'Key selection source' of 'Fixations', this setting dictates how long you must direct your attention to a key (using whatever 'Source' you have selected, e.g. by looking at a key when using an eye tracking source) before a fixation begins. The lock-on period is designed so that a deliberate pause is required on a key before a fixation begins. Without a 'lock-on' period every key will immediately begin a fixation as you direct your attention around the keyboard, which makes the interface busy and less clear.

4. 锁定按键定位的时间（毫秒）：当“按键选择来源(Key selection source)” 是 “定位(Fixations)”时，这个设定表明在定位开始前，你要注视多长时间在一个按键上（使用你选择的 “来源（Source）”，比如，当使用一个眼动仪时注视一个按键）。在定位开始之前，需要经过一个刻意设计的锁定延迟时间。如果没有这个锁定时间，一旦当你注视到键盘上，按键会立刻起作用，这样会让接口很忙而且不够清晰。

5. Resuming an incomplete key fixation requires a new lock-on: Specific to 'Key selection source' of 'Fixations', this setting dictates whether you need to direct your attention to a key for the lock-on period again when resuming an incomplete selection before the progress continues. **N.B.** An incomplete selection can be discarded during the lock-on period when returning to an incomplete selection.
5. 需要一个新的锁定来恢复一个未完成的按键定位：当 “按键选择来源（Key selection source）” 是 “定位（Fixations）” 时，这个设定表明在恢复一个未完成的定位之前，你是否需要再注视锁定多长时间在一个按键上。注意：在恢复未完成选择的锁定期间，这个选择是可以被丢弃。

6. Key fixation time to complete (ms): Specific to 'Key selection source' of 'Fixations', this setting dictates how long you must direct your attention to a key (using whatever 'Source' you have selected, e.g. by looking at a key when using an eye tracking source) before a fixation completes. A lower number means fixations complete faster and you can type at a more rapid pace, but your likelihood of making unintended selections also increases. A higher number means fixations complete more slowly, restricting your typing pace, but reducing the chance of unintended selections.

6. 完成按键定位的时间（毫秒）：当 “按键选择来源（Key selection source）” 是 “定位（Fixations）” 时，这个设定表明在一个定位完成前，你要注视多长时间在一个按键上（使用你选择的 “来源（Source）”，比如当使用眼动仪时注视一个按键）。数值越小说明完成定位的时间就越快，你就可以更快速地输入，但造成选择错误的机会也就增大了。数值越大说明完成定位的时间就越长，这会限制你的输入速度，但减少了出现选择错误的机会。

7. Incomplete key fixation time to live (ms): Specific to 'Key selection source' of 'Fixations', this setting dictates the period of time to keep an in-progress fixation when that key loses attention, e.g. you direct your attention at the letter "A" until the fixation is 50% complete, at which point you look away to the letter "L" - the fixation on the letter "A" will remain and can be continued for the period of time defined by this setting. If the fixation is not resumed by returning your attention to the "A" key then it will be discarded.
7. 未完成按键定位的使用期限（毫秒）：当 “按键选择来源（Key selection source）” 是 “定位（Fixations）” 时，这个设定表明当目光从按键离开后，这个进行中的定位可以保持多久，比如你注视在一个字母 “A” 上，当定位完成到 50% 时，你开始看字母 “L” —— “A” 字母上的定位还保持着，持续的时间由这个设定决定。如果你的注意力没有返回到按键 “A”，原来的定位就不会恢复，这个按键就会被丢弃掉。

N.B. When your attention returns to an incomplete fixation there will be an initial "lock-on" period again (the length of which is dictated by the 'Key fixation time to lock-on (ms)' setting). The fixation can time out and be discarded during this lock-on period.

注意：当你的目光返回到一个未完成的定位上，还会有一个初始的 “锁定时间”（时间长度由 “锁定按键定位的时间（Key fixation time to lock-on (ms)' setting）” 来决定）。在锁定期间，这个定位可能会因为超时而被丢弃掉。

8. Point selection source: The method used to select a point when simulating a physical mouse (see ['Simulate a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) for more. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is Fixations.
8. 点选择的来源：当模拟一个物理鼠标时，这个方法被用来选择一个点（查看 “[模拟一个物理鼠标](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) ” 获取更多信息）。可能的方法有定位、键盘按键和鼠标按键。这个例子中来源就是定位方法。

9. Point fixation time to lock-on (ms): Specific to 'Point selection source' of 'Fixations', this setting dictates how long you must direct your attention to a point (using whatever 'Source' you have selected, e.g. by looking at a point on the screen when using an eye tracking source) before a fixation begins. The lock-on period is designed so that a deliberate pause is required on an area of the screen before a fixation begins. Without a 'lock-on' period point selections will begin as soon as you direct your attention to any point on the screen, which makes point selection difficult.
9. 锁定定位点的时间（毫秒）：在 “点选择来源（Point selection source）” 是 “定位（Fixations）” 时，这个设定表明在定位开始前，你要注视多长时间在一个点上（通过你选择的 “来源（Source）”，比如使用眼动仪时观看屏幕上一个点）。在开始定位屏幕上的一块区域之前，需要经过一个刻意设计的锁定延迟时间。如果没有一个锁点时间，只要你注视到屏幕上的任一点，点选择就开始了，这让点选择很难操作。

10. Point fixation time to complete (ms): Specific to 'Point selection source' of 'Fixations', this setting dictates how long you must direct your attention to a point (using whatever 'Source' you have selected, e.g. by looking at a key when using an eye tracking source) before a fixation completes. A lower number means fixations complete faster and you can make selections at a more rapid pace, but your likelihood of making unintended selections also increases. A higher number means fixations complete more slowly, restricting your selection pace, but reducing the chance of unintended selections.
10. 定位点的完成时间（毫秒）：在 “点选择来源（Point selection source）” 是 “定位（Fixations）” 时，这个设定表明在定位完成前，你要注视多长时间在一个点上（通过你选择的“来源（Source）”，比如使用眼动仪时观看屏幕上一个点）。数值越小说明完成定位的时间就越快，你就可以更快速地完成选择，但造成选择错误的机会也就增大了。数值越大说明完成定位的时间就越长，会限制你的选择速度，但会减少出现选择错误的机会。

11. Point lock-on radius (pixels): Specific to 'Point selection source' of 'Fixations', this setting dictates the size of the initial 'lock-on' area. Your attention must remain completely inside this area for the lock-on time before a fixation begins. A larger radius results in a larger lock-on area (the area is a circle) making it easier to keep your attention within the bounds and begin a fixation, but reduces the accuracy of your selection. A smaller radius results in a smaller lock-on area making it more challenging to keep your attention within the bounds and begin a fixation, but increasing the accuracy of your selection.
11. 点的锁定半径（像素）：在 “点选择来源（Point selection source）” 是 “定位（Fixations）” 时，这个设定表明锁定区域的初始大小。定位开始前，在锁定这段时间里，你的目光要完全集中在这个区域。半径越大锁定区域（区域是个圆）越大，也越容易将你目光在范围内并开始定位。半径越小锁定区域越小，也越难将你的目光在范围内并开始定位，但这会增加选择的准确性。

12. Point fixation radius (pixels): Specific to 'Point selection source' of 'Fixations', this setting dictates the size of the fixation area (after the initial lock-on). Your attention must remain completely inside this area for the fixation to complete. A larger radius results in a larger fixation area (the area is a circle) making it easier to keep your attention within the bounds and complete the fixation, but more difficult to deliberately break the fixation by directing your attention elsewhere. A smaller radius results in a smaller fixation area making it more challenging to keep your attention within the bounds and complete the fixation, but easer to deliberately break the fixation by directing your attention elsewhere.
12. 点的定位半径（像素）：在 “点选择来源（Point selection source）” 是 “定位（Fixations）” 时，这个设定表明定位区域的大小（初始锁定之后）。你的目光必须完全在这个区域内直到定位完成。半径越大定位区域（区域是个圆）越大，也越难将目光集中到其它地方来故意结束定位。半径越小定位区域越小，也越难将目光集中在范围内并完成定位，但越容易将注意力集中到其它地方来故意结束定位。

13. Selection progress indicator behaviour - Only available if the key or point selection source is 'Fixations', this controls the selection progress animation that is displayed on the key or at the point being selected. You can choose to have a pie chart fill up to show your selection progress, or for a solid circle to shrink (to help draw your eye to the centre of the key if using an eye tracker), or grow.
13. 选择进度指示行为 —— 只有按键或者点选择的来源是 “定位（Fixations）” 时，这个选项才可用，它控制了选择进度动画，将动画显示在选择的按键或点上。你可以选择一个饼图来显示选择的进度，或者通过一个实心圆收缩或增长的方式（如果使用眼动仪可以帮助你的眼球集中到按键的中心）。


<a name="multi-key-selection">**Multi-key selection**</a>

<a name="multi-key-selection">**多键选择**</a>

14. Minimum dwell time on a key to include in capture (ms): When a multi-key selection (see ['Multi-key selection'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#multi-key-selection) for more) is in progress this setting dictates the minimum amount of time that you must direct your attention to each key in order to register your interest in that key. Lower values allow you to complete the multi-key selection more quickly, but increase the chance that you will accidentally register interest in keys you are not actually interested in, resulting in less accurate matches. Higher values increase the amount of time required to complete each multi-key selection, but decrease the chance of registering keys accidentally.
14. 录入按键的最小停留时间（毫秒） ：在一个多键选择（查看“[多键选择](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#multi-key-selection)”获取更多信息）进行时，这个设定表明你在要选择的按键上，你要注视的最小时间。数值越小你可以更快地完成多键选择，但是增加了出错的机会（你只是偶然看了这个按键，并不是真的要选），导致准确性不高。数值越高增加了完成多键选择的时间，但是降低了出错的机会（偶尔看了的按键）。

15. Capture timeout (ms): The maximum duration of a multi-key capture. If a multi-key capture exceeds this amount of time the capture will be discarded.
15. 录入超时（毫秒）：一个多键录入的最长时间。如果一个多键录入超过这个时间，这次录入会被丢弃。

---

<a name="pointing-with-a-mouse">**Pointing with a mouse**</a>

<a name="pointing-with-a-mouse">**用鼠标点**</a>

![Management Console Pointing and Selecting tab with mouse position source](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Management_Console_Pointing_And_Selecting_Mouse_Pointing_Section_Numbered.png)

1. Source: Which device is providing location data, e.g. the mouse, an eye tracker, etc. In this example the source is the mouse.
1. 来源：提供位置数据的设备，比如鼠标、眼动仪等。这个例子中来源是鼠标。

2. Mouse position sample interval (ms): How often the mouse position is sampled. Lower values are more efficient, but result in less accurate location data.
2. 鼠标位置的采样间隔（毫秒）：鼠标位置的采样速率。数值越小越高效，但位置信息越不准确。

3. Time until point becomes irrelevent (ms): As described above.
3. 点失效的时间（毫秒）：前面说明过。

---

<a name="selection-with-a-mouse">**Selection with a mouse**</a>

<a name="selection-with-a-mouse">**用鼠标选择**</a>

![Management Console Pointing and Selecting tab with mouse selection trigger](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Management_Console_Pointing_And_Selecting_Mouse_Button_Trigger_Section_Numbered.png)


1. Key selection source: The method used to select a key. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Mouse Button.
1. 按键选择的来源：这个方法用来选择一个按键。可能的方法有定位、键盘按键和鼠标按键。这个例子中来源是一个鼠标的按键。

2. Selection mouse button: The Mouse Button used to trigger a key selection.
2. 鼠标按键的选择：这个鼠标按键被用来触发一次按键选择。

3. Point selection source: The method used to select a point when simulating a physical mouse (see ['Simulate a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) for more. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Mouse Button.
3. 点选择的来源：当模拟一个物理鼠标时（查看“模拟一个物理鼠标”获取更多信息），这个方法被用来选择一个点。可能的方法有定位、键盘按键和鼠标按键。这个例子中来源是一个鼠标的按键。

4. Selection mouse button: The Mouse Button used to trigger a point selection.
4. 鼠标按键的选择：这个鼠标按键被用来触发一次点选择。

    ![Management Console Pointing and Selecting tab with mouse selection trigger - Multi-key selection section](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Management_Console_Pointing_And_Selecting_Button_Trigger_Multi_Key_Selection_Numbered.png)

5. Stop signal: When a multi-key selection capture has begun by pressing the mouse button, this setting dictates how should that session is ended. Available options are to release the button, or to press the same button again to stop the capture.
5. 停止信号：当按下这个鼠标按键，开始一次多键选择录入时，这个设定表明会话如何结束。可能的选择有释放按键，或者再次按下相同的按键来停止录入。

---

<a name="selection-with-a-keyboard">**Selection with a keyboard**</a>
<a name="selection-with-a-keyboard">**用键盘选择**</a>

![Management Console Pointing and Selecting tab with keyboard selection trigger](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Management_Console_Pointing_And_Selecting_Keyboard_Key_Trigger_Section_Numbered.png)


1. Key selection source: The method used to select a key. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Keyboard Key.
1. 按键选择的来源：这个方法用来选择一个按键。可能的方法有定位、键盘按键和鼠标按键。这个例子中来源是一个键盘的按键。

2. Selection keyboard key: The Keyboard Key used to trigger a key selection.
2. 键盘按键的选择：这个键盘按键被用来触发一次按键选择。

3. Point selection source: The method used to select a point when simulating a physical mouse (see ['Simulate a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) for more. Possible methods are fixations, keyboard keys and mouse buttons. In this example the source is a Keyboard Key.
3. 点选择的来源：当模拟一个物理鼠标时（查看“[模拟物理鼠标](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse) ”获取更多信息），这个方法被用来选择一个点。可能的方法有定位、键盘按键和鼠标按键。这个例子中来源是一个键盘的按键。

4. Selection keyboard key: The Keyboard Key used to trigger a point selection.
4. 键盘按键的选择：这个键盘按键被用来触发一次点选择。

    ![Management Console Pointing and Selecting tab with mouse selection trigger - Multi-key selection section](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Management_Console_Pointing_And_Selecting_Button_Trigger_Multi_Key_Selection_Numbered.png)


5. Stop signal: When a multi-key selection capture has begun by pressing the keyboard key, this setting dictates how should that session is ended. Available options are to release the key, or to press the same key again to stop the capture.
5. 停止信号：当按下这个键盘按键，开始一次多键选择录入时，这个设定表明会话如何结束。可能的选择有释放按键，或者再次按下相同的按键来停止录入。

---

<a name="selection-with-an_eye_tracker_which_supports_processing_levels">**Selection with a tracker which supports different processing levels**</a>

<a name="selection-with-an_eye_tracker_which_supports_processing_levels">**用支持不同处理级别的跟踪设备选择**</a>

![Eye tracker processing levels](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Management_Console_Pointing_And_Selecting_Eye_Tracker_Processing_Level.png)

¹ If you are using an eye tracker which supports a range of processing levels (the amount of smoothing or other processing that will be applied to the information the tracker produces about where you are looking) you can select a level of processing. Currently this works for the Tobii eye trackers which run on the EyeX engine, for example the EyeX tracker itself. A higher amount of processing can result in a more stable selection on the screen (but OptiKey will react very slightly slower as you look around), whilst a lower level of processing can result in a more responsive, but more erratic eye tracking experience.
¹ 如果你使用支持不同处理级别（当观看时，用于平滑和处理跟踪设备产生信息的数量）的眼动仪，你可以选择的处理级别。当前这个工作运行在 EyeX 引擎的 Tobii 眼动仪，比如 EyeX 眼动仪本身。处理级别越高屏幕上的选择就越稳定（但是你查看是，OptiKey 会反应得会比较慢），处理级别越低响应速度越快，眼球跟踪体验也容易出错。
