# 银行信息

在文件data.json中以数组形式存放着银行的信息。

```
[
  {
    "name": "中国工商银行",
    "url": "http://www.icbc.com.cn/icbc/",
    "branch_url": "http://www.icbc.com.cn/ICBC/%E5%AE%A2%E6%88%B7%E6%9C%8D%E5%8A%A1/business_offices.htm",
    "remark": "备注信息"
  }, 
  {
    "name": "中国银行",
    "url": "http://www.boc.cn/",
    "branch_url": "http://www.bankofchina.com/sourcedb/operations/",
    "remark": "备注信息"
  }
]
```

其中的四个字段表征的意义如下：

`name`: 银行名称，必填；

`url`: 银行网址（首页），必填；

`branch_url`: 银行网点页面的链接，必填；

`remark`: 备注信息，选填；
