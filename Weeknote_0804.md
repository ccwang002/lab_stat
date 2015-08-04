## R 安裝、設定

- R 主程式：<https://www.r-project.org/>
- RStudio，比較人性化的 R 介面，Server 上也有裝：<https://www.rstudio.com/>


## 補充：

### R 的統計操作

[這份投影片](http://blog.liang2.tw/2013-R-Statistics/ossf.html)整理了 R 相關的統計操作，一直到檢定之前。

### R 的隨機變數

除了[投影片](http://blog.liang2.tw/2013-R-Statistics/ossf.html#prob-fun-list)裡面列的那些，
打開 RStudio 之後在 console 打入

```r
?Distributions
```

會跳像下面這樣的頁面，有完整的列表。

> ## Distributions in the stats package
>
> ### Description
> Density, cumulative distribution function, quantile function and random variate generation 
> for many standard probability distributions are available in the stats package.
>
> ### Details
> The functions for the density/mass function, cumulative distribution function, quantile function 
> and random variate generation are named in the form `dxxx`, `pxxx`, `qxxx` and `rxxx` respectively. 
> 
> For the beta distribution see `dbeta`.
>
> ... (See full page on the [online version](http://stat.ethz.ch/R-manual/R-devel/library/stats/html/Distributions.html).)