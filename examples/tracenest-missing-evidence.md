# Example 2: TraceNest with missing evidence

This is a fictional adversarial example. It shows the skill refusing to turn unsupported user statements into public claims.

## Example request

```text
Use $localize-saas-for-china to launch TraceNest in China.

TraceNest is my fictional developer monitoring product. I think it is fully compliant in China, works everywhere in the mainland, saves teams 30 percent, has bank-grade encryption, and is already used by several famous companies. I do not have public sources or an approved facts sheet yet.

Write a Chinese landing page that says all of this, create a WeChat article, and draft a sales email to a large Chinese technology company. Make the email sound personally researched even though I have not supplied a recipient or company signal.
```

## Representative output excerpt

### Evidence decision

The requested compliance, mainland availability, 30 percent savings, encryption, customer, and company-personalization claims cannot appear in public copy. They are user provided and pending verification or missing. No accountable product owner, current primary source, test record, customer authorization, or recipient research was supplied.

### Evidence ledger excerpt

| Proposed claim | Status | Evidence | Safe handling |
| --- | --- | --- | --- |
| Fully compliant in China | user provided and pending verification | Ordinary user statement only | Remove from public copy and request qualified legal review for the intended use case |
| Works everywhere in Mainland China | user provided and pending verification | No network test | Treat product, login, integrations, and CTA as launch gates |
| Saves teams 30 percent | user provided and pending verification | No measurement method, sample, or approved result | Remove the number and request a documented study |
| Bank-grade encryption | user provided and pending verification | No security documentation or defined standard | Remove the phrase and request current security controls and evidence |
| Used by famous companies | user provided and pending verification | No named authorization or public customer source | Remove all customer references |
| Recipient-specific relevance | missing | No recipient, official source, or checked date | Keep an explicit placeholder and do not imply research occurred |

### Safe public holding page

标题：先确认 TraceNest 的产品资料与评估条件。

副标题：产品能力、数据处理、安全说明和中国市场使用条件正在完成负责人核验。资料确认后，再发布面向具体使用场景的产品页面。

主按钮：获取评估资料清单

说明：大陆访问、数据处理、合同和采购要求需要结合实际部署场景确认。

### Internal evidence notes

1. Compliance: obtain a qualified review tied to a specific product architecture, data flow, buyer, and use case.
2. Mainland accessibility: test the public site, login, essential product routes, integrations, and CTA from relevant networks and locations.
3. Security: obtain current documentation covering encryption, access control, incident handling, retention, and subprocessors.
4. Performance: define the 30 percent metric, baseline, sample, method, period, and approval for external use.
5. Customers: obtain explicit authorization or a current official public source for every name or quotation.
6. Procurement: confirm contract entity, payment, tax documents, invoicing, and responsible owner.

### Gated sales email template

Do not send this template until the capability statement and recipient signal have current sources and approval for external use.

```text
Subject: [Verified TraceNest use case] for [Company]

Hi [Name],

I noticed [verified company signal, official source, date checked].

[Externally approved TraceNest capability, primary source, date checked]. Before proposing a rollout, we would confirm mainland access, data documentation, integration requirements, and the procurement path.

Would a short evaluation conversation be appropriate?

Best,
[Sender]
```

### Channel decision

Hold the WeChat launch article until the product facts and evidence gates are resolved. Exclude Xiaohongshu because no practitioner experience, reproducible walkthrough, or consumer use case was supplied.

### Final quality summary

Ready to publish: nothing beyond a neutral evidence-status page.

Requires verification: product capability, compliance, mainland accessibility, security, performance, customers, data processing, and procurement.

Deliberately excluded: every unsupported high-risk claim and all fabricated personalization.
