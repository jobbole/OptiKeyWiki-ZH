OptiKey supports the Presage engine, a 3rd party application you can install and use for word completion and next word prediction. It is free and excellent. To use Presage with OptiKey:

1. Install Presage version **0.9.2 32-bit** (specifically "presage-0.9.2~beta20150909-32bit" from [presage-0.9.2~beta20150909-32bit-setup.exe](https://sourceforge.net/projects/presage/files/presage/0.9.2~beta/win32/presage-0.9.2~beta20150909-32bit-setup.exe/download)). **PLEASE DO NOT CHANGE ANY OF THE DEFAULT INSTALLATION OPTIONS - Presage must be installed to the default location and Start menu location**

2. Ensure Presage is running (by default it runs automatically and can be seen in the taskbar in the bottom right as "Presage WCF Service"). If Presage is not running then start it manually; on my machine you would run _C:\Program Files (x86)\presage\bin\presage_wcf_service_system_tray.exe_).

3. If you are using a standard user account, you must run OptiKey as an administrator for presage to work. You may do this by right clicking the shortcut and then clicking 'Run As Administrator'. Alternatively to save the setting, right click the shortcut, click the button "Advanced Properties", and then check 'Run As Administrator'.

4. Start OptiKey and open the Management Studio. Select the  Words tab and then change the 'Suggestion Mode' to 'Presage'.

5. For best performance we recommend that you then edit two of the default Presage settings. You can do this by manually editting the presage.xml setting file (on my machine this is located at _C:\Program Files (x86)\presage\etc\presage.xml_). Find the "<Selector>" section and change suggestions to 12 and repeat suggestions to yes, i.e.

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

N.B. Presage 0.9.1 is also supported.

---

**Using Presage in other languages:**

Presage supports a few languages by default. The language files are in C:\Program Files (x86)\presage\share\presage (available are en, es and it). The setting is in the config file under:

    <Predictors>
        <DefaultSmoothedNgramPredictor>
            <DBFILENAME>C:\Program Files (x86)\presage\share\presage\database_en.db</DBFILENAME>