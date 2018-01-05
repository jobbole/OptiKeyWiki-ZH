Cannot open Management Console
无法打开管理控制台
======

**Two things need to happen for the Management Console to open:**
**打开管理控制台需要先做以下两件事：**

1. OptiKey must have focus - it will be highlighted on the taskbar when it has focus, but if you are unsure just click on OptiKey to focus it.
2. Press the 'ALT' key and the 'M' key at the same time - to do this hold down 'ALT' and then press 'M' once.
If the console is still not opening then check that you do not have any modifier keys pressed/locked down as they will interfere with you pressing ALT + M. Release any down modifier keys (Shift, Ctrl, Win, or Alt). More info on modifier keys can be found on the ['Simulate a physical keyboard' page](https://github.com/JuliusSweetland/OptiKey/wiki/Simulate-a-keyboard).

1. 首先激活 OptiKey ，当 OptiKey 被激活时，在任务栏上高亮显示，但是如果你不确定，只需要点击 OptiKey 来激活。
2. 同时按住 “ ALT ” 和 “ M ” 键打开控制台。

如果控制台没有打开，检查是否有其他的按键已经处理在按下状态，这些键会影响控制台激活热键输入，需先释放这些按键，比如 Shift, Ctrl, Win 或者 Alt 等。

更多关于按键输入信息可以参考 “ [Simulate a physical keyboard （模拟外置键盘）](https://github.com/JuliusSweetland/OptiKey/wiki/Simulate-a-keyboard) ” 页面。

---

**Alternatively use the right click context menu:**
**通过右击菜单栏打开控制台**

If you have OptiKey v2.2.3 (or later) you can right click anywhere ON OptiKey (NOT on the icon in the taskbar) and select 'Open Management Console'.

如果当前的 OptiKey 为 v2.2.3(或更高版本），可以通过在 OptiKey 状态栏上右击，在弹出现的菜单上选中 'Open Management Console' 即可打开控制台。

---

**Problem with the latest version of the Tobii EyeX software:**
**最新版本中 Tobii Eyex 的软件问题**

If you are using a Tobii tracker with EyeX software version 2.0.2.219 (or later) then the ALT key may change which application is focussed as the EyeX software has a built in window selection action ("Mouse Warp") which interferes with the Management Console shortcut (ALT+M). There are 2 possible work arounds;

如果你使用了 Tobii 眼动仪的 EysX 软件 2.0.2.219(或更高版本) , ALT 键可能被 EysX 更改为窗口选择动作("Mouse Warp")，这个会导致控制台的快捷键(ALT+M)不生效，这个问题有两个解决方法：

1. Disable "Mouse Warp" and ensure the "Mouse warp on click" and "Mouse clone" both have their keys set to "No Key". You might have to reset the EyeX settings (from Settings -> About) and reboot your computer for these settings to correctly take effect.

2. If you require "Mouse Warp" to be on then make sure you are looking at the keyboard, or at OptiKey when the ALT key is pressed as part of the ALT+M shortcut. This will make sure that OptiKey keeps focus and the shortcut works correctly.

1. 禁用 "Mouse Warp" 功能，注意 "Mouse warp on click" 与 "Mouse clone" 这两个功能都要禁用，确认没有绑定任何快捷键。此时最好重置下 EyeX 的设置（在 Setting->About 菜单下)，并重启电脑以确保配置生效。
2. 如果想要保留 "Mouse Warp" 设置，那么在输入 ALT+M 时需要确保目光是盯着软键盘，或都 OptiKey 软件当前处于激活状态。只要在 OptiKey 处理激活状态，ALT+M 的快捷键才能正常生效。


