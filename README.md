# AI Meeting Minutes & Action Items｜ai-meeting-action-minutes

> 把会议记录转成决策、风险、责任人、截止时间和可跟踪行动项。

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![AI Agent Skill](https://img.shields.io/badge/AI-Agent%20Skill-blue)
![Language](https://img.shields.io/badge/language-中文-orange)

这是一个面向真实业务工作的开源 AI Agent Skill。它不是一组零散 Prompt，而是一套包含任务边界、执行流程、质量检查和交付模板的可复用方法，让支持 Markdown 指令的 AI 助手能够更稳定地完成 **AI Meeting Minutes & Action Items** 相关任务。

**English:** An open-source AI agent skill for ai meeting minutes & action items, built around practical workflows, reusable deliverables, quality checks, and human-review boundaries.

## 为什么这个技能有用

把会议记录转成决策、风险、责任人、截止时间和可跟踪行动项。技能强调可执行结果、明确假设和人工复核点，适合从一次性对话升级为可复用的团队工作流。

### 核心能力

- 会议事实与议题结构化
- 决策、分歧和未决事项提取
- 行动项、责任人和截止时间识别
- 风险跟踪与会后沟通

### 你可以获得

- 结构化会议纪要
- 决策与风险清单
- 行动项跟踪表
- 会后同步摘要

## 适合谁

- 项目经理和团队负责人
- 销售与客户成功团队
- 需要高质量会议纪要的组织

## 直接这样使用

将下面任一请求交给支持读取本地文件的 AI Agent：

> 把这段会议转录整理成决策、行动项和风险清单
>
> 生成一份适合发给客户的会后纪要与下一步安排

Agent 应先读取 [SKILL.md](SKILL.md)，再按其中的流程和质量要求执行任务。

## 快速开始

~~~bash
git clone https://github.com/zchstime/ai-meeting-action-minutes.git
cd ai-meeting-action-minutes
~~~

然后对你的 AI 助手说：

~~~text
请读取 SKILL.md，并使用这个技能处理我的任务。开始前先确认目标、输入、限制和期望交付物。
~~~

不同 AI Agent 客户端的技能安装目录和触发机制可能不同；只要客户端能够读取 Markdown 文件，就可以直接引用本仓库中的 **SKILL.md**。

## 技能包内容

- [SKILL.md](SKILL.md)：技能定义、执行步骤与质量边界
- [output-template.md](references/output-template.md)
- [LICENSE](LICENSE)：MIT 开源许可证

## 设计原则

- **结果导向**：输出方案、模板、清单、指标或可执行下一步，而不止是泛泛建议。
- **证据与假设分离**：明确哪些是事实、推断和待验证信息。
- **人机协作**：对高风险判断保留人工复核、权限控制和撤销路径。
- **可复用与可验收**：让同类任务能够重复执行，并通过明确标准检查质量。

## 搜索关键词

<code>ai</code> · <code>ai-agent</code> · <code>agent-skills</code> · <code>prompt-engineering</code> · <code>open-source</code> · <code>meeting-minutes</code> · <code>action-items</code> · <code>meeting-notes</code> · <code>productivity</code> · <code>project-management</code>

## 为什么值得 Star

如果你正在建设 AI Meeting Minutes & Action Items 相关的 AI 工作流，这个仓库可以作为可直接复用的起点，也适合作为团队内部 Prompt、SOP 和验收规范的共同底稿。**Star ⭐ 这个仓库，方便以后快速找到；也欢迎通过 Issue 或 Pull Request 分享真实案例和改进建议。**

## License

[MIT License](LICENSE) © 2026 珠海横琴来一桔文化科技有限公司
