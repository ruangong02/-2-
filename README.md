# 第2组v2
软件工程项目研究报告



项目名称：学习成果分享平台 


第二组
组长：方琳
组员：俞凌飞、卫梦琪、晏思颖


报告更新日志
3.5 确认项目名称、功能需求。
3.9 搭建软件需求规格说明框架，确定本项目所采取的过程模型。







目录
软件需求规格说明	3
1. 引言	3
1.1 目的	3
1.2 适用范围	3
1.3 参考资料	3
1.4 术语和缩略语	3
2. 系统概述	3
2.1 产品描述	3
2.2 产品功能	4
3. 功能性需求分类	4
3.1 管理员角色	4
3.1.1 管理员登录	4
3.1.2 创设科目标签	4
3.1.3 筛选动态	4
3.1.4 发布通知	4
3.1.5 处理举报	5
3.2 用户角色	5
3.2.1 注册登录	5
3.2.2 发表动态、上传文件	5
3.2.3 查看动态	5
3.2.4 评论动态	5
3.2.5 举报功能	5
4. 产品非功能性需求	6
4.1 外部接口说明	6
4.2 性能需求	6
4.3 属性	6
4.4 系统运行环境	6
4.5 其他	6
附录	6
软件项目计划	7
1. 过程模型	7


 
软件需求规格说明
1. 引言
1.1 目的
疫情期间，学生开启线上学习模式。为了督促大家每日完成学习任务，促进学习热情，激发学习动力，营造良好的学习氛围，我们计划开发一个可以分享学习成果的互动平台。在此平台上，大家可以分享自己的学习成果，可以看到不同科目下同学们发表的“今日学习成果”的分享动态，还可以线上交流与讨论。
1.2 适用范围
适用于信机学院2017级的想要了解他人的学习情况、获得学习动力的大学生。（目前仅限PC端）
1.3 参考资料
1.4 术语和缩略语
2. 系统概述
2.1 产品描述
本项目主要研究学习成果分享平台的开发与功能实现，该平台可在PC端使用，使用Visual Studio进行具体的项目开发。
（1）用户设定为信机学院2017级的大学生，可对发布的学习动态进行科目分类、在发表学习动态时还可以上传文件，并对该学习动态所属的科目进行标记；除此之外，用户可以在登录之后选择想要查看的科目，从而与对应科目的动态用户进行信息交互；若是发现不适宜的内容，用户可以向管理员举报。
（2）管理员是负责平台管理的专门人员，其主要工作有：根据实际需要实时创设科目标签、对用户发布的动态进行筛选、发布通知以及处理举报。
2.2 产品功能
序号	功能名称	对应角色	功能简要描述
1	管理员登录	

      
管理员	管理员通过已经存在的工号及密码进行登录，进入管理员主页界面。
2	创设科目标签		管理员可实时更新增设科目标签。
3	筛选动态		管理员可以对用户发布的动态进行筛选，动态是否能成功发布由管理员审查的结果决定。
4	发布通知		管理员可以通过发布通知来告知用户系统更新、举报是否已处理等消息。
5	处理举报		管理员对用户发出的举报会进行相应的处理。
6	注册登录	


用户	用户需要先进行注册之后，才能登录进入主页面。
7	发表动态
上传文件		已注册的用户可以根据自己的需要发表动态、上传文件。
8	查看动态		登录后，用户可以根据想要了解的科目，查看别人发表的学习动态。
9	评论动态		登录后，用户可以在其他用户发表的学习动态下进行文字的评论。
10	举报功能		对于不适宜的内容，用户可以向管理员举报。

3. 功能性需求分类
3.1 管理员角色
3.1.1 管理员登录
管理员通过已经存在的工号及密码进行登录，进入管理员主页界面。
3.1.2 创设科目标签
管理员登录后可创设用户需要的所有科目标签，例如：软件工程、计算机教学法、硬件类课程、Andriod技术开发等，以供用户在发表动态时勾选标记动态的科目类型。
3.1.3 筛选动态
管理员登录后，可接收到由用户发表的动态申请，根据用户发表的动态内容，筛选与学习相关的动态与文件并同意发表，如发现用户发表与学习无关的动态或文件则不予通过。
3.1.4 发布通知
管理员登录后可以发表通知动态，可针对全体和个人（选择群发或@某个用户）。具体内容可以是平台使用指南、发布动态流程指导、动态问题处理反馈等。
3.1.5 处理举报
用户使用评论回复功能时，发现有不文明用语（包括：低俗用语、恶意引战、淫秽色情、人身攻击、其它不文明用语等），可使用举报功能，而管理员登录后可以处理此类举报，对于被举报用户言论进行删除，净化平台的信息交互环境。
3.2 用户角色
3.2.1 注册登录
未注册学生可使用姓名、学号进行注册。注册成功后，使用学号及密码进行登录，进入个人主页界面。
3.2.2 发表动态、上传文件
已注册学生登录后可在个人主页界面上选择科目标签发表学习动态，上传学习文件，例如：个人学习笔记、学习计划及成果等。用户动态及文件在发表时默认为所有用户可见。
3.2.3 查看动态
所有用户可通过选择科目标签对所有动态进行筛选，从而查看所选标签下的相关动态及文件。
3.2.4 评论动态
所有用户可对感兴趣的动态进行文字评论，也可以在别人的评论下进行文字回复，从而进行信息交互，提高平台的活跃度。
3.2.5 举报功能
所有用户使用评论回复功能时，发现有不文明用语（包括：低俗用语、恶意引战、淫秽色情、人身攻击、其它不文明用语等），可以使用举报功能，向系统管理员进行举报，以维护平台和谐稳定的使用。
4. 产品非功能性需求
4.1 外部接口说明
4.2 性能需求
4.3 属性
4.4 系统运行环境
4.5 其他
附录
 
软件项目计划
1. 过程模型
本项目拟使用迭代式开发方式中的增量模型进行开发。原因如下：
（1）本项目的核心是学习成果分享平台的开发与功能实现，在这样一个平台中，功能
较多，且各个功能之间的优先权不同。比如发表动态和上传文件就是最核心的功能，评论功能及举报功能次之。利用增量模型，具有最高优先权的核心增量构件将会被最先交付，而随着后续构件不断被集成进系统，这个核心构件将会受到最多次数的测试。这意味着软件系统最重要的心脏部分将具有最高的可靠性，这将使得整个软件系统更具健壮性。
（2）采用增量模型，可使得开发初期用户只需对软件需求进行大概的描述，对于需求
的细节性描述则可以延迟到增量构件开发时进行，以增量构件为单位逐个地进行需求补充。这使得我们可以尽快地着手项目的开发。但是增量模型的缺点是灵活性较大，容易退化为边做边改的模型，我们会尽量克服这一切困难。
（3）不采用瀑布模型或快速原型化模型是因为这种模型的目标是一次性把一个满足所
有需求的产品提交给用户。而作为小组作业，以学习为目的的共同开发一个项目的过程中，制定阶段性的目标有利于及时检测学习成果，也可鼓舞团队士气以及降低项目的风险。
