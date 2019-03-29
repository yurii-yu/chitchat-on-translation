# 译句讲评

图灵出版公司的编辑们在审稿及译者交流中收集了这些例句，它们的毛病比较典型。为避免其他译者犯同同样的错误，本节会详细指出问题所在，并给出修改之后的翻译。

## 例句1

> *A moment's reflection will convince the reader that it is extremely undesirable to change the pointers in every reference to A just because the first element of A is being deleted.*
> 
> 略加考虑，读者就会相信，非常不希望仅因为删除A的第一个元素就改变对A的所有引用。

原文整句话很长，译者将其分为三个短句，这是正确的处理。但有两个单词的翻译不到位：

* **convince**，一般做“说服、使相信”解，但“相信”的对象一般是某种陈述，所以这里取“使清楚明白/使认同”的意思更合适；
* **undesirable**，翻译为“不希望”比较勉强，“希望”一般必须是主体发出的动作，而这里的“非常不希望”没有明确主体，所以翻译为“讨厌、麻烦/不可取”更合适。

另外，the pointers in every reference 中的 **pointers** 在译文中漏掉了，这不是小问题，因为指针和引用是完全不同的概念。

改译

> 读者想想就会明白，如果仅仅删掉A的第一个元素，就得修改A的所有引用之处的指针，这种做法是极为麻烦的。

## 例句2

> *The problem we will consider arises in connection with writing a compiler program for the translation of COBOL and related languages.*
> 
> 我们将要考虑的这个问题的出现与为COBOL及相关语言编写一个编译器程序有关。

这是一句承上启下的话，它道明了问题发生的情境，以及下面要讨论的主题，实际上表达了两重意思。

译文的问题在于按照原文逐字翻译，导致译文不符合中文习惯，且没有断句，将两重意思挤到单个长句里，更增加了理解的难度。

另外还有几个单词翻译不当：

* consider 翻译为“考虑”并不合适，这里的意思明显是“探究、仔细思考”，而不是“纳入思考的范畴”；
* arises in connection with，意思是“与xx联系，就产生了”，翻译为“的出现与xx有关”较为生硬，且“为COBOL及相关语言编写一个编译器程序”作为中间成分过长，影响理解，所以整句可以改为“来自xx”。

改译

> 我们将要探究的问题来自这里：写一个用来翻译COBOL及相关语言的编译程序。

## 例句3

> *When a subroutine is written to handle a general case, it is expressed in terms of parameters. Parameters are values that govern the subroutine’s actions; they are subject to change from one call of the subroutine to another.*
> 
> 当编写处理一般情况的子程序时，通常是通过参数表示的。参数是支配子程序的操作的一些值；它们从子程序的一次调用到另一次调用是需要改变的。

这段译文的一大问题是逐字翻译，这个毛病不赘述。而且译者似乎没明白原文到底在说什么，所以译文的问题较多。

**when** 有两个含义，一个表示同时发生，一个表示条件，前者通常翻译为“当……的时候”，后者通常翻译为“如果/若”，这里的when显然是后一个意思。

“子程序通过参数表示”完全让人不知所云，这里的 **express** 并不是“表示/传达”的意思，而是 *to represent by signs* （用一些符号代表）的意思，所以expressed in terms of parameters也不是“通过参数表示”，而是“在外面看来就是一组参数”、“可以用一组参数来代表/描述”。

“参数是支配子程序的操作的一些值”不通顺，且action不是“操作”而是“行为”。

be subject to的意思不是“需要改变”，而是“改变的对象”，且根据原文，*one call of the subroutine to another* 的意思是“对子程序的这种调用和那种调用”，强调的是不同场景不同种类的调用，而不是相同场景的重复调用。

改译
> 如果要编写的子程序是用来处理一般情况的，那么它可以用一组参数来代表。参数是一些值，它们决定了子程序的行为。不同调用之间，子程序中变化的只有参数。

## 例句4
> *To get the best understanding of a problem or an issue, it’s important to view it from different perspectives. Someone may get usefully different insights by looking at the same data set depicted as both a bar chart and a pie chart.*
> 
> 【译文一】为了更好地了解问题和情形，从多个角度来观察是很重要的。例如，一组数据同时用柱状图和饼图来表示，会更加有表现力。
> 
> 【译文二】为了全面理解所面临的问题，必须从不同角度来对其进行审视。对于一张柱状图和一张饼图，人们可以从中得到不同的洞见，即使它们是由同一组数据绘制而成。

译文一直译成分更多，译文二意译成分更多，但两句译文各有优劣。

*the best understanding* 是最高级，译文一翻译为“更好地”错了；*different perspectives* 是复数，翻译为“从不同角度”容易让人误解为“换个角度”，且“对其进行审视”太累赘，直接说“审视”即可。

第二句的意思是，同一组数据，同时以饼图和柱图来表现，可能有助于某些人收获不同洞见。注意其中的 *usefully* 是副词，是用来修饰动词 **get** 的，而不是后面的 **insights**。不幸两句译文都没有发现这一点，而且译文一的“表现力”不够准确，译文二所使用的“即使”表示转折，原文并没有转折关系。

改译
> 为全面理解某个问题或主题，从多个不同角度来观察很重要。同一组数据如果同时用柱状图和饼图来表现，或许可以有效地帮助某些人得到其他深入发现。

## 例句5
> *You may not be aware of it, but chances are that you are already a regular user of machine learning technology.*
> 
>【译文一】或许你从未意识到，但很有可能你已是使用机器学习的常客。
>
>【译文二】您也许尚未意识到，在日常生活中我们每个人都在有意无意地享受或运用着机器学习技术。

第二种译法没有清楚表现 *but* 的转折关系，而且“日常生活中我们每个人都在有意无意地享受或运用着机器学习技术”属于译者自己的阐释，即便真的需要，也应当在认真比对上下文添加。

第一种译法也不够好，原文没有“从未”，**user** 翻译为“常客”不合适且搭配不当，因为“常客”是针对某个处所而言的，可以说“酒店的常客”、“景点的常客”，但不能说某种艺术的“常客”。其实 *regular user* 是很常见的说法，表示“常规用户”、“普通用户”，比如linux系统就有regular user和root user的分别。

改译
> 【改译一】其实你很可能已是机器学习的常规用户了，只是自己或许没意识到。
> 
> 【改译二】虽然你或许还不清楚，但极有可能已经是机器学习的常规用户了。

## 例句6

> *It may seem that the form of Fig. 15 would be preferable simply because that is how trees grow in nature; in the absence of any compelling reason to adopt any of the other three forms, we might as well adopt nature's time-honored tradition.*
> 
> 看上去图15的形式可能更可取，因为它反映了树在自然界中如何生长；也没有什么令人信服的理由接受其他三种形式，我们同样可以沿袭自然界的悠久传统。

**simple** 的意思没有翻译出来，*simple because*一般翻译为“仅仅是因为”，但不够顺畅，其实只要能表示原因和结果之间的直接联系即可。

**as well** 的意思也没有翻译出来，*as well* 一般翻译为“也/同样”，但译文里的“同样”明显不符合句意，查阅词典可知，as well在这里应该理解为precisely, exactly, just，也就是“直接”。

另外要注意的是原文中出现的分号，英文中的分号用来连接两个形式上相对独立，但意思紧密联系的完整句子，翻译成中文时可以将分号改为逗号，以关联词表示原有联系。

改译：

> 看来图15的形式更好，因为大自然里的树就是这么生长的，而且其他三种形式都缺乏足够有力的采纳理由，我们只管遵循大自然的古老传统就好。

## 例句7
> *There is an overwhelming tendency to make hand-drawn charts grow downwards instead of upwards (and this is easy to understand in view of the way we write).*
> 
> 有一种压倒性趋势，手工绘图时，树向下而不是向上生长（从我们手写方式角度，这也容易理解）。

这句译文是典型的“硬译”，而不是“直译”，英文的顺序和词性都保留下来，造成译文生硬晦涩。

这里的难点是 *overwhelming tendency*，硬译的结果当然是“压倒性优势”，这个词不好翻译，而且有点不知所云，那么“压倒性优势”到底是什么意思呢？

不妨看看上下文，原文是在讨论计算机中的“树”这种图形到底应该根在上还是根在下，作者统计之后发现超过80%的树图都是根在上的，然后出现了这句话。所以“压倒性优势”的意思“根在上的图形数量远远超过根在下的图形”，这样翻译就通了。

改译
> 在手工绘图时，选择根在上、叶在下的数量远远超过根在下、叶在上的数量（考虑到我们涂写的顺序，这很好理解）。
> 
> 注：“根在上、叶在下”也可翻译为“顶置根结点”，相应的“根在下、叶在上”则翻译为“底置根结点”。

## 例句8
> *As an example of the theory that can be derived, suppose we consider the case when the tables grow only by insertion; deletions and subsequent insertions that cancel their effect are ignored.*
> 
> 作为一个可能被推导出来的理论的例子，假设我们考虑表仅因插入而增长的情况；忽略掉删除和其后抵消其影响的插入。

原文的理论是“可以推导出来”，而不是“可能被推导出来”。*as an example of* 翻译成“作为一个xx的例子”比较别扭，看看中文的教材就知道，要举例之前觉不会说“作为一个xx的例子”。

同样的道理，中文教材里举例时不会用“假设我们考虑”来描述条件，“假设”真正的对象是后面的条件，而不是“我们考虑”。

最后的句子理解起来要动点脑筋，译者理解了意思是“先删除，再插入，插入内容的宽度和删除的一样多，不会改变原有的长度”，但表达为“抵消其影响的插入”不当，读者不容易明白这里的“影响”到底是什么，应当具体化。

另外这里也出现了分号的问题，比较适合的处理是改为逗号，并以关联词维持原句的联系。

改译
> 关于可推导出来的这种理论，来看一个例子。假设表只能因为插入而增长，同时忽略删除后再插入同样长度内容的情况。
