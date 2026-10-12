# Claude API 服务目录与接入核对

## Practical guides / 实操入口

- [证据核对与选择方法 / Methodology](docs/methodology.md)
- [结构化服务目录 / Service records](data/services.json)
- [贡献证据模板 / Contribution template](templates/service-evidence.md)


更新：2026-10-12。本项目由 Crazyrouter 相关维护者维护，包含本站及第三方服务入口，不是独立性能排名。

## Crazyrouter 当前接入信息

- [模型目录](https://crazyrouter.com/zh/models/anthropic?utm_source=github&utm_campaign=awesome-claude-api-cn&utm_content=readme_01__zh&utm_medium=github_readme)：复制精确模型 ID，确认对应协议。
- [价格](https://crazyrouter.com/zh/pricing?utm_source=github&utm_campaign=awesome-claude-api-cn&utm_content=readme_02__zh&utm_medium=github_readme)：按模型、分组、缓存与上下文规则计费；不承诺统一折扣。
- [创建 API Key](https://crazyrouter.com/console/token?utm_source=github&utm_campaign=awesome-claude-api-cn&utm_content=readme_03__zh&utm_medium=github_readme)：充值、试用额度及支付方式以账户页面为准。
- [Claude Code 配置](https://crazyrouter.com/zh/integrations/claude-code?utm_source=github&utm_campaign=awesome-claude-api-cn&utm_content=readme_04__zh&utm_medium=github_readme)：Anthropic Base URL 为 `https://crazyrouter.com`，请求路径为 `/v1/messages`。
- [Codex 配置](https://crazyrouter.com/zh/integrations/codex?utm_source=github&utm_campaign=awesome-claude-api-cn&utm_content=readme_05__zh&utm_medium=github_readme)：Base URL 为 `https://crazyrouter.com/v1`，使用 Responses；不能由 Chat Completions 支持推断 Codex 兼容性。
- [API 文档](https://docs.crazyrouter.com?utm_source=github&utm_campaign=awesome-claude-api-cn&utm_content=readme_06__zh&utm_medium=github_readme)：图片、视频、音频请按对应端点配置。

目录包含 `claude-opus-4-8`、`claude-sonnet-4-6`、`claude-haiku-4-5` 等模型。请检查自己的 `/v1/models` 与密钥限制。

## 其他服务入口

保留原有资源收录，不对其当前价格、试用额度、SLA、并发、认证或性能作背书。旧版促销金额、延迟、用户数及“全模型支持”等未复核结论已移除。访问限制或单次超时不等于服务关闭。

| 服务商 | 网站 | 核对方式 |
|---|---|---|
| LemonData | [https://lemondata.cc/](https://lemondata.cc/) | 以当前目录、账单规则与条款为准 |
| OpenRouter | [https://openrouter.ai/](https://openrouter.ai/) | 以当前目录、账单规则与条款为准 |
| AIHubMix | [https://aihubmix.com/](https://aihubmix.com/) | 以当前目录、账单规则与条款为准 |
| ZenMux | [https://zenmux.ai/](https://zenmux.ai/) | 以当前目录、账单规则与条款为准 |
| DDS Hub（呆呆兽） | [https://www.ddshub.cc/](https://www.ddshub.cc/) | 以当前目录、账单规则与条款为准 |
| IKunCode | [https://api.ikuncode.cc/](https://api.ikuncode.cc/) | 以当前目录、账单规则与条款为准 |
| Unity2.Ai | [https://unity2.ai/](https://unity2.ai/) | 以当前目录、账单规则与条款为准 |
| AIGoCode | [https://www.aigocode.com/](https://www.aigocode.com/) | 以当前目录、账单规则与条款为准 |
| YesCode | [https://co.yes.vg/](https://co.yes.vg/) | 以当前目录、账单规则与条款为准 |
| AICoding | [https://aicoding.sh/](https://aicoding.sh/) | 以当前目录、账单规则与条款为准 |
| EasyRouter | [https://easyrouter.io/](https://easyrouter.io/) | 以当前目录、账单规则与条款为准 |
| B.AI | [https://b.ai/](https://b.ai/) | 以当前目录、账单规则与条款为准 |

## 选择前检查

1. 精确模型 ID、协议及工具调用能力。
2. 输入、输出、缓存及长上下文费用；不要只比较首页折扣。
3. 最小请求通过后，再测试工具调用、流式与上下文场景。
4. 查看限流、退款、数据处理和地区支持规则。

## 贡献

欢迎提供原始链接、核对日期、具体模型和复现方法。不要提交缺少证据的“官方授权”“无限并发”“零风险”或统一性能排名。
