# python-data-analysis
 自己写的一些用Python数据分析的项目（陆续会加、东西）

 语言： Python 3.7
 
 工具： Jupyter Notebook
 
 相关库： Pandas, Numpy, Matplotlib, Seaborn, Wordcloud等

项目列表:
1. Titanic

	分析基于kaggle数据源 https://www.kaggle.com/c/titanic
	
	● 收集到数据源train.csv，文件内容为891名泰坦尼克号乘客的不完整数据，如姓名、年龄、性别、船舱、船票价格以及是否生存等信息；
	
	● 对train.csv进行数据清洗，包括补充少部分缺失数据，删除无用字段数据，基于源数据再制造便于分析的新字段数据等；
	
	● 利用pandas、matplotlib、seaborn等python库的数据透视、可视化等功能，对数据进行分析。数据集显示，891名乘客中仅有342人能逃过死神的魔爪，生存的大部分为女性，绝大部分男性在此次灾难中丧生。进一步探索当年泰坦尼克号沉船事故中乘客的存亡与其身份信息的关系，例如女性乘客存活率比男性乘客大很多（毕竟是在绅士国度，大灾大难面前还能Ladies First）；高级船舱的乘客比较经济船舱的乘客明显存活率更大；除以上之外，乘客的年龄、家庭关系也会对其存活有一定影响。
	
2. 仿照ELK的Dashboards分析统计ELK示例飞行数据

3. 西帝本西蒙斯的投篮分布统计分析

	侃侃球吧，西帝在NBA赛场上给人的感觉像是当代魔术师约翰逊，组织能力强，技术细腻，借助出色的身体天赋能够终结大部分近距离得分，唯一被人诟病的就是中远距离投篮了。
	
	做这次投篮分布图也可以看出，西帝很擅长篮下三秒区的终结，近距离区域的命中率特别高，西帝的投篮随着离篮筐距离越远，命中率就越低，三分线外更加不用说了，有看球的朋友应该对西帝本赛季唯二投进的三分球印象比较深，此外就没有其它亮点可言了。都说西帝的出手选择比较聪明（也有球迷说西帝进攻欲望冷淡...怂得像个弟弟，所以才叫西弟），从直方图可以看出，西帝极少会选择三秒区以外出手，就算是罚球线踏前两三步左右的出手也不算多，结合看球分析的话，我估计通常应该是碰到大个子正面防守，西帝也很聪明地选择分球给空位队友完成终结了。总体统计，即便投篮能力一般，西帝生涯常规赛命中率也能达到55.5%。最后是一个统计西蒙斯生涯的得分手段的词云图。当拿到NBA官方的投篮数据，不仅包括投篮位置点的坐标，还包括每次投篮的手段方式（接球方式、终结前的动作、终结方式，非常仔细）。我对数据进行了简单清洗，把空格删掉，甚至把官方的英文翻译成中文。最后生成词云图按照西帝的投篮照片。不难发现，很大部分完成得分的动作都是上篮，跳投次之，也有很多其他手段的得分，像空接、扣篮、勾手、打板投篮等。
