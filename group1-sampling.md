---
title: 第一组抽样名单
---

可使用R和Rstudio来执行抽样过程（确保`group1-evopsy.xlsx`文件在当前工作路径中），具体命令如下：

    install.packages(c("dplyr", "readxl"))
    library(dplyr)
    library(readxl)
    x = read_xl("group1-evopsy.xlsx")
    set.seed(743)
    sample_n(x, 6)



