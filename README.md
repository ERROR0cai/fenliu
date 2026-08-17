# fenliu（分流）
为自己量身定做的分流配置

# 每个配置的作用
## 后缀
首先，每个ini文件有2个，没有后缀的是一开始的超多规则旧版，如all_equal.ini；后缀2的都是稍微精简了一些的版本，好像更加兼容新的机场，如all_equal2.ini

## 类型
`Multiple_first is expensive`：第1个机场昂贵，其余差不多便宜——可以在一些情况下优先使用便宜机场

`Multiple_first_two is expensive`：第1、2个机场昂贵，其余差不多便宜——可以在一些情况下优先使用便宜机场

`all_equal`：所有机场差不多便宜——混合使用，权重一致（可以只使用单条机场）

## 其它
`ShouldCN.list`：我认为应该是CN的列表

`Steam.list`：修改版steam列表
