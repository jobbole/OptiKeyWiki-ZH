Next word prediction
单词联想
======

OptiKey supports the Presage engine, a 3rd party application you can install and use for word completion and next word prediction. It is free and excellent. To use Presage with OptiKey:

OptiKey 支持 Presage 引擎，一个优秀且免费的第三方应用程序，安装后即可在输入完单词后自动进行单词联想，在 OptiKey 中使用 Presage：

1. Install Presage version **0.9.2 32-bit** (specifically "presage-0.9.2~beta20150909-32bit" from [presage-0.9.2~beta20150909-32bit-setup.exe](https://sourceforge.net/projects/presage/files/presage/0.9.2~beta/win32/presage-0.9.2~beta20150909-32bit-setup.exe/download)). **PLEASE DO NOT CHANGE ANY OF THE DEFAULT INSTALLATION OPTIONS - Presage must be installed to the default location and Start menu location**

1. 下载 Presage **0.9.2 32-bit** 版本（下载地址[presage-0.9.2~beta20150909-32bit-setup.exe](https://sourceforge.net/projects/presage/files/presage/0.9.2~beta/win32/presage-0.9.2~beta20150909-32bit-setup.exe/download))）。**注意:不要修改任何的安装选项 - Presage 必须安装在默认目录下，同时必在默认的 "开始" 菜单分类下**

2. Ensure Presage is running (by default it runs automatically and can be seen in the taskbar in the bottom right as "Presage WCF Service"). If Presage is not running then start it manually; on my machine you would run _C:\Program Files (x86)\presage\bin\presage_wcf_service_system_tray.exe_).

2. 确保 Presage 已经在运行（默认情况下，会自动运行，可以在右下方的任务栏中看到 “Presage WCF Service” ，如果 Presage 未运行，需要在 _C:\Program Files (x86)\presage\bin\presage_wcf_service_system_tray.exe_ 手动启动）。

3. If you are using a standard user account, you must run OptiKey as an administrator for presage to work. You may do this by right clicking the shortcut and then clicking 'Run As Administrator'. Alternatively to save the setting, right click the shortcut, click the button "Advanced Properties", and then check 'Run As Administrator'.

3. 如果是用普通用户帐户登录系统的，则必须以管理员身份运行 OptiKey，以便 Presage 正常工作。 通过右键单击快捷方式，单击 “以管理员身份运行(Run As Administrator)” 来启动 OptiKey，也可以先保存设置，然后右击快捷方式，选中 “高级属性(Advanced Properties)” 按钮，然后选用 “以管理员身份运行(Run As Administrator)” 启动 OptiKey。

4. Start OptiKey and open the Management Studio. Select the  Words tab and then change the 'Suggestion Mode' to 'Presage'.

4. 启动 OptiKey 后打开 "管理工具(Management Studio)"，选择 "单词签标(Words tab)"，然后将 "建议模式(Suggestion Mode)" 改为 "Presage"。

5. For best performance we recommend that you then edit two of the default Presage settings. You can do this by manually editting the presage.xml setting file (on my machine this is located at _C:\Program Files (x86)\presage\etc\presage.xml_). Find the "<Selector>" section and change suggestions to 12 and repeat suggestions to yes, i.e.

5. 修改 Presage 的两个默认配置，优化 Presage 性能。 打开 presage.xml 的设置文件（_C:\Program Files (x86)\presage\etc\presage.xml_），找到 “<Selector>” 把 "suggestions" 改为 12，把 "repeat suggestions" 改为 "yes"，即:

```
    <Selector>
        <LOGGER>ERROR</LOGGER>
        <!-- SUGGESTIONS
	     Controls how many suggestions are returned in each prediction.
        -->
        <SUGGESTIONS>11</SUGGESTIONS>
        <!-- REPEAT_SUGGESTIONS
	     Allow the same suggestion to be offered in subsequent
	     predictions, even if no context change has been detected.
        -->
        <REPEAT_SUGGESTIONS>yes</REPEAT_SUGGESTIONS>
        <!-- GREEDY_SUGGESTION_THRESHOLD
	     Select only tokens whose completion length is greater than
	     the specified greedy suggestion threshold.
	     i.e. If this option is set to 2 and the current prefix is
               "cu", then the word "cub" will not offered as a
               suggestion, because the completion's length is only one
               character long. Tokens "curb" or "cube" or "cubicle" or
               "cucumber" will however be offered, because these
               words' completions are at least 2 characters long.
        -->
        <GREEDY_SUGGESTION_THRESHOLD>0</GREEDY_SUGGESTION_THRESHOLD>
    </Selector>
```

You can find out more about Presage here https://sourceforge.net/projects/presage/files/presage/

关于 Presage 的更多信息可以参看官方链接: https://sourceforge.net/projects/presage/files/presage/

N.B. Presage 0.9.1 is also supported.

注意: OptiKey 也支持 Presage 0.9.1 版本。

---

**Using Presage in other languages:**

**其他语言**

Presage supports a few languages by default. The language files are in C:\Program Files (x86)\presage\share\presage (available are en, es and it). The setting is in the config file under:

Presage 默认还支持部分语言，语言文件目录 _C:\Program Files (x86)\presage\share\presage_ （可以看到 en，es 等），语言的配置文件：

    <Predictors>
        <DefaultSmoothedNgramPredictor>
            <DBFILENAME>C:\Program Files (x86)\presage\share\presage\database_en.db</DBFILENAME>
