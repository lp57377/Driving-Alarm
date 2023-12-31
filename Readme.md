# 项目背景
- 随着汽车的普及和交通的发展，驾驶安全问题日益突出。驾驶员的危险行为，如打电话、抽烟、疲劳、分心等，是导致交通事故的重要原因之一。为了有效预防和减少驾驶员危险行为，提高道路安全水平，本项目旨在开发一套基于图像识别的驾驶员危险行为检测系统。
# 项目目标
## 本项目的目标是利用摄像头采集驾驶员的图像信息，通过Openpose算法提取人体关键点信息，如脸部和手部，结合其他图像处理技术，实现对驾驶员危险行为的实时检测和预警。本项目主要涉及以下几种危险行为：
- 打电话：当驾驶员手持手机或耳机通话时，系统发出语音或视觉提示，提醒驾驶员放下手机或耳机。
- 抽烟：当驾驶员手持香烟或口含香烟时，系统发出语音或视觉提示，提醒驾驶员熄灭香烟。
- 疲劳：当驾驶员闭眼、打哈欠、低头等表现出疲劳迹象时，系统发出语音或视觉提示，建议驾驶员休息或换人驾驶。
- 分心：当驾驶员转头、低头、看后视镜等表现出分心迹象时，系统发出语音或视觉提示，提醒驾驶员注意前方路况。
# 项目功能
## 本项目的主要功能如下：
- 图像采集：使用摄像头采集车内的图像信息，并将其传输到后台服务器进行处理。
- 图像处理：使用Openpose算法对图像进行人体姿态评估，并提取出脸部和手部关键点信息。结合其他图像处理技术，如肤色检测、动态追踪、目标识别等，对图像进行分析和判断。
- 行为检测：根据图像处理的结果，判断是否存在危险行为，并给出相应的置信度。
- 行为预警：根据行为检测的结果，通过语音或视觉方式向驾驶员发出预警提示，并记录下预警时间和类型。
# 项目技术
## 本项目可能需要的技术：
- Openpose：一个开源的人体姿态评估算法，可以检测出人体的关键点信息，如脸部和手部。Openpose具有高精度和高速度的特点，适用于多人二维姿态识别。
- Python：一种通用的编程语言，具有简洁、易读、易扩展的特点。Python拥有丰富的第三方库和框架，支持多种图像处理和机器学习技术。
