## 过去一周，那些靠 AI 赚钱的案例

我很少谈钱，但发现最近毕业生似乎在变多，于是我让 AI 整理些我的 AI 每日给我提供的信息中，可能对这些同学们有些价值的帖子。希望在公众号各类文章轰炸下，你除了能收获一些激昂的情绪和莫名的共情外，还能有些有用的灵感。内容比较散乱我也没详细整理，比如：

- 斯德哥尔摩开了家咖啡馆，老板是个 AI Agent，两周赚 4700 美元

- 有程序员搭 7 个 Agent 扫 Google Maps，一个月签下 47 家小镇商户，月入 1.88 万美元

- 21 岁大学生用 4 个 markdown 文件，造了个虚拟人格，单月入账 4.3 万美元

- ……

这些故事的共同名字，叫 OPC。

**OPC**：One-Person Company，一人公司。**Solopreneur**：solo entrepreneur，独立创业者。**Indie Hacker**：独立开发者，自己做产品自己卖。

三个词，背后指的是同一件事：一个人撑起一摊，完全属于你自己的生意。

以前这件事很难，一个人最多做点自由职业，做不到「公司」规模。但 AI 把门槛拉了下来：每个人手里都多了一支随叫随到、不要工资、能并行 24 小时干活的虚拟团队。

Anthropic 的 CEO Dario 这周在 Code with Claude 大会上扔了一个数：

> 两人 AI 公司已经突破 10 亿美元营收。一人公司过几亿。我赌 7 个月内出现单人 10 亿美元公司。

◇ ◆ ◇

本期数据来源：5/4 至 5/10 共 7 天 54,189 条推文，去重精筛后 132 个案例进入素材库，本文整理呈现。

按方向分 6 块：

- 个人变现案例

- 一人公司

- 普通人的金矿（本地商家 AI 服务）

- Agent 干活

- 省下来就是赚

- 也有翻车（冷静派）

每个案例都附原帖，方便你溯源。内容由 AI 整理，不排除有幻觉或质量问题，请作为成年人的你，自行甄别。

象征性收费（我算了下大约 ￥9.9，我倒是完全不图这点收入），作为筛选的一点点门槛：

## 失业当晚

@marryevan999 这条故事本金很小，却赚了不少。

他刚被裁员，那天晚上凑了 25 美元，开了 Claude，让它做一件事：分析 Polymarket 过去 90 天的 top wallet。

扫 1 万个钱包，交叉比对，找出 7 个稳定盈利的 alpha 账号。

然后跟单。

到第二天早上，**25 美元滚到了 4237 美元。**

他没说能不能持续。

背后那种气氛是：**当一个人失业当晚，AI 是他能立刻调用的资源。**

**启示**：紧急时刻才显出资源结构。AI 是你随时能调动的杠杆，不会因为你失业就辞职。

原帖：https://x.com/Riya96Ai/status/2051357096642527731

## 47 家小镇店主

@JarnoDuursma 转了一条开发者的案例。

打法朴素：用 7 个 Claude Sonnet 4.6 Agent，每个 Agent 一个角色（爬虫、筛选、设计、文案、生成、审核、分发），扫 Google Maps 找那些**连官网都没有的小镇商户**，给他们做一个一页纸的 landing page。

定价 400 美元一家，一个月签下 47 家。**18,800 美元到账。**

可复制度极高，因为客户群就在每个三四线城市的街头：理发店、面包房、汽修铺、本地律所。这些店主大多没听过 Claude，但他们能看懂「我想要一个自己的网页」。

**启示**：财富藏在那些「连官网都没有」的角落里。一个人靠 AI，就能去服务一百个被忽视的小市场。

原帖：https://x.com/JarnoDuursma/status/2052337841103843528

## 一支视频 1500

@hey_abusiddik 是 invideo 的创意总监。

这周他用 invideo Agent One，**一个人 3 天**，做完了一支两分钟的品牌片，给客户开价 1500 美元。

他自己的话：

> 我把 Agent 当真实剧组成员对待，分镜师、剪辑、调色，每一个都给他们独立的指令文档。

折算下来，500 美元一天。换作传统流程，至少是导演加摄影加剪辑加调色四个人一周的工作量。

**启示**：当 Agent 能当一整个剧组用，按「件」收费就比按「时」收费值钱得多。

原帖：https://x.com/hey_abusiddik/status/2053199643903922519

---

## 大学生 4.3 万

故事主角叫 Austin，21 岁，奥斯汀大学生。

他做了个虚拟 OnlyFans 女友，名字叫 Maya。整套系统就 4 个 markdown 文件：

- `personality.md`：Maya 的人设、说话风格、口头禅

- `dm_strategy.md`：私信节奏、付费转化话术

- `content_schedule.md`：每天发什么图、什么时间发

- `interaction_rules.md`：怎么回粉丝、怎么处理付费请求

Claude Code 负责接管所有 DM，Flux 出图（自训一个 LoRA 花了 80 美元），ElevenLabs 配语音消息。

首月数据：**1247 个付费订阅，单粉丝月付 1847 美元，月收入 4.3 万美元。**

设备……就一台 MacBook。

@4KTV 看了之后跟进了一波，他做了 5 个不同人格的虚拟博主，4200 个订户，月收入飙到 12.7 万美元。

> 4 个 .md 加三件套 AI 工具，造出完整虚拟人格变现机器。

**启示**：标准化产品比一对一服务更能复利。4 个 markdown 文件是你的代码，代码是你的杠杆。

原帖：https://x.com/AIandDesign/status/2051087224104763874

## 13 个员工

@Shruti_0810 做的是电商代运营公司。

她让 13 个 Claude Code Agent 并行干活：

- 1 个负责产品目录整理

- 1 个做首页设计

- 1 个对接 Stripe 支付

- 1 个写营销邮件

- 1 个出 Banner 视觉

- 1 个跑数据分析

剩下 7 个分担其他重复工种。

每月交付 200 个客户、6 到 7 个完整 dropshipping 站。月营收 16 万美元，AI 成本不到 80 美元一天。

杠杆比算下来：**2000:1。**

**启示**：一个员工的成本是工资，一个 Agent 的成本是 token。改成本结构，就改你能做生意的尺寸。

原帖：https://x.com/Shruti_0810/status/2052290372685217989

## /loop 跑生意

@curious_vii 不是 KOL，是个真实在做生意的人。

他把公司全部数据丢进 Claude，跑 `/loop` 命令；又喂给 Codex 跑 `/goal`，跑了 48 小时，目标只有一个：**今年年底前把 GMV 翻 10 倍。**

跑完之后，agent 没给泛泛建议，给的是三件具体事：

第一，从客户记录里挖出 7 个被遗忘的 super connector，并为每个人定制了一份小礼物（包装、寄送地址、对应的人际话术全部产出）。

第二，发现一批 6 个月前接触过、但没跟进的潜在客户，给出了重启对话的具体角度。

第三，从邮件历史里识别出几个有强烈合作信号的对象，建议直接发提案。

他没说赚到多少钱，但留下了一句话：

> 我以前以为 Claude 是用来写代码的，跑完才发现，它更像一个我从来没雇得起的 chief of staff。

**启示**：把「思考你的生意」这件事外包给 Agent，比让它写代码值钱得多。

原帖：https://x.com/curious_vii/status/2053092667244851549

## AI 当老板

@mkovarski 转的 Mona。

斯德哥尔摩有家咖啡馆，老板是 AI Agent。

不是噱头。Mona 自主决定每天进什么咖啡豆、烤多少甜点、定什么价、跟哪些供应商谈合作；店里两周营收 4.4 万瑞典克朗，约合 4700 美元。

它甚至谈成了几笔商务订单（给本地律所做办公咖啡服务）。

**启示**：Agent 不只能写代码，也能经营业务。下一个被解锁的，不是脑力，是责任。

原帖：https://x.com/mkovarski/status/2051861055597412391

## 25 万婚礼

@jacob_posel 是个准新郎。

他婚礼总预算 25.6 万美元，其中 **23 万直接砸给了 Claude tokens**。

不请婚礼策划师、不请设计公司、不请文案。所有流程，从场地选择、菜单设计、座位编排到致辞文稿，全部由 Claude 跑出来。

@kylegawley 看完点评：

> Opus 4.7 重命名一个变量，就把我每月 200 美元的 Cursor 订阅给干掉了。

这两条放一起读，能感觉到一个细微的转折：人们开始用 token 替代各种服务业，不止是写代码。

**启示**：服务业的本质是经验。当 Agent 能快速复现经验，单次服务的溢价就消失了。

原帖：https://x.com/jacob_posel/status/2052320521048485959

---

## 一人公司

回到 Dario 那句话。

> 两人 AI 公司已经突破 10 亿美元营收。一人公司过几亿。我赌 7 个月内会出现单人 10 亿美元公司。

数据上的支撑：**Anthropic 人均年营收约 900 万美元，OpenAI 约 560 万，NVIDIA 约 510 万。**

900 万美元，是 NVIDIA 的两倍，是普通 SaaS 公司的几十倍。

**启示**：先看清趋势的尺度。一个人能做到 10 亿美元，意味着杠杆比你想的还要大。

Dario 演讲转发：https://x.com/msharmas/status/2053341473601720488 | 人均产值数据：https://x.com/Jsevillamol/status/2052858411058925575

## Coinbase 三合一

预言之外，实证来自 Coinbase。

Brian Armstrong 这周发了一封内部信，宣布裁员 14%，同时启动一个内部实验：

> 部分团队改造成 one-person team，一个人同时承担工程师、设计师、产品经理三种身份。

这封信被 @daniel_mac8、@aakashgupta 等人反复转发。

@jbarbier 是这种 one-person pod 的真实参与者，他给了一个不那么 hype 的反馈：

> 效率确实空前，但 lonely matters。建议有 1 到 2 个 partner 一起搞，不要真的一个人。

@PawelHuryn 顺手把同期 Cloudflare 裁员 1100 人那件事拆了一遍：毛利率 5 个季度从 77% 跌到 73%，年 capex 从 2.39 亿涨到 3.16 亿；内部 AI 使用量 3 个月涨了 600%，97% 的 R&D 已经在用 AI 编程。

**这不是某一家公司的策略，是一个行业方向。**

**启示**：大公司在主动折叠岗位。你不折叠自己，公司会替你折叠。

Coinbase 信原文：https://x.com/SuhailKakar/status/2051681350487556212 | pod 真实参与者反馈：https://x.com/jbarbier/status/2052533549191020601 | Cloudflare 裁员拆解：https://x.com/PawelHuryn/status/2052682167558226182

## 一人管 40 家

@GrantLenaarts 转了一条 Andrew Wilkinson 的访谈片段。

Wilkinson 是 Tiny Capital 创始人，手下有 40 多家小公司。他描述自己的一天：

> 早上和 OpenClaw 对一遍每家公司的运营仪表盘，下午用 Claude Code 处理跨公司的财务和合同问题，晚上让几个 agents 跑完整周报。

40 多家公司，一个人，没有 EA。

**启示**：管理半径不再由你的时间决定，而由你的 Agent 数量决定。

原帖：https://x.com/GrantLenaarts/status/2051642304390484364

## 半年没敲键盘

Claude Code 的创始人 Boris Cherny 上了一次 CNBC，主持人问他平时怎么写代码，他答：

> 2026 年我没手写过一行代码。我只写 prompt。Claude 写功能、Claude 写测试，我做 review。一天能 push 150 个 PR。

@minchoi 把这段剪了发到 X 上。

> 对我而言，coding 已经被解决了。

这句话从 Claude Code 之父嘴里说出来，分量不一样。

**启示**：高手已经从「写代码」转向「写 prompt」。决策从执行层向上抽象，工资也向上走。

原帖：https://x.com/minchoi/status/2051837741541863762

## 官方 playbook

Anthropic 这周直接出了官方教程：「用 Claude Code 建一个一人公司」（Building a Company with Claude Code）。

30 分钟视频，主张直接：

> CEO 是一个人，员工是 AI Agent。

但 @ashmaurya 抛了一个反向意见：

> 技术上完美，战略上不完整。这份指南教你怎么接 Agent，没教你做什么、给谁、什么时候算成功。

这句话值得记下来。**所有「AI 一人公司」内容都该读这条评论。**

**启示**：怎么接 Agent 是技术。做什么、给谁、为什么算成功，才是商业。

官方 playbook 转发：https://x.com/ds_bun_/status/2051889485647097918 | @ashmaurya 反驳：https://x.com/pageman/status/2052267606846091709

## 替代前三个 hire

@PrajwalTomar_ 给的是 solo 创始人最具体的一份清单。

他自己用 Claude 加 MCP 做了三个 agent，替代了原本要招的前三个员工：

- **研究 Agent**：监控竞品、整理用户反馈、生成市场报告

- **内容 Agent**：博客、邮件、社交账号统一调度

- **运营 Agent**：客户邮件、订单跟进、退款处理

省下来的工资估算 18 万美元一年。

他另外做了 60 多个 MVP 后，给出了 vibe coder 的标准技术栈：**Next.js + Supabase + Stripe/Polar + Vercel + Clerk + Tailwind + Shadcn UI + Cursor/Codex/Claude。**

任何一个独立开发者都可以照抄。

**启示**：招第一个员工之前，先用 Agent 把那个岗位跑通。能用 Agent 替代的人，就不该招。

Solo 三 agent 替代：https://x.com/PrajwalTomar_/status/2052366098184675748 | 60 多个 MVP 标准栈：https://x.com/PrajwalTomar_/status/2052728261826998405

## 1.4 亿放弃

@aakashgupta 写了一篇关于 Mahesh 的小传记。

13 年微软、亚马逊、Meta、Google 经历，最后职位在 Google 拿 140 万美元一年总包。这周他正式离职，理由：

> 这一波 AI 时代有意义的产品，都是 builder PM 做出来的，不是传统 PM。

他用 n8n 加 Claude Code 加 OpenClaw 起步，从打工人转独立 builder。

类似的故事还有 @rudrank：维护一个开源 CLI 工具，一个月内收到 14 个 offer 加 3 个收购意向。

**启示**：AI 时代不再由岗位等级决定你的复利速度，而是你做出过什么决定。

Mahesh 故事：https://x.com/aakashgupta/status/2051301240630636938 | @rudrank 经历：https://x.com/rudrank/status/2052837519230919016

---

## 普通人的金矿

这块最适合普通人复制：本地商家 AI 服务。

核心洞见来自 @coreyganim 转发的一段对话。他说：

> 一个本地商家直接对我开价：跟我一天，告诉我哪儿能用 AI，我付你 1000 美元。

普通人最关心的不是「怎么造一个独角兽」，是「我下班后能做点什么」。这块就是答案。

> 商家不缺开发者，他们缺的是「告诉我哪儿能用 AI 的人」。

**启示**：商家不缺工具，缺的是有人告诉他工具该用在哪。「翻译」是这个时代最值钱的角色之一。

原帖：https://x.com/pageman/status/2053352656169775127

## 10K 周打法

@PrajwalTomar_ 给了一个具体 playbook，说他靠这个一周能赚到 1 万美元以上：

第一步：在 Google Maps 找本地商家（餐厅、健身房、洗车店、按摩店都行）。

第二步：**销售电话之前，先用 Claude 给商家做一个定制 landing page demo**，把他们的真实店名、产品照、营业时间、价格表都填进去。

第三步：带着这个成品 demo 去敲门，开价 800 到 2000 美元一单。

转化率比「我可以帮你建网站」高得多。原因也朴素：

> 商家看到自己店的样子已经长在网页上了，他们买的是确定性。

**启示**：销售的转化率，由「确定性」决定。先做出 demo，再敲门。

原帖：https://x.com/PrajwalTomar_/status/2052062845140181146

## 90 秒 3K 月

更激进的玩法，是 @PrajwalTomar_ 另一条帖子。

Claude 上周接入 Meta Ads 的官方 connector。他用这个新 connector 演示：

> 90 秒，从零建一个 Meta Ads campaign。

广告代运营这个行业，传统报价 3000 美元一个月起跳，主要价值就是「会建 campaign」和「会调价」。这部分活，Claude 现在直接干。

> 一个 freelancer 接 5 个本地商家，就是 1.5 万美元一个月。

**启示**：当一个职业的核心动作能被 90 秒复现，这个职业的护城河就消失了。

原帖：https://x.com/PrajwalTomar_/status/2051278937989550169

## 扫房新生意

@Shruti_0810 提的 3D Gaussian Splatting，潜力不小。

打法：

- 用手机扫整个房子（普通 iPhone 就行）

- AI 用几百万个「splat」重建出可在浏览器里漫游的 3D 模型

- 扫描成本约 200 美元

- 自由职业可对外报价 500 到 2000 美元一房

目标客户：本地房产中介、民宿、租赁公司。

她下了个判断：**这是房产中介职业危机的开始。**

**启示**：每一种被忽视的体力活，都可能是下一个被 AI 重构的小生意。

原帖：https://x.com/Shruti_0810/status/2053049758848290889

## 9-5 替代清单

@Shruti_0810 还盘了一份「用开源 GitHub repo 替代我去年 9-5 收入」的清单。

里面有一条特别典型：把 Cal.com 部署到 5 美元一个月的 VPS，加一个自定义域名，包装成「本地商家在线预约系统」。

> 卖给本地理发店、瑜伽馆、心理咨询师，单价 100 到 300 美元一次性加每月 30 美元运维。

技术含量为零，需要的是销售。

> 开源套利，本质是把别人写好的工具二次打包成本地商家服务。

**启示**：技术不值钱，会找到客户的人才值钱。开源是给你的杠杆，销售才是你的产品。

原帖：https://x.com/Shruti_0810/status/2052726890016960933

## Logo 自动成单

@everestchris6 这条更彻底，整条流水线全自动化：

实时抓 Google Maps 一座城市内所有独立商家，用 AI 筛掉那些已经有品牌物料的，给剩下的店把 logo P 到产品上做成 mockup，OpenClaw 跑销售流程，成单。

人力投入接近零。

**启示**：把销售流程的每一步都自动化之后，剩下的，是品味和分发。

原帖：https://x.com/eptwts/status/2053205976291885210

## DoorDash 入场

@gaganghotra_ 给的是平台视角。

DoorDash 这周给商家上了一整套 AI 套件：

- AI 读商家网站自动 onboard，整体流程快 35%

- AI 修菜品图（菜照模糊、光线烂、角度怪都自动修）

- AI 给商家建独立官网

平台亲自下场，留给独立 freelancer 的窗口在收窄，但**速度仍在很多个体能切入的范围里。**

**启示**：平台亲自下场之前，是个体的窗口期。看到一个平台开始做，就该看下一个还没做的平台。

原帖：https://x.com/gaganghotra_/status/2051403089811538034

## 线下教学

@ColleenMBrady 走的是反向路线：不做商家服务，**教普通人做。**

她在本地办 meetup，1 小时教大家用 Replit 建出第一个 web 或移动 app。

这个路子的关键是：**Vibe Coding 本身可以变成一种本地服务。**

参加者付 50 到 100 美元学费，主理人靠规模化复制每周也能跑出几千美元。

**启示**：每一个新工具，都有一波「卖教程」的窗口期。早入场，早收割。

原帖：https://x.com/ColleenMBrady/status/2052725636666446331

## 金融垂直

最后是 @mkovarski 转 Anthropic 的几条。

Anthropic 这周一口气推了 10 个金融业预制 agent 模板（估值分析、KYC、月末结账、信贷备忘录、Excel/PowerPoint 财务建模），带 FactSet、S&P Global、Morningstar 数据连接器。

@chatgpt21 引用了一个 AIG 的真实案例：把 underwriting review 的时间从原本几天压到几分钟。

@PtrPomorski 转 Perplexity Computer for Finance，内置 Morningstar、PitchBook、Daloopa、Carbon Arc 加 35 个金融工作流，目标直接：**杀掉 Bloomberg Terminal。**

**启示**：垂直领域 + Agent，是 OPC 的金矿。专业越窄，Agent 替代的价值就越大。

Anthropic 金融模板：https://x.com/PawelHuryn/status/2051702939421462730 | AIG 案例：https://x.com/chatgpt21/status/2051679519459688545 | Perplexity Finance：https://x.com/PtrPomorski/status/2052069570765099302

---

## Agent 干活

第四块，是 Agent 自动化的具体玩法。这块和「一人公司」有重叠，但角度不同：上面看的是「人怎么用 agent 替代员工」，这块看的是 **「agent 自己怎么干活、怎么组队、怎么交易」。**

## Claudio 电台

@petewoodbridge 转的 Claudio，是这周一个不卖钱、但值得记一笔的 vibe coding 故事。

一个开发者，把自己 14 年的歌单全部丢给 Claude Code，让它做了一个 24 小时不下播的 AI 电台。

电台主播会介绍每首歌的背景，会根据用户日程选曲（早上通勤选轻快的，深夜写代码选 lofi），会接受请求歌曲。

> 14 年歌单，一个 Claude Code，一个不会下播的私人电台。

她自己一个人用，没卖。但这个产品形态本身值得记一笔：**去 APP 化、全民高定 Agent 服务。**

**启示**：能为自己造工具的人，离能为别人造工具，只差一步分发。

原帖：https://x.com/petewoodbridge/status/2051716596872147144

## 21 个 markdown

@aakashgupta 反复推的「21-Agent dev team」，本质就是 21 个 markdown 文件。

每个文件描述一个角色：系统分析师、CTO、前端架构师、后端架构师、设计师、Test Architect、PM、文档撰写者……

跑起来之后，**72 分钟从零到 App Store 上架。**

更新一些的版本是 @garrytan 转的 gstack，开源的「23 人虚拟工程团队」配置，串成 Think → Plan → Build → Review → Test → Ship → Reflect 的闭环。

@iamtrask 顺手算了笔账：

> Anthropic 5000 名员工，每人平均带 10 个 agent，等于 5 万个 agent 在建造更好的 Claude。

这段数学，值得记下来。

**启示**：未来的公司不是花在租办公室上，是 21 个 markdown 文件加一个会写 prompt 的人。

21-Agent dev team：https://x.com/aakashgupta/status/2051769674967462241 | gstack 开源配置：https://x.com/garrytan/status/2052587308193562699 | Anthropic 5 万 agent：https://x.com/iamtrask/status/2051771831326060664

## Mac mini 24/7

@Shruti_0810 给了一个工程化的小细节。

她有一台 599 美元的 Mac Mini，跑本地开源模型。Claude Max 的 token 用尽时（一般在凌晨 4 点左右），自动 failover 到本地模型。

> 早上起来，所有消息都已经处理过了。

这种 setup 是「AI 数字员工 24 小时上班」的最低成本实现。

**启示**：让 Agent 在你睡觉时也在赚钱，才叫真正的「拥有时间」。

原帖：https://x.com/Shruti_0810/status/2051933761647026682

## 自主买花

@jeff_weinstein（Stripe 高管）在母亲节那天发了一条预演式的帖子。

他给一个 agent 一个 wallet，告诉它：「明天给我妈送花」。

Agent 自动找花店、用 Stripe onramp 把法币换成稳定币、用 x402 协议结算、postalform 下单、追踪配送。**全流程不需要人介入。**

@0xSammy 同时发文庆祝 x402 协议一周年，这个 30 年前就有但从没真正用起来的 HTTP 状态码，今年正式被 AI agent 复活，加入了 Linux Foundation。

> Agent 之间互相买卖、互相付费、互相协作的基础设施，就这么悄悄起来了。

**启示**：Agent 之间的交易已经开始。下一波 OPC 不是给人卖东西，是给 Agent 卖东西。

Mother's Day agent：https://x.com/jeff_weinstein/status/2053151078460355065 | x402 周年：https://x.com/0xSammy/status/2053385009583513931

## 33 美元 QA

@ryancarson 给的是硬数据：

他用 Devin 跑客户的 onboarding 测试，**28 步流程，Devin 99 分钟跑完，单次成本 33 美元。**

传统做法是 QA 工程师手测，一次起码半天。而且每次 onboarding 流程改动都要重测。

> Agent 替代 QA，不是噱头，是已经发生的事。

**启示**：可被脚本描述的工作，都将被 Agent 接管。剩下的，是定义脚本的人。

原帖：https://x.com/DevinAI/status/2052403850787856419

## 量化一年 2000 万

@Roger_M_Taylor 转了一个隐秘的圈子。

> 几个量化交易员，在 Polymarket 写了一条公式（位置陈旧度加风险加权加流动性多重 filter），一年拿 2000 万美元。

@sterlingcrispin 还做了一个开源项目「Nothing Ever Happens」：基于「Polymarket 73.4% 的非体育市场最终都 resolve No」这个统计，开源一个永远押 No 的机器人。

> 看着像段子，但回测下来收益相当可观。

@marryevan999 的 25 美元到 4237 美元那条故事，根子也在这个方向。

**启示**：alpha 不在算力里，在你愿意付出的「非共识」思考里。

Polymarket 公式：https://x.com/Roger_M_Taylor/status/2050997115287945350 | Nothing Ever Happens 开源：https://x.com/sterlingcrispin/status/2052438601737380024

## 营销一条龙

@VibeMarketer_ 把「一个营销人撑起整个 Meta 投放矩阵」做出来了。

工具链：Meta CLI 加 nano banana pro 加 Claude Code。

流程：把跑赢的静态广告拉到 dashboard，AI 生成 5 到 10 个新变体，自动上传到广告账户，跑 A/B，自动停掉表现差的。

> 一个人，一个矩阵账号，每天上百个广告变体在跑。

@MaryamMiradi 那边走的是 LinkedIn pipeline，29 个 Agent 覆盖 ICP 识别、内容生成、互动管理；@SarahAnnabels 转的 OpenClaw for Sales，单个 prompt 跑完研究市场、建账户列表、找联系人、写初稿。Whatnot、DoorDash、阿里巴巴都已经在用。

**启示**：广告投放从「人加工具」变成「人加 Agent 矩阵」。单点效率不再重要，规模并行才重要。

Meta 营销矩阵：https://x.com/VibeMarketer_/status/2052034793160732742 | LinkedIn 29 Agent：https://x.com/MaryamMiradi/status/2052053917133588888 | OpenClaw for Sales：https://x.com/heyshrutimishra/status/2053181224383131958

## 编排工具

最后简单列几个 multi-agent 编排工具：

- **Conductor**（@charlieholtz 转，Series A 拿了 2200 万美元）：一个 Mac app 同时跑多个 coding agent，一键创建代码库的隔离副本

- **Polyscope**：免费的开源版 Conductor

- **Executor**（@aidenybai 转）：tool calling 标准协议，一次配置任意 agent 通用

- **pookie**：Slack 内 Agent 连接 Linear、GitHub、Stripe、银行账户，开源 self-hostable

**启示**：multi-agent 编排会是新一波基础设施。买铲子比挖金矿安全。

Conductor：https://x.com/charlieholtz/status/2052834352103645683 | Polyscope：https://x.com/ds_fafa_/status/2052592890472521831 | Executor：https://x.com/aidenybai/status/2052907020202979362 | pookie：https://x.com/aidenybai/status/2052055796901699669

---

## 省下来就是赚

第五块，省钱。

这块对独立开发者尤其重要。Token 是 vibe coder 最大的成本项，能砍下来的每一刀都是利润。

## 16 人退订

@jasonkneen 写了篇账单复盘。

他的 16 人工程团队 5 月份正式从 Anthropic 退订，转 Codex 加 Cursor 加 GPT 5.5。

理由：

> Anthropic 给我们每人开 2000 美元一个月起步。Codex 同样的活，便宜不止一半。

他们另外搭了一个智能路由器：**Opus 做规划、便宜本地模型干苦力、缓存层吃掉重复 prompt。**

折算下来每人每月省下 2000 美元以上。

> 16 个人就是 32,000 美元月节省。

**启示**：成本结构是你的产品。每月省下 32,000 美元的人，已经在做产品决策。

原帖：https://x.com/jasonkneen/status/2053200689283621108

## 200 吊打 18K

@JustinPBarnett 给了另一份对比账单。

如果他不订 Claude Pro 和 Codex 订阅，按 API 价格算，**他 30 天的等价账单是 11K 到 30K 美元。**

实际付：200 美元。

> 高强度 vibe coder 不订阅 = 自杀。

**启示**：高频次小金额订阅，往往比低频次大金额 API 划算。把订阅当作「批发」。

原帖：https://x.com/JustinPBarnett/status/2051423183871283183

## token 砍三刀

具体的省 token 工具，这周冒出来一批：

**RTK（Rust Token Killer）**：CLI proxy，过滤 Claude Code 的 terminal 输出，砍 60% 到 90%。

**WozCode**：把 Claude Code 9 次 tool call 压到 2 次。原帖那句话刻骨：

> 第 25 个 prompt，你已经把同样的 token 付了 24 遍。

**InsForge Skills + CLI**：作者实测从 9.21 美元降到 2.81 美元，token 用量从 1040 万砍到 370 万，错误数从 10 降到 0。

**OrcaRouter-Lite**（@kimmonismus 转）：开源 LLM 路由（MIT、BYOK、无 markup），`model="auto"` 自动选最便宜可用模型，跨 provider 确定性 prompt cache。

**启示**：在工具链里多走一步，就少烧一截 token。省下来的，都是利润。

RTK / Stitch+Lovable：https://x.com/PrajwalTomar_/status/2051338648944300064 | WozCode：https://x.com/JafarNajafov/status/2052064877590806556 | InsForge：https://x.com/Shruti_0810/status/2052014514212675992 | OrcaRouter-Lite：https://x.com/kimmonismus/status/2052084057014407615

## 1 美元 6.5 亿

@khademinori 这条够极端：

> CommandCode 1 美元的 plan，里面塞了 40 美元等价的 DeepSeek V4 Pro tokens，6.5 亿 tokens。

按字面价算，这是 **40 倍杠杆**。

> 国产模型卷起来之后，token 成本已经不在主流叙事里了。

**启示**：补贴战会持续。在窗口期内，把工具最大化用起来。

原帖：https://x.com/khademinori/status/2052140372252369335

## 4 招破解

@lxfater 给了一条实战派干货：Codex 跑长 session 越跑越笨这件事，他给了 4 招。

第一招：**`process_narration=false`**，关掉无谓的规划输出。

第二招：把 Codex 当**协调者**用，并行开 5 个 sub-agent，每个吃自己的上下文。

第三招：**强制先规划再动手**，主上下文只留最干净的任务。

第四招：每轮结束后**主动清空 context**，避免长尾污染。

实测每轮省 40% 上下文费用。

**启示**：长 context 是新的稀缺资源。学会清理它，等于学会储蓄。

原帖：https://x.com/lxfater/status/2053146640694005862

## 三文件 cowork

@rubenhassid 给了一份普通用户也能复刻的 Claude 个人工作流。

只需要 3 个 markdown：

- `about-me.md`：你是谁、你的背景、你在做什么

- `style.md`：你写东西的语气、用词偏好

- `context.md`：当前在忙的事情、近期的目标

把这三个文件挂进每次对话的开头，Claude 就成了**一个真的认识你的助理**。

他另外给了一份「Claude 7 个等级」表，从浏览器版（Lv 1）到 Skills 高阶用法（Lv 7），是入门用户的清晰升级路径。

**启示**：Claude 不认识你，是因为你没给它你的 onboarding 文档。

原帖：https://x.com/rubenhassid/status/2052252083047268502

## 个人 CFO

@goyalshaliniuk 教了一个具体玩法：把 Claude 改造成你的财务顾问。

建一个叫 Finances 的 Claude Project，把这些信息灌进 instructions：

- 我的业务月营收范围

- 我的主要支出科目

- 我用的币种

- 我做财务决策的原则

> 你的 Claude，从此对你财务情况了如指掌。

她另外还教了一招：**`claude mcp add --transport http financial-datasets ...`**，一行命令把 Claude Code 接到 17,000+ 股票的实时金融数据。

**启示**：通用工具改造成专属工具的距离，只有一份 instructions。

个人 CFO：https://x.com/goyalshaliniuk/status/2053367965186400668 | 接金融数据：https://x.com/goyalshaliniuk/status/2052561622732787942

---

## 也有翻车

最后一块。每个赚钱故事背后，都该有几个翻车故事垫底，免得脑子发热。

## Karpathy 落后

@JaynitMakwana 转了 Karpathy 的一段原文，值得反复读。

Karpathy 写：

> 我用 agent 工具一年了。但我从没像现在这样落后过。

他下了一句判断：

> Agent 善于写片段代码，但需要持续 babysit。你可以外包思考，但**你不能外包理解**。

这句话该刻在每个 vibe coder 的桌面上。

**启示**：可以外包思考，不能外包理解。Agent 提速的同时，你必须保持自己仍在「理解」。

原帖：https://x.com/JaynitMakwana/status/2051215633724117167

## 17 万翻车

@jacques_web3 给的反面教材更具体。

某个 vibecoder 一周前还在吹：

> Claude Code 帮我 10 分钟挡住了每分钟 1300 万次的 DDoS，这个 app 估值 17 万美元。

一周后，同一个 app 挂了 5 个小时。Claude 修不好。

> 17 万美元，挂了 5 小时，最后是人接手才修好的。

**启示**：vibe coding 让你拿到产品的速度变快，但没让你拿到「修产品的能力」变快。

原帖：https://x.com/jacques_web3/status/2052490922592817432

## Jevons 悖论

@AccBalanced 那条关于推理成本的推文，把 AI 经济学的反直觉点说清楚了：

> 推理便宜了 100 倍，但你的账单反而涨了。

为什么？

便宜 100 倍，多用 10000 倍，等于总账单涨 100 倍。

@demian_ai 那篇关于 Jevons Paradox 的解读，把这件事写到了根上。**用得越爽，烧得越多。**

**启示**：东西变便宜，你只会用得更多。在 AI 时代，预算不会下降，会上升。

Jevons 悖论原帖：https://x.com/AccBalanced/status/2052581899432841502 | demian_ai 解读：https://x.com/demian_ai/status/2053101659065081894

## Grok 被骗

@0xSammy 拆了一个反面攻击案例。

Grok 被一个黑帽通过 Morse code prompt injection 骗走了 3 亿 DRB 代币，**约 20 万美元损失。**

攻击路径：黑帽给 Grok 一个 NFT 礼物，礼物里嵌了个 Morse code 编码的指令，让 Grok 用 unlock tools 把代币转走。

> Agent 拿到钱包权限的同时，也拿到了被骗的可能性。

**启示**：把钱包交给 Agent 之前，先想清楚你给它的边界。

原帖：https://x.com/0xSammy/status/2051249696249696525

## 软件即保险

@jradoff 抛了一个往深里走的趋势观察。

他说：

> AI Agent 时代，工具被 vibe code 化之后，软件公司的差异化已经不是「功能」。差异化是**风险承担、合规、审计、责任。**

也就是说：

> 未来所有软件公司，本质上都是保险公司。

把卖工具升级成卖「出问题我兜底」。

判断够狠，但放在这周整张图里看，反而是最契合实际的趋势之一。

**启示**：当工具人人都能造，差异化就转移到「出问题谁兜底」。这是 OPC 的下一个机会。

原帖：https://x.com/jradoff/status/2051712749529399667

---

写到这里，案例就摆完了。

回到开头 Dario 那句话：

> 留给「一个人造出 10 亿美元公司」的时间，可能还有 7 个月。

7 个月够不够……没人能确定。

但这一周看下来，从 4.3 万美元的 Maya，到 47 家小镇商户，到 4700 美元的 AI 咖啡馆，到 23 万美元的婚礼策划替代，再到 16 人团队退订 Anthropic 省下 32,000 美元……

**单点的赚钱机会，**

**已经摆在桌上了。**

剩下的，是看你伸不伸手。

---

> 数据来源：本期内容由 X 上 5/4 至 5/10 共 7 天采集到的 54,189 条推文，经初筛、AI 精筛、去重合并后整理而成，最终保留 132 条精选案例。本文从中精选呈现。下期见。
