# crawler_code
Crawl unlabeded text from news sites.  <BR/>

zw:  <BR/>
人民日报1946-2003  <BR/>  <BR/>
mgw：  <BR/>
1.搜集主流蒙古文新闻网站；查看获取以新闻文本为内容的栏目地址。  <BR/>
2.分析不同网站栏目下，新闻页url的参数来源，有静态的、post传参和json传参；根据这些差异和网站结构，编写代码，获取url地址库集合。  <BR/>
3.分析不同网站的新闻页面，编写代码，迭代url地址库，获取文本并整合。  <BR/>
4.对文本进行预处理，主要是编码转换，把爬取下来的蒙科立编码数据转换为utf8（使用在线编码转换工具，迭代上传文本并把接受的结果保存）。  <BR/>
5.根据蒙语的特殊性，切分词缀；调用glove和word2vec工具，获取词频和词向量。  <BR/>