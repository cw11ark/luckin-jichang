# Luckin 机场测评：广州/上海 IEPL 中转，200G 起 20 元/月（2026-11-25 实抓价目） (updated 2026-11-25)

> 小而美中转机场：4 档套餐、最多 10 个 IP 同时连接；价目按官网接口当日实抓。

Luckin 是一家节点组合精简的中转机场：入口在广州、上海，节点走 IEPL 中转，站点自述为「Luckin 加速器」，流媒体主打 Netflix、Hulu、HBO、Disney+、Dazn。本页价目于 2026-11-25 直接从官网套餐接口读取，并与第三方测评 2026-07-28 的记录逐档对照：四档价格完全一致，说明这家在近四个月没有调价。需要先明确的是它的两条硬限制——最多 10 个 IP 同时连接，且官方明确不保证 TikTok 与大陆应用改定位。

> [!NOTE]
> Compiled from the vendor's public pricing endpoint and a third-party review — no independent speed test of this provider.

## Contents

- [💰 套餐与实抓价目](#套餐与实抓价目)
- [⚠️ 权益与硬限制](#权益与硬限制)
- [🧭 入口、协议与怎么选](#入口协议与怎么选)

## 💰 套餐与实抓价目

| 套餐 | 流量 | 月付 | 半年付 | 年付 | 同时连接 |
|---|---|---:|---:|---:|---|
| Bronze | 200GB/月 | ¥20 | ¥110 | ¥200 | 最多 10 个 IP |
| Silver | 500GB/月 | ¥50 | ¥268 | ¥498 | 最多 10 个 IP |
| Gold | 950GB/月 | ¥90 | ¥480 | ¥898 | 最多 10 个 IP |
| Special | 200GB/**年总量** | — | — | ¥128 | 最多 10 个 IP |

以上为 2026-11-25 直接读取官网套餐接口得到的当日报价（接口原始单位为分，已折算为元）；半年付/年付是该周期总价，不是月价。Special 档是全年 200GB 总量，与 Bronze 的「每月 200GB」不是同一量级。

| Project | What it is | Tags |
|---|---|---|
| [官网套餐接口（原始数据）](https://user.susucloud.net/api/v1/guest/plan/fetch) | 本站价目的唯一来源：返回四个套餐的流量、月/半年/年价格与权益原文。上表逐档转录，未做倒算或补猜；接口字段 transfer_enable 单位为 GB，价格字段单位为分。 | `一手`, `2026-11-25` |
| [官网首页](https://user.susucloud.net/) | 下单与登录入口所在站点；页面为单页应用，套餐与价格由上述接口动态渲染，因此静态页面本身不含价目数字。 | `官方`, `下单入口` |

## ⚠️ 权益与硬限制

官方套餐说明的原文要点：能做什么，以及明确**不保证**什么。这两条比价格更该先看。

| Project | What it is | Tags |
|---|---|---|
| [注册门槛：需要邮箱验证](https://user.susucloud.net/api/v1/guest/comm/config) | 官网配置接口 2026-11-25 实读：is_email_verify=1（注册需邮箱验证）、is_invite_force=0（不强制邀请码）。要注册得先准备一个能收信的邮箱。 | `邮箱验证`, `无需邀请码` |
| [站点自述与主题配置](https://user.susucloud.net/env.js) | 站点前端配置实读：title 为「Luckin 加速器」，主题为 dark、无客服组件（crisp_id 为空）。也就是说遇到问题只能走站内工单或邮箱，没有在线客服窗口。 | `官方`, `无在线客服` |
| [流媒体与线路（官方说明）](https://user.susucloud.net/#/plan) | 四个套餐的权益原文一致：解锁 Netflix、Hulu、HBO、Disney+、Dazn 等主流流媒体；线路写「全球主流地区线路」；每档都写「最多【10】个 IP 同时链接使用」。 | `流媒体`, `10 IP 上限` |
| [TikTok 与大陆应用改定位：不保证](https://user.susucloud.net/#/knowledge) | 官方套餐原文明确写：不保证 TikTok 能用，海外用户无法使用（含港澳台）；不保证抖音、快手、微博、B 站等大陆应用修改定位。需要这两类场景的，不要按「解锁全部流媒体」推断。 | `TikTok`, `不保证` |

## 🧭 入口、协议与怎么选

第三方测评记录的入口与协议，以及按用量直接落档的建议。

| Project | What it is | Tags |
|---|---|---|
| [入口、中转与不保证项（第三方测评）](https://www.duyaoss.com/archives/5248/) | 测评记录（2026-07-28 晚测速）：入口有广州、上海，节点采用 IEPL 中转，支持 Trojan；支付为支付宝、微信支付、云闪付；同时写明「完全舍弃冷门国家节点」。该测评与官方口径一致地注明不保证 TikTok 与大陆应用改定位。 | `广州`, `上海`, `IEPL`, `Trojan` |
| [注册入口](https://user.susucloud.net/register?code=OFiCTB6y) | 官网注册页。先按用量选档：轻度（月 200G 内）走 Bronze 月付试一个月；中度看 Silver；重度看 Gold。年付单价更低但一次付清，且 10 IP 上限三档都一样，不因加钱放宽。 | `注册`, `按量选档` |

---

## About this list

- **8** entries across **3** sections.
- Compiled from public sources; every linked project carries its own license.
- Last updated: **2026-11-25**.
- Data lives in `data/content.json` — this README is generated, do not edit by hand.

## License

The text and curation in this repository are licensed under CC BY 4.0. Linked projects keep their own licenses.
