# 简介

本处方用于完全屏蔽taobao的ChannelServices，屏蔽其导致的应用间相互唤醒，缓解ali系或使用aliSDK的app启动时的卡顿。 

新增屏蔽AgooService，TCMSService，OrangeService，AnalyticsService，mtopsdk。 

根据SDK文档、AndroidManifest屏蔽action测试中。ChannelService真的很难干掉，有更好的方案也欢迎朋友共享到社区。

(By DJun，酷安ID：djunxp)

点击使用处方：https://wulinfo.github.io/rx-channel-services

