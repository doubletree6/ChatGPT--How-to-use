
# ChatGPT&New Bing AI 使用心得

>2023.05.02 Updated by qinglin, leave comments if any questions
>if problem prosists after google, please contant **[Editor](#jump_1)**


- [ ChatGPT 中文指南 ](#-chatgpt-中文指南-)
    - [什么是 ChatGPT ?](#-什么是-ChatGPT?-#)
  - [使用途径](#使用途径)
    - [💻 OpenAI 官网](#-openai-官网)
    - [💻 poe](#-poe)
    - [💻 微软必应](#-微软必应)
    - [国内可使用ChatGPT镜像站点](#国内可使用chatgpt镜像站点)
    - [💻 第三方开发者开发的 ChatGPT 客户端](#-第三方开发者开发的-chatgpt-客户端)
    - [💻 国外竞品](#-国外竞品)
    - [💻 国产 ChatGPT 类似产品](#-国产-chatgpt-类似产品)
    - [更多工具](#更多工具)
  - [ChatGPT 工具](#chatgpt-工具)
    - [翻译: OpenAI Translator](#翻译-openai-translator)
    - [中科院科研工作专用ChatGPT](#中科院科研工作专用chatgpt)
    - [科研福音 chatPDF: 像聊天一样阅读 PDF](#科研福音-chatpdf-像聊天一样阅读-pdf)
    - [科研助手：researchgpt](#科研助手researchgpt)
    - [通过文字聊天实现 Excel 数据处理：酷表 ChatExcel](#通过文字聊天实现-excel-数据处理酷表-chatexcel)
    - [Doc 文件阅读助手: ChatDoc ](#doc-文件阅读助手-chatdoc-)
    - [写作助手: rytr](#写作助手-rytr)
    - [与文件对话：chatfiles](#与文件对话chatfiles)
    - [Multimedia GPT](#multimedia-gpt)
    - [与AI对话生成思维导图 ChatMind](#与ai对话生成思维导图-chatmind)
  - [ChatGPT 插件功能](#chatgpt-插件功能)
    - [ChatGPT 浏览器插件和小程序](#chatgpt-浏览器插件和小程序)
  - [如何与 ChatGPT 高效对话？——好的提示语学习](#如何与-chatgpt-高效对话好的提示语学习)
    - [Prompt 框架](#prompt-框架)
      - [Elavis Saravia 总结的框架：](#elavis-saravia-总结的框架)
      - [Matt Nigh 总结的 CRISPE 框架：](#matt-nigh-总结的-crispe-框架)
    - [Prompt 编写模式：如何将思维框架赋予机器](#prompt-编写模式如何将思维框架赋予机器)
    - [一个可以帮你自动生成优质Prompt的工具: AIPRM](#一个可以帮你自动生成优质prompt的工具-aiprm)
    - [💡 让生产力加倍的 ChatGPT 快捷指令](#-让生产力加倍的-chatgpt-快捷指令)
    - [💡 学习如何提示：Learn Prompting](#-学习如何提示learn-prompting)
    - [💡 提示语自动生成](#-提示语自动生成)
    - [创建，使用，分享 ChatGPT prompts: OpenPrompt](#创建使用分享-chatgpt-prompts-openprompt)
    - [生成AI绘图灵感](#生成ai绘图灵感)
  - [码农专区](#码农专区)
      - [OpenAI 官方使用指南：openai-cookbook](#openai-官方使用指南openai-cookbook)
      - [OpenAI python 接口](#openai-python-接口)
      - [OpenGPT](#opengpt)
      - [亚马逊的免费 AI 代码助手：CodeWhisperer](#亚马逊的免费-ai-代码助手codewhisperer)
      - [AI代码助手: codeium](#ai代码助手-codeium)
      - [Github Copilot 开源平替，可本地部署: Tabby ](#github-copilot-开源平替可本地部署-tabby-)
      - [将 OpenAI ChatGPT 集成到 VSCode: vscode-chatgpt](#将-openai-chatgpt-集成到-vscode-vscode-chatgpt)
      - [GPT 驱动的代码编辑器: Cursor](#gpt-驱动的代码编辑器-cursor)
      - [帮你生成完整 Github README](#帮你生成完整-github-readme)
      - [shell 中使用 ChatGPT](#shell-中使用-chatgpt)
      - [自动生成任何编程语言的文档: AutoDoc-ChatGPT](#自动生成任何编程语言的文档-autodoc-chatgpt)
      - [使用ChatGPT搭建微信聊天机器人](#使用chatgpt搭建微信聊天机器人)
      - [开源 ChatGPT 替代品列表](#开源-chatgpt-替代品列表)
      - [在任意软件上操作ChatGPT: Portal](#在任意软件上操作chatgpt-portal)
      - [一键免费部署你的私人 ChatGPT 网页应用: ChatGPT-Next-Web](#一键免费部署你的私人-chatgpt-网页应用-chatgpt-next-web)
      - [电报 ChatGPT 机器人：Chatgpt-Telegram-bot](#电报-chatgpt-机器人chatgpt-telegram-bot)
      - [将代码从一个语言翻译为另一个语言：ai-code-translator](#将代码从一个语言翻译为另一个语言ai-code-translator)
  - [相关资料](#相关资料)
  - [更多 AI 工具](#更多-ai-工具)
    - [AI 绘画](#ai-绘画)
    - [代码生成](#代码生成)
    - [AI辅助写作](#ai辅助写作)
    - [PPT生成](#ppt生成)
    - [语音/视频合成](#语音视频合成)
    - [AI 研究所](#ai-研究所)
  - [思考](#思考)
    - [ChatGPT 之父 Sam Altman: 万物摩尔定律](#chatgpt-之父-sam-altman-万物摩尔定律)
    - [GPT-4 ，人类迈向AGI的第一步](#gpt-4-人类迈向agi的第一步)
    - [OpenAI GPT4 技术报告](#openai-gpt4-技术报告)
    - [真·万字长文：可能是全网最晚的ChatGPT技术总结](#真万字长文可能是全网最晚的chatgpt技术总结)
    - [OpenAI: Our approach to AI safety](#openai-our-approach-to-ai-safety)
  - [致谢](#致谢)


## 什么是 ChatGPT ?

以下是 ChatGPT 做的自我介绍：

> 你好！我是ChatGPT，一个由OpenAI开发的大型语言模型，基于GPT-4架构。我的任务是通过自然语言处理技术，与用户进行交流并提供帮助。我可以回答问题、提供建议、进行简单对话等。我的知识截止于2021年9月，所以关于那之后的信息可能无法为您提供准确的答案。请随时向我提问，我会尽我所能帮助您。


## 使用途径
### 💻 [OpenAI 官网](https://openai.com)

(推荐) 注册后免费使用，无次数限制，官方出品，性能最强，技术最佳。缺点是国内注册困难：
* 需要科学上网，使用的代理 IP 质量不好的话无法成功
* 需要国外手机号验证，google voice 等虚拟号码无法通过验证，可使用淘宝解决 or [海外号码](https://sms-activate.org/)
* 国内注册教程及各种问题解决: https://nujuo8y1qx.feishu.cn/docx/AdqEdlT52oBiawx6Vv2cc89DnLb
* [Plus 开通教程](https://github.com/gclhaha/chatGPT-plus-guide) 技术路线是 RMB -> USDT —> Depay 虚拟卡 -> 充值，优点是匿名性好，缺点是操作复杂
* 开通 Plus 的另一条技术路线是: RMB -> nobepay 虚拟卡 -> 充值，优点是操作简单，缺点是需要绑定微信手机号等个人信息
  * [nobepay 虚拟卡开卡教程](https://zhuanlan.zhihu.com/p/619289623), [nobepay 官网](https://www.nobepay.com/)
  * [防止失效备份教程](imgs/nobepay_chatgpt.png)



### 💻 [Poe](https://poe.com/chatgpt)

注册后免费使用，可免费试用当前最先进的 GPT-4，提供多种模型选择。能科学上网即可注册，有 iPhone 客户端可以使用。

![poe](imgs/poe.jpg)

缺点是每天只有一次的 Chatgpt 4 提问机会。

### 💻 [微软必应](https://www.bing.com/)

申请Waitlist通过后免费使用，有次数限制(经常调整)，需要使用微软的 Edge 浏览器访问 www.bing.com, 国内会重定向到 cn.bing.com 导致无法使用。国内使用有两种方法：
* 科学上网访问 www.bing.com
* 重定向访问 www.bing.com
* [国内使用教程](https://juejin.cn/post/7199557716998078522)
* [如果不想使用 Edge 想使用 Chrome 教程](https://cloud.tencent.com/developer/article/2235566)
* [第三方开发者开发的 bing 客户端：BingGPT](https://github.com/dice2o/BingGPT)
  
![new_bing](imgs/new_bing.jpg)

### 国内可使用ChatGPT镜像站点
* [国内可使用ChatGPT镜像站点: carrot](https://github.com/xx025/carrot)
* [免费的 ChatGPT 镜像网站列表](https://github.com/LiLittleCat/awesome-free-chatgpt)
* [可以直接在国内访问的ChatGPT网站](examples/free_chatgpt_website.md)
* [集成了ChatGPT的浏览器预览页](https://www.wetab.link/zh)

### 💻 第三方开发者开发的 ChatGPT 客户端

第三方客户端很多，基本都是通过调用 OpenAI 的 API 实现，这些客户端往往需要你自备 OpenAI 的 Api Key 使用。

- [lencx/ChatGPT](https://github.com/lencx/ChatGPT): 使用 rust 编写的, 基于 tauri 的跨平台 ChatGPT 客户端. 支持: Windows, Linux, MacOS. 本质是应用内嵌入 ChatGPT 网页, 需要翻墙.
- [chatbox](https://github.com/Bin-Huang/chatbox) 开源的ChatGPT桌面应用，prompt 开发神器，全平台支持，下载安装包就能用
- [ChatGPT-Desktop](https://github.com/ChatGPT-Desktop/ChatGPT-Desktop) 基于 tauri + vue3 开发的跨平台桌面端应用，需要自行准备 API KEY 使用。
- [川虎 ChatGPT 🐯 Chuanhu ChatGPT](https://github.com/GaiZhenbiao/ChuanhuChatGPT) 为ChatGPT API提供了一个轻快好用的Web图形界面，支持直接在Hugging Face上部署，很方便。
- [token/ChatGpt.Desktop](https://github.com/239573049/ChatGpt.Desktop): 使用 C# 编写的, 基于 Blazor Web Assembly 的跨平台客户端. 支持: Windows, Linux, MacOS, Android, iOS, Web. 本质是程序内内嵌自建网页并调用 API, 所以你需要一个 OpenAI 账户, 需要翻墙.
- [SlimeNull/OpenGptChat](https://github.com/SlimeNull/OpenGptChat): 使用 C# 编写的, 基于 WPF 的原生 Windows 客户端. 支持: Windows. 本质是调用 OpenAI 的 API, 所以你需要一个 OpenAI 账户. 内置反向代理, 国内可用.
- [ChatGPT-Desktop](https://github.com/Synaptrix/ChatGPT-Desktop)

### 💻 国外竞品
<ul>
<li>
<details>
  <summary>  Bard </summary>

> https://bard.google.com/
谷歌出品，使用需申请，与 OpenAI ChatGPT 相比不支持代码功能，需翻墙注册使用

![Bard](imgs/bard.jpg)

</details>
</li>

<li>
<details>
  <summary> Claude </summary>

> https://www.anthropic.com/product

脱胎于 OpenAI 的初创公司 Anthropic 产品 Claude 模型，需申请使用

更新：Claude 模型现已经可以通过 slack 免费使用，地址: https://www.anthropic.com/claude-in-slack

![claude](imgs/claude.jpg)

</details>
</li>

<li>
<details>
  <summary> YouChat </summary>
  
> https://you.com/

注册登陆后即可免费使用，并且由于 you.com 本身是搜索引擎，侧边栏会出现实时搜索结果

![youchat](imgs/you_chat.jpg)

</details>
</li>

<li>
<details>
  <summary> Phind </summary>
  
> https://phind.com/

无需注册直接使用，并且由于 phind.com 本身是搜索引擎，侧边栏会出现实时搜索结果

![phind](imgs/phind.png)

</details>
</li>

<li>
<details>
  <summary> ChatSonic </summary>
  
> https://writesonic.com/chat

注册后提供一定免费额度，超出免费额度需付费

![chatSonic](imgs/writesonic.jpg)

</details>
</li>
</ul>

### 💻 国产 ChatGPT 类似产品
<ul>
<li>
<details>
  <summary> 文心一言</summary>

> https://yiyan.baidu.com/welcome

百度出品，目前未大规模开放，可申请使用

![wenxin](imgs/wenxin.jpg)

</details>
</li>

<li>
<details>
  <summary> 通义千问</summary>

阿里达摩院出品，目前未大规模开放，可申请使用

![tongyi](imgs/ali_llm.jpg)

</details>
</li>

<li>
<details>
  <summary>  ChatYuan: 元语功能型对话大模型</summary>
  
> https://huggingface.co/spaces/tianpanyu/ChatYuan-Demo

2023 年 2 月曾短暂发布，后因未知原因关闭，现在已经更新升级到 v2 版本，可使用抱抱脸体验 demo, 性能与 OpenAI 的 ChatGPT 有一定差距。代码和模型已开源 [[GitHub 代码](https://github.com/clue-ai/ChatYuan)].

![chatYuan](imgs/chatYuan.jpg)

</details>
</li>

<li>
<details>
  <summary> MOSS </summary>
  
> https://moss.fastnlp.top/

现已无法使用

![MOSS](imgs/MOSS.jpg)

</details>
</li>

</ul>

### 更多工具
[ChatGPT 用法和 APP](https://gpt3demo.com/)
![gpt3_demo](imgs/gpt3_demo.jpg)

## ChatGPT 工具

### [翻译: OpenAI Translator](https://chrome.google.com/webstore/detail/openai-translator/ogjibjphoadhljaoicdnjnmgokohngcc?hl=zh-CN)

基于 ChatGPT API 的划词翻译浏览器插件和跨平台桌面端应用。 

[Chrome 插件地址](https://chrome.google.com/webstore/detail/openai-translator/ogjibjphoadhljaoicdnjnmgokohngcc?hl=zh-CN), [GitHub 开源地址](https://github.com/yetone/openai-translator)

![translator](imgs/open_translator.jpg)

### [中科院科研工作专用ChatGPT](https://github.com/binary-husky/chatgpt_academic)

中科院科研工作专用ChatGPT，特别优化学术Paper润色体验，支持自定义快捷按钮，支持markdown表格显示，Tex公式双显示，代码显示功能完善，本地Python工程剖析功能/自我剖析

![chat_academic](imgs/chatgpt_academic.png) 

### [科研福音 ChatPDF: 像聊天一样阅读 PDF](https://www.chatpdf.com/)

上传科研论文 PDF ,可以让 chatPDF 帮助快速总结文章内容，创新点，贡献点，实验结果。以下是一个例子

![chatPDF_paper](imgs/chatPDF_paper.jpg) 

类似工具：
* [PandaGPT](https://www.pandagpt.io/)

### [科研助手：researchgpt](https://github.com/mukulpatnaik/researchgpt)

与上面的 chatPDF 功能比较类似。

[[GitHub 代码](https://github.com/mukulpatnaik/researchgpt)] [[网站](https://researchgpt.ue.r.appspot.com/)]

### [通过文字聊天实现 Excel 数据处理：酷表 ChatExcel](https://chatexcel.com/)

酷表ChatExcel是通过文字聊天实现Excel的交互控制的AI辅助工具，期望通过对表输入需求即可得到处理后的数据，减少额外的操作。

![chat_excel](imgs/chat_excel.jpg)


### [Doc 文件阅读助手: ChatDoc ](https://chatdoc.com/)

基于 ChatGPT 的文件阅读助手，支持中英文，可以快速从上传研究论文、书籍、手册等文件中提取、定位和汇总文件信息，并通过聊天的方式在几秒钟内给出问题的答案。

![chat_doc](imgs/chat_doc.png)


### [写作助手: rytr](https://rytr.me/)

邮件，博客等各类文档智能写作助手，支持中文

![rytr](imgs/rytr.jpg)


### [与文件对话：chatfiles](https://github.com/guangzhengli/ChatFiles/blob/main/README.zh.md)

上传文件然后与之对话

![chatfiles](imgs/chatfiles.png)

### [Multimedia GPT](https://github.com/fengyuli-dev/multimedia-gpt)

将OpenAI GPT与视觉和音频连接起来。您现在可以使用OpenAI API密钥发送图像、音频记录和pdf文档，并获得文本和图像格式的响应。目前正在增加对视频的支持。

![multimedia_gpt](imgs/multimedia_gpt.jpg)


### [与AI对话生成思维导图 ChatMind](https://www.chatmind.tech/)

![chatmind](imgs/chatmind.jpg)

## ChatGPT 插件功能

OpenAI 现已经支持插件功能
- [官方文档](https://platform.openai.com/docs/plugins/introduction)
- [ChatGPT plugins waitlist 申请地址](https://openai.com/waitlist/plugins)

### ChatGPT 浏览器插件和小程序
* [ChatGPT Sidebar](https://www.chatgpt-sidebar.com/)

Chat-GPT 超级挂件，以侧边窗口的形式提供服务，可以在阅读书籍时划选文本点击按钮给你解释，总结和提取；也可以在使用笔记软件时为笔记润色，翻译和补充.....

![sidebar](imgs/chatgpt_sidebar.png)

* [ChatGPT 接入谷歌: chatgpt-google-extension](https://chatgpt4google.com/)
* [使用 GPT-4 实现浏览器自动化: TaxyAI](https://github.com/TaxyAI/browser-extension)
* [ChatGPT 协助回答知乎问题: chat-gpt-zhihu-extension](https://chrome.google.com/webstore/detail/chatgpt-for-zhihu/dgoinfidjelfolhnkaableghhppplbak)
* [邮件助手：ChatGPT for Email - Remail](https://chrome.google.com/webstore/detail/chatgpt-for-email-remail/jjplpolfahlhoodebebfjdbpcbopcmlk)
* [分享你与 ChatGPT 的对话：ShareGPT](https://github.com/domeccleston/sharegpt)
* [与不同角色对话 & 多种实用技能：神奇海螺](https://github.com/yzfly/awesome-chatgpt-zh/issues/5)
* [让 ChatGPT 联网: WebChatGPT](https://github.com/qunash/chatgpt-advanced)
* [用日常语言提问，轻松搜索和查找个人或工作文件: ChatGPT Retrieval Plugin](https://github.com/openai/chatgpt-retrieval-plugin)

## 如何与 ChatGPT 高效对话？——好的提示语学习

### Prompt 框架

#### Elavis Saravia 总结的框架：

- Instruction（必须）： 指令，即你希望模型执行的具体任务。
- Context（选填）： 背景信息，或者说是上下文信息，这可以引导模型做出更好的反应。
- Input Data（选填）： 输入数据，告知模型需要处理的数据。
- Output Indicator（选填）： 输出指示器，告知模型我们要输出的类型或格式。
  
https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/guides/prompts-intro.md

#### Matt Nigh 总结的 CRISPE 框架：

更加复杂，但完备性会比较高，比较适合用于编写 prompt 模板。
CRISPE 分别代表以下含义：

- CR： Capacity and Role（能力与角色）。你希望 ChatGPT 扮演怎样的角色。
- I： Insight（洞察力），背景信息和上下文（坦率说来我觉得用 Context 更好）。
- S： Statement（指令），你希望 ChatGPT 做什么。
- P： Personality（个性），你希望 ChatGPT 以什么风格或方式回答你。
- E： Experiment（尝试），要求 ChatGPT 为你提供多个答案。
  
https://github.com/mattnigh/ChatGPT3-Free-Prompt-List

### [Prompt 编写模式：如何将思维框架赋予机器](https://github.com/prompt-engineering/prompt-patterns)

Prompt 编写模式是一份中文教程，介绍了系列 Prompt 编写模式，以实现更好地应用 Prompt 对 AI 进行编程。

项目逻辑清晰，示例丰富，作者对比了不同 Prompt 模式下 AI 输出内容的显著差异，撰写逻辑也是非常“中文”的。适合中文使用！

项目结构与速查表

![ChatGPT Prompt cheatsheet](imgs/prompt-simple-cheatsheet.jpg)

### [一个可以帮你自动生成优质Prompt的工具: AIPRM](https://chrome.google.com/webstore/detail/aiprm-for-chatgpt/ojnbohmppadfgpejeebfnmnknjdlckgj)

### 💡 [让生产力加倍的 ChatGPT 快捷指令](https://newzone.top/chatgpt/)

如何让 ChatGPT 的回答更准确，更符合我们的要求，网站提供了许多例子供参考。

![chatgpt_sc](imgs/chatGPT_shortcut.jpg)


### 💡 [学习如何提示：Learn Prompting](https://learnprompting.org/zh-Hans/)

学习如何使用 prompt，支持中文

![learnPrompt](imgs/learning_prompting.jpg)

### 💡 [提示语自动生成](https://huggingface.co/spaces/merve/ChatGPT-prompt-generator)  

如果感觉自己写的 prompt 不够好， 可以让模型帮你写，然后再输入 ChatGPT .

![prompt-gen](imgs/chatGPT_promote_gen.jpg)

### [创建，使用，分享 ChatGPT prompts: OpenPrompt](https://openprompt.co/) 

### [生成AI绘图灵感](https://www.aigenprompt.com/zh-CN)

输入简单的词，这个工具会帮你优化成适合生成带有艺术感画面的一连串prompt，可以在大部分绘画工具使用。

![aigenprompt](imgs/aigenprompt.jpg)

### 码农专区

#### [OpenAI 官方使用指南：openai-cookbook](https://github.com/openai/openai-cookbook)

#### [OpenAI python 接口](https://github.com/openai/openai-python)

#### [OpenGPT](https://open-gpt.app/)

#### [亚马逊的免费 AI 代码助手：CodeWhisperer](https://aws.amazon.com/codewhisperer/)

免费，支持中文的 AI 代码助手，注册教程如下：

官方地址：https://aws.amazon.com/codewhisperer/

知乎保姆级教程：https://zhuanlan.zhihu.com/p/621800084


#### [AI代码助手: codeium](https://codeium.com/)
个人使用免费，有 vscode 插件，github copilot 平替

![codeium](imgs/codeium.jpg)

#### [Github Copilot 开源平替，可本地部署: Tabby ](https://github.com/TabbyML/tabby)

#### [将 OpenAI ChatGPT 集成到 VSCode: vscode-chatgpt](https://github.com/gencay/vscode-chatgpt)

#### [GPT 驱动的代码编辑器: Cursor](https://www.cursor.so/)

GPT-4 驱动的一款强大代码编辑器，可以辅助程序员进行日常的编码，目前免费。

![cursor](imgs/cursor.jpg)

#### [帮你生成完整 Github README](https://readme.rustc.cloud/zh)
简单描述项目简介即可快速生成 GitHub README 内容

![github_readme](imgs/gpt_readme.jpg)

#### [shell 中使用 ChatGPT](https://github.com/TheR1D/shell_gpt)

![shellGPT](imgs/shell_gpt.gif)


#### [自动生成任何编程语言的文档: AutoDoc-ChatGPT](https://github.com/awekrx/AutoDoc-ChatGPT)

#### [使用ChatGPT搭建微信聊天机器人](https://github.com/zhayujie/chatgpt-on-wechat)

#### [开源 ChatGPT 替代品列表](https://github.com/nichtdax/awesome-totally-open-chatgpt)

#### [在任意软件上操作ChatGPT: Portal](https://github.com/lxfater/Portal) 

Portal是一款传输工具，旨在将ChatGPT的能力整合到用户的工作流程中。它把整个操作系统当成自己的舞台，可以在任意软件上操作ChatGPT。

#### [一键免费部署你的私人 ChatGPT 网页应用: ChatGPT-Next-Web](https://github.com/Yidadaa/ChatGPT-Next-Web)

![Chatgpt_next_web](imgs/chatgpt_next_web.png)

#### [电报 ChatGPT 机器人：Chatgpt-Telegram-bot](https://github.com/n3d1117/chatgpt-telegram-bot)

#### [将代码从一个语言翻译为另一个语言：ai-code-translator](https://github.com/mckaywrigley/ai-code-translator)

![code_translator](imgs/ai_code_translator.png)


## 相关资料
* [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts)
* [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)
* [awesome-ChatGPT-resource-zh](https://github.com/DeepTecher/awesome-ChatGPT-resource-zh)
* [ChatGPT 中文调教指南](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)
* [ChatGPT调教指南-咒语指南-聊天提示词指南](https://github.com/wikieden/Awesome-ChatGPT-Prompts-CN)
* [ChatGPT-Awesomes-Collection](https://github.com/yzfly/chatgpt-awesomes-collection)

## 更多 AI 工具

### AI 绘画

- [Midjourney](https://www.midjourney.com/home/)  
- [MidJourney提示词工具](https://aijiaolian.chat/midjourney)
- [Stable Diffusion](https://stablediffusionweb.com/)  
- [DALL·E 2](https://labs.openai.com/)

### 代码生成

- [Copilot](https://github.com/features/copilot)  
- [Codeium](https://codeium.com/)  
- [Replit](https://replit.com/)

### AI辅助写作

- [ChatGPT](https://chat.openai.com/)  
- [Craft](https://www.craft.do/)  
- [Notion](https://notion.so/)  
- [Compose AI](https://www.compose.ai/)  
- [copy.ai](http://copy.ai/)  
- [Jasper](https://www.jasper.ai/)  
- [copysmith](https://copysmith.ai/)

### PPT生成

- [Tome](https://beta.tome.app/)
- [beautiful.ai](https://www.beautiful.ai/)
- [gamma](https://gamma.app/)

### 语音/视频合成

- [Murf AI](https://murf.ai/)  
- [Resemble AI](https://www.resemble.ai/)  
- [Synthesia](https://www.synthesia.io/)  
- [Adobe Podcast](https://podcast.adobe.com/)

### [AI 研究所](https://www.aiyjs.com/)

AI研究所：一个收录 AI 相关工具和AI资讯的中文网站

![ai_yjs](imgs/ai_yjs.jpg)


## 思考
### ChatGPT 之父 Sam Altman: 万物摩尔定律

[英文原文](https://moores.samaltman.com/) [中文翻译](https://zhuanlan.zhihu.com/p/577620007)

本文来自2021年Sam Altman的博客，他在文章中写了对人工智能革命的思考。我认为他自己总结的很好，下面是观点摘要：

  我在OpenAI的工作每天都在提醒我，社会经济的重大变革将会比绝大多数人认为的更快到来。越来越多人类的工作将被能够思考和学习的软件取代，更多的权力将从劳动力转移到资本上。如果我们的公共政策不做出相应的调整，最终，大多数人会比现在过得还要糟糕。

  我们需要设计一种制度拥抱这种技术化的未来，然后对构成未来世界大部分价值的资产（公司和土地）征税，以便公平地分配由此产生的财富。这样做可以使未来社会的分裂性大大降低，并使每个人都能参与收益分配。

  未来五年，会思考的计算机程序将可以阅读法律文件，并提供医疗建议；在接下来的十年里，它们将可以从事流水线工作，甚至可能成为人类的同伴；而在之后的几十年里，它们几乎可以做所有的事情，包括探索新的科学发现，扩大我们对”一切”的概念。

  这场技术革命势不可挡。当这些智能机器又可以帮助我们制造更智能的机器时，创新的循环往复将加快这场革命的步伐。随之而来的是三个至关重要的后果：

  1. 这场革命将创造惊人的财富。一旦有足够强大的人工智能「加入劳动大军」，很多种劳动力的价格（驱动商品和服务的成本）将逐渐归零。

  2. 世界将发生翻天覆地的变化，因此我们需要同样颠覆性的政策变化来分配财富，从而使更多的人可以追求自己想要的生活。

  3. 如果我们把这两方面的工作做好了，就能将人类的生活水平提高到前所未有的状态。

  由于我们正处于巨变的开端，因此人类有一个难能可贵的机会去打造未来。这种设计不会简单地解决当前人类面临的社会和政治问题，人类需要着眼于不久的将来，设计一套截然不同的政策体系。

  如果我们在制定政策时不着眼于未来，那人类即将面临重大的考验，就像我们把前农耕社会或封建社会的组织原则应用到当今社会，必然会导致失败一样。 

### [GPT-4 ，人类迈向AGI的第一步](https://orangeblog.notion.site/GPT-4-AGI-8fc50010291d47efb92cbbd668c8c893)

文章节选+翻译了本月最重要的一篇论文的内容，《通用人工智能的火花：GPT-4早期实验》

该论文是一篇长达154页的对 GPT-4 的测试。微软的研究院在很早期就接触到了 GPT-4 的非多模态版本，并进行了详尽的测试。

这篇论文不管是测试方法还是测试结论都非常精彩，强烈推荐看一遍，传送门在此 。[https://arxiv.org/pdf/2303.12712v1.pdf](https://arxiv.org/pdf/2303.12712v1.pdf)

[《GPT-4 ，通⽤⼈⼯智能的⽕花》论⽂内容精选与翻译](files/《GPT_4，通用人工智能的火花》论文内容精选与翻译_.pdf)

中文翻译全文在此：
[《GPT-4 ，通⽤⼈⼯智能的⽕花》](files/%E3%80%8AGPT_4%EF%BC%8C%E9%80%9A%E7%94%A8%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E7%9A%84%E7%81%AB%E8%8A%B1%E3%80%8B154%E9%A1%B5%E5%BE%AE%E8%BD%AFGPT%E7%A0%94%E7%A9%B6%E6%8A%A5%E5%91%8A%EF%BC%88%E5%85%A8%E4%B8%AD%E6%96%87%E7%89%88%EF%BC%89.pdf)

### OpenAI GPT4 技术报告

报告链接：
https://arxiv.org/abs/2303.08774

GPT-4的发布直接填补了之前GPT系列的跨模态信息生成能力的空缺，GPT-4目前已经可以同时接受图像和文本输入，来生成用户需要的文本。并且OpenAI团队在多个测试基准上对其进行了评估，GPT-4在大部分测试上已经与人类水平相当了。有很多学者分析，GPT-4相比前代的GPT-3.5以及ChatGPT”涌现“出了更加成熟的智能，其内部原因可能是投入了更大的训练数据库和训练算力，真有一些力大砖飞的感觉。但是不可否认的是，GPT-4仍然面临着生成”幻觉“ (Hallucination)的问题，即仍有可能产生事实性错误的生成文本。此外，GPT-4主打的多模态生成模式是否也会进一步带来生成具有政治导向、错误价值观、暴力倾向等内容的风险呢，那么如何灵活的应对这些局限性和风险性，对GPT-4的健康落地也具有非常重要的意义。

### [真·万字长文：可能是全网最晚的ChatGPT技术总结](https://www.techbeat.net/article-info?id=4766)

[原文链接](https://www.techbeat.net/article-info?id=4766)  [备份](files/simpread-真%20·%20万字长文：可能是全网最晚的%20ChatGPT%20技术总结%20-%20TechBeattech.md)

ChatGPT的强大能力是显而易见的，但对于人工智能领域不太熟悉的人，对这种黑盒的技术仍然会担忧或者不信任。恐惧通常来自于不了解，因此本文将为大家全面剖析ChatGPT的技术原理，尽量以简单通俗的文字为大家解惑。

### [OpenAI: Our approach to AI safety](https://openai.com/blog/our-approach-to-ai-safety)

* 英文原文: [《Our approach to AI safety》](https://openai.com/blog/our-approach-to-ai-safety)
* 中文报道：[界面新闻：OpenAI回应安全性质疑，公布保障AI模型安全方法](https://www.jiemian.com/article/9194641.html)

文章介绍了ChatGPT六个方面的安全部署，包括构建日益安全的AI系统、在实际使用中学习改进安全措施、保护儿童、尊重隐私、提高事实准确性，以及持续研究和参与。


## 致谢


- [OpenAI](https://www.openai.com/)，因为开发了 GPT 系列语言模型。
- [GPT-4](https://github.com/openai/gpt-4)，因为提供了底层语言模型。
- [Hugging Face](https://huggingface.co/)，因为他们在 NLP 和开源工具上的广泛工作。
- [awesome-chatgpt](https://github.com/OpenMindClub/awesome-chatgpt)，因为他们在 ChatGPT 方面的出色工作。
- [awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompt)，因为他们提供了一系列有趣的 ChatGPT 提示。




<a id="jump_1"></a>
![IMG_3150(20230505-145951)](https://user-images.githubusercontent.com/108912608/236395159-3a6fb485-2970-4e1e-a806-d3fb592564e3.JPG)
