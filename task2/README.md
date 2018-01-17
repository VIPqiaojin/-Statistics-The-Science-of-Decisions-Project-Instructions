# 项目介绍  
对于这个项目，你需要进行数据分析，并创建一个文档分享你的发现。你可以首先了解数据集，想想它可以用来回答哪些问题。然后，你应该使用 Pandas 和 NumPy 回答你感兴趣的问题，并编写一份报告，分享你的结论。你不需要使用统计学或机器学习知识来完成此项目，但是你需要在报告中声明，你的结论是暂时的，可能需要进一步改进。这个项目是开放性的，没有标准答案。

## 第一步 - 选择数据集  
  从下面的数据集中任选一个，在此项目中进行分析：  

  泰坦尼克号数据：包括泰坦尼克号上 2224 名乘客和船员中 891 名的人口学数据和乘客基本信息。你可以右键点击 该链接 选择“另存为”下载。你也可以在 Kaggle 网站上查看这个数据集的详细描述。这个数据集就是来自 Kaggle。  
  棒球赛数据：这个数据集包括从 1871 年到 2014年完整的棒球赛击球和投球数据，还包括防守数据、排名、球队数据、管理记录、季后赛数据等等。这个数据集含有很多文件，你可以任选一个你最感兴趣的展开分析。选择“逗号分开”的文件版本（comma-delimited version），其中有 CSV 格式文档。  
## 第二步 - 做好准备  
  最终，你需要提交一份报告（并与你的朋友、家人或同事分享）。在正式开始之前，让我们为此做好准备。我们建议你新建一个文件夹，包括： 

  报告文档，用来传达你的发现  
  你用来分析数据的任何 Python 代码  
  你分析的数据集（当然，提交的时候你不需要包括它）  
  你可以使用 IPython Notebook，这样，你可以在同一份文件里编写报告和提交代码。不然你可能只能分别提交报告和代码了。  

## 第三步 - 分析数据  
  思考你可以用数据集回答哪些问题，然后开始着手调查。

## 第四步 - 分享发现  
分析完数据以后，编写一份报告，分享你觉得最有意思的发现。

## 第五步 - 检查  
使用这个项目评估准则来检查你的项目。如果你已达到所有要求，可以继续提交你的项目。如果你发现还有改进的空间，不要迟疑，这就去做吧。

#### 注:使用 Anaconda Python 3.6 version *  


附:[数据字典链接](https://www.kaggle.com/c/titanic/data)  
Data Dictionary  
Variable	Definition	Key  
survival	Survival	0 = No, 1 = Yes  
pclass	Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd  
sex	Sex  
Age	Age in years	  
sibsp	# of siblings / spouses aboard the Titanic	 
parch	# of parents / children aboard the Titanic	 
ticket	Ticket number	 
fare	Passenger fare	 
cabin	Cabin number	 
embarked	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton  

Variable Notes  
pclass: A proxy for socio-economic status (SES)  
1st = Upper  
2nd = Middle  
3rd = Lower  

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5  

sibsp: The dataset defines family relations in this way...  
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)  

parch: The dataset defines family relations in this way...  
Parent = mother, father  
Child = daughter, son, stepdaughter, stepson  
Some children travelled only with a nanny, therefore parch=0 for them.

