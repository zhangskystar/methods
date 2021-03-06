### 编程一万小时的反思
> Matt Rickard 是在谷歌从事 Kubernetes 开源工作的开发者，主要负责构建和维护 Kubernetes 开发者工具，例如 minikube 和 skaffold。此外他还作为 Kubeflow 项目的维护者负责机器学习管道方面的工作。
Matt 拥有大约 15 年的编程经历，目前在谷歌 Kubernetes 和私募股权公司 Blackstone 担任专业软件工程师。根据Matt的介绍，他已经拖入了一万小时用于训练编程技能。

#### 以下就是 Matt 编程一万小时后的 31 条反思：
1. 阅读源代码常常会比在 Stack Overflow 上更快找到答案
2. 大多数情况下，如果你正在做的事情无法在互联网上找到答案，那么这通常意味着这个问题很难或者很重要，或者两者都是
3. 尽可能多地删除代码
4. 语法糖通常是不好的
5. 简单往往是最难的
6. 拥有各种各样的工具，并知道该用哪些工具来完成工作
7. 了解最常用的工具的内部结构，如 git 和 bash
8. 为重复的工作流程构建自己专用的工具
9. 从最好的资料中进行学习（这里 Matt 举例称他在学习 Go 时阅读了标准库）
10. 如果代码看起来很丑，那很可能是一个严重的错误
11. 如果必须编写不是文档字符串 (docstring) 的注释，则应该考虑对这段代码进行重构
12. 如果不了解所编写的程序是如何在生产环境中运行的，那就说明不了解程序本身。优秀的工程师知道他们的程序在各种环境中是如何运行的
13. 上面这条经验对于构建管道也适用
14. 谨慎使用他人的代码
15. 互联网上找到的代码大多数都很糟糕，有时候自己写一个更好的版本会更容易
16. 永远不要直接依赖自己可以轻松重写的小型库，或本应很小的大型库
17. 知道什么时候该打破规则。对于“不要重复自己”这种规则，有时候重复比使用依赖要好
18. 将代码组织成模块、包和函数很重要。了解 API 的边界位置是一门艺术
19. 大多数情况下应选择最有效的工具，但也要选择自己所知道的。Arch Linux 是现代开发者最高效的操作系统吗？对我来说，是的，但对大多数人来说，可能不是
20. 避免圈复杂度 (Cyclomatic complexity)
21. 避免多层嵌套条件
22. 正确命名变量，这也是一门艺术
23. 虽然很少见，但有时报错可能确实是编译器的问题
24. 谨慎使用深奥的语言特性，但在应该使用的时候还是要使用
25. 技术的传播并不均衡对等。例如，前端开发者可以从负责底层技术的工程师那里学到许多东西，云工程师可从 JavaScript 开发者身上学到用户体验和可用性方面的知识。但反过来却未必成立
26. 因此，不同类型的工程师看待世界的方式是不同的
27. 部分程序员的效率是其他程序员的 10 倍
28. 成为 10 倍程序员与 10 倍员工这两者之间没有相关性（或许是负相关）
29. 好的 API 易于使用且难以误用
30. 配置七边形（Matt 自创的术语）从硬编码值开始，到环境变量、CLI Flag、配置文件、模板化配置文件、DSL、通用 bash 脚本，再到硬编码值。开发者应了解这个七边形中的各个位置。
31. 所有抽象层都是可改变的。如果遇到了根本性的问题，有时答案就是往下再抽象一层，不要局限于表面
