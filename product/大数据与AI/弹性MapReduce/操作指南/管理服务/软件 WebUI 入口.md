## 功能介绍
软件 WebUI 入口功能是 EMR 提供的组件原生 UI 访问能力，通过 Master 节点的外网 IP（建议及时配置安全策略），可以快捷访问组件原生 UI。如果集群内网与企业网络互通，可关闭该外网 IP，直接通过内网访问组件原生 UI。

## 操作步骤
1. 登录 [EMR 控制台](https://console.cloud.tencent.com/emr)，在集群列表中单击对应的集群 **ID/名称**进入集群详情页。
2. 在集群集群详情页中选择**集群服务**，然后单击对应的组件卡页下方 **WebUI 地址**即可访问。
访问地址需要进行身份验证，用户名为 root，默认密码为创建集群时输入的密码。如果需要修改密码，可以在此页面中单击**重置 WebUI 密码**进行修改。
![](https://qcloudimg.tencent-cloud.cn/raw/141180cc37405442613e09fbd240a349.png)
