Simulate a keyboard
模拟键盘
======

OptiKey is always simulating keystrokes (i.e. outputting what you type as if you are using a keyboard) , unless you are in the "Conversation" keyboard. Key-stroke simulation works like this:

OptiKey 除了在“对话（Conversation）” 模式下有些特殊外，其原理就是模拟按键键入（比方说，键入什么就输出什么，和你用外置键盘时一样），键盘键入模拟的过程是这样的：

1. Focus another application where you would like to begin typing, e.g. you want to type a letter into Microsoft Word, or an email into Gmail. You can focus the other application by using a physical mouse to select it and bring it to the foreground, or use OptiKey to simulate the mouse selection (see ['Simulating a physical mouse'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#simulate-a-physical-mouse)).

1.  注视你想开始输入的应用，比如你想键入字母到微软的 Word，又或者在 Gmail 里写封邮件。你也可以用鼠标选中应用程序，将其激话到前台，或者用 OptiKey 模拟鼠标选中（详情请参看 ['模拟鼠标'](https://github.com/jobbole/OptiKeyWiki-ZH/blob/master/%E6%A8%A1%E6%8B%9F%E9%BC%A0%E6%A0%87.md)）。

2. Select keys in OptiKey to type letters and words as usual. As you make each key selection it will appear in both the scratchpad and your selected application. The BackOne and BackMany keys can be used to correct any mistakes (introduced in the ['Type your first word'](https://github.com/JuliusSweetland/OptiKey/wiki/User-Guide#type-your-first-word) section).

2. 通过选中 OptiKey 中的按键来键入字母和单词。当你选取对应的按键，它会同时出现在提示框（scratchpad）和你选中的应用中。利用回删键（BackOne）和清空键（BackMany）可以删除错误（详情请参看 ['Type your first word'](https://github.com/jobbole/OptiKeyWiki-ZH/blob/master/Type%20your%20first%20word.md)）。

![Simulating a physical keyboard to type into Microsoft Word](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Typing_Into_Word.png)

Along the bottom row of the keyboard you will notice a number of "modifier" keys, for example the Shift, Ctrl, Win and Alt keys:

键盘最后一行为 “修饰（modifier）” 按键，例如 Shift，Ctrl，Win 和 Alt 等。

![Shift key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Shift_Up.png)
![Ctrl key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Ctrl_Up.png)
![Win key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Win_Up.png)
![Alt key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Alt_Up.png)

These work in exactly the same way as they do on a physical keyboard, and can be combined with other keys by holding them down. Try selecting one of them and you'll notice that it cycles through 3 states; UP, DOWN, and LOCKED DOWN, before returning to UP. For example, the Shift key progresses like this:

这些按键的效果和外置键盘上的完全一样，同样能和其他按键一起按下构成组合键。在选取其中某个键后，在恢复到未选取（UP）状态以前，它会遍历（cycles）三个状态；未选取（UP），选取（DOWN），和锁住（LOCKED DOWN）。例如，Shift  键处理过程如下：

![Shift key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Shift_Up.png)
 ⇨
![Shift key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Shift_Down.png)
 ⇨
![Shift key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Shift_Locked_Down.png)
 ⇨
![Shift key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Shift_Up.png)
etc...

This makes it easy to press or lock down a number of keys together. For example, select Ctrl to press it down, and then press the "P" key to send the "Print" command to the active application. The Ctrl key will be automatically released after you select the "P" key, unless it is in the LOCKED DOWN state.

这就使得同时按下或者锁住某些键变得容量。例如，选取 Ctrl 键按下，接着按下 “P” 键来发送 “打印（Print）” 命令到当应用用。除非是在锁住（LOCKED DOWN）状态，否则选取 “P” 键以后 Ctrl 键会自动松开。

It is a good idea to check if any of these "modifier" keys (Shift, Ctrl, Win, Alt) are pressed if you experience unexpected behaviour while typing into another application as they can impact your key selections.

如果在其他应用键入时却发生了一些意想不到的问题，先检查 “修饰（modifier）” 键是否按下，这会影响实际输入的按键选取。

N.B. It is useful to clear the scratchpad (by selecting the Clear key) when changing where you are typing (e.g. when starting a new email, or moving to another application):

注意，当改变键入位置时（比如说，当你开始写新邮件，或者切换到其他应用），最好清理提示框（scratchpad）（通过选取清理（Clear）键）：

![Clear key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Clear_Up.png)

---

**The physical keyboard**

**外置键盘**

The 'Physical' keyboard contains the "other" keys from a standard keyboard, e.g. the function keys (F1-F12, PG UP, PG DN, INSERT, etc). To access it:

“物理” 键盘包含 “其他” 标准键盘上的按键，例如说，功能按键（function keys）（F1-F12，PG UP，PG DN，INSERT，等等）

1. Select the 'Menu' key:

2. 选取 “菜单（Menu）” 键：
    ![Menu key](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Key_Menu_Up.png)

3.  Select the 'Physical' key:

4.  选取 “物理（Physical）” 键：
    ![Menu keyboard with numbers](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Keyboard_Menu_Numbered.png)

The 'Physical' keyboards look like this:

“物理” 键盘如下：

![Physical keyboard](https://github.com/JuliusSweetland/OptiKey/blob/gh-pages/images/Keyboard_Physical.png)
