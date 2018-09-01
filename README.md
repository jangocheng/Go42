# 《Go语言四十二章经》

作者：ffhelicopter（李骁）  时间：2018-04-15


## 起因
一直都很懒，所以这几年也没写什么东西。这次写《Go语言四十二章经》，纯粹是因为开发过程中碰到过的一些问题，踩到过的一些坑，感觉在Go语言学习使用过程中，有必要深刻理解这门语言的核心思维、清晰掌握语言的细节规范以及反复琢磨标准包代码设计模式，于是才有了这本书。

Go语言以语法简单、门槛低、上手快著称。但入门后很多人发现要写出地道的、遵循 Go语言思维的代码却是不易。

在刚开始学习中，我带着比较强的面向对象编程思维惯性来写代码，但后来我转变了思路，因为我发现，带着面向对象的思路来写Go 语言代码会很难继续写下去，或者说看了系统源代码或其他知名开源包源代码后，围绕着Struct和Interface来写代码会更高效，代码更美观。虽然有人认为，Go语言的Strcut 和 Interface 一起，配合方法，也可以理解为面向对象，这点我姑且认可，但开发中不要过意考虑这些。因为在Go 语言中，Interface接口的使用将更为灵活，刻意追求面向对象，会导致你很难理解接口在Go 语言中的妙处。

作为Go语言的爱好者，在阅读系统源代码或其他知名开源包源代码时，发现大牛对这门语言的了解之深入，代码实现之巧妙优美，所以我建议你有时间多多阅读这些代码。网上有说Go大神的标准是“能理解简洁和可组合性哲学”，的确Go语言追求代码简洁到极致，而组合思想可谓借助于struct和interface两者而成为Go的灵魂。

Function，Method，Interface，Type等名词是程序员们接触比较多的关键字，但在Go语言中，你会发现，其有了更强大，更灵活的用法。当你彻底理解了Go语言相关基本概念，以及对其特点有深入的认知，当然这也这本书的目的，再假以时日多练习和实践，我相信你应该很快就能彻底掌握这门语言，成为一名出色的Gopher。

这本书适合Go语言新手来细细阅读，对于有一定经验的开发人员，也可以根据自己的情况，跳开一些章节来看。最后，希望更多的人了解和使用Go语言，也希望阅读本书的朋友们多多交流。虽然本书中例子都经过实际运行，但难免出现错误和不足之处，烦请您指出；如有建议也欢迎交流。联系邮箱：roteman@163.com

祝各位Gopher们工作开心，愉快编码！

## 阅读

本书内容在github更新：https://github.com/ffhelicopter/Go42/blob/master/SUMMARY.md<br>
本书内容在简书更新：  https://www.jianshu.com/nb/29056963

## 交流

虽然本书中例子都经过实际运行，但难免出现错误和不足之处，烦请您指出；如有建议也欢迎交流。

联系邮箱：roteman@163.com 

