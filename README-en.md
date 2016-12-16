# RocketMQ-Learning

<p align="center"><img src ="logo.png" alt="RocketMQ-Learning logo" /></p>

Even if you have never used RocketMQ, Through this tutorial, You will have a thorough understanding of RocketMQ.<br>

Why should i read this book?
* The purpose of this tutorial is to make up for <b>the lack of official documents</b> and <b>source code comments</b>.<br>
* Through this tutorial, You will have a <b>good use</b> of RocketMQ
* Through this tutorial, you can learn the <b>design principles</b> of RocketMQ, As well as the overall structure of RocketMQ
* Meanwhile, You will learn something about <b>network programming, operating system</b>...

It includes:

* The <b>design principles</b> of important modules, as well as code analysis
* <b>A detailed source code comments</b>
* Related information index, such as <b>Linux page cache</b>, <b>tcp/ip</b>, etc..

You can use this tutorial as a mini book, This tutorials' directory can be shown as follows.<br>

If you are using RocketMQ for the first time, it is recommended that you should start with the part1.

## Article Index

#### [1.Overview](book/1-overview.md)
* Glossary explanation
* Start your own example

#### [2.How components work together](book/2-components.md)
* RocketMQ' Architecture
* The flow of messages in the component:message send, message store, push/pull message, consume message.

#### [3.What is NameServer](book/3-nameserver.md)

#### [4.The core of RocketMQ - Broker(1)](book/4-broker1 overview.md)
* Broker's Responsibilities:Coordinate message flow, message store

#### [5.The core of RocketMQ - Broker(2)](book/5-broker2 commit log.md)
* Commit log's implementation

#### [6.The core of RocketMQ - Broker(3)](book/6-broker3 consume queue.md)
* How consume queue works

#### [5.The core of RocketMQ - Broker(4)](book/7-broker4 index service.md)
* Index Service

#### [6.Consumer](book/8-consumer.md)
* How messgaes are consumed

#### [7.Producer](book/ch1-components.md)
* How messages are sent 
* Order message 





