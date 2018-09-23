# 简介

本处方用于完全屏蔽taobao的ChannelServices，屏蔽其导致的应用间相互唤醒，缓解ali系或使用aliSDK的app启动时的卡顿。 

新增屏蔽AgooService，TCMSService，OrangeService，AnalyticsService，mtopsdk。 

根据SDK文档屏蔽action测试中。

IFW防止ChannelService复活的方案（实验性，有风险）：手动复制本项目ifw目录下的channel_service.xml，到/data/system/ifw，并将xml文件修改权限为0644。

(By DJun，酷安ID：djunxp)

点击使用处方：https://greenify.github.io/djun/rx-channel-services

