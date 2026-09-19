# 沪美 IPLC 价格：共享带宽 198 元/月起、独享 800 元/月起，Mkcloud 沪美专线全套餐价格表与选型指南

沪美 IPLC 的价格按计费方式分三档：共享带宽流量计费套餐 198 元/月起，独享带宽 800 元/月起，BGP 入口的独享线路 850 元/月起；如果你的服务器本身架在国内云厂商（阿里云、腾讯云这类）上，还有更省钱的 IXP 上云互联方案，266 元/月起。

以上是 Mkcloud 官网商店当前挂出的价格，月付、支持支付宝，全部套餐需要国内身份信息实名。这篇文章把四条产品线的完整价格表、配置差异、延迟表现和购买限制拆开讲清楚，你看完就能判断该花哪一档的钱。

## 先看全套餐价格表：沪美方向目前一共有四类产品

Mkcloud 的沪美专线不是一个单一产品，而是按“入口类型 × 计费方式”分成了四条产品线。四条线路的端内参考延迟都是 124~134ms，出口都是美国 BGP，每台机器都分配独享 IPv4 x2（一个入口 IP、一个出口 IP），差别在入口和计费方式上。

**一、沪美 IPLC 共享带宽（流量计费，入口上海电信）**

这是最多人选的入门系列，按月流量计费，带宽是峰值不保证跑满：

| 套餐 | CPU/内存/硬盘 | 带宽峰值 | 月流量 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- |
| 100GB | 1核/2G/20GB | 150M | 100GB/月 | ¥198/月 | [ 查看共享带宽套餐](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-sh) |
| 500GB | 1核/2G/20GB | 150M | 500GB/月 | ¥258/月 | [ 查看共享带宽套餐](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-sh) |
| 1TB | 1核/2G/20GB | 200M | 1TB/月 | ¥428/月 | [ 查看共享带宽套餐](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-sh) |
| 2TB | 2核/4G/40GB | 300M | 2TB/月 | ¥698/月 | [ 查看共享带宽套餐](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-sh) |
| 4TB | 2核/4G/40GB | 300M | 4TB/月 | ¥1258/月 | [ 查看共享带宽套餐](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-sh) |
| 6TB | 4核/8G/60GB | 500M | 6TB/月 | ¥1758/月 | [ 查看共享带宽套餐](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-sh) |
| 10TB | 4核/8G/60GB | 500M | 10TB/月 | ¥2888/月 | [ 查看共享带宽套餐](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-sh) |
| 20TB | 4核/8G/60GB | 1G | 20TB/月 | ¥5666/月 | [ 查看共享带宽套餐](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-sh) |

**二、沪美 IPLC 独享带宽（带宽计费，入口上海电信）**

流量无限制，带宽独占。适合持续传输、对速率有明确要求的业务：

| 套餐 | CPU/内存/硬盘 | 独享带宽 | 流量 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- |
| 5M | 2核/4G/40GB | 5M | 不限 | ¥800/月 | [ 前往独享带宽专线页面](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-ex) |
| 10M | 2核/4G/40GB | 10M | 不限 | ¥1100/月 | [ 前往独享带宽专线页面](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-ex) |
| 20M | 2核/4G/40GB | 20M | 不限 | ¥2100/月 | [ 前往独享带宽专线页面](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-ex) |
| 50M | 4核/8G/60GB | 50M | 不限 | ¥5000/月 | [ 前往独享带宽专线页面](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-ex) |
| 100M | 4核/8G/60GB | 100M | 不限 | ¥9000/月 | [ 前往独享带宽专线页面](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-ex) |
| 200M | 4核/8G/60GB | 200M | 不限 | ¥18000/月 | [ 前往独享带宽专线页面](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-ex) |
| 300M | 4核/8G/60GB | 300M | 不限 | ¥27000/月 | [ 前往独享带宽专线页面](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-ex) |
| 定制 | 按需配置 | 更高带宽 | 不限 | 另议 | [ 前往独享带宽专线页面](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-ex) |

**三、沪美 BGP 专线（独享带宽，入口 UCloud 上海 BGP）**

和上一条的区别只在入口：上海电信换成 UCloud 上海 BGP，国内多家运营商接入的用户访问入口表现会更均衡，出口同样是美国 BGP：

| 套餐 | CPU/内存/硬盘 | 独享带宽 | 流量 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- |
| 5M | 2核/4G/40GB | 5M | 不限 | ¥850/月 | [ 查看沪美BGP独享专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/shh-us-ex) |
| 10M | 2核/4G/40GB | 10M | 不限 | ¥1300/月 | [ 查看沪美BGP独享专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/shh-us-ex) |
| 20M | 2核/4G/40GB | 20M | 不限 | ¥2560/月 | [ 查看沪美BGP独享专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/shh-us-ex) |
| 50M | 4核/8G/60GB | 50M | 不限 | ¥6000/月 | [ 查看沪美BGP独享专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/shh-us-ex) |
| 100M | 4核/8G/60GB | 100M | 不限 | ¥11500/月 | [ 查看沪美BGP独享专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/shh-us-ex) |
| 定制 | 按需配置 | 更高带宽 | 不限 | 另议 | [ 查看沪美BGP独享专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/shh-us-ex) |

**四、沪美 IXP 上云互联专线（流量计费，云厂 BGP 入口）**

这条线只允许云厂 BGP 网络连入（阿里云国内全网、腾讯云国内全网、百度云国内全网、火山云华东、华为云华东、UCloud 华东等），适合你的业务本来就跑在国内云服务器上的情况。注意这个系列超量后是停机而不是限速：

| 套餐 | CPU/内存/硬盘 | 带宽峰值 | 月流量 | 价格 | 购买链接 |
| --- | --- | --- | --- | --- | --- |
| 1TB | 2核/4G/40GB | 200M | 1TB/月 | ¥266/月 | [ 了解沪美IXP上云互联专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/cloud-us-sh) |
| 2TB | 2核/4G/40GB | 200M | 2TB/月 | ¥430/月 | [ 了解沪美IXP上云互联专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/cloud-us-sh) |
| 3TB | 2核/4G/40GB | 500M | 3TB/月 | ¥615/月 | [ 了解沪美IXP上云互联专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/cloud-us-sh) |
| 6TB | 4核/8G/40GB | 500M | 6TB/月 | ¥1166/月 | [ 了解沪美IXP上云互联专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/cloud-us-sh) |
| 10TB | 4核/8G/40GB | 1G | 10TB/月 | ¥1945/月 | [ 了解沪美IXP上云互联专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/cloud-us-sh) |
| 20TB | 4核/8G/40GB | 1G | 20TB/月 | ¥3686/月 | [ 了解沪美IXP上云互联专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/cloud-us-sh) |
| 30TB | 4核/8G/60GB | 2G | 30TB/月 | ¥5529/月 | [ 了解沪美IXP上云互联专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/cloud-us-sh) |
| 50TB | 8核/8G/60GB | 2G | 50TB/月 | ¥9216/月 | [ 了解沪美IXP上云互联专线](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/cloud-us-sh) |

> 所有系列均支持月付，计费流量按上行、下行双向统计；共享带宽为峰值速率，不保证持续跑满。以上价格来自官网商店当前页面，下单时以结算页显示为准。

## 为什么同样叫沪美 IPLC，价格能差一百多倍

从 ¥198 到 ¥27000，差距看起来夸张，其实是三个变量在起作用。

第一个变量是计费方式。共享带宽套餐卖的是“流量+峰值带宽”，你在页面看到的 150M、300M 是峰值上限，实际速度取决于当时线路上的负载；独享带宽套餐卖的是“保证速率+无限流量”，带宽这一整段是你独占的，所以 5M 就要 800 元/月。两者没有绝对优劣——一个月只跑两三百 GB 的轻度使用，共享套餐便宜得多；要是需要 7×24 小时持续推流或大文件同步，独享按速率封顶反而可控。

第二个变量是入口类型。上海电信入口便宜一些，UCloud 上海 BGP 入口的独享系列整体贵 50~150 元（比如 5M 档 800 对 850，100M 档 9000 对 11500）。官方知识库的说法比较实在：BGP 入口不一定比电信入口好，应该按你实际用的宽带和所在省份测，两者是候选方案而不是固定的高下关系。

第三个变量是流量档位。沪美方向流量给得比沪日、广港少——同样 1 核 2G 的配置，沪日 IPLC 500GB 卖 ¥228，沪美 500GB 卖 ¥258，沪美起步更是只有 100GB。跨太平洋线路的带宽成本本来就高，这不算 Mkcloud 一家的定价怪癖。另外注意流量是双向统计的，实际“可用”的下载量大概是标称值的一半，算预算时要留余量。

## 端内延迟 124~134ms 是什么水平

官方给出的端内参考延迟是 124~134ms，这是上海到美国出口这一段的数值，不含出口到目标网站的最后一段。中美之间的物理距离决定了延迟不可能再低一个量级，所以看到任何商家宣传“沪美 50ms”都可以直接跳过。

第三方公开测评的数据能佐证这个范围。NodeSeek 上一份 500GB 套餐的测评里，从出口机 ping 8.8.8.8 连续 20 次全部稳定在 119ms，波动几乎为零——这正是 IPLC 的价值所在，它走的是内网专线，不经过公网拥堵。另一份 100GB 套餐的测评显示，上海电信入口的 TCP ping 三网平均在 28~33ms（电信 28、联通 30、移动 33），说明入口这半段对三网用户都算友好。

出口 IP 属于 Nearoute Limited 的美国 BGP 网段，实测出口落在洛杉矶、西雅图一带。原生 IP、无 IPv6，流媒体解锁情况以美区为主：ChatGPT、Amazon Prime 正常，Netflix 仅自制剧，TikTok 识别为美区但带 IDC 标记。拿它刷 Netflix 4K 不太现实，做美区店铺和业务访问没问题。

## 这些业务适合买，这些不行

官方知识库对沪美专线的定位写得很明确：它交付的是一台 VPS，你连入口操作，程序自动从美国出口向外访问。适合的场景是三类——美区店铺后台、海外办公和授权 API 访问；从这台 VPS 发起的素材上传、文件传输或数据同步；针对美国服务的客户端测试与运维操作。TikTok 运营、美区开发测试、SSH 和远程桌面加速这些用法在第三方测评里也都被点名推荐过。

有几条红线要提前知道。出口 IP 不支持外部连入，所以它承载不了买家页面、支付回调、公开网站或游戏服务端——这类需求你需要的是一台常规美国 VPS，而不是沪美专线。平台条款明确禁止机场和回国用途，一经发现清退不退款。所有专线产品采用省级白名单，只允许一个省份的 IP 连入（下单时选省份，开通后可以改），这也是防滥用的措施之一。

## 下单前必须确认的几条规则

购买流程里有两道门槛。一是实名认证，需要国内手机号、身份证号和姓名三者一致验证，这意味着没法匿名购买；二是附加选项里要设置可连入省份。系统选择倒是很宽，Ubuntu、Debian、CentOS、AlmaLinux、Rocky、Fedora、openSUSE、Arch、Oracle Linux 都能选。

退款政策比普通 VPS 严格得多：仅支持质量问题退款，而且需要你提供准确具体的延迟、速度数据来证明问题；开通后不支持更换到其他地域的产品。官方也明确说明默认无 SLA 保证，有连续性要求的大单应该先谈付费定制和故障处理约定。共享套餐流量超量后会停机，可以自助购买流量重置或提交工单补差价升级套餐。好在这类专线支持月付，先买一个月试水，不合适就停，试错成本可控。

## 优惠码和几个省钱的判断

Mkcloud 官方知识库记录过的两个常规优惠码：流量计费产品用 **MK-8.8**（8.8 折循环），独享带宽产品用 **MK-7.8**（首月 7.8 折）。官方同时注明优惠码只在活动期内有效，所以最稳的办法是下单时在结算页输入试一下，能用就省，不能用说明活动已过期，不要按过期价格做预算。历史活动里还出现过新客专享价、IXP 专项折扣等形式，关注官方 Telegram 通知群能看到最新一期。

按单价算账，有几个结论比较清晰。100GB 档不建议当首选：¥198 摊到单向流量约 4 元/GB，而 500GB 档只贵 60 元，单价直接降到 1 元/GB 左右，这也是测评社区普遍推荐至少从 500GB 起步的原因。月流量在 1TB 上下、跑美区店铺的中小卖家，共享带宽 1TB（¥428）或 2TB（¥698）档是主力价位。需要固定速率的长跑业务，5M 或 10M 独享（¥800/¥1100）比堆共享流量更省心。业务已经在国内云上的，先看 IXP 系列，1TB 档 ¥266 比电信入口共享版便宜近 40%，前提是你接受超量停机而不是限速。

[👉 查看 Mkcloud 沪美IPLC最新套餐与优惠](https://www.mkcloud.net/aff.php?aff=390&url=https://www.mkcloud.net/index.php/store/sh-us-sh)

## 常见问题

**沪美 IPLC 为什么比沪日贵？**

同配置下沪美流量档位更少、单价更高，500GB 档沪日 ¥228、沪美 ¥258。跨太平洋方向的带宽成本高于中日方向，这是全行业的定价现实，不是单一商家的问题。

**价格里包含独立 IP 吗？**

包含。全部沪美套餐标配独享 IPv4 x2，一个入口 IP、一个出口 IP，做美区业务防关联时这点比较重要。

**买错了或者用不惯能退吗？**

只有质量问题才支持退款，且需要提交具体的延迟、速度数据作为证据；服务开通后不能换地域。建议先月付一个月验证线路质量再考虑长周期。

**共享带宽能不能跑满标称速率？**

峰值速率不承诺持续跑满，实际吞吐受协议、目标和本地网络影响。如果你的业务要求固定速率，直接看独享系列更省事。

**没有国内身份信息可以买吗？**

不行。沪美全线产品都要国内手机号加身份证实名，并且仅限个人或企业的正规用途。这一条没有任何变通空间，购买前先确认自己能满足。
