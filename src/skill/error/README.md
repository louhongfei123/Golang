# 错误封装技巧

## 适用场景
在开发框架或底层代码时，通常会遇到一个问题：   
当程序运行出error后，希望能通过error知道更全面的错误信息。   
可以通过自定义error结构来实现错误信息的封装。