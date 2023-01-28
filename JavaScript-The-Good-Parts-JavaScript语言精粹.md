# JavaScript: The Good Parts - JavaScript语言精粹

## 图书信息

- 英文书名：JavaScript: The Good Parts
- 中文书名：JavaScript 语言精粹
- 作者：[美] Douglas Crockford
- 译者：赵泽欣 / 鄢学鹍
- 页数：正文 100 页 / 附录 47 页
- 英文出版社：O'Reilly Media
- 中文出版社：电子工业出版社
- 出版日期：英文原版 2008 / 简体中文版 2009
- 个人分类：前端 / JavaScript
- ISBN：978-7-121-17740-8

## 书评

写于2022年2月24日。

花了一下午时间，从头到尾读完了这样一本十多年前的老书。

老实说，Douglas Crockford的许多理念我都是不赞成的，比如说行末必须加分号。但就他关于“摘出一门语言的精简子集”这个观点，我真是非常赞成。

对比犀牛书和高程，*JavaScript: The Good Parts*精简到令人难以置信，很难想象这样小的一个一个子集也能写出优雅的代码，但Douglas确实做到了，还做得很好。当然了，犀牛书和高程越来越厚的原因也有很大一部分是因为JavaScript在不停更新，但相信我即使在今天，加入ES6之后的新版“Good Parts”，也不会超过两百页。

书中的很多东西已经被实现了。Douglas自创的Object.create真的被加入了正式语法中，当年他一直诟病的全局变量和作用域问题现在也随着let和const的加入而不再存在了。class的添加倒是不如他所愿，Douglas显然是不希望Java式的class去污染JavaScript的原型继承特性的，或许class的加入确实是个错误，但事已至此，我们已无从评价。而Douglas一直觉得及其智障的new关键字也仍保留着，我也和他一样觉得这东西确实是个糟粕，原型继承需要用new本来就很诡异。

事实上，Douglas Crockford自创的这个Simplified JavaScript，在加上let/const，for of，Promise(async/await)，模块以及JavaScript近些年来扩展的标准库之后（其实我个人还比较想加上箭头函数，另外函数式方法比如`Array#map`也是不得不加的），就已经基本成了一个Modern Simplified JavaScript了。

当然，Douglas Crockford有很多我个人认为算是偏见的观点。比如Douglas Crockford认为生成器是从Python抄来的对于JavaScript没啥用的特性，实际上这主要是为了在当时还没有Async/Await的JavaScript中配合Promise实现类似协程的体验，不过自从Async/Await落地后确实就没几个人在用生成器了。

在十多年前，Douglas Crockford用这本一百页的小薄书证明了JavaScript实际上可以是一门很好的语言。现在是很难想想这样一本书能造成什么样的影响，但在当时确实几乎是造成了轰动。即使现在看来，这本书仍旧有很多值得称道的洞见，而且对原型链的阐释也非常棒，仍旧是很推荐前端程序员阅读的。不过由于内容确实太陈旧，已经算不得必读了。