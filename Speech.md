**How to speak**

1. Make key selections to type some text into the "scratchpad" (the area at the top of the OptiKey keyboard).

2. Select the Speak key (it will turn blue while the speech is being read out):

    ![Speak key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Speak_Up.png)

3. If you want to stop the in-progress speech at any time select the Speak key again (while it is still blue). This is useful if you accidentally intruct OptiKey to speak before you are ready and the "scratchpad" has a lot of text.

4. The voice, rate of speech and volume are all changeable from the Management Console (with OptiKey focussed press ALT + M). 

---

**Voices**

OptiKey supports Microsoft SAPI voices, which can be found by installing various Windows languages packs, or by installing any 3rd party SAPI compatible voices. Voices can be selected in the Management Console (with OptiKey focussed press ALT + M). Please google for instructions on how to add new voices as the method varies for each version of Windows.

There is a free male English voice "Rich" which has been very kindly donated by a voice actor. See below on this page for details.

---

**Specific instructions for difficult to find languages:**

*Slovak, Czeck and German*

Microsoft doesn't seem to have released a Slovak voice for Windows, and trying to use the English voice to read Slovak is pointless. There is a free piece of software called EPOS which comes with a selection of Czech, English, German, and Slovak voices: http://epos.ufe.cz/

Once you've downloaded and installed EPOS open the OptiKey Management Console and select one of the new voices under Sounds -> Speech -> Voice.

Several Czech voices are available (male: machac, bob, and female: violka). There is only one Slovak voice (male: igor).
You can either stick with igor, or try one of the Czech voices. The pronunciation is similar enough, and the Czech voices are generally better quality. However, they can have problems with certain letters that are not present in Czech, such as ľ or ô, so you may want to avoid them when speaking. You'll also be speaking Slovak with a Czech accent.

 -- info courtesy of @TheGreenAirplane

---

**Free UK Male Voice 'Rich'**

A British voice actor called Rich has very kindly created and donated his voice for use with OptiKey. The TTS voice was created using ModelTalker.org (you can read more about [voice banking here](https://github.com/OptiKey/OptiKey/wiki/Voice-banking)).

To download Rich's voice (British English) log in to [https://www.modeltalker.org/get-your-voice](https://www.modeltalker.org/get-your-voice) with the username **Rich** with password **ModelTalker** (note both are case sensitive).

 -- Thank you Rich!

---

**Mary TTS**

MaryTTS is an stand alone, free application that can be used with OptiKey to give you access to more free voices! MaryTTS currently supports German, British and American English, French, Italian, Luxembourgish, Russian, Swedish, Telugu, and Turkish, with more languages in preparation.

To use MaryTTS with OptiKey download marytts-5.2.zip (or later) from [http://mary.dfki.de/download/index.html](http://mary.dfki.de/download/index.html) and extract it to anywhere (such as "C:\MaryTTS\marytts-5.2"). Then in Optikey's management console, under the Sounds tab, check Use MaryTTS speech synthesizer and press FIND to navigate to the unpacked marytts-server.bat ("C:\MaryTTS\marytts-5.2\bin\marytts-server.bat" in the example). After Optikey restarts a minimised cmd window will also be started containing the MaryTTS server and the available MaryTTS voices will be listed in the management console in the Sounds tab under MaryTTS voice:Welcome

To install more MaryTTS voices run marytts-component-installer.bat ("C:\MaryTTS\marytts-5.2\bin\marytts-component-installer.bat" in the example).

N.B. some users have reported problems where OptiKey cannot automatically start/stop MaryTTS. If you experience this please ensure you have an up to date version of Java installed.

 -- Thank you to William for adding MaryTTS support