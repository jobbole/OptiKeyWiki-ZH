# Eye tracker problems
# 眼球追踪器的问题
***

### *Eye tracker not working or stops working.*
#### *眼球追踪器不工作或停止工作。*
</br>

#### 1. Check that your eye tracking applications are running as expected and that you've completed any required setup, such as calibrating your eye tracker using its supplied software.
#### 1. 检查你的眼球追踪应用是否运行正常，并且是否你已经完成了所有要求的设置，例如使用眼球追踪器提供的软件完成校准。
</br>

#### 2. Check that the eye tracking device is connected securely to the computer/laptop/tablet.
#### 2. 检查眼球追踪设备是否牢固地和电脑 / 笔记本 / 平板电脑链接。
</br>

#### 3. Check the eye tracking software's logs, for example if you are using TheEyeTribe tracker then both the server and client applications produce logs. Are there any messages explaining that something has gone wrong (these are usually marked with WARNING or ERROR). Not sure how to find the logs or how to read them then please email me at optikeyfeedback@gmail.com.
#### 3. 查看眼球追踪软件的日志。比如，如果你正在使用 TheEyeTribe 追踪器，那么服务器和客户应用端都会生成日志。看是否有任何信息解释说某处有异常，通常这些信息用警告 （WARNING） 或者错误 （ERROR ） 标记。如果你不确定如何找到或者阅读日志，请发邮件给我 [optikeyfeedback@gmail.com]() 。
</br>

#### *Poor eye tracking performance/accuracy.*
#### *眼球追踪性能 / 准确性低*


#### 1. Check that the eye tracking device is connected securely to the computer/laptop/tablet.
#### 1. 检查眼球追踪设备是否牢固地和电脑 / 笔记本 / 平板电脑连接。

</br>

#### 2. Check the eye tracker setup. The correct positioning is specific to each tracker, so check the tracker's documentation, but commonly the tracker should be in the middle of the screen and directly below it.
#### 2. 检查眼球追踪器设置。每个追踪器的正确定位是特定的，因此要查看追踪器的文档，但是通常追踪器应该在屏幕中间的下方。
</br>

#### 3. Is there too much light coming in through a window or a direct light source? Eye trackers typically use infra-red light, so can be confused if there is a strong source of IR light near you, such as the sun.
#### 3. 是否从窗户透进来太多的光或者是否有直接光源。眼球追踪器一般使用红外光线，因此如果在你附近有一个强红外光源，比如太阳，眼球追踪器会分辨不清。

</br>

#### 4. Don't look down - keep the screen & tracker level with your eyeline. Looking down closes your eyelid over your eye, reducing tracking accuracy.
#### 4. 不要向下看。保持屏幕和追踪器和你的眼球位置水平。向下看会让眼睑把眼睛盖住，进而降低追踪的准确性。
</br>

#### 5. Calibrate the eye tracker to an area less than the total screen size if you are experiencing poor performance at the screen edges. Alternatively sit slightly further from the screen.
#### 5. 如果眼球追踪器在屏幕边缘处的性能不好的话，将眼球追踪器校准到一个小于整个屏幕尺寸的区域。或者坐在离屏幕稍微远一点的地方。
</br>

#### 6. Only screen sizes up to 24 inches are supported by trackers like GazeTracker and TheEyeTribe, or 27 inches for the Tobii EyeX. Check the limitations.
#### 6. GazeTracker 和 TheEyeTribe 支持的最大屏幕尺寸是 24 英寸，而 Tobii EyeX 支持的最大屏幕尺寸是 27 英寸。检查这些限制。
</br>

#### 7. If available, calibrate for more points (12 rather than 9, for example).
#### 7. 如果可以的话，校准更多的点，比如校准 12 个点而不是 9 个点。

</br>

#### 8. If available, when calibrating try to match the background/foreground colours to the product you will end up using, e.g. this on-screen keyboard.
#### 8. 如果可以的话，校准的时候尽量将你最终要用的产品 （ 例如屏幕上的键盘 ） 的背景颜色和前景颜色调成一致

</br>

#### 9. An effective head rest can prevent head movement.
#### 9. 有效的头部靠枕可以防止头部移动。

</br>

#### 10. Sit so that your head is within the effective range of your eye tracker. For GazeTracker and TheEyeTribe this is between 45 and 75cm from the tracker/screen.
#### 10. 坐在头部可以在眼球追踪器有效范围内的地方。对 GazeTracker 和 TheEyeTribe 来说，这是距离追踪器或屏幕 45 厘米到 75 厘米之间的位置。

</br>

#### 11. Try your eye tracker at different refresh rates, for example TheEyeTribe tracker can be set to 30fps or 60fps, which is achieved by starting the EyeTribe server with the "-f=30" or "-f=60" switch, e.g. "C:\Program Files (x86)\EyeTribe\Server\EyeTribe.exe" -f=60

#### 11. 尝试调整眼球追踪器使用不同的刷新率。比如，TheEyeTribe 追踪器可以通过用 " -f=30 " 或者 " -f=60 " 开关打开 EyeTribe 服务器 （即 "C:\Program Files (x86)\EyeTribe\Server\EyeTribe.exe" -f=60）来设置为 30 fps 或 60 fps。

</br>

