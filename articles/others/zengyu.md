# 腾讯副总裁曾宇：谈谈腾讯的技术价值观与技术人才修炼

> **作者简介**：曾宇先生，腾讯公司副总裁。 2002 年加入腾讯，曾负责腾讯研发线管理，后续担任互动娱乐事业群研发部总经理，负责游戏、互娱相关的技术研发及管理工作，2012 年升任公司 VP，16 年起主要负责移动互联网事业群技术管理工作，继续参与公司级技术管理工作。

## 正文

![1](http://img.blog.csdn.net/20171110111742770)

### 技术人员的核心素养

　　腾讯的职业发展通道大概有 6 级，1 级是初入者，2 级是有经验者，3 级是骨干，4 级是专家，5 级和 6 级是权威和资深权威。我认为 1、2 级主要是学习、执行、改进的循环，在这个过程中你的经验不断增长；3 级可以对交付负责，交付过程中持续思考和总结，跳出自己做的事情，宏观看待它们在整个战略中的位置，就可以走到 4 级。以前 Tony（编者注：腾讯主要创始人张志东，曾任职公司 CTO）对 4 级的要求就是什么事找这个人，他都能解决，自己解决不了就会主动去找其他资源来解决。我对技术通道4级的定义就是能在组织里起技术掌控的作用。

![2](http://img.blog.csdn.net/20171110111923079)

　　技术人员的成长一般有两个分支——在管理和在技术通道的发展。Tony 对四级专家的定义包含了三个维度：技术深度、大局观、影响力，技术深度是你的深度，大局观是你的广度，影响力其实是你的纵深，就是说这个东西多大限度辐射影响到同行，这是比较高屋建瓴的看法。

![3](http://img.blog.csdn.net/20171110111958209)

　　我认为一个技术人员或者专家、工程师最重要的核心素质是业务洞察力、技术视野和原创力，业务洞察力是指技术人员对价值点的识别，技术视野和原创力可以体现在价值输出，就是做出多少东西，解决了多少问题，最终解决方案有没有可借鉴性，有没有可以传递的价值。这三点最后就就转化为技术深度、大局观、影响力，串联起来就是我们最终对一个专家工程师的定义。下面举几个例子，来阐述一个优秀的专家工程师是什么样的。

![4](http://img.blog.csdn.net/20171110112044440)

　　首先讲一个业务洞察力的案例。大家都知道腾讯利润的增长很大程度上是由于游戏的增长，腾讯的游戏起飞是 2008 年，当时一个很大的增长动力是在 2007 年到 2008 年之间，我们签下了一批非常优秀的游戏，大部分来自韩国。但是这些引进的游戏有很致命的地方，就是做技术的人基本上完全不考虑安全问题。我们理一下这个逻辑：公司的增长来自于游戏，游戏的增长来自于引进，引进的游戏来自于韩国，韩国的游戏有致命的安全问题，所以，游戏的业务安全当时对公司来说具备战略意义。当时互娱业务安全的同事非常敏锐地洞察到这个事情的重要性，投入了很大精力去研究，经过长时间的摸索，深入的思考，和严酷的实战，形成了很多的解决方案，在很大程度上解决这个问题的同时，也为自己赢得了发展空间。

　　再来看 CF 透视外挂的例子，在技术上也是很有特点的。外挂之所以难以防范，是因为可以无成本的拿到客户端进行分析，我们作为防御方非常被动，所以团队同事开始把思考着眼点放在我方的优势上，那就是服务器在我们手里。最终大家设计了一个方案，使用从服务器下载的动态代码对客户端的坐标进行加密，这样我们可以几乎以零成本随时发布加密方案，而对抗方则需要花费比较大的力气进行破解，这样可以在架构上具备防御优势。当然还有很多挑战，比如每次读写坐标都需要加解密，这样对动态算法的性能要求就会很高，等等。但最终我们还是把这个方案做出来了。这个案例，我想说的是一个专家工程师应该在战略上认识到价值点，在方案选择上能看到各种各样的技术，在原创——算法优化、性能方面能做到极致，最终这个方案才是具备足够竞争优势的。
 
　　关于影响力，举个 3D 游戏的例子。大家知道做 3D 游戏不是简单的光照、投射，如果要让场景看起来非常真实自然，必须要有阴影在里面。但如果要把所有的细节，非常高精的模型去做投射，真实去追踪光线的话，基本上不可实现。互娱当时进行了原创，用的方法就是放弃 3D 直接处理这个阴影，根据这个像素的深度可能用一个 2D 的算法简单地把阴影描出来，叠到原来的图上面去，做这个效果肉眼也比较难看出来差异，但效率大大提升了。这样的方案对整个行业都是有影响力，可以说它规避了这里面最难的问题，但是实际上做的效果却是非常好。
 
　　在这里我希望总结一下技术的第一生产力意义，我认为技术解决了几个问题：**第一是赋能，第二是提效**。一方面，我认为可以把技术当做一个工具箱，也就是说技术是工具箱里面的工具，最后能加工出什么样的产品，肯定是产品策划说了算，由他去构思，但是技术的作用就是让工具箱里面的工具越来越多；另一方面，从技术的角度可以让产品研发的效率变高，带来的结果是创新尝试的次数可以更多，在同样的条件下，原来只能尝试十次，但现在可以允许你试一百次，留下十个点子，这十个点子最后有一个做成一个巨量级的产品，这是技术带来的。
 
　　我觉得我们做技术的不要妄自菲薄，也不要迷失方向。也许每个技术人员每天都应该反思，我在赋能和效率上到底有什么成就和贡献，如果每天只是 follow 产品的节奏，只满足于疲于奔命地实现产品的需求，我的效率上没有任何提升，能力上没有任何变化，不能比去年做出更多更好的东西，就应该反思我们作为技术负责人的责任是否已经尽到，我是否在本领域中没有任何的长进。

### 技术管理者的自我修炼

　　我们刚才说，技术发展有两个通道，一个是专家通道，一个是技术管理者的通道，这两个都是由专业来撬动的，技术管理者越往后发展，战略和人才这两块的重要性会越来越凸显，但最终都还是依托自己的专业。

![5](http://img.blog.csdn.net/20171110112208290)

　　战略需要你决定技术团队做什么事，怎样高效完成，从技术角度能看到未来什么方向；战略除了自己思考以外，还要依托整个团队的信息输入和思考，这时人才梯队就非常重要。随着团队不断发展，你的战略要越来越好，需要你看的东西越来越广，每个进来的人都应该变成你的一只眼睛，他能看到某些你看不到的东西，所以人才积累是战略的一个非常重要的要素。
 
　　要战略必须要人才，要人才就必须要专业，所以最终还是回到原点——专业。所谓专业怎么解读？举个 PC 时代的例子，如果一个游戏的下载时间过长，就会成为用户进入的一个高门槛，为了让游戏下载加速，技术团队提出了微端化的概念，做了一个 VFS 文件系统，先给用户一个最小的下载包，在用户玩的过程中，后台一点一点拉回数据，这个技术出来之后马上获得了成功，分享这个过程是想说明专业在里面起到的作用。这算是一个战略方向，要做一个微端，谁能提出这样的想法？有战略眼光，有深厚的技术基础，看到这个可能性，然后把产品做出来，这是一个技术管理者应有的素质，或者说他所带的团队应该具备的素质。
 
　　分享一段曾国藩的话，我认为用在技术管理者身上非常合适。他强调为官者要知人晓事，位居高位者以知人，晓事二者为职。知人是要能够看准人，要能够对人做评价考核和应用；晓事就是要知道怎么做事情。我认为，评价一个人最终是看他做出多少事情，做出多少贡献，所以所谓知人晓事，根本点在晓事，从管理的角度，晓事即知人。支持人做出贡献的，大部分人是靠经验，少数人则可以上升到方法的高度，差别在于泛化应用的层次会不一样。所以在看一个人的时候，判断他的成功是来自于过往经验还是来自于他的方法论，是非常重要的。再往底层看，人最本质的东西是事业心和悟性，事业心会决定他做事有多积极，悟性决定他的经验转换成方法的效率有多高，如果这两件事情都 OK 的话，这个人就是你需要的人。

![6](http://img.blog.csdn.net/20171110112257096)

### 工程师的提升路径

　　总体来说，工程师的自我修炼有两条分支，一个是走专家路线，一个是走技术管理者路线，不管哪个，专业都是你的基石，就是你最终的原创力，你在专业方法论上必须不断提升。如何提升？我有几点体会：
 
　　**第一，找到自己，知道自己在哪个位置上**。

　　你要知道自己的本心，你喜欢做什么样的事情，比如说你喜欢钻研，未来是专家的方向；比如说你喜欢一丝不苟把东西码得整整齐齐，也许做架构师、项目经理、运营策划都很适合你；如果你天马行空，对生活品质要求很高，我觉得很大可能你适合做一个产品经理。每个人都会有自己的特质，你心里对自己有清晰的定位是非常重要的，这个会决定你在前进的过程中会不会痛苦。

![7](http://img.blog.csdn.net/20171110112341837)

　　**第二，树立互联网企业的技术价值观——技术必须产生价值**。

　　不可否认历史上有很多伟大的人，做出了一些对社会发展起到非常重要作用的事情，例如无线电波的发明对我们的生活产生多大的影响，是不可估量的，但是这个东西在当时是没有用的。我想说的是技术能真正产生价值是非常重要的。举个反面例子：2006 年，3D 技术已经开始流行，看起来效果非常酷炫，而网易的回合制游戏《大话西游》也很火。所以当时我们有一个项目用最先进的 3D 技术，加上最火的游戏类型做了一款游戏，结果发现两个最好的东西加在一起并不等于是一个好的产品，3D 无法支撑多个客户端同时运行，而且当时 3D 制作成本相对较高，导致项目延期，最终放到市场上也不太被玩家认可。这个例子给我们的反思是，技术有没有创造价值？我们做的这款游戏，3D 酷炫效果给这个游戏带来的价值到底有多大？这个值得反思。我们在选择技术方向的时候，永远要考虑和洞察用户此刻最急需的是什么。

![8](http://img.blog.csdn.net/20171110112436733)

　　还有一个正面例子。Oren Etzioni 是一个数据科学家，他喜欢省钱，计划一个旅行时会提前几个月把机票买好，他觉得买得越早机票越便宜。有一次，他在飞机上很得意地和别人说“我这个机票几个月前买的，非常便宜”，那人就问他多少钱，他说这么多钱，那人说我是两周前买的，比你还便宜，他就崩溃了，下了飞机就开始找数据看，发现果然是这样。他就开始反思这个问题，看来并不是说买得越早机票就会越便宜。他是一个数据科学家，很会建模，他把影响机票的各种因素放在这个模型中，用了机器学习的算法，预测机票价格趋势的准确率可以高达80%。这个系统上线之后，每年航空公司损失几千万，大家都在用这款产品买便宜机票，这个产品最后被微软收购了。这就是技术深度带来的价值，也是他创造的价值。
 
　　**第三，在个人素质修炼方面，应该一直保持着好奇心和创新精神**。

　　所谓战略，就是决定做什么不做什么。概念上大家都希望做蓝海，不愿意做红海，而我的观点是真正意义上看得见的蓝海是不存在的，因为以现在的市场效率，它一旦被证明的时候一定已经变成红海了。所以蓝海只是一个临时意义上的东西，而红海是一个常态，真正创新、真正突破，真正要找蓝海市场，你需要从没有的地方去找，正如道德经所说“万物生于有，有生于无”。一个强势的产品可能会带动一个生态，这个叫做万物生于有，就像微信出来了，可以衍生出很多东西；而有生于无，就是指微信本来就是从没有的地方长出来的。

　　举个 IEG 的例子。逆战是我们自研的一个 FPS 游戏，一开始照着 CF 学习，采用了 3D 技术，用 unreal 引擎做的，当时没有人看好这个项目，能立项已经是很不容易了。但这个团队很热爱这个游戏，他们没有想到这个产品后来对公司的战略意义是什么，但他们坚持把这个做下来了，越做越好，最终这个项目做成了，而且这个团队起来之后，可以分支做自研 FPS 游戏这条线，这也算是万物生于有，有生于无的例子。也许从技术的角度上讲，更多要关注它不可能的地方，如果有人说这个不可能，可能属于我的机会真的来临了。

![9](http://img.blog.csdn.net/20171110112549432)

　　**第四，尽人心，知天命**。

　　做到你心目中最好的自己就可以，剩下的事情老天爷会安排。看这两张图，你看到的是左边万众敬仰、世界上唯一的球神乔丹，还是右边在街上跟一帮小混混玩篮球的乔丹？其实我想说，这两个人是同一个人，乔丹说“Just  play，have  fun，enjoy  the  game”。我十来年做技术的生涯，也有摔倒，我的感悟是修行即道，最重要的是你在不停进步，你在不断修行。谢谢大家！

![10](http://img.blog.csdn.net/20171110112641913)


----------


**转载声明**：本文转自微信公众号「腾讯大学」，[首发重磅 | 腾讯副总裁曾宇：谈谈腾讯的技术价值观与技术人才修炼](https://mp.weixin.qq.com/s?__biz=MzA5MTMyNzAzMQ==&mid=2651542761&idx=1&sn=c735d327278e57b616604d8c58455116&chksm=8b81ebb1bcf662a71784e364d3e6931083e7067821b75846f3ffde044348bcb099e160c34ebf&mpshare=1&srcid=1031rw5qpgOKekv3anJBVWZt&scene=21#wechat_redirect)。
