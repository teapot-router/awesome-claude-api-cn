# Compare evidence, not just headline discounts

[Machine-readable directory](../data/services.json) · [Contribution template](../templates/service-evidence.md)

This repository is maintained by people affiliated with Crazyrouter. It is not an independent ranking. Third-party entries currently have link-only evidence: null fields mean **not checked**, not unsupported. Entry review date refers to the directory record, not a certification of current service quality.

## Three evidence levels

1. **Provider claim:** quote a specific public document and its retrieval date. Do not relabel a sales statement as a test result.
2. **Document checked:** confirm the exact model, endpoint, billing unit, context/cache conditions and dated source.
3. **Request tested:** disclose protocol, client version, exact model ID, date, region, input fixture, test dimensions and redacted output. A single 200 does not establish uptime, model identity or tool compatibility.

## Questions worth asking before paying

| Decision | Evidence needed | Common trap |
|---|---|---|
| Can I use Codex? | Responses request and full client task | Treating Chat Completions support as sufficient |
| Is caching cheaper? | Read/write rates, TTL, actual cache usage | Comparing only uncached input prices |
| Will my job survive failures? | Retry, timeout, task polling and duplicate billing semantics | Treating every timeout as safe to resubmit |
| Is this service suitable for my region/data? | Current access and data processing terms | Inferring inference availability from the homepage |
| What will I really spend? | Same workload, all attempts, normalized ledger | Comparing incompatible units or account groups |

## Contributing

Use the template for one factual claim at a time. Provide a public source and date; mark not tested where appropriate. Do not include API keys, private prompts, signed URLs or customer identifiers. Disclose affiliation. A negative result needs the same reproduction detail as a positive result. Conflicting results are retained with conditions rather than resolved by an unsupported ranking.

中文：每个结论分清“服务商自述、文档核对、实际请求验证”。第三方字段未核对时留空，不能写成不支持。把缓存、协议、计费单位、账户组与失败重试一起比较，避免仅看一个折扣数字。
