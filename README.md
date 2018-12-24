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

[]()



[]()

[]()


[]()

[]()

