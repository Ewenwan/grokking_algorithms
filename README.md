# Grokking Algorithms

This is the code in my book [Grokking Algorithms](https://www.manning.com/bhargava).

Also check out [Python Tutor](http://pythontutor.com/), a great website that helps you step through Python code line by line.

## Errata

[Here's the errata page](http://adit.io/errata.html).

## Images

This repo also contains every image in Grokking Algorithms, in hi-res. These images are available for free for non-commercial use. If you use an image, please add "copyright Manning Publications, drawn by adit.io". You are welcome to use these images in any non-commercial teaching materials, presentations, etc.

## Contributing

- The examples in this book are in Python, but I'd like to get examples in Ruby, Javascript, C, and other languages too. Please add examples in other languages!
- I'm pretty responsive to PRs. That is the quickest way to contribute to this repo.

## 目录
[第一章 算法简介](https://blog.csdn.net/nfzhlk/article/details/80551522)
     
    二分查找比简单查找快； 
    O(logn)比O(n)快，当要查找的项变多时，O(logn)速度变快的更明显； 
    算法速度不是以秒来衡量的； 
    算法时间复杂度以增长速度来衡量； 
    算法时间复杂度用大O表示（这不是唯一的，也有用Sigma标示的）
    
[第二章 选择排序 Selection Sort ](https://blog.csdn.net/nfzhlk/article/details/80532587)
    
     你的计算机内存就像有很多抽屉集合的巨人。 
     你需要用数组或链表存储很多项 
     数组中存储的每项的存储位置是紧挨着的，是连续的。 
     在链表中，存储位置是不连续的，前一个位置中存储下一项的地址信息； 
     数组支持快速读取； 
     链表支持快速插入和删除； 
     数组中项的类型必须相同（比如，都是整型、浮点型等等）


[第四章 快速排序法 Quicksort ](https://blog.csdn.net/nfzhlk/article/details/80372456)

     分治法是将问题逐渐分解，变得越来越小，若你在使用分治法，那基础场景是空数组或只含有一项的数组； 
     若你在用快排算法，随机选取一项作为支点，快排的平均运行时间是O(nlogn)； 
     大O表示法中的常量有时候也起作用，这也是为什么快排法比冒泡法快的原因； 
     比较简单查找和二分查找，常量是不起作用的。因为当数组很大时，O(logn)比O(n)快多了。 



[第五章 哈希表 Hash tables ](https://blog.csdn.net/nfzhlk/article/details/80317570)

     你不需要自己实现哈希功能，你使用的编程语言会提供这项功能。
         你可以使用Python的哈希功能，也可以假设你会得到平均性能：常数时间。 
     哈希表是一个非常有效的数据结构，因为它很快而且将数据用不同的方式抽象成了数据模型，
         你随后会发现你一直在使用他们： 
     你可以用哈希功能和数组来实现哈希表 
     冲突是不好的，你的哈希功能要最小化冲突 
     哈希表在查找、插入和删除都很快 
     哈希表很适合对一种事物和另一种事物的关系进行建模 
     当负载系数大于0.7时，需要重新调整大小； 
     哈希表被用来缓存数据（比如，通过浏览器服务器） 
     哈希表可以避免重复项。


[ 第六章 广度优先搜索算法 breadth-first search（BFS）](https://blog.csdn.net/nfzhlk/article/details/80290952)

     广度优先搜索告诉我们是否有A点到B点的路径； 
     若是有，广度优先搜索算法可以找到最近的路径； 
     若是你有“找最短X”的问题，可以先将问题抽象成图，然后利用广度优先搜索来解决； 
     有向图带有箭头，箭头指出关系（rama—>adit 表示rama欠adit的钱）； 
     无向图没有箭头，表示相互指向（ross—rachel表示rachel和ross约会，ross和rachel约会）； 
     队列是FIFO的（先进先出）； 
     堆栈是LIFO的（后进先出）； 
     你需要校验这个人是否被加入过搜索列表。因此搜索列表需要一个队列，否则，你得不到最短路径。； 
     当你检查某人时，你需要确认不重复检查。否则，你会陷入死循环。


[第七章-Dijkstra's algorithm迪杰斯特拉算法](https://blog.csdn.net/nfzhlk/article/details/79949785)

     无权图适合用深度优先搜索算法; 
     迪杰斯特拉算法只适用于有权图; 
     迪杰斯特拉算法只适用于权值都是正数的图; 
     如果图中有父权值，需要使用Bellman-Ford(贝尔曼·福特)算法。

[第八章 贪婪算法 Greedy algorithms](https://blog.csdn.net/nfzhlk/article/details/80114311)

     贪婪算法可以快速找到局部最优解，从而找到全局的还不错的解决方案 
     NP完备问题么有快速解决方案 
     当遇到NP完备问题时，最好的选择方案是贪婪算法 
     贪婪算啊简单、高效，是最好的求近似解的算法。

[第九章 动态规划 Dynamic programming ](https://blog.csdn.net/nfzhlk/article/details/80159809)

     当你需要查找有限制的最优解时，动态规划是有效的； 
     当问题可以分解为互不相干的小问题时，动态规划是起作用的； 
     动态规划要用表格； 
     单元格中的值时我们需要的最优解； 
     每个单元格都是一个子问题，所以要好好想想怎样将问题分解为小问题； 
     对于动态规划的解决方案没有固定的公式。

[第十章 K-邻近算法 K-nearest neighbors]()

     我希望学完本章后，你有个印象，利用K-邻近算法可以处理很多不同的事情。
     机器学习是非常有趣的一个领域。你可以深挖，若是你喜欢的话。 
     K-邻近算法需要归类和回归，需要寻找K个最邻近的点； 
     分类=将不同类型分组 
     回归-预测反应（比如数字） 
     特征提取的意思是将事物（如水果或用户）抽象成数字标示的集合 
     在K-邻近算法中，选择好的特征项是非常重要的。


[其他算法](https://blog.csdn.net/nfzhlk/article/details/80248133)
     
树 

     让我们回到二分查找法的例子，当我们登陆Facebook时，
     它要去遍历一个大的数组来检查我们的用户名是否存在，我们说过，
     遍历数组最快的方式时二分查找法，但是有一个问题：每当有一个新用户注册时，
     你需要将它插入数组并对数组重新排序，因为二分查找法只能用于排序后的数组，
     若是你可以将新用户快速的插入正确的位置，是不是更好一些呢？ 

傅立叶变换 

     傅立叶变换是非常稀有的算法之一：聪明优雅。
     有数百万的使用场景。
     最好的学习媒介是 Better Explained（一个将数学介绍的通俗易懂的网站），
     傅立叶变换可以告诉你制作冰沙的原料，换句话说，给你一首歌，傅立叶变换可以将它拆成独立的音符。 
     这也证实了这种想法有很多的使用场景。比如，你可以将歌曲分解为旋律，然后找出你关注的。
     你可以低音增强和隐藏高音。傅立叶变换很适合处理信号，也可以利用它来压缩歌曲。
     首先，将音频文件分解成音符，傅立叶变换可以很精确的告诉你多少音符组成了整首歌，
     你可以将不重要的音符去掉，这正是MP3格式是如何工作的。
     音乐不是唯一的数字信号，JPG格式是另一种压缩格式，它也是这么工作的。
     人们可以利用傅立叶变换来预测地震和分析DNA。 
     你可以利用它来制作类似Shazam的app，它可以猜测正在播放的是哪一首歌。
     傅立叶变换有很多种用途，你若是钻研，会发现更多。

并行算法 

     下面的三个主题是有关可量测性的，可作用于大数据。
     现如今，计算机运行越来越快，若是你想让算法快一点，你可能等几个月计算机本身就会快很多，
     但是我们处在世纪末了，笔记本和台式机的cpu有很多核，若是让算法快一点，我们可以使它们运行在多个核上。 
     例如，这是个简单的例子。
     排序算法是最快的，时间复杂度是O(nlogn)，大家都知道，
     你不能在O(n)的时间内，对数组排序的—若你不用并行算法的话，用并行算法的快拍算法将数组排好序需要O(n). 
     并行算法很难设计，而且很难保证它们正确运行，运行时间能快多少页很难计量。
     有一点是确定的—时间节省并不是线性的，若是你的笔记本有2个核而不是单核，
     这并不意味着你的算法运行会比单核快一倍，这有很多原因。 
     管理并行性的开销。 假设有一个数组，有1000个元素需要排序，你怎么将这项工作分为2个核？
     每个分500个，然后将2个排好序的数组合并成一个大数组？合并2个数组也需要时间。 
     负载均衡—假设你有10项任务，你给每个核分配了5个任务。但是A核分到的都是简单的任务，
     所以10秒钟就完成了，但是B核分配到的任务都是很难的任务，它花费了1分钟，也就是说，
     当B核在工作时，A核空闲了50秒，你怎样分发工作，才能让每个核的工作任务都一样呢？

MapReduce 

     这是个并行算法而且它变得越来越流行了：分发算法。
     若是你的笔记本电脑有2个核或4个核，用并行算法是可以的，但是若是你需要上千个核呢？
     这样你可以写一个可以在多个机器上运行的算法了。
     MapReduce算法是一个流行的并行算法。
     你可以通过开源工具Apache Hadoop来使用它。

     为什么分发算法是有用的？ 
     假设你有一个表含有一亿行或者万亿数据，你需要运行一个非常复杂的SQL查询方法。
     你不能用MySQL，因为超过亿级行后，MySql就崩溃了。但是你可以通过Hadoop的MapReduce。 
     或者假设你有一个job清单，上面有很多要运行的job，每个job需要10秒，你有大约100万这样类似的job。
     若是你用一台机器，需要花费数周，但是若是用100台机器的话，只需要几天就可以了。 
     当你有很多工作要做而且要求很快完成的时候，分发算法是有用的。
     MapReduce由2个简单的步骤组成：map功能和reduce功能。

布隆过滤器和HyperLogLog（基数统计） 

     假设你正在使用Reddit（一个社交新闻网站），当某个人上传一个链接时，
     你需要判断他以前是否上传过，没有上传过的内容被视为有价值的。
     所以你需要识别出这个链接是否被上传过了。或者假设你在用谷歌，你正在爬出网页，
     你只想爬取没有爬去过的网页，所以你需要识别出这些页面以前是否被爬取过。 
     或者你在使用bit.ly，它可以使URL变短。你不想重定向用户到恶意网站，
     你有一个恶意网站集合，现在你需要判断这个URL是否在恶意网站集合里面。 
     这些例子有一个共同点，那就是有一个非常大的集合。

布隆过滤器 

     布隆过滤器提供了一个解决方案，这是一个概率数据结构。
     他给你的答案对的可能性比较大，但也有可能是错误的。
     除了Hash表，你也可以使用布隆过滤器来判断是否爬取过URL网页。
     Hash表可以给你一个精确的答案。但是布隆过滤器可以给你一个准确性很高的答案： 
     假阳性是可能的 谷歌可能会说，“你已经爬取过这个网页了”，实际上你并没有爬取过 
     假阴性是不可能的。若布隆过滤器说，“你没有爬取过这个页面”，那你肯定没有爬取过 
     布隆过滤器很伟大，因为它占用很小的空间。Hash表需要将每个爬取过的页面都存储下来，
     但是布隆过滤器并不需要。它们之所以伟大是因为在这些例子中，我们不需要精确答案。
     bit.ly可以说，“这个网站可能是恶意网站，你要小心！”

HyperLogLog算法 

     另一个类似的算法是HyperLogLog算法，假设谷歌要统计用户做了多少次不同的搜索，
     或者亚马逊要统计今天被所有用户访问过的额所有商品。查找这类问题的答案也很占空间。
     对于Google，它需要记录每一条搜索。当用户搜索什么时，它需要查询这个在日志中有记录了吗，
     若是没有，需要将它记录在日志中，尽管只是一天的数据，那日志的量也是非常巨大的。 
     HyperLogLog预测集合中的每项的值，和布隆过滤器很像。它不会给你一个准确的数值，
     但是答案是非常接近的而且使用的内存空间比起计算精确答案要少很多。 
     若你有很多数据而且也接受近似值，那么你可以试一下概率算法。

SHA算法 

     校验密码 
     比较文本 
     局部敏感哈希 
      SHA还有另一个重要的特征：它是局部敏感的。假设你有一个字符串，你为它生成了一个Hash值。 
      dog——-> cd6357 
      当你改变了这个字符串中的字符，然后重新生成Hash值时，这完全不同， 
      dot. ——-> e392da 
      
Diffie-Hellman算法（密钥交换协议算法） 

     我们提到Diffie-Hellman算法，是因为它优雅的解决了一个古老的问题。
     你怎样来加密消息使它只能被真正接收的人读取呢？ 
     最简单的方式是设置一个密码，比如a=1，b=2等等，如果你传送的是“4，15，7”，
     那么翻译过来就是“d，o，g”，但是我们必须都同一个这个密码才行，
     我们不能通过Email沟通，因为黑客有可能破解了我们的消息。
     真见鬼，就算我们面对面商议密码，有些人也有可能猜到它—因为它并不复杂。
     所以，我们是需要每天改变它。但是我们做不到两人每天见面，然后交换密码。 
     就算我们每天更换密码，这样简单的加密算法也很容易被破译，比如通过暴力算法。 

线性规划 

     我把最好的放在最后，线性规划是我认为的几个最酷的事情之一。
     线性规划是在给定限制下获得最优解。例如，你的公司生产两种产品—衬衣和手提袋，
     需要1米布料和5个扣子，手提袋需要2米布料和2个扣子。你有11米布料和20个扣子。
     每个衬衣可以卖2美元，手提袋卖3美元。你需要做多少个衬衣和手提袋才能使收益最大呢？ 
     另一个例子。你是一个政客。你想拉选票，调查发现（市场、研究等等），
     为了获取一个圣弗朗西斯科选民的投票，你需要花费1.5个小时，但是对于芝加哥选民来说，
     只需要花费1个小时，你至少需要500个圣弗朗西斯科选民支持，300个芝加哥选民的支持，
     你只有50天，一个圣弗朗西斯科选民花费2美元，芝加哥选民花费1美元，你的竞选资金是1500美元。
     你能最多得到多少选民的投票（圣弗朗西斯科+芝加哥）？ 
     这里，你需要最大化选票，你的资金和时间是有限的。 
     你可能会在想，你讨论的都是求最优解的话题，这与线性规划有什么关系？
     这些图的算法通过线性规划也可以解决，线性规划是一个通用框架。
     图的问题只是其中的一个子集，我想你被打击到了。 
     线性规划使用了单纯形算法。这是个复杂算法，这也是为什么我不放在本书的原因。
     你若是对最优解感兴趣，可以查看线性规划。
 
