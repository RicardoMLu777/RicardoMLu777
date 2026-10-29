# Hi, I'm Ricardo

网络空间安全本科在读（2027 届）。方向在 **AI Agent × 安全工程** 的交叉点上：让 LLM 安全地驱动真实的攻击面工具，同时给这种自主性设计足够硬的约束边界。

Undergraduate in cyber security, building security tooling around LLM agents — and spending most of my time on the part that keeps them from doing something stupid.

---

## 现在在做什么

**[SecAgent](https://github.com/RicardoMLu777/secagent)** — 基于 MCP 的自主安全评估 Agent。Plan-and-Execute 规划 + 并行工具调用 + 分层记忆 + MITRE ATT&CK 映射，把 nmap / httpx / sqlmap / ffuf 封装成 MCP Server 交给模型调度。

重点不在「让模型会用工具」，而在于**怎么让它在不该动手的时候停下来**：工具分级、目标白名单、fail-closed 审批、全链路审计。项目里的 `policy.py` 比我写的任何扫描逻辑都长，这是刻意的。

**毕业设计** — 医疗编码（ICD-10 / DRG 3.0）映射系统的设计与实现，涉及数据分级、字段脱敏与操作审计。答辩后开源。

## 关注的方向

```
AI Agent 安全     自主系统的权限边界、工具调用策略门控、prompt injection 防御
应用安全          认证授权、输入校验、数据脱敏、审计可追溯
威胁建模          真实攻击路径 → MITRE ATT&CK → 倒推防御缺口
```

## 技术栈

**语言** Python · Java · SQL · JavaScript
**安全** nmap · sqlmap · ffuf · httpx · Burp Suite · Wireshark
**后端** Spring Boot · MyBatis-Plus · MySQL · Redis · MCP · OpenAI API
**前端** Vue 3 · Element Plus · ECharts
**工程** Git · GitHub Actions · pytest · Docker · Linux

## 项目

| 项目 | 说明 |
|---|---|
| [**secagent**](https://github.com/RicardoMLu777/secagent) | MCP-based autonomous security assessment agent. Explicit planning, parallel tool calls, tiered memory, MITRE ATT&CK mapping, policy-gated execution. |
| *毕业设计* | ICD-10 / DRG 3.0 编码映射原型系统（2027 公开） |

## 联系

- Email：`822210782@qq.com`
- 寻找 **2027 届安全岗实习 / 校招** 机会 —— 应用安全、安全研发、AI 安全方向

---

<sub>我的项目只用于获得明确授权的目标。漏洞验证一律在本地靶场完成。</sub>
