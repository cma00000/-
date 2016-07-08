# Jibo Feature部分测试整理
## 一、Animate模块
### 1.LED(set LED color)
可以脚本控制颜色。
### 2.动作控制
a)animation keys控制  b)脚本通过设置LookAt目标三维坐标，以及设置动用那些部分。但不能分别指定身体部位的转动方向。
## 二、audio 模块
### 3.音量控制
可以获得当前和控制主音量。
## 三、body模块
### 4.电池电量
可以获得当前电池剩余电量百分比
### 5. 头部触摸板
头顶触摸板6块，可检测被触摸与否（在最新固件上测试）。
## 四、face模块
### 6. 隐藏显示
可将眼睛、覆盖层和背景同时设为隐藏。
## 五、lps模块
### 7.照相
可以返回url，显示在屏幕上。但没有图片格式文件。
### 8.声音定位
获得可听到的声源空间坐标。但是在吵杂背景、回声房间效果不好，不是很准确。
### 9.人脸定位和跟踪
获得最近人脸实体坐标。太近、太远、运动快、背景复杂、多目标都会丢失目标。
### 10.屏幕预览
可同步屏幕显示当前摄像头拍摄到的内容。但会有报错、无法获得视频文件、不同固件版本可能会有眼球遮挡问题。
## 六、nlu模块





