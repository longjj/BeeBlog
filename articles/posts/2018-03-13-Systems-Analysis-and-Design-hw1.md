@(系统分析与设计)[homework]

# Systems Analysis and Design hw1

## 一、 简单题

### 1. 软件工程的定义
软件工程是研究和应用如何以系统性的、规范化的、可定量的过程化方法去开发和维护软件，以及如何采用工程的概念、原理、技术和方法来开发与维护软件，把经过时间考验而证明正确的管理技术和当前能够得到的最好的技术方法结合起来的学科。


### 2. 阅读经典名著“人月神话”等资料，解释 software crisis、COCOMO 模型。
1.	首先解释下软件危机(software crisis)。它是指在软件开发及维护的过程中所遇到的一系列严重问题，这些问题皆可能导致软件产品的寿命缩短、甚至夭折。软件开发是一项高难度、高风险的活动，由于它的高失败率，故有所谓“软件危机”之说，其中的一些具体表现有：
  - 软件开发成本日益增长，开发成本超出预算。
  - 软件开发进度难以控制，实际进度比预定计划一再拖延。
  - 用户对“已完成” 系统不满意的现象经常发生，用户需求不明确。
  - 软件产品的质量不可靠。
  - 软件的可维护程度低， 数量不断膨胀的软件产品缺乏适当的文档资料。
  - 软件开发生产率跟不上硬件的发展和人们需求的增长
2. 1960 年代中期开始爆发的软件危机， 催生出了 COCOMO模型以及软件工程。COCOMO模型以及软件工程的诞生正是为了解决软件危机。 前者是一种软件成本估算方法，使用一组“成本驱动者”来对产品、 硬件、 人员以及项目属性做出客观评价。 软件工程的定义则明确了用以解决软件危机中的软件质量低下、 需求不匹配、 项目无法管理等问题的一组方法论。



### 3. 软件生命周期
软件生命周期（Software Development LifeCycle）是指软件的产生直到报废的全部过程。从时间的角度来说， 可以把整个周期划分为六个阶段：
1. 可行性分析与计划阶段
	- 确定软件开发的总体目标，给出功能、性能、可靠性以及接口等方面的要求，进行完成可行性分析。
	- 估计可利用的资源(硬件、软件、人力等)、成本、效益、开发进度，进行投资-收益分析，制订开发计划。
	- 提交可行性分析报告、开发计划等文档。
2. 需求分析阶段
	- 分析用户提出的要求，给出需求详细定义，确定软件系统的各项功能、性能需求和设计约束，确定对文档编制的要求。
	- 提交软件需求说明、软件规格说明、数据要求说明等文档和初步的用户手册。
3. 设计阶段
	-  概要设计：把各项需求转换成软件的体系结构。结构中每一组成部分都是意义明确的模块，每个模块都和某些需求相对应。
	-  详细设计：对每个模块所要完成的工作进行具体的描述，提供源程序编写的直接依据。
	-  提交结构设计说明、详细设计说明和测试计划初稿等文档。
4. 实现阶段
	- 完成源程序的编码、编译(或汇编) 和排错调试，得到没有语法错误的程序清单。程序结构良好、清晰易读，且与设计相一致。
	- 编写进度日报、周报和月报(取决于项目的重要性和规模)。
	- 提交用户手册、操作手册等面向用户的文档的编写工作。
	- 编制测试计划。
5. 测试阶段
	- 全面测试目标软件系统，并检查审阅已编制的文档，提交测试分析报告。逐项评价所生产的程序、文档以及开发工作本身，提交项目开发总结报告。
	- 在整个开发过程中(即前五个阶段中)，开发集体需要按月编写开发进度月报。
6. 运行与维护阶段
	- 软件提交给用户后，在运行使用中得到持续维护，根据用户新提出的需求进行必要而且可能的扩充、删改、更新和升级。
	- 软件维护包括改正性维护(发现错误)、适应性维护(适应运行环境变化) 和完善性维护(增强功能)。

### 4. 按照 SWEBok 的 KA 划分，本课程关注哪些 KA 或 知识领域？
- 软件需求 Software requirements 
- 软件设计 Software design 
- 软件质量 Software quality 
- 软件工程工具与方法 Software engineering models and methods


### 5. 解释 CMMI 的五个级别。例如：Level 1 - Initial：无序，自发生产模式。
- Level 1 - initial： 无序、 自发生产模式。
- Level 2 - Managed： 管理制度化、 建立了基本的管理制度和规程。
- Level 3 - Defined： 开发过程实现标准化、 文档化。
- Level 4 - Quantitatively Managed： 产品和过程已建立了定量的质量目标。
- Level 5 - Optimizing： 集中精力改进过程， 得出最佳方法。 

### 6. 用自己语言简述 SWEBok 或 CMMI （约200字）
软件工程知识体系（SWEBOK）是ISO / IEC TR 19759：2005 的国际标准，**详细说明了公认的软件工程知识体系指南**。“软件工程知识体系指南”（SWEBOK指南）是由多个专业团体和行业成员合作创建的，由IEEE计算机协会（IEEE）出版。该标准可以从IEEE计算机协会免费获取。2013年底，SWEBOK V3被批准发布并发布，它关注了软件工程的15个领域，分别是：软件需求、软件设计、软件构造、软件测试、软件维护、软件配置管理、软件工程管理、软件工程过程、软件工程模型与方法、软件质量、软件工程专业实践、软件工程经济学、计算机基础、数学基础、工程基础。

## 二、 解释 PSP 各项指标及技能要求

- 阅读[《现代软件工程》的 PSP](http://www.cnblogs.com/xinz/archive/2011/11/27/2265425.html)中的[Personal Software Process 章节](http://www.cnblogs.com/xinz/archive/2011/10/22/2220872.html)。 

- 按表格 PSP 2.1， 了解一个软件工程师在接到一个任务之后要做什么，需要哪些技能，解释你打算如何统计每项数据？ （期末考核，每人按开发阶段提交这个表）



回答：接到任务后要按顺序完成下面的一些任务：
1. 计划
	- 估计这个任务需要多少时间
2. 开发
	3. 分析需求
	4. 生成设计文档
	5. 设计复审（和同事审核设计文档）
	6. 代码规范（为目前的开发制定合适的规范）
	7. 具体设计
	8. 具体编码
	9. 代码复审
	10. 测试（包括自我测试，修改代码，提交修改）
3. 记录花费时间
4. 书写测试报告
5. 计算工作量
6. 事后总结
7. 提出过程改进计划

其中需要的技能：
1. 需求分析，从用户的角度出发
2. 项目设计，选择合适的模型和结构
3. 设当的项目经验并且知道相关的代码规范
4. 编码能力过关
5. 了解基本测试的流程和方法

主要统计数据的方法是以**时间统计**为基础。对于每项数据，统计具体完成的时间（以小时为单位），以此推导出完成该项任务的效率和成果评估。
