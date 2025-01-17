# 有料信息流sdk 变动日志

## 1.3.2-beta06
1. fix 已知bug

## 1.3.0-beta03
1. 依赖的adroi-sdk版本为：10.0.0.51，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：2.7.0.6
3. 依赖的穿山甲广告-sdk版本更新为：4.7.1.2
4. 依赖的快手小视频版本更新为：3.3.31
5. 依赖的百度内容版本为：9.23
6. 新增依赖的百度小说版本为：6.0.3.5，注意小说版本需要和百度内容版本匹配
7. 新增百度api新闻第一屏缓存
8. 新增字体大小设置
9. fix 已知bug

## 1.3.0-beta01
1. 依赖的adroi-sdk版本为：10.0.0.45，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：2.7.0.6
3. 依赖的穿山甲广告-sdk版本更新为：4.6.0.7
4. 依赖的快手小视频版本更新为：3.3.29
5. 依赖的百度内容版本为：9.22
6. 新增依赖的百度小说版本为：6.0.3.5，注意小说版本需要和百度内容版本匹配
7. 新增百度api新闻第一屏缓存
8. 新增字体大小设置
9. fix 已知bug

## 1.2.9
1. 依赖的adroi-sdk版本为：10.0.0.39，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：2.5.0.0
3. 依赖的穿山甲广告-sdk版本更新为：4.4.9.1
4. 移除YouliaoNewsSdk.setLocationProvider方法
5. 优化百度api新闻加载速度

## 1.2.8
1. 依赖的adroi-sdk版本为：10.0.0.33，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：2.5.0.0
3. 依赖的穿山甲广告-sdk版本更新为：4.4.0.9

## 1.2.7
1. 依赖的adroi-sdk版本为：10.0.0.29.2，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：2.4.0.0
3. 依赖的穿山甲广告-sdk版本更新为：4.3.0.8

## 1.2.6
1. 依赖的adroi-sdk版本为：10.0.0.23，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：2.2.0.1（Application的Module中添加命令依赖gradle脚本，详见文档）
3. 依赖的穿山甲广告-sdk版本更新为：4.3.0.8
4. 由于头条内容sdk的更新，NewsFragment实例方法中去除isScrollTop()方法  
5. 新增支持百度-sdk信息流(依赖为adroi提供的百度广告-sdk)
6. 新增青少年模式开关 YouliaoNewsSdk.setBytedanceTeenagerMode(boolean)
7. 新增头条合规开关 YouliaoNewsSdk.updateBytedanceDpRecommendation(boolean)

## 1.2.5
1. 依赖的adroi-sdk版本为：10.0.0.17，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：1.7.0.0
3. 依赖的快手小视频版本更新为：kssdk-all-3.3.24.6.aar
4. 新增默认配置功能（运营会给到配置文件，放到assets中，初始化时传入名称）
5. 初始化参数增加配置文件名称
## 1.2.5
1. 依赖的adroi-sdk版本为：10.0.0.17，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：1.7.0.0
3. 依赖的快手小视频版本更新为：kssdk-all-3.3.24.6.aar
4. 新增默认配置功能（运营会给到配置文件，放到assets中，初始化时传入名称）
5. 初始化参数增加配置文件名称
## 1.2.4
1. 依赖的adroi-sdk版本为：10.0.0.3，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：1.3.0.0
3. 依赖的快手小视频版本更新为：all-3.3.23
4. 新增头条小说合规开关 YouliaoNewsSdk.updateNovelRecommendation(boolean)

## 1.2.3
1. 依赖的adroi-sdk版本更新为：10.0.0.3，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：1.2.0.0
3. 新增快手合规开关 YouliaoNewsSdk.updateKsRecommendation(boolean)

Breaking Changes:
1. 小说sdk初始化 改为传入配置文件名称。详见`头条小说sdk`接入

## 1.2.2
1. 依赖的adroi-sdk版本更新为：10.0.0.1，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：1.0.0.0

Breaking Changes:
1. 头条短视频和小说已经合并，接入方式有所改变
2. 短视频sdk初始化，改为传入配置文件名称。详见`头条短视频sdk`接入
3. 小说sdk初始化 增加需要传入的参数。详见`头条小说sdk`接入
4. 新增demo说明

## 1.2.1
1. 依赖的adroi-sdk版本更新为：3.9.7或3.9.9.3，请注意要匹配
2. 依赖的内容合作-sdk版本更新为：2.7.1.2，请注意已变为线上依赖（需要添加maven仓库地址，详见文档），另AppLog版本有更新
3. 依赖的穿山甲小说-sdk版本更新为：3.0.1
4. 快手小视频需确保添加依赖 'androidx.legacy:legacy-support-core-ui:1.0.0'
5. fix 已知bug

## 1.2.0
1. 迁移到androidx
2. 依赖的adroi-sdk版本更新为：3.8.7
3. 依赖的内容合作-sdk版本更新为：2.4.1.0
4. 依赖的穿山甲小说-sdk版本更新为：2.0.2
5. fix 已知bug

## 1.1.9
1. 依赖的adroi-sdk版本更新为：3.8.7
2. 依赖的内容合作-sdk版本更新为：2.4.1.0
3. 依赖的穿山甲小说-sdk版本更新为：2.0.2
4. fix 已知bug

## 1.1.8
1. 增加头条内容&快手小视频上报
2. fix 广点通广告点击问题
3. fix 自渲染点击区域问题
4. fix 已知bug

## 1.1.6
1. 新增获取穿山甲小说单频道
2. 新增快手小视频
3. 依赖的adroi-sdk版本更新为：3.7.7
4. 依赖的内容合作-sdk版本更新为：2.4.0.2
5. 依赖的穿山甲小说-sdk版本更新为：1.0.6
6. 请注意查看 `SDK接入`->`一、增加依赖`->`接入头条内容合作sdk`->`1）添加sdk` 中新增的依赖

## 1.1.5
1. 修改maven地址
2. 新增穿山甲小说
