# 碧蓝航线CD计算工具

访问地址: [GithubPages](https://pages.autumn21.top/)

该工具的数据和计算公式主要来源于[碧蓝航线Wiki](https://wiki.biligame.com/blhx/%E9%A6%96%E9%A1%B5)和[碧蓝航线](https://game.bilibili.com/blhx/)的游戏内数据.


## TODO
### CD计算器
- [x] 简单CD展示
- [x] 绑定技能CD展示
- [x] 交互界面优化
- [x] 自定义对轴项解析和展示
- [x] 基于舰娘和装备信息的CD计算
- [ ] 记录保存和加载(基于localStorage实现)
- [ ] 记录分享
- [x] 界面优化: 移动端适配
- [x] 基本功能
- [x] 舰载机筛选: 支持对各位置的舰载机进行进一步的筛选
- [ ] 排序方式优化: 支持按Buff覆盖率排序
- [x] 界面优化: 移动端适配
- [x] 界面优化: 显示舰娘头像
- [ ] 界面优化: 显示装备图标

## 开源协议

[CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/legalcode)

## 已知问题

- 航战只支持主炮时间轴和战列相关设备

目前所有的舰船只支持一条武器时间轴，这导致航战目前只有主炮时间轴、而没有舰载机时间轴。相应的，第4、5装备槽也只列出了战列相关设备

- 战列公共CD问题 #2

因公共CD的处理逻辑, 战列实际开炮时间在部分情况下会和游戏内不一致.
由于实际机制尚不明确而本人暂时没空进行详细测试, 并且这种情况出现概率较小, 所以暂时不会进行修复.

- 约克城II的'翱翔天际之鹰'技能

由于机制较复杂, 暂时无法模拟
