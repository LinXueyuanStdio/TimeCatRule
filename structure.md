# 架构

# 业务

4个大业务

本地 IM综合所有业务、记录业务、git、商店（本地自定义商店 + 官方商店 + 第三方用户商店）

多个次业务

插件、皮肤、设置


## 记录业务

基础：笔记、任务、习惯 

综合显示：列表、日历、周、日、月、书架、瀑布流
综合显示进阶：课程表、块时间、四象限、激励语、聊天、时间轴

详细显示与编辑：markdown、git、org、时间规划

## repo 分层
TimeCatModule-Git + TimeCatModule-BookReader + TimeCatModule-Online + TimeCatModule-Browser + TimeCatModule-File
TimeCatMiddle
TimeCatPage
TimeCatLayout     + TimeCatDatabase + TimeCatShowIn
TimeCatComponents
TimeCatIdentity   + TimeCatElement  + TimeCatThird   + MView