+++
title = "【迷途知返】2025 FDU Puzzle Hunt"
author = ["Zenith John"]
publishDate = 2025-05-03
tags = ["Essay", "Puzzle"]
draft = false
series = ["迷途知返"]
series_weight = 10
+++

## 活动介绍 {#活动介绍}

[FDU Puzzle Hunt](https://fduph25.fdupuzzle.fun/) 是复旦大学推理协会谜题分部策划的puzzle hunt解谜活动，面向校内同学与社会公众。2025年的 FDU Puzzle Hunt 名为 Final Deadline Upcoming，在 2025年4月18日至2025年4月27日期间举行。


## 做题进度 {#做题进度}

18 日 20:00 开始做题，大概 12 点左右完成了一区。周末完成了二区的小题，周一完成了二区的 Meta。这两部分都还算顺利。但是三区之中有很多非常厚的题，同时由于在工作日，做题的时间大幅减少，最终在 24 日晚的时候完成了三区的 Meta，并根据 Meta 反爆了三区各个小题的答案。从结果来看 Final Meta 并不困难，但是由于最开始对于字里行间的错误理解，导致我们把剩下的小题都做出来之后，才成功解出 Final Meta。最后在 25 日午夜时分完成了 Final Meta。


## 以下有剧透，特此警告 {#以下有剧透-特此警告}


## 总体评价 {#总体评价}

题量适中。有些题目（比如《解・密》《洪水》《本题不使用任何 metadata》）过于厚了，让人没有做的兴趣。很多题目的答案有一些巧思在里面，比如《本题不使用任何 metadata》的小题答案和对应的小题之间往往有联系，比如《破碎词句》需要补充叠词，而答案中刚好也有 GoGo 这样的“叠词”。不少题目采用了防爆机制，比如答案之前增加 answer，enter 等字样，比如《季姬击鸡记》的中间答案是拼音，比如《奇怪的旅程》的中间答案包含了缩写，比如《五行棋》的中间答案包含了代表长度的两个数字等等，制作组在这方面是下了一番功夫的。《奇怪的旅程》和《Self-Reference》都巧妙的使用了做两次。纸笔题也都有一些新意。综合来说，满分 100 分，可以给个 80 分吧。

LX（化名）:按 Bangumi 分值标准，给个 7 分。出了三个区的体量，规模在中上水平。Final Meta 没有用到分区 Meta 的答案，是我非常不满的一个要素。有些题目出得挺好，比如《洪水》，让我一下子就想到了 C(CBC)13 的《提交记录》。还比如《奇怪的旅程》，除了 ex ISO 这个答案以外，题目构思还是挺巧妙的。但是，有些题目提示还是太少了点。中文 Hunt 没有预设提示确实比较特立独行。


## 谜题选讲 {#谜题选讲}


### A Rule-Explorer's Adventure {#a-rule-explorer-s-adventure}

题面见 <https://fduph25.fdupuzzle.fun/puzzle/r2q2> 。

这是一道黑箱题，需要根据题目推测规则和答案。题面说每道题目有且仅有两解，所以猜测黑白之间没有区别，也就是黑白互换构成了所有可能的解。Set A 没有附加符号，最开始猜测旁边的数字是该行对应的黑白交换次数，但是进入 B 区之后在很快发现事实上并不是交替次数而是连通块的个数。在 C 区中增加了在网格内的数字，通过 C2-4 很容易继续猜测出其中的数字表示的的是周围的连通块个数。Set D 是一个难点，其中出现了新的元素星星。根据 D2-4 猜测星星的作用是把连通块对各个数字的影响增大为它面积的大小。基于对于 Set E 中巨大数据的观察，LX 提出了数字增长为 （面积）^（星星数量）。虽然能够解决包括 E9-11 之内的各个小题，但是却使得 D12-14 之中有多解。通过观察 D12-14，一个更合理的推测出现了，即每个连通块最多只能有一个星星。但是这样要如何解释 Set E 的巨大数字呢？注意到这些数字都出现在网格外，所以推测网格外的规则和网格内有不同。同时由 E3-6 注意到星星的位置对于网格外的数字有影响，进行一些猜测后发现连通块对侧边数字的影响是（面积）^（此连通块到边上各个连通块的星星数量之和）。在 Set F 中出现了负数，很容易想到 X 的作用是取相反数，对于题目进一步地解答发现 X 对于距离边上数字更远的块也依然有效。这样就得到了完整的规则：

-   左边/上边的数字=Ʃ (-1)^(左 / 上连通块 X 的数量) \*（面积）^（此连通块到左 / 上各个连通块的星星数量之和）
-   中间的数字=Ʃ (-1)^(此连通块 X 的数量) \*（面积）^（此连通块星星数量）
-   每个连通块最多只能有一个星星。

注意到 Final 中 A 是 9 个数相加，刚好 Set A 有 9 道小题。根据提示，“黑白相消，余数累和”，很容易发现指的是把每个区中的答案中黑白格的差的绝对值加起来得到最后一道小题所需要的数字。最后根据得到的规则涂色并象形，就得到了最终答案 AGE。

虽然这道题目没有将规则告诉参赛者，但是通过示例、同解题等等还是能够比较容易地发现规律，使得题目有一定难度但没有过于夸张。题目的各个部分环环相扣，是一道设计地非常巧妙的题目。


### 奇怪的旅程 {#奇怪的旅程}

题面见 <https://fduph25.fdupuzzle.fun/puzzle/r2q7> 。

其中有几个空是比较容易的，比如加勒比 Pirates， Kalahari 沙漠，Stalin 的故乡，没有与 Russia 接壤的前苏联国家，位于 Southasia，OPEC 的成员国，首都 Islamabad 等。但是其中的数字看起来是一个干扰项，完全找不到对应的东西，使得在做题的过程中对于后半句话的答案有很多不确定的地方。通过对于已知的答案进行分析，同时进行一些猜测之后，得到本次比赛最饱受争议的中间答案之一 take ex ISO letters。这里的 ex 可能是 extra 的缩写，但是这个缩写并不常用，使得这一中间答案不能被 nutri 爆出，致使此题被超过 20% 的完赛玩家认为是一道孬题。

得到这一中间答案之后，由于之前做过 [MiaoHunt](https://mh2023.puzzlehunt.cn/home) 的 Meta 《梦幻岛的隐藏秘密》，很容易想到要使用 2 位和 3 位国家之间多出来的字母进行提取。但是得到的字母显然元音过多，并不能组成单词。这时 LX 想到了可以使用货币代码之中多出来的字母。这时候，我忽然回想起当时在查几内亚的水库的时候记得凯乐塔水库好像是被印在货币上的，才反映过来第一道小题中的数字其实指的是货币的面值，后半句指的是对应的货币上的图案。根据这一发现，我们纠正了最开始对于第一个国家的错误猜测澳大利亚，发现其实是巴哈马。每个国家的 3 位国家代码和货币缩写多出的字母，再一次和第一步一样，根据原有题面给出的顺序进行排序，得到了第二个中间答案 half a dollar in rap。查询后得到最终答案 fifty cent。

回顾这道题，发现由于忽视了很多信息，因此走了弯路。比如没有将凯乐塔水库对应的货币面值 20000 和题面中的 20000 联系起来，没有对于 flavor text 中的“交易”这一提示重视起来。如果注意到了这些信息，无论是第一步还是第二步都会变得顺理成章。（不过我也要吐槽这个中间答案。）


### 谜神 {#谜神}

题面见 <https://fduph25.fdupuzzle.fun/puzzle/r3q3> 。（目前已无法抽卡，无法做题）

主要是为了宣传我开发的工具 <https://zenith-john.github.io/potior/#/chinese>。 在错乱诗小题中可以发现每个字的笔画数是不变的，通过在 Chinese Nutri 中使用 {\* 15}{\* 10}{\* 10}{\* 15}{\* 4}{\* 8}{\* 5} 进行搜索可以立刻找到上半句：踏破铁鞋无觅处。立刻得到要提取的字母“工”=I。

这道题使用了抽卡的形式，从各个方面提示你需要考虑概率，事实上有三个小题都是从不同的角度对于概率分布进行分析。这个形式还是比较有新颖的。即使有一个小题做不出来，考虑到已经给了字母的顺序，因此有着不错的容错。综合来看是不错的一道题。


### 必须修改的结论 {#必须修改的结论}

题面见 <https://fduph25.fdupuzzle.fun/puzzle/r3m> 。

在四月区的每道题做出来之后都会有一句导师评语。有点像 CCBC12 的《终结点E》，将导师评语和小题答案放在一起，同时联系题目的 Flavor Text，我们发现将小题的答案翻译成中文之后，中间会出现一个包含“日”的字，在去掉日之后，再加上一个符号所对应的部件，可以得到一个新的字，而这个字会出现在某一个导师评语之中，比如迷神的答案 ninja -&gt; 忍者 -&gt; 耂 + 🗡匕 -&gt; 老 -&gt; 第 7 题的导师评语“从小玩到老”。同时注意到这个导师评语刚好只有 5 个字母和 Ninja 的字母数相同，所以应该提取字母 a。根据这一规律，可以将所有的题目排成一个环，并得到最终的答案。这道题的容错非常不错，同时为反爆提供了便利。在开启 Meta 的时候我们组只做出了 9 道题，根据对于 Meta 的观察和《Self-Reference》的评语进行观察，猜测得到了答案只有 5 个字母的《找啊找朋友》的答案交易=TRADE。虽然还没有做出两道小题，但是基本上得到了环的结构，通过 Nutri 得到了最终答案 sleep all day。

这道题巧妙地利用了题目解出来之后的额外信息，利用了汉字部件化的优势，巧妙地在中文和英文之间相互转换，得到了一个环结构，同时得到了提取字母的方法。是一道很有意思的 Meta 题目。
