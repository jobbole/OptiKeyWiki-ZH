Speed up and slow down
调整速度
======


**Slowing everything down**
**降低速度**

If you are finding OptiKey difficult to control because it is reacting too quickly (e.g. selections are too sensitive) then the main settings to change are:

如果发现 OptiKey 难以控制，可能是它反应太快（例如选择太敏感），那么需要尝试调整以下设置：

1. If you are using the selection source of 'Fixations' (also known as "dwell") then you can increase the time it takes to complete a fixation (e.g. to 1.5 to 2 seconds). You can also increase the "lock-on" time which will require you to direct your attention to each key more deliberately before the fixation starts. Lastly if you are finding that your in-progress fixations are being discarded too quickly as your attention briefly moves elsewhere then you can increase the incomplete key fixation time to live setting. *See [Pointing & Selecting settings](https://github.com/JuliusSweetland/OptiKey/wiki/Pointing-&-selecting-settings) for more on these settings.*

1. 如果你正在使用定位（"Fixations"，或叫"dwell") 作为选择来源，你可以尝试调长完成选择所需要的注视时间（如，将 1.5秒调成 2秒）。或者也可以通过增加锁定时间（"lock-on"）时间，这要你在注视开始之前选择按键时得要更加刻意。最后，在注视过程中一旦你的目光稍微移动，注视就停上了，那么你需要根据实际情况调长 “注视完成时间”（incomplete key fixation time）。 *具体查看 [定点与选择设置](https://github.com/JuliusSweetland/OptiKey/wiki/Pointing-&-selecting-settings) 章节*

2. If your multi-key selections are resulting in poor word suggestions then it may be that letters that you mistakenly direct your attention to are being included in the matching process. You can increase the 'minimum dwell time on a key to include in a capture' which means that you will have to direct your attention to each key within the multi-key selection for longer, which will reduce the chance of accidentally including letters you do not intend to include. *See [Pointing & Selecting settings](https://github.com/JuliusSweetland/OptiKey/wiki/Pointing-&-selecting-settings) for more on this setting.*

2. 如果多键选择功能所提供的单词联想效果不好，可能是由于其在联想过程中对注视的单元出现误匹配，你可以通过增长“最短注留时间”配置（“minimum dwell time on a key to include in a capture”），之后在多键选择时，需要通过更长时间的注视进行键选择，这样就可以避免出现意外的误匹配。*具体查看 [定点与选择设置](https://github.com/JuliusSweetland/OptiKey/wiki/Pointing-&-selecting-settings) 章节*

---

**Speeding everything up**
**提升速度**

If you are finding OptiKey too slow because it is reacting too slowly (e.g. selections are taking too long) then the main settings to change are:

如果发现 OptiKey 的输入速度太慢，原因是 OptiKey 的反映速度慢（如：选择的时间太长），那么需要尝试调整以下设置：

1. If you are using the selection source of 'Fixations' (also known as "dwell") then you can decrease the time it takes to complete a fixation (e.g. 0.8 seconds). You can also decrease the "lock-on" time which will require you to direct your attention to each key for less time before the fixation starts. Lastly if you are finding that in-progress fixations that you do not intend are hanging around for too long then you can decrease the incomplete key fixation time to live setting. *See [Pointing & Selecting settings](https://github.com/JuliusSweetland/OptiKey/wiki/Pointing-&-selecting-settings) for more on these settings.*

1. 如果你正在使用定位（"Fixations"，或叫"dwell") 作为选择来源，你可以尝试调短完成选择所需要的注视时间（如，0.8 秒）。或者也可以通过减少锁定时间（"lock-on"）时间，这要你在注视开始之前选择按键时得要更加刻意。最后，在注视选择过程需要保持较长的目光凝视才能选中按键，那么你需要根据实际情况调短 “注视完成时间”（incomplete key fixation time）。 *具体查看 [定点与选择设置](https://github.com/JuliusSweetland/OptiKey/wiki/Pointing-&-selecting-settings) 章节*

2. If your multi-key selections are resulting in poor word matches it may be that letters that you intend to include are being ignored because the threshold to register a letter is too high. You can decrease the 'minimum dwell time on a key to include in a capture' which means that you will have to direct your attention to each key within the multi-key selection for less time before it will be included in the matching process. *See [Pointing & Selecting settings](https://github.com/JuliusSweetland/OptiKey/wiki/Pointing-&-selecting-settings) for more on this settings.*

2. 如果多键选择功能所提供的单词联想效果不好，如出现你想选中的按键实际并未被选中，你可以通过减少 “最短注留时间”（“minimum dwell time on a key to include in a capture”），之后在多键选择时，只需要较短的注视时间进行键选择，这样就可以避免出现漏匹配的情况。*具体查看 [定点与选择设置](https://github.com/JuliusSweetland/OptiKey/wiki/Pointing-&-selecting-settings) 章节*

3. If there is a noticeable delay when generating multi-key selection suggestions, or word auto-complete suggestions then you can reduce the 'maximum number of dictionary matches' setting, which may speed things up. You can also turn off auto-complete suggestions. *See [Word settings](https://github.com/JuliusSweetland/OptiKey/wiki/Word-settings) for more on this setting.*

3. 如果在生成多键选择联想或单词自动联想时出现明显的延迟，则可以减少 “字典匹配的最大数量”（“maximum number of dictionary matches”）设置，这可以加快联想速度，当然你可也可以关闭自动联想。*具体查看 [单词设置](https://github.com/JuliusSweetland/OptiKey/wiki/Word-settings) for more on this setting.*

*If you are experiencing performance problems then it would be very helpful if you could email me with some details and I can attempt to fix the issue: [optikeyfeedback@gmail.com](mailto:optikeyfeedback@gmail.com)*

*如果您遇到性能相关的问题，那么如果您可以将相关信息通过电子邮件发送给我 [optikeyfeedback@gmail.com](mailto:optikeyfeedback@gmail.com)，以使我及时解决问题*
