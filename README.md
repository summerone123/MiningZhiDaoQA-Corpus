# MiningZhiDaoQACorpus
580万百度知道问答数据挖掘项目
ZhiDaoChatCorpus, zhidao QA pairs crawled from Baidu zhidao which contains more than 5,800,000 question and answers with certain tags。百度知道问答语料库，包括超过580万的问题，每个问题带有问题标签。基于该问答语料库，可支持多种应用，如逻辑挖掘。    

# 项目介绍
知道类问答社区,是目前社会知识传播和交流的重要场所之一,有问题找百度,有问题,更找百度知道,这句话鲜明的点出了作为国内最大的全民问答社区,百度知道所占据的地位。 本项目以百度问答数据位试点进行挖掘，目标有二，其一是开源数据，其二是基于该数据集做知识挖掘。    

# 知道类问答数据的特点 
1, 规模之大。截止到我敲下这个现在这个字时,百度知道已经积累了549,406,017个问题,这个问题数量无时不刻在增长,并且已经达到了5亿的级别,这个数量隐藏着百度知道这一社区的知识财富。  
2, 质量之伤。既然是众包之下的一个产物,准确性和规范性容易被人诟病,我们必须承认很多答非所问,乱说一通现象的存在。但好的占多数(这个数字可以参考相关论文,已有论文做过研究)。    
3, 范围之广。百度问答社区所涉及到的问题有很多,有专业领域的问题,也有吃喝拉撒睡之类的生活问题,也有小学生问作业怎么做,这与人们的生活息息相关。    
5, 价值之大。一问一答,往往是以解决问题为目的而产生的,这种解决问题的行为是一种潜在的因果逻辑所在,这种逻辑又包括多种领域。  

# 知道类问答数据的应用
因此,知道类问答社区,可以支持以下应用:  
1, 问答QA。问答语料库目前不少,加上这个百度问答语料能够有一定程度的扩充,用作算法学习也好,用作闲聊或者领域问答也好,都能发挥出其价值。    
2, 数据挖掘。社区问答是社会语言生活最为直接的一种反映途径,基于百万级的问答对,可以支持多方面的分析,如问题画像等。  
3, 语言挖掘。语言挖掘,指的是基于问答语料做诸如百度社区问句风格上,词语使用情况等的分析工作,借此来考察语言生活上的特点,也可以用该特定语料进行领域模型的训练。    
4, 知识挖掘。百度问答对是非结构化的知识库,里面隐藏着大量的逻辑知识,实体知识和关系知识,如果对其进行结构化,那将能够挖掘出大量的实体性,事件性的逻辑知识出来。(这也是本项目的一个目标)。     

# 知道类问答数据的概况
因此,考虑到百度知道的四个数据特点以及4个应用点,本项目通过采集百度知道,形成了百万级别的问答数据库规模。其中:
1, 问题个数583万个。     
2, 问答对983万个。     
3, 每个问题的答案个数1.7个。   
4, 问题标签个数5824个。  


# 数据介绍

1, 文件路径:已经上传至网盘,网盘地址为链接:https://pan.baidu.com/s/1Eesx24tAbfJ3Mch-6OeGrA  密码:oin3  
2, 文件名称:zhidao_qa。json, json文件的内容样式为:  

        {
            "_id" : ObjectId("5d36e599bc54f451543da02b"),
            "url" : "http://zhidao.baidu.com/question/2207667243516878988.html",
            "answers" : [
                "这与当时的历史背景有关。卡萨布兰卡属于法国的殖民地，而当时的法国是与纳粹德国合作的。但在法国人中又分为合作和抵抗两派。警长的立场早先是在双方之间摇摆不定。后来与Rick站在了一起。拿酒瓶又扔掉象征其抛弃过去，走上了义无反顾的抵抗道路。----------------------------------------------------------------------------------------卡萨布兰卡的剧情简介   · · · · · · 二战期间，卡萨布兰卡是欧洲逃往美国的必经之地，那里鱼龙混杂，局势紧张。里克（亨佛莱?鲍嘉 Humphrey Bogart 饰）是一个神秘的商人，他在卡萨布兰卡开了一家人气很旺的夜总会，并拥有两张宝贵的通行证。一天，反纳粹人士维克多和妻子伊尔莎（英格丽?褒曼 Ingrid Bergman 饰）来到夜总会，原来他们正在逃避纳粹的追捕。碰巧的是，里克发现，伊尔莎竟然是他的旧日情人。那段爱曾经刻骨铭心，却因为一个误会而终止。而当误会消解时，伊尔莎和里克的感情还是不可避免的重燃了。里克手上的两张通行证能帮助维克多度过难关，但这样一来，伊尔莎是决定留下，还是离去，他们的爱情在政治和伦理的推波逐流中走向何方。"
            ],
            "question" : "卡萨布兰卡为什么是欧洲逃往美国的必经之地",
            "tags" : [
                "美国"
            ]
        }
        {
            "_id" : ObjectId("5d36e599bc54f451543da02c"),
            "url" : "http://zhidao.baidu.com/question/1929874578384929307。html",
            "answers" : [
                "你好是的！现在办理的身份证都是2代身份证！都是有磁性的"
            ],
            "question" : "2017年办的身份证是二代身份证吗",
            "tags" : [
                "公务办理"
            ]
        }
        {
            "_id" : ObjectId("5d36e599bc54f451543da02d"),
            "url" : "http://zhidao.baidu.com/question/941683273505984492.html",
            "answers" : [
                "龙凤汤是一道色香味俱全的传统名肴，属于闽系。此菜汤色微红，清澈见底，是一道上等滋补药膳。此菜由泰西宾馆一级厨师孙业富创作，被泰安市地方名吃评审会评为一等奖，受到海内外宾客的好评。龙凤汤主要食材：鲤鱼 ，口    味：鲜香 ，辅    料：香菇主料鲤鱼1条﹐鸡(大雏鸡)1/2只﹐香菇5个﹐大枣﹑栗子各10个﹐切好的葱2大勺﹐蒜1头﹐香油﹐胡椒粉鸡肉佐料切好的葱1大勺﹐捣好的蒜1大勺﹐胡椒面1/4小勺﹐香油1小勺调料鸡蛋﹐辣椒丝做法(1) 鸡要准备大雏鸡﹐去掉头和瓜﹐除去内脏洗净。(2) 要准备活鲤鱼﹐去尾放血后刮鳞﹐并切成块洗净。(3) 把香菇泡在水里除去香菇柱﹐大枣去核﹐栗子去皮。(4) 鸡蛋煎出来﹐切成丝。(5) 往平锅里倒水﹐开锅时放鸡﹑香菇﹑栗子﹑大枣﹑蒜煮熟。营养价值编辑鸡完全煮熟时﹐捞取撕肉与葱﹑蒜﹑香油﹑胡椒粉一起拌。在煮鸡的汤里放鲤鱼块儿﹐重煮一遍。有龙凤汤的真味儿出来时﹐盛在碗里﹐并在上面放拌的鸡肉和辣椒丝。",
                "因为香菇具有特殊的香味，会相互影响口味，所以不适合放。"
            ],
            "question" : "为什么炖龙凤汤不能放香菇呢",
            "tags" : [
                "美食",
                "花鸟鱼虫",
                "香菇"
            ]
        }

其中,url表示该问句所在百度百科的网址;question表示问题描述,answer是一个答案列表,列表中的顺序为百度知道问答中的排序,一般是越靠前,置信度越高;tags是问题的标签列表。

3, 文件的说明:
1, len_distribution.txt,问题答案个数分布
2, tag_distribution.txt,问题的标签分布


# 问答对数据概况

| 问题答案个数 | 频次 |
| :--- | :---: |
| 1 | 3524209 |
| 2 | 1315246 |
| 3 | 554687 |
| 4 | 229455 |
| 5 | 186532|
| 6 | 25256 |
| 7 | 629 |
| 8 | 9 |
| 9 | 2 |
| 11 | 1 |


# 问题标签概况

| 问题标签 | 频次 | 问题标签 | 频次 |
| :--- | :---: | :--- | :---: |
| 学习 | 405608 | 感情 | 218283 |
| 理工学科 | 344649 | 汽车 | 213075 |
| 手机 | 338319 | 硬件 | 212689 |
| 游戏 | 319145 | 商业| 206260 |
| 保健养生 | 267062| 网络游戏 | 193532 |
| 烦恼 | 264315 | 法律 | 191664 |
| 交通 | 261084 | 医疗 | 177384 |
| 生活 | 253055| 人体常识 | 175527|
| 生活常识 | 243856 | 教育 | 172151|
| 恋爱 | 236902 | 软件 | 169979 |

# 下一步的工作
1, 基于问答对, 进行逻辑关系挖掘,具体实施后续开源 

# 总结
1, 本项目开源了一个问题个数583万个, 问答对数目达到983万的问答数据集。  
2, 本项目对问答数据集的概况进行了介绍, 请用于学习交流使用, 若有侵权,请联系我删除。   
3, 欢迎大家使用该数据集进行知识挖掘,语言挖掘,数据挖掘等方面的学习和研究工作。   
4, 本项目后续将尝试基于该数据集进行逻辑事理的挖掘工作,目标是建成百科社区的逻辑知识库。   

If any question about the project or me ,see https://liuhuanyong.github.io/


如有自然语言处理、[知识图谱、事理图谱]、社会计算、语言资源建设等问题或合作，如果对事件知识库有兴趣的落地或者研究，可联系我：    
1、我的github项目介绍：https://liuhuanyong.github.io  
2、我的csdn博客：https://blog.csdn.net/lhy2014  
3、about me:刘焕勇，中国科学院软件研究所，lhy_in_blcu@126.com  
4、懂语言者得天下，得语言者分天下，掌语言逻辑者，游得天下。 
