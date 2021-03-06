# 第4章　数据建模

## 1. 第4章　数据建模 <a id="&#x7B2C;4&#x7AE0;&#x3000;&#x6570;&#x636E;&#x5EFA;&#x6A21;"></a>

面向数据库开发的应用软件，可以认为由三个部分构成：数据、功能、界面。

为企业建立信息化管理体系，需要以信息为核心，信息是由数据构成的，面向数据库的软件绝大部分数据都存放在数据库中，而软件功能就是围绕这些数据工作的，数据是企业管理的宝贵财富。

面向用户的软件功能可以这样描述其过程：用户通过界面调用软件功能，对数据库中的数据进行操作，或者读出数据，或者新增数据，或者修改数据，或者删除数据，如图4-1所示。

![](http://b.7dtime.com/B01N1216C4/images/00012.jpeg)

图4-1　面向数据库的应用软件示意图

软件设计围绕数据、功能、界面这三部分展开，可以划分成三项对应的工作：数据建模（数据库设计），功能逻辑设计，用户操作界面设计。当然，不要认死理，在实际工作过程中，这三项工作往往是穿插进行的，很少有团队会严格按照这种方式划分工作，或者只设计了数据库就投入研发，或者只设计了界面就投入研发，等等，但这并不表示某项工作不重要甚至可以省略，只是团队在管理中弱化了某些工作的交付物（工作过程在设计者头脑中进行，然后他们通过口头沟通的方式将头脑中的思想表达给团队其他成员），或者将某些工作转嫁给了研发人员而已，绝不能认为不需要这种设计工作。

本章从数据建模谈起。

