###报告###
##练习1##
根据代码注释提供的提示既可以完成，但是在实现的时候遇到`sfs_bmap_get_nolock: invalid index`错误，经过调试和观察参考答后案发现是`blks`变量是无符号的，减一之后可能变成0；无其他明显错误；  

和答案对比发现在循环上的实现有一些区别。基本相同。

##练习2##
根据代码注释和Lab7的代码完成，Lab8 和 Lab7的主要区别是增加了argv/argc参数的加入和读取方式由直接读取变成了文件读取，因此只要把对应部分改成读取文件即可。  

和参考答案主要部分基本相同，主要区别在于argv/argc加入的方式，参考答案给每个argv多填补了一些空间。


