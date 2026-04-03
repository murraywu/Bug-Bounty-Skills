# 🐛 OpenClaw Security Skills

**Bug Bounty & Web Security Skill Pack for OpenClaw**

---

## 📦 技能包清单

本仓库包含 10 个完整的 OpenClaw 安全技能包：

| # | 技能 | 功能 | 状态 |
|---|------|------|------|
| 1 | [Bug-Bounty-Vulnerability-DB](./Bug-Bounty-Vulnerability-DB/) | 15+ 漏洞类型知识库 | ✅ Ready |
| 2 | [Bug-Bounty-Report-Generator](./Bug-Bounty-Report-Generator/) | 漏洞报告生成 | ✅ Ready |
| 3 | [Bug-Bounty-Learning-Guide](./Bug-Bounty-Learning-Guide/) | 个性化学习路径 | ✅ Ready |
| 4 | [Bug-Bounty-Code-Review](./Bug-Bounty-Code-Review/) | 代码安全审查 | ✅ Ready |
| 5 | [Bug-Bounty-Security-Checklist](./Bug-Bounty-Security-Checklist/) | 安全检查清单 | ✅ Ready |
| 6 | [Bug-Bounty-XSS-Helper](./Bug-Bounty-XSS-Helper/) | XSS Payload 生成 | ✅ Ready |
| 7 | [Bug-Bounty-SQLi-Helper](./Bug-Bounty-SQLi-Helper/) | SQL 注入助手 | ✅ Ready |
| 8 | [Bug-Bounty-Burp-Guide](./Bug-Bounty-Burp-Guide/) | Burp Suite 指南 | ✅ Ready |
| 9 | [Bug-Bounty-Recon](./Bug-Bounty-Recon/) | 信息收集指南 | ✅ Ready |
| 10 | [Bug-Bounty-Writeup-Helper](./Bug-Bounty-Writeup-Helper/) | CTF Writeup 助手 | ✅ Ready |

---

## 🚀 快速开始

### 安装方法

将技能包复制到 OpenClaw 的 skills 目录：

```bash
# Windows PowerShell
Copy-Item -Path ".\Bug-Bounty-*" -Destination "$env:USERPROFILE\.openclaw\workspace\skills\" -Recurse

# 或使用 git clone
git clone https://github.com/murraywu/openclaw-security-skills.git
Copy-Item -Path ".\openclaw-security-skills\Bug-Bounty-*" -Destination "$env:USERPROFILE\.openclaw\workspace\skills\" -Recurse
```

### 使用示例

**查询漏洞知识**:
```
用户：解释一下 SSRF 漏洞

助手：# SSRF (服务器端请求伪造)
**风险等级**: 高/严重
**原理**: 攻击者诱导服务器发起 HTTP 请求...
```

**代码安全审查**:
```
用户：帮我检查这段代码有没有安全问题
[粘贴代码]

助手：🔍 代码安全审查结果
⚠️ 发现 2 个潜在安全问题...
```

**生成漏洞报告**:
```
用户：帮我写一个 XSS 漏洞报告

助手：# Stored XSS in Comment Section
## 概要
Comment submission feature contains stored XSS...
```

---

## 📊 技能包统计

| 指标 | 数值 |
|------|------|
| 技能包数量 | 10 个 |
| 文档总量 | ~50KB |
| 覆盖漏洞 | 15+ 种 |
| 工具学习 | 50+ 个 |
| 推荐资源 | 100+ 个 |
| 检查清单 | 6 份 |

---

## 🎯 适用人群

- **Bug Bounty 新手** - 系统学习漏洞知识
- **安全学习者** - 获取学习路径和资源
- **开发人员** - 学习安全编码实践
- **安全工程师** - 快速查询和报告生成

---

## 📚 技能包详情

### 1. Bug-Bounty-Vulnerability-DB

15+ 常见 Web 漏洞类型详解，包含：
- XSS / SQL Injection / CSRF / IDOR
- SSRF / XXE / RCE / SSTI
- 文件上传 / 目录遍历 / HTTP 走私
- 子域名接管 / CORS 错误 / 命令注入 / 反序列化

每个漏洞包含：原理、攻击流程、Payload、检测方法、防御方案、真实案例。

### 2. Bug-Bounty-Report-Generator

一键生成规范的漏洞报告，适用于：
- HackerOne / Bugcrowd / Intigriti
- 内部安全报告
- 渗透测试报告

包含完整报告结构、示例和最佳实践。

### 3. Bug-Bounty-Learning-Guide

根据用户背景提供个性化学习路径：
- 零基础入门 (16 周)
- 程序员转安全 (8 周)
- 快速入门 (4 周)

包含资源推荐、时间规划、常见问题解答。

---

## 🛡️ 安全声明

⚠️ **本技能包仅用于**:
- 授权的安全测试
- 合法的安全学习
- 代码审查和修复

❌ **禁止用于**:
- 未经授权的攻击
- 恶意目的
- 侵犯他人系统

请遵守当地法律法规，仅在授权范围内使用。

---

## 📈 路线图

### Phase 1 (已完成)
- [x] 10 个核心技能包开发
- [x] 文档完善
- [x] GitHub 仓库创建

### Phase 2 (进行中)
- [ ] SkillHub 发布
- [ ] GitHub Pages 文档站
- [ ] 视频教程制作

### Phase 3 (计划中)
- [ ] 新增技能包 (移动安全/API 安全)
- [ ] 付费高级版
- [ ] 企业培训服务

---

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License

## 👤 作者

**murraywu**

GitHub: [@murraywu](https://github.com/murraywu)

---

*最后更新：2026-04-03*
