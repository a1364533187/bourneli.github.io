---
layout: post
title: 《企业IT架构转型之道：阿里巴巴中台战略思想与架构实战》读后感
categories: [Review]
---



十一假期的尾声，终于读完了这本书。这本书记录了阿里巴巴中台战略从萌芽，发展，成形以及到能力输出的整个过程。通俗的理解就是：阿里的中台策略历经考验，非常高效，可以在阿里云上高效落地，有国企案例和时尚零售案例作为背书，值得信赖，大家都来阿里云改造现有的IT架构吧。

虽然有明显的广告印记，而且这本不到250页书竟然售价79元。但是，读完后确能够学到一些东西，

* 大企业通病--烟囱现象。
* 基于业务的技术分工，利于业务和技术的沉淀。
* 基于接口和服务的IT架构。
* 分布式事务，高并发服务，监控，限流等一些列系统架构。

结合到笔者本身的工作经验，对上面的部分观点比较认同。

彻底去除烟囱现象，必须有一个强有力的游戏规则指导其实施，否则由于利益关系，基本上不可能实现。举个例子，比如业务B是企业核心业务，有两个部门M和D分别对齐支持。部门B会根据服务给予M和D相应的回报。虽然M和D有明确的智能划分，但是M觉得能够胜任D的事情，所以做了一套与D类似的服务，建立了一个烟囱。M对B提供的服务，稍加改造就可以支持D，但是因为D不会给回报给M，所以M不支持D，D不得不自己开发一套相关的服务，建立起了另外一个烟囱。虽然上述重复造轮子的现象显然造成了资源的浪费，但是在这种利益交换的游戏规则下，这种方式是参与多方利益最大化的自然选择，烟囱现象不可避免。

基于业务的技术分工可以带来自发的业务沉淀，这一点笔者比较认同。技术在企业的价值就是服务业务，技术脱离业务没有任何商业价值。所以将这两者绑定在一起，一方面技术人员可以潜移默化的加深对业务的理解，开发出的平台或工具也更契合业务场景。另一方面技术人员开发的系统或工具都是与当前业务相关，所以很多公共的地方可以抽取和复用，提高工作效率，并形成完善的解决方案。所以，笔者非常认同此观点。

书中谈到了非常多的企业架构方面的分享，比如分布式事务，高并发服务，系统监控等。这些系统都是非常有技术含量的工作，需要大量的计算机软硬件开发人员的参与。但是，由于目前AI太过于火热，导致很多计算机开发人员都为了金钱，而不是个人喜好，投入到了全民AI的浪潮之中。趋利避害是人类天性，但是在跟风之前必须要对自己情况以及当前环境有清楚的认识。做任何事情，只要足够出色，一定可以得到相当丰厚的回报。所以，希望大家还是冷静的对待目前的AI泡沫。

当然此书提到的内容远远不止这些，以上是笔者的一点感悟，希望对读者有帮助。












