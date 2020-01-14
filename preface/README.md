# 写在一切之前

## 为什么要写这本书？

市面上关于编程入门的书多到无法想象，但是其中令人满意的却很少。事实上，写一本面向初学者的书比写一本面向专家的书更困难。面向专家的书籍，最重要的是专业性和正确性，而面向初学者的书籍在此基础上还要加上通俗性。市面上的一些书籍，在通俗性和正确性上往往二者不能兼顾。

对于初学者来说，给予错误资讯的危险性是极大的。如果你今天拿到一份乐谱准备练琴，练了一个月发现，调号就没看对。等你再去纠正，形成了肌肉记忆的手再想纠正回来就必须付出更多的代价。我虽然对于 Ruby 编程也算颇有经验，但也绝不能说内容 100% 的正确性。我也不敢想 Donald E. Knuth 老先生那样为第一个发现错误的准备 2.56 美金，此后每发现一个翻倍，这样我离破产基本上是不远的。维护这本书正确性的核心，除了反复校稿，更重要的就是秉持开放的态度，基于 GitHub 进行协作。欢迎大家自由为书籍纠错、 提意见。

至于通俗性，我觉得大家要有对编程难度的一个正确认知。如果你觉得编程对你很难，这里的「难」指的是「问题困难」还是「问题复杂」。「问题困难」往往是一些计算机科学学科强相关的内容，比如算法、数据结构、形式语言；而「问题复杂」常常是工程问题，里面的内容通常是你所熟知的，唯一的问题是你没有办法很好解构这个问题，将复杂的实际问题转换成一系列你熟悉的小问题。

我非常喜欢陶哲轩先生所写的《实分析》，因为他把一个「困难」的数学分析问题讲得很简单易懂，和他比起来我还差太远。好在这本书所涉及的问题，几乎都是后一类问题，很少会涉及前一类问题。所以大可不必妄自菲薄，你一定具备理解这本书内容的前置知识。同时，这本书会在每个章节后通过一系列复杂性逐渐上升的综合练习，让你可以慢慢解构问题，最终能够独当一面完成一个复杂的项目。

## 什么人适合读这本书？

- 想要了解编程的人
- 想要将编程作为自己工作而入门的人
- 想要学习 Ruby 编程语言的人
- 有一定编程基础，想尝试 Ruby 语言的人
- 有一定 Ruby 基础，想进一步理解 Ruby 的人

## 什么是 Ruby？

Ruby 是最初由 Matz（Yukihiro Matsumoto）于 1993 年开发，现在作为开源软件开发的语言。它可以在多个平台上运行，并在世界各地使用。尤其适合于网站的开发。

## 为什么选择 Ruby？

因为我喜欢 Ruby。

Ruby 是一门适合用来作为入门教学的语言。使用这门语言不需要对计算机组成原理有着比较深刻的理解。使用这门语言进行教学，我们不但可以学习形如面向对象等在工程中常用的范式，还可以掌握形如 Lambda 演算、元编程这样非常 Lisp 的特性。站在功利的角度来说，Ruby 不是一门非常大众的语言，虽然可能岗位相比 Java、PHP 少很多，但是相对的竞争的求职者也更少。但是，编程的工具绝不是一招鲜吃遍天的，10 年前所流行的框架放到今天可能多半已经被淘汰了。如果单靠一门技术就想在这个行业活到退休是非常困难的，但是这些框架背后的思想确是共通的。无论你最后会不会选择 Ruby 作为工作，都不妨碍我们用 Ruby 作为教学语言。

## 怎么阅读这本书？

我把这个书的设计理念定义为「在两座山脊之间寻找山谷」。这两座山脊分别是站在语言学习者角度语法使用的山脊，以及站在语言设计和实现角度对语言特性思考的山脊。

所谓「学而不思则罔，思而不学则殆」。如果只学习基本的语法使用，没有认清很多设计面向的场景，没有理解语言的思考方式，不但写出来的代码非常脏乱差，而且实际使用的时候往往不知从何下手。

这本书每个章节的开头会有一个颜色的标记 🟢 或者 🔵。🟢 表示这个章节是在自上而下讨论一个使用方法，而 🔵 则是在自下向上讨论具体的实现和思路。如果你是第一次接触编程，我推荐阅读顺序是先把所有 🟢 章节读完，再来读 🔵 章节。如果你是有一定编程经验，甚至是已经掌握一定 Ruby 编程能力的，可以同时阅读 🟢 和 🔵 章节。