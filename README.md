## Mark · popstk

后端出身，现在大部分时间在给自己造工具 —— 一套跑在家里和一台云服务器上的
自托管基础设施，外加一条把 AI 编码 agent 接进日常工作流的链路。

写 Go 为主，够用就好的前端（Vue），安卓用 Kotlin。偏好单二进制、零依赖、
配置即真相源、每个决定都能在 README 里找到「为什么这么做」。

---

### 在做什么

**🛡 自托管基础设施**
一台云服务器托着全部对外入口：Caddy + Coraza 做 WAF 与反向代理，站点清单是唯一真相源，
配置生成、证书探测、攻击看板收在同一个二进制里。往下接自建 WebDAV、MTProto 代理、
通知网关，都走同一套「systemd + 单文件 + 可回滚」的部署姿势。

**🤖 AI 编码工具链**
在模型网关这一层做事情：让只认文本的模型也能读图片，把多家套餐的额度聚到一个面板，
把 Claude Code 的会话事件收成一条可配置的通知流推到手机。

**🏠 家庭自动化与网络**
Home Assistant 的 UI 改造与公网 mTLS 访问、局域网设备与流量看板、
PVE 存储载重线告警。共同点是：**在出事之前把人叫醒**，而不是事后给一张好看的图。

**📱 移动端**
一个安卓客户端，用 SSH 隧道把上面这些只在内网可达的面板搬到手机上 ——
不装 VPN、不依赖任何外部 app。

> 这些仓库大多是私有的：里面写着域名、主机名和完整的部署 runbook。

---

### 公开的东西

| | |
|---|---|
| [**onedrivehelper**](https://github.com/popstk/onedrivehelper) | OneDrive 辅助工具 |
| [**subserver**](https://github.com/popstk/subserver) | v2ray 订阅服务 |
| [**ntfy-android**](https://github.com/popstk/ntfy-android) | ntfy 安卓客户端的 Material 3 美化分支 |
| [**popstk.github.io**](https://github.com/popstk/popstk.github.io) | 博客，现发布在 [blog.popstk.top](https://blog.popstk.top) |

---

<sub>早年的练手仓库（go-kit / go-utils / webtool / interview 等）留着当考古层，不代表现在的写法。</sub>
