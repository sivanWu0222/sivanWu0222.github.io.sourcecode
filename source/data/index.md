---
title: data
date: 2019-11-07 12:18:48
---
# 数据



google 关键字：face image to 3d model, dataset






[以下参考](http://www.face-rec.org/databases/)
[60 Facial Recognition Databases](https://www.kairos.com/blog/60-facial-recognition-databases)


## 相关(按相关性从高到低)

[BJUT-3D中国人脸数据库](http://www.bjpu.edu.cn/sci/multimedia/mul-lab/3dface/facedatabase.htm)
BJUT-3D是一个包括500个中国人的三维人脸数据库。数据库中有250位女性和250位男性。每个人都有3D人脸数据，具有中性表情，无需附件。原始高分辨率3D人脸数据是由Cyber​​Ware 3D扫描仪在给定环境中获取的，每个3D人脸数据均已进行了预处理，并切掉了多余的部分。现在，人脸数据库仅可用于研究目的。北京工业大学多媒体与智能软件技术北京市重点实验室，是数据库分发的技术代理，并保留数据库中所有数据的版权。

[PhotoFace：使用光度立体的人脸识别](http://www.uwe.ac.uk/research/photoface)
这个独特的3D人脸数据库是目前最大的3D人脸数据库之一，包含3187个453个主题的会话，在两个大约六个月的记录期内捕获。Photoface设备位于不受监督的走廊中，可以进行真实世界的无限制捕获。每个环节包括四张主题照度不同的彩色照片，可以从中计算出表面法线和反照率估计值（包括光度立体Matlab代码实现）。这允许许多测试方案和数据融合方式。为了对齐目的，已在每个会话上手动定位了11个面部标志。另外，提供了Photoface查询工具（在Matlab中实现），该工具允许根据所选的元数据（例如性别，面部毛发，姿势，表情）提取数据库的子集。


[3D遮罩攻击数据库（3DMAD）](https://www.idiap.ch/dataset/3dmad)

3D掩码攻击数据库（3DMAD）是生物特征（面部）欺骗数据库。它当前包含76500帧，每人17帧，使用Kinect记录下来，用于实时访问和欺骗攻击。每帧包括：（1）深度图像（640x480像素– 1x11位）；（2）相应的RGB图像（640x480像素– 3x8位）；（3）手动注释眼睛位置（相对于RGB图像）。针对所有主题，在3个不同的会话中收集了数据，并且每个会话都捕获了300帧的5个视频。记录是在受控条件下进行的，具有正面视图和中性表情。前两个会话专用于实际访问样本，其中记录主题的时间间隔为两次获取之间的间隔约为2周。在第三部分中，单个操作员（攻击者）会捕获3D面具攻击。如果您使用此数据库，请引用此出版物：N. Erdogmus和S. Marcel。”“使用3D蒙版进行2D面部识别中的欺骗和使用Kinect进行防欺骗 ”，在IEEE第六届国际生物识别技术会议：理论，应用和系统（BTAS）中，2013年。再现本文实验的源代码：https：// pypi。 python.org/pypi/maskattack.lbp

[EURECOM Kinect人脸数据集（EURECOM KFD）](http://rgb-d.eurecom.fr/)
数据集由使用Kinect传感器采集的52人（14位女性，38位男性）的多模式面部图像组成。在两个会话中以不同的时间间隔（大约两周）捕获数据。在每个阶段中，根据不同的面部表情，光线和遮挡条件从每个人收集9张面部图像：中立，微笑，张开嘴巴，左轮廓，右轮廓，闭塞的眼睛，闭塞的嘴巴，用纸和纸遮盖的侧面点亮。为所有样本提供了RGB彩色图像，深度图（作为位图深度图和包含Kinect感测的原始深度级别的文本文件）以及相关的3D数据。此外，该数据集还包括每个脸部的6个手动标记的地标位置：左眼，右眼，鼻尖，嘴巴左侧，右边的嘴巴和下巴。还提供其他信息，例如性别，出生年月，种族，眼镜（一个人是否戴眼镜）以及每个会话的时间。



[德州3D人脸识别数据库（Texas 3DFRD）](http://live.ece.utexas.edu/research/texas3dfr/)
德州3D人脸识别数据库（Texas 3DFRD）包含1149对105名成人受试者的脸部颜色和范围图像。这些图像是在Iris International，Inc.（加利福尼亚州查茨沃斯）的子公司Advanced Digital Imaging Research（ADIR），LLC（德克萨斯州Friendswood）的公司购得的，并得到了图像和图像实验室的研究学生和教职员工的帮助。德克萨斯大学奥斯汀分校的视频工程（LIVE）。该项目由美国国家标准技术研究院（NIST）的高级技术计划赞助。该数据库由UT Austin的Alan C Bovik博士提供。使用立体成像系统以0.32 mm的高空间分辨率获取图像。彩色和范围图像是同时捕获的，因此可以完美地彼此对齐。所有脸部均已标准化为正面位置，并且鼻尖位于图像中心。这些图像是来自所有主要种族和性别的成年人类。对于每张脸，还可以获得有关受试者的性别，种族，面部表情以及25个人体测量基准点位置的信息。使用基于计算机的图形用户界面将这些基准点手动定位在面部彩色图像上。LIVE所采用的特定数据分区（培训，画廊和探针）用于开发 种族，面部表情和位置25人体测量面部基准点。使用基于计算机的图形用户界面将这些基准点手动定位在面部彩色图像上。LIVE所采用的特定数据分区（培训，画廊和探针）用于开发 种族，面部表情和位置25人体测量面部基准点。使用基于计算机的图形用户界面将这些基准点手动定位在面部彩色图像上。LIVE所采用的特定数据分区（培训，画廊和探针）用于开发人体测量3D人脸识别算法也可用。


[LFW3D和Adience3D集](http://www.openu.ac.il/home/hassner/projects/frontalize/)
正面化是合成单张不受约束的照片中出现的面孔的正面视图的过程。最近的报告表明，此过程可能会大大提高人脸识别系统的性能。通过将识别从不受约束的视点观看的面部的挑战性问题转换为识别受约束的，面向前方的姿势的面部问题的较简单问题。作者提供了广泛使用的野外标签脸（LFW）的正面版本（用于面部身份验证）和Adience集合（用于年龄和性别分类）。这些集合（LFW3D和Adience3D）与我们用于正面化的方法的实现一起提供。




[巴塞尔人脸模型（BFM）](http://faces.cs.unibas.ch/)
巴塞尔人脸模型（BFM）是一个3D可变形人脸模型，由100个男性和100个女性示例面孔构成。BFM由一个生成的3D形状模型和一个高质量的纹理模型组成，该模型覆盖了从耳朵到耳朵的整个脸部表面。该模型可以直接用于2D和3D人脸识别，也可以针对任何成像条件生成训练和测试图像。因此，除了是用于人脸分析的有价值的模型之外，它还可以看作是元数据库，可以创建准确标记的合成训练和测试图像。为了与其他算法进行公平比较，我们提供了训练数据集（BFM）和通过我们的拟合算法获得的几个标准图像数据集（CMU-PIE，FERET）的模型拟合结果。BFM网页还提供了一组对十个人的扫描记录，以及这些人的270张具有系统姿势和光线变化的渲染图。这些扫描不包括在BFM的训练集中，而是形成具有姿势和照明基本事实的标准化测试集。

[Face Recognition Database](http://cbcl.mit.edu/software-datasets/heisele/facerecognition-database.html)


[博斯普鲁斯海峡数据库](http://bosphorus.ee.boun.edu.tr/default.aspx)
Bosphorus数据库是一个新的3D人脸数据库，其中包含丰富的表情集，姿势的系统变化以及不同类型的遮挡。该数据库从三个方面是独特的：（1）面部表情由明智选择的动作单元子集和六个基本情感组成，并且结合了许多演员/女演员以获得更真实的表情数据；（2）有丰富的头部姿势变化集；（3）包括不同类型的面部遮挡。因此，该新数据库对于开发和评估在不利条件下的面部识别和面部表情分析算法以及面部表情合成算法而言，可能是非常有价值的资源。

[UMB遮挡的3D人脸数据库](http://www.ivl.disco.unimib.it/umbdb/)
米兰比可卡大学3D人脸数据库是多模式（3D + 2D彩色图像）人脸采集的集合。该数据库可用于对人脸检测，人脸识别，人脸合成等感兴趣的大学和研究中心。UMB-DB的购买重点是人脸遮挡，例如围巾，帽子，手，眼镜和其他类型的遮挡这可能发生在现实情况中。

[3D_RMA数据库](http://www.sic.rma.ac.be/~beumier/DB/3d_rma.html)
3D_RMA数据库是由120人组成的两个会话（1997年11月和1998年1月）的集合。对于每个阶段，以不同（但受限）的头部方向记录三张照片。有关人口的详细信息和影响质量的典型问题在参考链接中给出。3D的捕获归功于基于结构化光（模拟相机！）的专有系统的第一个原型。质量受到限制，但足以显示3D人脸识别的能力。出于隐私原因，纹理图像不可用。在2003年至2008年期间，该数据库已被大约100位研究人员下载。一些论文介绍了数据库的识别结果


[GavabDB：3D人脸数据库，GAVAB研究小组，西班牙雷伊·胡安·卡洛斯大学](http://gavab.escet.urjc.es/recursos_en.html)
GavabDB是3D人脸数据库。它包含549张面部三维图像。这些网格对应于每个人具有9个图像的61个不同的个体（45个男性和16个女性）。这些人的总数为白种人，年龄在18至40岁之间。每个图像都由连接的面部表面3D点的网格提供，没有纹理。该数据库提供有关姿势和面部表情的系统变化。特别是，每个人对应的9张图像为：2个具有中性表情的正面视图，2个具有中性表情的x旋转视图（分别为±30o，向上和向下），2个y旋转视图（±90o，左右轮廓）分别带有中性表情和3个正面手势图像（笑，微笑和用户选择的随机手势），



[FRAV3D数据库](http://www.frav.es/databases/FRAV3d/)
该数据库包含106个主题，每三个男人大约有一个女人。使用Minolta VIVID 700扫描仪获取数据，该扫描仪提供纹理信息（2D图像）和VRML文件（3D图像）。如果需要，可以通过VRML文件计算相应的距离数据（2.5D图像）。因此，它是一个多峰数据库（2D，2.5D和3D）。在所有时间内，始终遵循严格的采集协议，并控制照明条件。该人坐在扫描仪对面的可调节凳子上，在蓝墙前。禁止戴眼镜，帽子或围巾。在每个会话中，每个人一共拍摄了16个具有不同姿势和光照条件的捕获，试图涵盖所有可能的变化，包括不同方向的转弯，手势和光照变化。在每种情况下，两次捕获之间仅修改了一个参数。这是该数据库相对于其他数据库的主要优点之一。该数据库是专门为研究目的免费提供的


[MORPH数据库（颅面纵向形态面部数据库）](https://uncw.edu/oic/tech/morph.html)
MORPH纵向数据库是世界上最大的纵向面部识别数据库。它包含40,395个主题的202,038个独特图像。受试者年龄为15至80岁，中位年龄为31.87岁。每个对象的平均图像数量为5，连续照片之间的平均时间为251天，最小为1天，最大为3,506天（9年和221天）。图像之间的天数标准偏差为308。单个对象的图像之间的最大持续时间为3,976天（10年和326天）。该数据库已获得开发和商业使用许可。有关MORPH数据库的其他信息，请参见[此处](https://uncw.edu/oic/tech/morph.html)。有一个单独的版本，即“学术MORPH数据库”，可用于学术用途。它是图像和相关元数据的缩写版本，可[在此处获得](https://ebill.uncw.edu/C20231_ustores/web/classic/product_detail.jsp?PRODUCTID=8)。


[BU-3DFE数据库（静态数据）](http://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)
BU-3DFE（宾汉姆顿大学3D面部表情）包括100个具有2500个面部表情模型的对象。BU-3DFE数据库可供研究界使用（例如，感兴趣的领域来自情感计算，计算机视觉，人机交互，安全性，生物医学，执法和心理学）。该数据库包含100位受试者（女性56％，男性44％），年龄从18岁到70岁不等，具有多种种族/种族血统，包括白人，黑人，东亚，中东，印度，和西班牙裔拉丁裔。[参考](http://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)

[BU-4DFE数据库（动态数据）](http://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)
为了分析从静态3D空间到动态3D空间的面部行为，扩展了BU-3DFE数据库并形成了一个新数据库：BU-4DFE（3D +时间）：一个3D动态面部表情数据库。介绍了一个新创建的高分辨率3D动态面部表情数据库，该数据库可供科研界使用。以视频速率（每秒25帧）捕获3D面部表情。对于每个对象，有六个模型序列分别显示六个原型面部表情（愤怒，厌恶，幸福，恐惧，悲伤和惊奇）。每个表达序列包含约100帧。该数据库包含从101个对象中捕获的606个3D面部表情序列，共有大约60,600个帧模型。3D视频序列的每个3D模型的分辨率约为35，000个顶点。纹理视频具有每帧约1040×1329像素的分辨率。结果数据库由58位女性和43位男性受试者组成，具有各种种族/种族血统，包括亚洲人，黑人，西班牙裔/拉丁美洲人和白人。

[BP4D自发数据库](http://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html)
由于姿势和不姿势（又称“自发”）3D面部表情在多个方面（包括复杂性和时机）不同，因此，需要对姿势不正确的面部行为进行充分注释的3D视频。因此，引入了新开发的，在各种各样的年轻人中自发性面部表情的3D视频数据库-BP4D-Spontanous：宾汉顿-匹兹堡3D动态自发性面部表情数据库。经过充分验证的情绪诱导被用来表达情绪和副语言沟通。使用面部动作编码系统获得面部动作的帧级地面真相。使用特定于人的方法和通用方法在2D和3D域中跟踪面部特征。该作品促进了微妙的面部表情中3D时空特征的探索，更好地了解面部动作单元中姿势与运动动力学之间的关系，并更深入地了解自然发生的面部动作。该数据库包括41名参与者（23名女性，18名男性）。他们是18-29岁；亚洲人11个，非裔美国人6个，西班牙裔4个，欧洲裔20个。情感激发协议旨在有效激发参与者的情绪。八项任务涵盖了采访过程和一系列引发八种情绪的活动。该数据库由参与者构成。每个参与者与8个任务相关联。对于每个任务，都有3D和2D视频。同样，元数据还包括手动注释的动作单位（FACS AU），自动跟踪的头部姿势和2D / 3D面部标志。该数据库的大小约为2。

[3DFace](https://github.com/Juyong/3DFace)
该数据集包含CoarseData和FineData，该数据使用3DFaceNet：通过合成真实感人脸图像进行实时密集人脸重构中所述的方法从300-W的 3131张图像中扩增而来。CoarseData是通过更改原始图像的姿势和表情来构造的。FineData是通过将细节从其他图像传输到原始图像而构造的。对于CoarseData和FineData，我们将每个图像放大30倍。

[Florence 2D/3D Face Dataset](http://www.micc.unifi.it/masi/research/ffd/)


## 其他未列出的
[总揽](https://areeweb.polito.it/ricerca/cgvg/3DDB.html)
[总揽](https://www.kairos.com/blog/60-facial-recognition-databases)

----------


## 可能相关

[CAFE-儿童情感表情集](http://childstudycenter.rutgers.edu/Child_Affective_Facial_Expression_Set.html)
尽管有大量研究检查情感面部表情的感知，但几乎所有的研究都集中在成人面部表情的感知上。有几种极好的成人面部表情刺激集可以轻松获得并用于科学研究（即NimStim，Ekman脸部）。但是，尚没有对儿童情感表情的完整刺激集，因此对儿童制作情感表情的知觉研究很少。为了充分理解人类如何应对和处理情感面部表情，重要的是要通过多种方式进行这种理解。儿童情感面部表情集（CAFE）是首次尝试创建庞大且具有代表性的儿童集，这些儿童制作了各种情感面部表情，可用于该领域的科学研究。该场景由1200幅超过100个儿童模型（2-8岁）的照片组成，这些照片中有7种不同的面部表情-快乐，愤怒，悲伤，恐惧，惊奇，中立和厌恶。


[MIT-CBCL人脸识别数据库](http://cbcl.mit.edu/software-datasets/heisele/facerecognition-database.html)
MIT-CBCL人脸识别数据库包含10个主题的人脸图像。它提供了两个训练集：1.高分辨率图片，包括正面，半轮廓和轮廓视图；2.从10个对象的3D头部模型渲染的合成图像（324个/对象）。头部模型是通过将可变形模型拟合到高分辨率训练图像而生成的。3D模型不包括在数据库中。测试集每个受试者包含200张图像。我们改变了照明，姿势（深度约达30度旋转）和背景。

[有效数据库](http://ee.ucd.ie/validdb/)
为宗旨，以促进强劲的音频，脸，多模态人识别系统，大的和现实的多模态的发展（视听）有效的数据库是在嘈杂的“真实世界”的办公情景收购上没有控制照明或声音噪声。该数据库由五个记录阶段组成，每个阶段记录106个主题，历时一个月。在具有可控照明且无背景噪音的演播室中录制一个会话，在办公室类型场景中录制另外四个会话。该数据库包含分辨率为720x576像素的未压缩JPEG图像。

[VidTIMIT数据库](http://conradsanderson.id.au/vidtimit/)
VidTIMIT数据库由43人的视频和相应的音频录音组成，其中包含简短的句子。它对于诸如多视图面部识别，自动唇读和多模式语音识别等主题的研究非常有用。该数据集记录了3个会话，每个会话之间间隔了大约一周的时间。每个人有10个句子，选自TIMIT语料库。除句子外，每个人在每个会话中都执行头部旋转顺序。该序列包括人的头向左，向右，回头到中心，上，下然后最后返回中心。录制是在办公室环境中使用广播质量的数码摄像机完成的。每个人的视频都存储为JPEG图像的编号序列，分辨率为512 x 384像素。


[IIIT-野外的卡通面孔](http://cvit.iiit.ac.in/research/projects/cvit-projects/cartoonfaces)
IIIT-CFW是野外卡通面孔的数据库。它是从Google图片搜索中获取的。查询词（例如，奥巴马+卡通，莫迪+卡通等）用于收集100位公众人物的卡通图像。数据集包含8928个带有注释的卡通面孔，这些面孔是世界各地不同专业的知名人物。此外，我们还提供了1000位公众人物的真实面孔来研究跨模式检索任务，例如Photo2Cartoon检索。IIIT-CFW可用于研究各种问题，例如人脸合成，异构人脸识别，交叉模式检索等。（请仅将此数据库用于学术研究）

[CAFE-儿童情感表情集](http://childstudycenter.rutgers.edu/Child_Affective_Facial_Expression_Set.html)
尽管有大量研究检查情感面部表情的感知，但几乎所有的研究都集中在成人面部表情的感知上。有几种极好的成人面部表情刺激集可以轻松获得并用于科学研究（即NimStim，Ekman脸部）。但是，尚没有对儿童情感表情的完整刺激集，因此对儿童制作情感表情的知觉研究很少。为了充分理解人类如何应对和处理情感面部表情，重要的是要通过多种方式进行这种理解。儿童情感面部表情集（CAFE）是首次尝试创建庞大且具有代表性的儿童集，这些儿童制作了各种情感面部表情，可用于该领域的科学研究。该场景由1200幅超过100个儿童模型（2-8岁）的照片组成，这些照片中有7种不同的面部表情-快乐，愤怒，悲伤，恐惧，惊奇，中立和厌恶。


[BAUM-1：Bahcesehir大学自发性情感和心理状态的多模态面孔数据库](http://mimoza.marmara.edu.tr/~cigdem.erdem/BAUM1/)
在情感计算应用程序中，访问标记的自发情感数据对于在自然和挑战性的条件下测试设计的算法至关重要。当今可用的大多数数据库已运行或不包含音频数据。BAUM-1是自发的情感和精神状态的视听情感面部数据库。数据库中的视频剪辑是通过使用立体摄像机从正面视图录制对象并使用单声道摄像机从半侧面视图录制对象而获得的。首先为对象显示一系列图像和短片，它们不仅经过精心设计，而且还定时唤起一组情感和精神状态。然后，他们以无脚本和无指导的方式用土耳其语表达他们对观看的图像和视频片段的想法和感受。目标情绪 包括六个基本要素（幸福，愤怒，悲伤，厌恶，恐惧，惊奇）以及无聊和蔑视。我们还针对几种不确定的心理状态，包括不确定的（包括困惑的，不确定的），思维的，专注的和烦恼的。BAUM-1数据库上的基线实验结果表明，在自然条件下识别情感和心理状态非常具有挑战性。该数据库有望在接近真实的情况下，进一步开展视听效果和心理状态识别方面的研究。BAUM-1数据库上的基线实验结果表明，在自然条件下识别情感和心理状态非常具有挑战性。该数据库有望在接近真实的情况下，进一步开展视听效果和心理状态识别方面的研究。BAUM-1数据库上的基线实验结果表明，在自然条件下识别情感和心理状态非常具有挑战性。该数据库有望在接近真实的情况下，进一步开展视听效果和心理状态识别方面的研究。


