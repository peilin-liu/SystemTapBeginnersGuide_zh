# 1.2. SystemTap的能力

**灵活性**：SystemTap提供了一门领域特定语言，使得用户可以编写自定义脚本，调查和监控各种内核函数、系统调用，和其它发生在内核空间的事件。就此而言，SystemTap不仅仅是个工具，它是一个让你能够自定义内核取证和监控工具的生态系统。

**易于上手**：正如前面谈到的，SystemTap把用户从在探测内核空间事件时，注入检测代码-重新编译-安装-重启这一繁琐过程解放出来。

我们在第五章——[SystemTap脚本集锦](5_UsefulSystemTapScripts.md)——列出的大多数SystemTap脚本所展现出的系统取证和监控能力，是其它同类型工具（比如`top`，`oprofile`，`ps`）所不能及的。这些脚本很好地诠释了SystemTap强大的功能，届时将会拓宽诸位读者编写自己的SystemTap脚本时的眼界。