# v5-frontend
zhelper V5 新前端

## 技术栈说明

前端基于 Vue + Daisy UI 开发

## 接口说明

zhelper V5 主要有 search 和 detail 两个接口。

```
r = requests.post('https://api.v5.zhelper.net/api/search/',json={'keyword':'电动力学','page':2})
```

```
r =  requests.post('https://api.v5.zhelper.net/api/detail/',json={'id':'3511911'})
```

