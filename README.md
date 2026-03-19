# 📚 DSE英语自适应学习系统

> 基于Web的自适应学习平台,支持多账户、发音训练、错题复习等核心功能

---

## ✨ 核心特性

### 👥 多账户系统
- 👦 小六 (9年级)
- 👧 小马 (5年级)
- 👨‍🏫 我 (教师账户,用于测试)

每个账户数据独立存储,互不干扰。

---

### 🎓 多账户诊断测试系统
- 90分钟完整评估:听说读写
- 听力部分: BBC真实视频 (5级难度)
- 文法词汇: 15道选择题
- 阅读理解: 2篇文章 + 6道题
- 写作部分: 支持语音输入
- 自动保存进度和答案

**文件**: `DSE_English_Multiuser_Test.html`

---

### 🎤 发音矫正训练系统
- 20个核心词汇 + 10个关键短语 + 5个例句
- Google Text-to-Speech标准美式发音
- 学生跟读录音保存
- 对比学生录音和标准发音

**文件**: `DSE_English_Pronunciation_Training.html`

---

### 📚 错题复习系统 (艾宾浩斯记忆曲线)
- 根据遗忘曲线自动安排4次复习 (1天/3天/7天/14天)
- 手动添加错题到系统
- 标记"掌握了"或"下次再复习"
- 进度追踪和统计图表

**文件**: `DSE_English_Review_System.html`

---

### 📊 教师仪表板
- 两个孩子的完整学习统计
- 各科得分分布
- 错题分类分析
- 复习进度追踪
- 活动记录

**文件**: `DSE_English_Teacher_Dashboard.html`

---

### 🎧 BBC听力系统 (5级难度)
- Level 1: BBC Learning English (入门)
- Level 2: BBC Learning English (进阶)
- Level 3: BBC World Service (专业)
- Level 4: BBC Hardtalk (深度讨论)
- Level 5: BBC Radio 4 (专业电台)

**文件**: `DSE_English_YouTube_Listening.html`

---

### 📝 自适应测试系统
- 动态难度调整
- 知识点讲解
- 错题生成强化练习
- 5级进阶系统

**文件**: `DSE_English_Adaptive_Test_System.html`

---

## 🚀 快速开始

### **在线使用**
访问已部署的系统链接即可使用。

### **本地使用**
直接在浏览器中打开HTML文件即可。

---

## 📁 文件结构

```
DSE英语自适应学习/
├── DSE_English_Multiuser_Test.html          ← 多账户诊断测试
├── DSE_English_Pronunciation_Training.html  ← 发音矫正训练
├── DSE_English_Review_System.html           ← 错题复习系统
├── DSE_English_Teacher_Dashboard.html       ← 教师仪表板
├── DSE_English_Adaptive_Test_System.html    ← 自适应测试系统
├── DSE_English_YouTube_Listening.html       ← BBC听力系统
│
├── adaptive_learning_engine.json            ← 自适应引擎数据
├── auto_marking_system.json                 ← 自动批改库
├── bbc_news_listening_library.json          ← BBC听力库
│
└── 英文教师_快速导航.md                     ← 快速导航
```

---

## 🎯 使用流程

### **学习流程**
```
1. 选择学生账户 (小六/小马)
2. 完成诊断测试
3. 查看错题分析
4. 进行发音训练
5. 复习错题 (艾宾浩斯记忆曲线)
6. 教师在仪表板查看进度
```

### **教师流程**
```
1. 打开教师仪表板
2. 查看两个孩子学习数据
3. 分析错题分布
4. 制定针对性教学计划
5. 追踪复习进度
```

---

## 🔧 技术栈

- **前端**: HTML5 + CSS3 + JavaScript (Vanilla)
- **数据存储**: LocalStorage (浏览器本地存储)
- **语音识别**: Web Speech Recognition API
- **语音合成**: Web Speech Synthesis API (Google TTS)
- **录音**: MediaRecorder API
- **无需后端**: 纯前端应用,所有数据本地存储

---

## 📊 版本历史

### v1.0.0 (2025-03-20)
- ✅ 多账户诊断测试系统
- ✅ 发音矫正训练系统
- ✅ 错题复习系统 (艾宾浩斯记忆曲线)
- ✅ 教师仪表板
- ✅ BBC听力系统 (5级难度)
- ✅ 自适应测试系统
- ✅ 三账户支持 (小六/小马/我)

---

## 🌟 核心优势

### **自适应学习**
- 动态难度调整
- 个性化学习路径
- 错题自动生成强化练习

### **科学记忆**
- 艾宾浩斯遗忘曲线
- 4次复习计划
- 自动安排复习时间

### **多媒体学习**
- BBC真实听力材料
- 语音输入支持
- 发音矫正训练

### **数据可视化**
- 教师仪表板
- 学习曲线图表
- 进度追踪统计

---

## 📖 使用指南

详细使用指南请查看:
- [英文教师快速导航](英文教师_快速导航.md)

---

## 🎉 开始使用

1. 打开系统
2. 选择你的账户
3. 开始学习!

**DSE英语自适应学习 - 你的智能学习伙伴!** 🚀

---

**项目地址**: GitHub仓库链接
**在线访问**: CloudBase部署链接
**最后更新**: 2025-03-20
