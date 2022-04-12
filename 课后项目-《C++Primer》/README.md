# 课后项目-《C++Primer》
some after-class exercisese and a little project of the 《C++Primer》

该项目是自己在学习《C++Primer》时做的一些课后习题&小项目，提供了源文件以供参考。
***
## 项目组成
1. **share_ptr** （实现的功能为多个指针共同指向（共享）同一个对象，并且在没有指针指向对象时自动进行析构）和 **unique_ptr**（实现的功能是一个指针独占对象，不允许除了此指针以外的指针指向该对象）的实现；
2. **Vec**的实现（vector的简化版本，包括StrVec类的设计和最终的Vec模板设计）；
3. **String**的实现（实现一个简化的string）；
4. **TextQueryProgram**文本查询程序（实现一个类（模板）来管理元素，能够提供对元素的共享（且核查过的）访问能力）。
5. **doc**存放了项目说明文档，标明了对应项目的知识点和所在页数
