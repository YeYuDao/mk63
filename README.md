# mk63
Vue3.0+TS打造企业级组件库 前端中高级开发者必修课
Vue3.0+TS打造企业级组件库 前端中高级开发者必修课
[![下载地址](https://img.mukewang.com/szimg/5fd1925a09eb9b7205400304.jpg "下载地址")](https://51xueit.vip "下载地址")
[下载地址](https://51xueit.vip "下载地址")
### 第1章 关于这门课，你需要知道的 

#### 本章中，将向大家介绍本门课的相关信息，包括你能学到的知识概览、最终项目效果、课程讲解方式以及相关储备知识介绍等等。
1-1 课前须知，这里有你需要了解的一切 (09:58)

1-2 【讨论题】是什么驱动你来学习Vue3的

1-3 开始学习之前你需要了解的 (04:55)

1-4 Vue3更新概览 (19:36)

1-5 关于TS的学习 (07:27)


### 第2章 【项目启动】项目的创建以及各个技术部件介绍 

#### 本章中，我们来创建项目的主题工程。基础设施决定整个项目将来是否合理，所以在最开始需要尽可能将会用到的功能考虑进去，在这里我们会确定项目的配置，vue3的开发模式，ts的使用方式等。
2-1 创建vue3的项目和目录结构讲解 (15:58)

2-2 代码格式化工具prettier (08:36)

2-3 如何用ts在vue3中定义组件 (24:05)

2-4 如何提取props定义 (07:52)

2-5 于vue的h函数详细讲解 (16:03)

2-6 setup的运用和其意义 (21:56)

2-7 setup返回render函数的用法 (11:09)

2-8 使用jsx开发vue3组件 (21:58)

2-9 【讨论题】你如何看待用jsx开发vue3这种形式？

2-10 为什么vscode没有对props类型进行提醒 (03:42)


### 第3章 【准备基础】JsonSchema标准和使用方式介绍

#### 这里介绍什么是json schema，她的功能是什么，在什么场景进行使用等。我们会讲解基本的字段和语义，以及如何进行校验等。
3-1 什么是json-schema (09:22)

3-2 如何试用ajv来定义和校验json-schema (13:25)

3-3 json-schema的fomart和自定义format (08:35)

3-4 如何自定义关键字 (15:37)

3-5 如何转换错误语言自定义关键字如何自定义错误信息 (05:38)

3-6 如何自定义错误信息 (05:58)


### 第4章 【基础功能开发】实现组件库的主流程

#### 我们需要根据json schema来生成表单，那么肯定需要依赖一些规则，json schema的语义就是最简单的规则。根据type的定义来进行不同的渲染方式就是最简单的方式，我们称之为renderer，在这一章中我们会实现这些一些简单类型的renderer。...
4-1 课程目标和接口定义 (09:40)

4-2 实现demo项目 (17:08)

4-3 展示项目的APP完善 (06:17)

4-4 开始实现SchemaForm (14:23)

4-5 组件SchemaItem的实现 (10:26)

4-6 使用SFC的setup语法开发StringField组件 (18:48)

4-7 NumberField节点渲染的实现 (12:05)

4-8 【讨论题】你如何看待Css in Js


### 第5章 【挑战难度】复合型的复杂节点渲染实现

#### 在json schema中有一些类型我们称之为复合类型，他们相对于上一章的节点来说比较复杂，比如对象节点可以里面有很多的string节点和number节点，那么这类节点的渲染方式肯定会更有难度和挑战性。
5-1 复杂节点的渲染章节介绍和准备 (10:23)

5-2 【讨论题】对于写一个开源的类库，我们需要考虑哪些问题？

5-3 开始实现ObjectField渲染并处理循环依赖的问题 (18:09)

5-4 使用provide跨层级传递信息以及provide源码解析 (19:12)

5-5 完成ObjectField的渲染 (19:54)

5-6 数据节点的渲染设计 (12:09)

5-7 固定长度数组的渲染 (09:21)

5-8 单类型数组的渲染 (26:29)

5-9 多选数组的渲染 (15:04)


### 第6章 【提升质量】为组件提供单元测试

#### 作为一个组件库，是可能被很多人用在他们自己的项目中的，那么质量和稳定性就是这个组件库是否好用的标准。单元测试的完整性是保证组件质量最高效合理的方法，所以这一章我们会为我们的项目加入单元测试的支持，并且使用vue标配的测试库vue-test-utils来帮助我们方便得测试组件。...
6-1 什么是单元测试以及为什嘛要单元测试 (08:53)

6-2 【讨论题】你如何看待单元测试？

6-3 如何部署jest单元测试 (16:48)

6-4 如何使用jest写测试用例 (26:03)

6-5 如何使用vue-test-utils测试vue3的组件 (18:33)

6-6 正式开始单元测试之问题解决 (17:56)

6-7 正式开始单元测试补全 (08:54)

6-8 单元测试的指标讲解 (09:54)

6-9 ObjectField的单元测试完善 (16:27)

6-10 ArrayField的单元测试补全 (14:32)


### 第7章 【扩展视野】设计一个主题系统来满足各种不同的需求

#### 这一章中我们设计一套主题系统，为什么需要设计主题呢？因为对于不同的用户来说，他们可能希望表单的最终展现形式是不一样的。但是核心的表单规则和校验是可以通用的，我们把不同的部分拆分出来，通过实现主题就可以实现不同的展现啦。...
7-1 为什么需要主题系统 (09:15)

7-2 拆分主题的代码打包 (13:03)

7-3 拆分主题并进行定义 (16:56)

7-4 使用ThemeProvider进行解耦 (18:52)

7-5 解决TS的定义问题 (13:39)

7-6 修复单元测试 (11:21)

7-7 迁移TextWidget和mergeProps (12:29)

7-8 Controlled-Input功能的实现 (09:11)

7-9 迁移NumberWidget (05:36)


### 第8章 【深入原理】vue3响应式原理逐行源码解析

#### 本章中会再次深度分析vue setup方法涉及到的API和使用方法，并总结一套vue setup的最佳实践。因为setup是vue3最大的更新亮点，也是最能体现vue3和vue2差别的部分，可以说未来大部分的vue开发都会使用setup，所以这是极其重要的一部分，非常有必要单独拿出一章来进行深度分析。...
8-1 reactive函数源码解析 (20:48)

8-2 proxy的handler源码详解 (18:16)

8-3 proxy的set和其他代理详解 (11:56)

8-4 集合类型的代理函数详解 (16:12)

8-5 ref和computed源码详解 (15:08)

8-6 整体过一遍watchEffect的API实现 (21:02)

8-7 最重要的effect源码深度逐行解析（上） (14:27)

8-8 最重要的effect源码深度逐行解析（下） (15:46)

8-9 关于effect理解的一些补充 (15:48)

8-10 关于vue3的调度scheduler的源码解析 (18:34)


### 第9章 【保障安全】表单校验功能开发

#### 表单表单，怎么能缺少表单校验呢？可以说我们之所以讲解表单组件，并把上面的组件归类为表单组件，最大的一个原因就是我们需要对这些组件的交互结果进行校验，所以自古以来，组件库对于表单校验功能的要求都是空前高的。在课程中我们会实现一套完整的表单校验功能，甚至不必开源组件诸如element-ui之类的差，这简直可以成为...
9-1 关于本章以及jsonschema的错误对象解析 (07:46)

9-2 从父组件调用子组件在setup中声明的方法 (12:35)

9-3 实现ajv的校验过程 (09:34)

9-4 转换错误信息到errorSchema (19:52)

9-5 把错误信息向下传递 (07:55)

9-6 实现FormItem组件来展示label和错误信息 (12:16)

9-7 通过高阶组件抽离FormItem逻辑 (13:04)

9-8 实现自定义校验的功能 (17:32)

9-9 异步校验的实现 (19:13)


### 第10章 【深度扩展】完善表单组件库功能

#### 对于表单，一些常用的组件可以实现80%的功能，但是一些不那么通用的功能我们还是需要进行一些自定义的。在我们系统中，通过定义表单项接入的接口形式来规定表单组件的接入方式。
10-1 关于自定义组件的功能介绍 (08:54)

10-2 使用widget字段实现自定义渲染 (10:19)

10-3 uiSchema更多的使用场景扩展 (08:26)

10-4 实现自定义format的自定义渲染 (20:46)

10-5 关自定义keyword来扩张功能实现 (15:52)


### 第11章 【我在开源社区等你】开源项目发布流程以及课程总结

#### 组件库如何打包发布，让更多的人认识它并爱上他？在这章中会向你一一介绍。相信学完这门课并且能够自主完成作业的同学，你已经比60%的vue开发者要强大了！加油~~
11-1 关于自动化构建相关的知识介绍 (09:26)

11-2 创建github仓库以及配置自动化构建 (14:28)

11-3 调整单元测试和命令 (03:54)

11-4 上传覆盖率数据道codecov (09:15)

11-5 发布类库到npm (07:27)

11-6 课程总结（上） (14:40)

11-7 课程总结（下） (14:52)


[下载地址](https://51xueit.vip "下载地址")
