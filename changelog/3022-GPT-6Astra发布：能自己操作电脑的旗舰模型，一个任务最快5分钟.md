# GPT-6 Astra 发布：能自己操作电脑的旗舰模型，一个任务最快5分钟

> 原文链接：[https://www.laoshoucun.com/chatgptdt/3022](https://www.laoshoucun.com/chatgptdt/3022)

<p><a href="https://www.laoshoucun.com/chatgpt" target="_blank" rel="noopener">GPT-6 Astra</a> 发布那天的演示里，最抓眼的是它自己操作电脑。官方放了一个找猫咪寄养的过程：从翻评价到打电话确认，AI 用了 5 分 27 秒，同样的事人来做平均要半小时。这类活以前只能人自己干。</p>
<p><img decoding="async" src="https://cdn.laoshoucun.com/web/2026/09/20260904184320_851796.png" alt="GPT-6 Astra 自动操作电脑"></p>
<p>这模型是 OpenAI 9 月初发布的。它跟上一代 Sol 比，变化集中在电脑操作这条线上。以前要让 AI 碰软件，得等厂商做接口，或者自己配一堆 MCP，现在这些都省了，它直接看屏幕，点鼠标，敲键盘。衡量电脑操作的 OSWorld 2.0 测试里，它拿到 72.6%，比 Sol 高出约 7 个百分点。跑完一项任务平均花 40 分钟，Sol 要 75 分钟。帮人筛职位投简历，过去前后要 5 个小时，它用 2 分 51 秒跑完。内测开发者还让它一次生成了能玩的原版级 Minecraft demo，以及一个完整的网页游戏。</p>
<p>价格不算低。输入一百万个 token 收 10 美元，输出一百万个收 50 美元，单次喂进去超过 27.2 万个 token，单价还要再翻一倍。按公开报价算，是上一代 Sol 促销价的 2.5 倍，跟 Anthropic 新出的 Fable 5.1 基本一个价位。</p>
<p>发布会上，总裁 Greg Brockman 也被问到了 AGI 的时间表。他说，几年后回看，答案大概就在这段时间，甚至就是这款模型。</p>
<p>跑分要分两拨看。官方公布的那拨，研究级数学的 FrontierMath（Tier 4）做对了 97.6%，GPQA Diamond 的科学题做了 96%，长程软件工程的 DeepSWE 做到 74.1%，漏洞利用的 ExploitBench 拿了满分。第三方 Artificial Analysis 测的通用智能是另一拨：Astra max 得 61 分，和 Sol 持平，Fable 5.1 是 66 分。两拨数据放在一起，它领先的其实是偏技术的活，泛泛的问答反而不突出。</p>
<p>省 token 是它另一个卖点。同样的编码活，它消耗的量只有 Sol max 的三分之一，Opus 5 high 的五分之一。OpenAI 估算，用最高配置跑完一个 DeepSWE 长任务，花在 API 上的钱比 Sol 少约 57%。幻觉率第三方也测了，Astra max 约 51%，Sol 是 92%。</p>
<p>安全上管得比较严。恶意网络请求，它拒答的比例是 91.5%，Sol 只有 59%。攻击能力最强的那一档被定为 Critical，只放给网络防御机构。跑长任务的时候，失对齐监控可能中途叫停，让人先看一眼再放行。</p>
<p>开放是分批进行的。最先是一小部分可信企业，ChatGPT 各级会员和 API 用户随后几天陆续拿到权限。拿到以后可以先拿自己的真实任务试一遍：同样的活烧多少 token，操作电脑的时候要不要人在旁边盯。</p>

---

原文链接：[https://www.laoshoucun.com/chatgptdt/3022](https://www.laoshoucun.com/chatgptdt/3022)
