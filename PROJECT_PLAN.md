# V1 项目规划

## 产品定位
面向导游人员资格考试备考的移动端学习工具。

## 技术路线
当前 V1 为纯静态 HTML + CSS + JavaScript：
- 无 Ollama
- 无后端
- 无数据库服务器
- 学习记录使用浏览器 localStorage
- 可以直接部署到 GitHub Pages

## 页面结构
- 首页
- 练习页
- 错题本

## 数据结构
题目字段：
- id
- s：科目
- type：题型
- q：题干
- o：选项
- a：正确选项下标
- e：解析

学习数据：
- wrong
- favorite
- answered
- correct

## V2 建议
如果 V1 在 GitHub Pages 正常运行，再增加：
1. 正式题库导入
2. 章节分类
3. 模拟考试
4. 成绩报告
5. 收藏题页面
6. 地方科目切换
7. 账号云同步
8. 在线 AI 学习助手
