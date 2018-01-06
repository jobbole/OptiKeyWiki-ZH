Speech
发音
======

**How to speak**
**朗读**

1. Make key selections to type some text into the "scratchpad" (the area at the top of the OptiKey keyboard).

1. 利用按键选取，键入一些文本信息到 “提示框（scratchpad）”（ OptiKey 键盘的顶部区域）

2. Select the Speak key (it will turn blue while the speech is being read out):

2. 选取朗读（Speak）键（语音朗读时按键会变蓝）:
    ![Speak key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Speak_Up.png)

3. If you want to stop the in-progress speech at any time select the Speak key again (while it is still blue). This is useful if you accidentally intruct OptiKey to speak before you are ready and the "scratchpad" has a lot of text.

3. 任何时候你想停止进行中的语音，只需要再次选取朗读（Speak）键（此时依然为蓝色）即可。如果 “提示框（scratchpad）” 塞满文本信息却没准备好，又不小心触发了 OptiKey 的朗读操作时，这就显得非常管用。

4. The voice, rate of speech and volume are all changeable from the Management Console (with OptiKey focussed press ALT + M).
4. 语音、语速和音量都可以通过管理控制台（Management Console）（在 OptiKey 下只需按 ALT + M 快捷键）控制。

---

**Voices**
**语音**

OptiKey supports Microsoft SAPI voices, which can be found by installing various Windows languages packs, or by installing any 3rd party SAPI compatible voices. Voices can be selected in the Management Console (with OptiKey focussed press ALT + M). Please google for instructions on how to add new voices as the method varies for each version of Windows.

OptiKey 支持 Microsoft SAPI 语音，可以安装各种 Windows 语言包及任何第三方 SAPI 兼容语音。在管理控制台中选择 "语音(Voices)"（使用OptiKey集中按ALT + M 可以打开管理控制台）。

添加新的语音请自行谷歌了解，主要是各 Windows 版本添加的方法各不相同。

There is a free male English voice "Rich" which has been very kindly donated by a voice actor. See below on this page for details.

英国一位男配音演员免费提供了英文的语音 “Rich”，具体见下文描述。


---

**Specific instructions for difficult to find languages:**
**难找的语言指引:**

*Slovak, Czeck and German*
*斯洛伐克语，捷克语和德语*

Microsoft doesn't seem to have released a Slovak voice for Windows, and trying to use the English voice to read Slovak is pointless. There is a free piece of software called EPOS which comes with a selection of Czech, English, German, and Slovak voices: http://epos.ufe.cz/

微软似乎并没有发布斯洛伐克语的 Windows 语音，斯洛伐克语也不可能用英语来朗读。可以偿试下名为 EPOS 的免费软件，它有捷克语，英语，德语和斯洛伐克语：http://epos.ufe.cz/

Once you've downloaded and installed EPOS open the OptiKey Management Console and select one of the new voices under Sounds -> Speech -> Voice.

下载并安装 EPOS 后，打开 OptiKey 管理控制台，并在 声音(Sounds) ->发音(Speech) ->语音(Voice) 下选择。

Several Czech voices are available (male: machac, bob, and female: violka). There is only one Slovak voice (male: igor).

目前有几个捷克语发音可使用（男：machac，bob，女：violka），斯洛伐克语发音目前仅有一个可用（男：igor）。

You can either stick with igor, or try one of the Czech voices. The pronunciation is similar enough, and the Czech voices are generally better quality. However, they can have problems with certain letters that are not present in Czech, such as ľ or ô, so you may want to avoid them when speaking. You'll also be speaking Slovak with a Czech accent.

 -- info courtesy of @TheGreenAirplane

 你可以使用 igor 语音或尝试任意一个捷克语音，发音是相似的，而捷克的声音通常质量更好。不过，可能会遇到某些捷克语不存在的字母，例如 ľ 或 ô，所以在讲话时可能要避开它们。 你也可以考虑用用捷克发音来朗读斯洛伐克语。

 -- 开自 @TheGreenAirplane

---

**Free UK Male Voice 'Rich'**

**免费的英国男性发音 "Rich" **

A British voice actor called Rich has very kindly created and donated his voice for use with OptiKey. The TTS voice was created using ModelTalker.org (you can read more about [voice banking here](https://github.com/OptiKey/OptiKey/wiki/Voice-banking)).

 英国配音演员 Rich 为 OptiKey 制作了免费语音库，并放在 ModelTalker.org 上供下载使用(具体可以参看[语音库](https://github.com/OptiKey/OptiKey/wiki/Voice-banking))。

To download Rich's voice (British English) log in to [https://www.modeltalker.org/get-your-voice](https://www.modeltalker.org/get-your-voice) with the username **Rich** with password **ModelTalker** (note both are case sensitive).


 登录 [https://www.modeltalker.org/get-your-voice](https://www.modeltalker.org/get-your-voice) 下载 Rich 的语音库（英式英语），用户名 **Rich**、密码 **ModelTalker** (注意大小写)。

-- Thank you Rich!

-- 感谢 Rich


---

**Mary TTS**

**Mary TTS**

MaryTTS is an stand alone, free application that can be used with OptiKey to give you access to more free voices! MaryTTS currently supports German, British and American English, French, Italian, Luxembourgish, Russian, Swedish, Telugu, and Turkish, with more languages in preparation.

MaryTTS 是一个独立的且免费的应用程序，可以与 OptiKey 一起使用，可以获得更多的免费声音！ MaryTTS 目前支持德语，英语，美国英语，法语，意大利语，卢森堡语，俄语，瑞典语，泰卢固语和土耳其语，更多的语言还在制作中。


To use MaryTTS with OptiKey download marytts-5.2.zip (or later) from [http://mary.dfki.de/download/index.html](http://mary.dfki.de/download/index.html) and extract it to anywhere (such as "C:\MaryTTS\marytts-5.2"). Then in Optikey's management console, under the Sounds tab, check Use MaryTTS speech synthesizer and press FIND to navigate to the unpacked marytts-server.bat ("C:\MaryTTS\marytts-5.2\bin\marytts-server.bat" in the example). After Optikey restarts a minimised cmd window will also be started containing the MaryTTS server and the available MaryTTS voices will be listed in the management console in the Sounds tab under MaryTTS voice:Welcome

从 [http://mary.dfki.de/download/index.html](http://mary.dfki.de/download/index.html)  可以下载 marytts-5.2.zip (或更新版本) 为 OptiKey 提供更多的 MaryTTS，将下载的文件解压到任意位置（如："C:\MaryTTS\marytts-5.2"）。之后在 OptiKey 的管理控制器的语音("Sound")标签下，选择 MaryTTS 语音合成器，选择查找（"FIND"）查找到之前解压的 marytts-server.bat 文件（如："C:\MaryTTS\marytts-5.2\bin\marytts-server.bat" ）。在重启 OptiKey 之后，一个包含 MaryTTS 的最小化命令端口将同时启动，此时在 OptiKey 的管理控制器的语音（"Sounds"）标签页下可选择 MaryTTS 语音（"Welcome")

To install more MaryTTS voices run marytts-component-installer.bat ("C:\MaryTTS\marytts-5.2\bin\marytts-component-installer.bat" in the example).

通过执行 marytts-component-installer.bat (如："C:\MaryTTS\marytts-5.2\bin\marytts-component-installer.bat") 可以安装更多的 MaryTTS 语音。

N.B. some users have reported problems where OptiKey cannot automatically start/stop MaryTTS. If you experience this please ensure you have an up to date version of Java installed.

 -- Thank you to William for adding MaryTTS support

 注意：有部分用户反映，有时候 MaryTTS 并不会随 OptiKey 打开/关闭，如果你也遇到这个问题，请确保所使用的 Java 运行环境已更新到最新版本。

-- 感谢 William 为 OptiKey 添加  MaryTTS 支持
