# 航天云课堂辅助工具

源码[gtjl12/HangtianTrainAssitant](https://github.com/gtjl12/HangtianTrainAssitant)。

有问题请在[issues页面](https://github.com/gtjl12/HangtianTrainAssitant/issues)留言。

## 主要功能

1. 专题课程页面生成学习按钮，全自动学习除  ***考试课程***  外的所有课程

2. 课程视频播放页面防止弹窗出现

## 使用方法

0. 油猴安装脚本

1. 专题课程学习：进入专题学习页面，点击“专题内容”上方的开始学习按钮，***全心打工***，等待所有课程播放完毕

2. 单个课程学习：进入课程视频页面，播放视频。***全心打工***，等待视频播放完毕

**注意** : 因浏览器对页面自动播放视频的限制，课程视频默认静音。

## Todo

1. [x] 支持课程视频列表播放
2. [x] 优化代码循环结构

## 鸣谢

大量借用 [TechXueXi/techxuexi-js](https://github.com/TechXueXi/techxuexi-js) 代码

---

## 更新历史

2022.09.02 v0.0.4： 

- 修正因浏览器策略（ play() failed because the user didn‘t interact）无法自动播放问题

2022.08.31 v0.0.3： 


- 修正播放停止不能自动重播
- 修正从专题页面进入有播放列表的课程，无法自动播放下一节课程
- 调整代码循环结构


2022.08.28 v0.0.2:

- 支持播放列表

2022.08.27 v0.0.1:

- 实现专题、单个课程自动学习
