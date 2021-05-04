# 《Go语言标准库》The Golang Standard Library by Example #

Golang标准库。对于程序员而言，标准库与语言本身同样重要，它好比一个百宝箱，能为各种常见的任务提供完美的解决方案。以示例驱动的方式讲解Golang的标准库。

标准库基于最新版本Go。注：目前 Go 标准库文档并没有标识某个 API 基于哪个版本的 Go，将来会加上这部分 [issue](https://github.com/golang/go/issues/5778)。

讲解中涉及到特定操作系统时，针对的都是 Linux/amd64。Go 中相关系统调用在 Linux 下，对于同一个系统调用，如果有对应的 `at` 版本，使用的都是 `at` 版本，如 `open` 系统调用使用都是 `openat`。更多信息参考 [Go语言中文网博客中关于系统调用的文章](http://blog.studygolang.com)。
