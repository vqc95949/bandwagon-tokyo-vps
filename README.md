# bandwagonhost tokyo：搬瓦工东京VPS价格、库存与线路全对比，CN2 GIA 和 DC39 该选哪个

搜 bandwagonhost tokyo 的人，多半想确认两件事：搬瓦工东京现在有哪些套餐、多少钱、有没有货。直接给结论：目前在售的东京套餐分两条线——Equinix TY8 机房的 CN2 GIA 系列（6 个套餐，年付 **$899.99 起**，全部有货），以及 DC39v2 机房的入门套餐 The Tokyo Plan（年付 $79，用优惠码后 **$73.65**）。两条线差的不只是价格，回程线路也完全是两套逻辑，选错机房比选错配置更影响体验。

> **只想快速决定的话**：年预算一百美元以内、能接受移动 CMI 回程 → 选 The Tokyo Plan，👉 [查看 The Tokyo Plan 年付价格（用码后 $73.65）](https://bwh81.net/aff.php?aff=77528&pid=162)。电信宽带、对晚高峰回程质量敏感、预算充足 → 从 40G CN2 GIA（$899.99/年）起步。全部套餐的配置和购买链接在下面表格里。

## 搬瓦工东京现在有哪些套餐？价格一览

截至本文检索时，东京在售的一共 7 个套餐：6 个 SPECIAL 40G–1280G KVM PROMO V5 - TOKYO CN2 GIA 系列（Equinix TY8 机房），外加定位入门的 The Tokyo Plan（DC39v2 机房）。CN2 GIA 系列 6 个套餐全部有货，库存数据与官方库存页同步；The Tokyo Plan 属于限量套餐，售完即止。

| 套餐 | 配置（CPU / 内存 / 硬盘） | 月流量 · 端口 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| The Tokyo Plan（DC39v2） | 1核 AMD / 1 GB / 20 GB SSD | 500 GB · 2.5 Gbps | $79/年（用码后 $73.65） | [ 查看限量库存](https://bwh81.net/aff.php?aff=77528&pid=162) |
| SPECIAL 40G KVM PROMO V5 - TOKYO CN2 GIA | 2核 / 2 GB / 40 GB | 500 GB · 1.2 Gbps | $899.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=108) |
| SPECIAL 80G KVM PROMO V5 - TOKYO CN2 GIA | 4核 / 4 GB / 80 GB | 1 TB · 1.2 Gbps | $1559.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=109) |
| SPECIAL 160G KVM PROMO V5 - TOKYO CN2 GIA | 6核 / 8 GB / 160 GB | 2 TB · 1.2 Gbps | $2999.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=110) |
| SPECIAL 320G 4TB KVM PROMO V5 - TOKYO CN2 GIA | 8核 / 16 GB / 320 GB | 4 TB · 1.2 Gbps | $5899.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=111) |
| SPECIAL 640G KVM PROMO V5 - TOKYO CN2 GIA | 10核 / 32 GB / 640 GB | 6 TB · 1.2 Gbps | $9989.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=123) |
| SPECIAL 1280G KVM PROMO V5 - TOKYO CN2 GIA | 12核 / 64 GB / 1280 GB | 8 TB · 1.2 Gbps | $18989.99/年 | [ 购买](https://bwh81.net/aff.php?aff=77528&pid=125) |

几个表格里放不下的细节：40G 和 160G 支持月付、季付、半年付（下文单独算账）；官方流量口径为 1 TB = 1000 GB；CN2 GIA 系列页面标注 99.95% 在线率保障。所有套餐都带一个独立 IPv4 和一个 routed /64 的 IPv6。

## 东京 CN2 GIA 和 DC39：两条线路差在哪

同样写着“东京”，这两个机房走的是完全不同的网络。CN2 GIA 系列（TY8）主打电信 CN2 GIA，The Tokyo Plan（DC39v2）走混合上游、回程统一移动 CMI，价格也差了一个数量级。

CN2 GIA 系列的官方购物车原文是"Direct route via China Telecom (CN2 GIA), China Unicom, China Mobile; CN2 GIA preference on outbound"——翻译过来：去程三网直连（电信走 CN2 GIA、联通、移动各有直连路由），回程优先走 CN2 GIA。机房位于 Equinix TY8，与 Google、Cloudflare、NTT 等有对等互联，对海外访问速度也有帮助。

The Tokyo Plan 的路线是另一套：去程电信走 CN2、联通走 4837、移动走 CMI；回程统一走移动 CMI 的日本线路。今年 5 月的一篇测评文章提到，移动宽带存在 QoS 行为，建议开通后先实测再决定去留——反正 30 天内可以退（条件见下文）。

怎么判断：电信宽带、经常在晚高峰用，CN2 GIA 的溢价花得值；移动用户走 DC39 的 CMI 回程反而是自家线路，性价比更高；联通用户两者差别相对小，可以按预算定。另外 DC39 的端口速率是 2.5 Gbps，比 CN2 GIA 系列的 1.2 Gbps 更快，下载大文件时有优势。如果你倾向 CN2 GIA，👉 [查看 40G CN2 GIA 套餐的年付价格](https://bwh81.net/aff.php?aff=77528&pid=108)，它是整个系列里最便宜的入门位。

## 同一套餐，月付和年付差多少

差别比很多人想的大。以最小的 40G CN2 GIA 为例：月付 $89.99，一年下来 $1079.88，比年付 $899.99 多花约 $180，相当于凭付款方式就差了 17%。

- **40G CN2 GIA**：月付 $89.99 / 季付 $249.99（折合 $83.33/月）/ 半年付 $479.99（折合 $80/月）/ 年付 $899.99（折合 $75/月）
- **160G CN2 GIA**：月付 $299.99，年付 $2999.99（折合 $250/月），年付一年能省约 $600
- **The Tokyo Plan**：只有年付一种，$79/年。今年 5 月的测评文章里给出了优惠码 BWHCGLUKKB（6.77% off），到手 $73.65，折合每月约 $6.14

我的建议是分两类处理：CN2 GIA 系列单价高，对线路没把握的话先月付验证一两个月，确认晚高峰稳定后再做长期投入；The Tokyo Plan 本身就便宜，直接年付就好，纠结月付省下的钱还不够一顿外卖。

## 下单前要确认的几个限制

这几条大多写在购物车页面和套餐介绍里，容易漏看，但对日常使用影响不小。

**纯自管理（Strictly self-managed）**。官方购物车明确标注了这一点：搬瓦工只保证机器和网络本身正常，系统装什么、软件怎么配、出了问题怎么排查，都靠自己。没有运维经验的话，把学习成本算进总成本里。

**退款条款两个系列不一样**。The Tokyo Plan 写得清楚：30 天内流量使用低于 10% 可以退款；如果 IP 被 GFW 屏蔽，同样支持退款，属于低风险尝试。CN2 GIA 系列的购物车页面没有展示同类退款承诺，下单前建议把结账页的服务条款完整看一遍再付款。

其他几条快的：在线率方面，CN2 GIA 系列标注 99.95%，The Tokyo Plan 的介绍写的是 99.9%；流量按月重置，1 TB 按 1000 GB 计，有用户反馈 The Tokyo Plan 实际给到约 550 GB，以你自己后台显示为准；所有套餐都支持免费自动备份和免费快照、KiwiVM 面板一键重装系统、手动挂载 ISO、自助更新 rDNS，系统覆盖 CentOS、Debian、Ubuntu、Rocky Linux 和 AlmaLinux。

## 按场景选：哪种情况买哪个

直接给决策规则，对号入座就行。

- **年预算一百美元以内** → The Tokyo Plan，$73.65 到手。1核1G 跑博客、轻量代理、学习环境都够，免费快照和自动备份对新手也友好。
- **电信宽带 + 晚高峰敏感 + 预算充足** → 40G CN2 GIA 起步，$899.99/年。它比 The Tokyo Plan 贵十倍不止，买的就是回程 CN2 GIA 这一条。
- **挂多个站点，或几个人分摊使用** → 80G（$1559.99/年）或 160G（$2999.99/年）。160G 的 8 GB 内存跑面板加数据库会宽裕很多，2 TB 月流量也够分。👉 [查看 160G CN2 GIA 的当前价格](https://bwh81.net/aff.php?aff=77528&pid=110)
- **320G 及以上** → 给业务和团队准备的。640G 和 1280G 对个人用户来说基本是多余配置，别为用不上的参数付费。

## 关于搬瓦工东京 VPS 的常见问题

**搬瓦工东京套餐现在有货吗？**
有。CN2 GIA 系列 6 个套餐在本文检索时全部有货；The Tokyo Plan 是限量套餐，官网标注先到先得，售完即止。

**CN2 GIA 优化的是去程还是回程？**
回程。官方购物车标注"CN2 GIA preference on outbound"，即 VPS 流回国内的方向优先走 CN2 GIA；去程则是三网直连。晚高峰卡不卡主要看回程，所以这个标注比“三网直连”四个字更值得关注。

**不好用能退款吗？**
The Tokyo Plan 可以：30 天内流量使用低于 10% 能退，IP 被 GFW 屏蔽也能退。CN2 GIA 系列页面没有列出类似条款，下单前先在结账页确认。

**优惠码在哪里填？**
在结账页（checkout）的优惠码栏填写。BWHCGLUKKB 来自今年 5 月的测评文章，折扣为 6.77%，官方优惠码可能随时调整，以结账页实际显示的折扣为准。

## 下单前最后确认两件事

先看自己家的宽带运营商：电信优先 CN2 GIA；移动选 DC39 的 CMI 回程更顺路；联通两者都可以，按预算定。再对一下用途和预算：轻量用途别为用不上的配置加钱，多站点和高并发再往大套餐走。

两件事都想清楚了，👉 [前往搬瓦工官网查看东京套餐的最新库存和价格](https://bwh81.net/aff.php?aff=77528)，东京线路的套餐库存变化比较快，看到合适的配置就别拖太久。
