# 研发：

## 前端（FE，front end）：
  
- 语言：[JavaScript](https://baike.baidu.com/item/javascript)，[html](https://baike.baidu.com/item/HTML)，[css](https://baike.baidu.com/item/CSS/5457)，[typescript](https://baike.baidu.com/item/typescript)，[node.js](https://baike.baidu.com/item/node.js)
- 框架：[angular](https://baike.baidu.com/item/AngularJS/7140293?fr=aladdin)，[vue](https://baike.baidu.com/item/Vue.js/19884851?fr=aladdin)，[react](https://baike.baidu.com/item/react/18077599#viewPageContent)，[pwa](https://baike.baidu.com/item/PWA)等
> - 前端主要指页面开发，技术栈是基于浏览器可运行语言，即JavaScript，前端目前发展十分迅速，因为总需要有人做页面，需求量比较大。
> - 前端的难度在于，如何在需要加载数据量越来越大，图片越来越多的互联网环境下，保证网页的流畅性，以及在不同的浏览器之间，甚至移动端浏览器，原生应用（即app）之间进行协调和适配。
> - 目前前端进行的某些工作有替代服务端的趋势，比如页面跳转路由等。

## 后端（RD，research & development）

### 服务端：

- 语言：基本上所有的语言都可以用于后端开发，包括[Java](https://baike.baidu.com/item/java/85979)，[python](https://baike.baidu.com/item/Python/407313)，[go](https://baike.baidu.com/item/go/953521)，[c#](https://baike.baidu.com/item/c%23)，[php](https://baike.baidu.com/item/php/9337)，[ruby](https://baike.baidu.com/item/Ruby/11419)等
- 框架：每种语言都有自己的框架
> - 区别于前端，服务端主要是为页面提供数据的，需要与数据库进行交互，为产品提供数据服务。
> - 服务端目前的发展趋势是：
>   - [分布式](https://baike.baidu.com/item/%E5%88%86%E5%B8%83%E5%BC%8F%E7%B3%BB%E7%BB%9F/4905336?fr=aladdin)
>   - [微服务](https://baike.baidu.com/item/%E5%BE%AE%E6%9C%8D%E5%8A%A1%E6%9E%B6%E6%9E%84/18705784?fr=aladdin)
>   - [云服务](https://baike.baidu.com/item/%E4%BA%91%E6%9C%8D%E5%8A%A1/7843499?fr=aladdin)
>   - [高可用](https://baike.baidu.com/item/%E9%AB%98%E5%8F%AF%E7%94%A8%E6%80%A7/909038)
>   - [高并发](https://baike.baidu.com/item/%E5%B9%B6%E5%8F%91%E6%80%A7/10804188)
> - 挑战即是如何在以上的集中场景下保持服务的稳定性。

### 移动端：

- iOS开发：[oc](https://baike.baidu.com/item/Objective-C)/[swift](https://baike.baidu.com/item/SWIFT/14080957)
- android开发：[Java](https://baike.baidu.com/item/java/85979)/[kotlin](https://baike.baidu.com/item/Kotlin)
> 移动app的开发，没啥好说的。
  
### 数据：

#### 基础：

- [关系型数据库](https://baike.baidu.com/item/%E5%85%B3%E7%B3%BB%E5%9E%8B%E6%95%B0%E6%8D%AE%E5%BA%93/8999831)，即sql，主要产品有[mysql](https://baike.baidu.com/item/mySQL/471251)，[SQL server](https://baike.baidu.com/item/Microsoft%20SQL%20Server?fromtitle=sql+server&fromid=245994)，[oracle](https://baike.baidu.com/item/%E7%94%B2%E9%AA%A8%E6%96%87%E5%85%AC%E5%8F%B8/430115?fromtitle=Oracle&fromid=301207)等
- [非关系型数据库](https://baike.baidu.com/item/NoSQL/8828247?fr=aladdin)。即nosql，主要产品有[redis](https://baike.baidu.com/item/Redis)，[mongodb](https://baike.baidu.com/item/mongodb)，[Neo4j](https://baike.baidu.com/item/Neo4j)等。
> - 基础的数据库操作知识是一个后端程序员所必须具备的能力。
> - 目前数据库在向[分布式数据库](https://baike.baidu.com/item/%E5%88%86%E5%B8%83%E5%BC%8F%E6%95%B0%E6%8D%AE%E5%BA%93/1238109?fr=aladdin)发展。

#### 大数据：

- 技术栈：[Hadoop](https://baike.baidu.com/item/Hadoop)，[spark](https://baike.baidu.com/item/SPARK/2229312)
> - 大数据从Google的[hdfs](https://baike.baidu.com/item/hdfs/4836121?fr=aladdin)论文开始迅速发展，已经成为各大企业所急需的人才，而许多创业公司也针对大数据为主要业务进行创业。
> - 其实大数据从本质上说就是很多很多数据，但是因为其数据量及其庞大，使得分析处理速度很慢，因此大数据技术应运而生。
> - 目前发展我不清楚。

### 云：

- [iaas](https://baike.baidu.com/item/IaaS)，代表产品为aws，azure，阿里云
- [paas](https://baike.baidu.com/item/PAAS)，代表产品为cloud foundry，kubernetes
- [saas](https://baike.baidu.com/item/saas)，代表产品为Office，gmail
- [iot](https://baike.baidu.com/item/%E7%89%A9%E8%81%94%E7%BD%91/7306589?fromtitle=IoT&fromid=552548)
> - 云是所有软件的基础，即将传统的服务器放到互联网云端来提供服务，以达到高可用，高容错，横向扩容等诸多优势。
> - 目前iaas呈现三足鼎立的局面，paas势必会成为未来各大厂商的必争之地，而用go语言开发的kubernetes已经成为paas届无可争议的标准，所以go将会成为云服务人才的一大必备技能，saas没啥意义。

### 人工智能：

- 技术栈：python等语言，tensorflow等框架  
- [nlp方向](https://baike.baidu.com/item/nlp/25220#viewPageContent)
- [cv方向](https://baike.baidu.com/item/%E8%AE%A1%E7%AE%97%E6%9C%BA%E8%A7%86%E8%A7%89)
- [ml方向](https://baike.baidu.com/item/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0)
> - 与算法紧密结合的一个方向，是未来的趋势。

### 算法：

> - 设计推荐算法，广告算法等，对计算机基础技术要求最高的一个方向，也是公认最难的一个方向，不用写代码，主要是涉及运用计算机基础知识和数学知识来设计算法解决实际问题。

### 区块链

# 测试（qa，question & answer）：

## 测试开发：

> - 通常指自动化测试，这一部分不仅仅要进行普通的测试，还需要维护测试脚本，搭建测试环境，编写自动化测试框架，测试技能与开发技能并存。

## 普通测试：

> - 主要就是gui的测试，点点页面，测测功能。

# 运维（op，operation）：

> - 对应用进行日常的维护，可能还会涉及到应用的部署。
> [几种部署形式](http://www.appadhoc.com/blog/product-release-strategy/)

# 其他必备技能

- 计算机网络，即tcp/ip
- 算法基础
- 计算机理论基础

# 软技能

- [agile](https://baike.baidu.com/item/%E6%95%8F%E6%8D%B7%E5%BC%80%E5%8F%91/5618867?fr=aladdin)
