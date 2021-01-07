| 场景                                                         | 目标                                                         | 手段                                                         | 结果                                                         | 评论                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 对学生完成的实际工作或任务进行程序化和规范化的评估           | 对学生所完成的任务，给与恰当的判断和评价，基于任务和实现的动态评价技术 | 1.评估库<br>2.解析器<br>3.等级分析器<br>4.信息库<br>         | 一个自动学习系统基于评估者和规则的评估能力，并提供开发计划并在需要时提供反馈和纯形式的消息。 | 自动评估只是第一步，仍然需要裁决者来评估，依然耗费人力。     |
| 自动题库评价系统，自动分析学生题库的数量，帮助教师完成题库的评价 | 学生编程能力的评判变为:期末考试+课堂实践                     | C/S架构<br>1.服务端教师电脑，负责系统的搭建，评估结果的收集和分析<br>2.客户端学生电脑，实时监控学生键盘输入，并上传代码到服务器。<br> | 已投入使用，平时实践练习代码越多的学生，最终成绩越好。各别异常待以后分析。 | 让编程能力不在只是体现于期末考试，加强了平时的学习和实践。键盘监控是核心，有利于分析学生思考思路。代码架构为python，通用性强。但只能分析运用此平台时的学生情况，无法分析课后及自主学习情况。且基于语法分割的关键词提取打分似乎也不是最佳的评判标准。 |
| 持续评估学生按时生成的源代码是一项具有挑战性的任务，评估个人编程练习和提供个性化及时反馈 | 研究一种通过源码分析自动持续评估编码技能的方法：A-Learn Evld | 1.源代码作为评估的输入，不同的策略被应用于识别证据，用于提供基于技能的学习者模型（输出）<br>2.技能评估由一个或多个证据；证据可以通过一种或多种自动策略来实现，最后返回特定编程方面的评估 | 提供了新的严格的自动编程源代码评估全景图。高阶认知技能可以在计算机编程环境中自动评估。 | 从多方面来评估学生编程能力，而不只是功能正确性评估和检测语义和编译错误。进行了多次试验来验证A-Learn Evld的学习能力。准确性和可靠性有待于提高。 |
| 编程过程的教学对学生开发计算机应用程序和软件解决方案至关重要 | 1.对于初学者的编程教学<br>2.分析自动代码验证工具的使用及其潜在的研究。 | 1.VPL<br>2.Mooshak<br>                                       | VPL的引入，支持多语言编辑和执行程序，并支持自动评估和及时反馈。 | 自动评估学生代码并进行评分，都是moodle插件，也支持防作弊等功能，使用方便简单， |
| 评估和管理学生                                               | 学生分组问题                                                 | k-means<br>基于网络密度的方法去除第一个离群点<br>用一种新的方法产生聚类中心，以取代随机判断。 | 成功对学生能力进行分组                                       | 能更好的对学生能力进行分类，而不是一味的按照平均成绩进行分类。 |
| 缺乏对代码风格问题的重视                                     | 规范编程风格                                                 | Style++                                                      | 规范编程风格                                                 | 简单实用                                                     |
| 手工检查代码枯燥、重复和费时；学生剽窃                       | 同1                                                          | 1.Moodle<br>2.YAP<br>3.APAC                                  | 同1                                                          | 开元、可实用。但APAC依赖于Moodle数据库，不够独立。           |
| 学生多，编程上手难，学生反馈不及时                           | 可视化编程与自动评估在STEM中的应用                           | 1.iVProg<br>2.VPL<br>3.The NASA-TLX Protocol                 |                                                              | 可以用于练习，但不能用于要求学生在场的正式评估。需要一种新的方法来比较学生在学完每一种编程模型之后通过算法解决问题的最终技能 |
| 学习编程和学习编程语言的语法                                 | 激发人类视觉系统的潜能                                       | 可视化编程与动画编程                                         | 产生了Jeliot                                                 | 评估方法并不太准确，但在可视化方向前进了一步                 |
| 非代码相关（模型、元模型或模型转换）的工作剽窃检测机制较少   | 提供有效的机制来检测模型驱动工程作业库中的剽窃行为           | 基于局部敏感哈希，近似最近邻搜索机制，适应建模技术空间       | 能有效发现抄袭                                               | 不同类型的作业有待优化，剽窃检测率有待提高                   |



A Rule-Based Self-Learning Model for Automatic Evaluation and Grading of C++ Programs



Design and Implementation of Automatic Exercises Evaluation System for Programming Courses

https://iopscience.iop.org/article/10.1088/1742-6596/1651/1/012021/pdf



Identifying Evidences of Computer Programming Skills Through Automatic Source Code Evaluation

https://sol.sbc.org.br/index.php/wcbie/article/view/13019/12872



Use of Automatic Code Assessment Tools in the Programming Teaching Process

https://drops.dagstuhl.de/opus/volltexte/2020/12291/pdf/OASIcs-ICPEC-2020-4.pdf



Application of K-Means Algorithm for Clustering Student's Computer Programming Performance in Automatic Programming Assessment Tool

https://www.atlantis-press.com/proceedings/ijcse-20/125946370



Supporting Students in C++ Programming Courses with Automatic Program Style Assessment



Automatic evaluation of correctness and originality of source codes 

https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6877393&tag=1



Visual programming and automatic evaluation of exercises: an experience with a STEM course

https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7757621



Animation and Automatic Evaluation to Support Programming Teaching

https://www.scitepress.org/papers/2015/55325/55325.pdf



Efficient plagiarism detection for software modeling assignments

https://www.tandfonline.com/doi/full/10.1080/08993408.2020.1711495