 ## Scrum开发模型
#### Scrum的定义和目的
Scrum是一个用于**开发和维护**复杂产品的框架，是一个**增量的、迭代的**开发过程，目的是让开发人员像打橄榄球一样迅猛并充满激情，通过团队合作，提高工作效率。通过团队间的有效交互，为企业创造价值 
  
***
#### Scrum中的人员角色
Scrum中的人员分为3个角色：**产品所有者（Product Owner）, Scrum Master，开发团队(Team)**


* 产品所有者   
**定义所有产品功能，决定产品发布的内容以及日期，对产品的投入产出负责**，**根据市场变化对需要开发的功能排列优先顺序，合理地调整产品功能和迭代顺序**，认同或者拒绝迭代的交付   

* ScrumMaster   
ScrumMaster不是项目经理，他没有分配任务的权力，没有考核的权力，没有下命令的权力，他**指导**项目组的成员按照Scrum的原则、方法做事情，领导团队完成Scrum的实践以及体现其价值，排除团队遇到的困难，确保团队胜任其工作，并保持高效的生产率，使得团队紧密合作，使得团队个人具有多方面职能的工作能力，保护团队不受到外来无端影响   


* 开发团队   
经典团队拥有 5-9 人，团队成员包含程序员、测试员、用户体验设计等等，团队关系在一个迭代中应该是固定的，个人的职能可以在新迭代开始时发生调整，团队自我组织和管理（自组织，自驱动），团队成员都全职工作
***

#### 开发过程
* 计划和体系结构设计（确定性过程）    
将Backlog（急待完成的一系列任务，包括：未细化的产品功能要求、Bugs、缺陷、用户提出的改进、具竞争力的功能及技术升级等）**按优先级排序**形成Backlog 列表，根据该表和风险评估制订产品交付基线。
建立系统体系结构（如为已有系统改进，则只作有限分析、调整），将Backlog项按**高内聚低耦合的原则**分解为一系列问题包(Packets,每个Packet是一组对象或构件的集合) ，依据同样原则相应划分若干个开发小组（SCRUM 小组）,分配各小组合适的Backlog项或问题包。**建立开发运行环境**   


* Sprint（经验性过程）   
该过程由若干个迭代的冲刺(Sprint) 活动组成，直至风险评估认为产品可交付为止。一个Sprint是在限定时间段内（Sprint周期，通常为1~6周，可在前一个Sprint结束时调整）的一系列开发活动（包括分析、设计、编码、测试等），每个SCRUM小组并行开发且必须步调一致（在一个Sprint结束后，均须完成所分配的Backlog项并有可执行的产出）。
每个Sprint包含以下活动：   
1.**开发**。对分配的Backlog工作进行分析，将所需改动（changes）映射到各packets，打开packets,进行领域分析，然后设计、开发、实施、测试、文档化这些改动。    
2.**打包(Wrap)**。封装packets,产生一个满足Backlog需求的可执行版本。    
3.**评审（Review）**。所有的SCRUM小组一起开会，提交各自的工作并演示(Demo)，然后提出和解决问题(Issue)及难点（problem）,增加新的Backlog项；发布、审查或调整产品的标准规范；进行风险评估并提出合适的对策；确定下一个Sprint的工作内容和结束时间。   
4.**调整（Adjust）**。根据评审会汇集的信息，对受影响的Packets进行适当调整和巩固    

* 交付和巩固（确定性过程）   
**一旦根据风险评估结果认为可交付产品时，即进入该阶段。**该阶段的活动包括：**组装，系统测试和回归测试（Regression），准备培训材料，完成最终文档。**
SCRUM过程认为一个产品的开发将一直持续下去，除非经风险评估后认为应停止。产品交付后的巩固活动类似于传统方法中的维护和改善，目的在于整理Sprint期压力下忽略的工作，为下一阶段的开发做准备，以便轻装上阵
***

### 12个原则
* 我们的最高目标是，通过尽早和持续地交付有价值的软件来满足客户   
* 欢迎对需求提出变更——即使是在项目开发后期。要善于利用需求变更，帮助客户获得竞争优势
* 要不断交付可用的软件，周期从几周到几个月不等，且越短越好
* 项目过程中，业务人员与开发人员必须在一起工作
* 要善于激励项目人员，给他们以所需要的环境和支持，并相信他们能够完成任务
* 无论是团队内还是团队间，最有效的沟通方法是面对面的交谈
* 可用的软件是衡量进度的主要指标
* 敏捷过程提倡可持续的开发。项目方、开发人员和用户应该能够保持恒久稳定的进展速度
* 对技术的精益求精以及对设计的不断完善将提升敏捷性
* 要做到简洁，即尽最大可能减少不必要的工作。这是一门艺术
* 最佳的架构、需求和设计出自于自组织的团队
* 团队要定期反省如何能够做到更有效，并相应地调整团队的行为