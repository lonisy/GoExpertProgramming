Go语言提供了go test 命令行工具，使用该工具可以很方便的进行测试。

不仅Go语言源码中大量使用go test，在各种开源框架中的应用也极为普遍。

目前go test支持的测试类型有：
* 单元测试
* 性能测试
* 示例测试

本章，我们先快速掌握这几种测试的基本用法，然后我们跟据源码来学习这些测试的实现机制。