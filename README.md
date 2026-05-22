# Cert Guides by Vrishabh Bhavsar

> **Free, open-source certification study guides — built while passing each exam.**
> No login. No paywall. No ads. Ever.

[![Live Site](https://img.shields.io/badge/Live-GitHub%20Pages-brightgreen)](https://vb-1405.github.io/aws-ccp-guide/)
[![AWS CCP](https://img.shields.io/badge/AWS-Cloud%20Practitioner%20✓-FF9900?style=flat&logo=amazon-aws&logoColor=white)](https://www.credly.com/badges/144c27ac-3106-4c8d-a9da-8aa5f3d3064a)
[![CCNA](https://img.shields.io/badge/Cisco-CCNA%20In%20Progress-1BA0D7?style=flat&logo=cisco&logoColor=white)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 🌐 Live Site

**[vb-1405.github.io/aws-ccp-guide](https://vb-1405.github.io/aws-ccp-guide/)**

Single HTML file — works in any browser, no internet required after loading, no build step.

---

## What's Inside

This is a growing collection of certification study guides. Each guide is built from scratch while actively preparing for and passing the real exam — so the content reflects what actually matters, not just what's in the textbook.

### ✅ AWS Certified Cloud Practitioner (CLF-C02) — Live

| Feature | Details |
|---------|---------|
| 📖 Study Notes | All 4 exam domains · 18 subtopics |
| ⚠️ Exam Traps | Callouts for every concept that trips people up |
| 🔗 Official Links | AWS documentation linked throughout |
| 📝 Practice Exams | 3 full-length exams · 182 questions |
| ⏱️ Timer | 90-minute countdown per exam |
| 📊 Results | Domain breakdown + full question review |
| ➡️ Next Buttons | Linear flow through all sections |

**Domains covered:**
- Cloud Concepts (24%) — NIST characteristics, deployment models, Well-Architected Framework, CAF
- Security & Compliance (30%) — Shared Responsibility, IAM, Shield, WAF, GuardDuty, Macie, compliance
- Technology & Services (34%) — EC2, Lambda, S3, RDS, DynamoDB, VPC, CloudFront, AI/ML
- Billing & Pricing (12%) — Pricing models, support plans, Organizations, Consolidated Billing

### 🔜 Cisco CCNA (200-301) — In Progress

Full study guide drops alongside the cert. Follow on [LinkedIn](https://www.linkedin.com/in/cyberrookie/) for updates.

### 📅 AWS Solutions Architect Associate (SAA-C03) — Planned

Deep dive into AWS architecture, high availability, security design, and cost optimization.

---

## The Story

I passed the **AWS Certified Cloud Practitioner (CLF-C02)** exam on **May 17, 2026**.

Rather than just moving on, I used AI (Claude by Anthropic) to turn my entire prep into a free, structured study guide that anyone can use. The practice questions are written in the exact style and difficulty of the real exam — because I wrote them while actively studying for it.

Once I passed, I expanded the site into a multi-cert platform. Every certification I earn from here gets its own guide, same site, same URL, no paywall.

> *This is what I think the future of learning looks like — AI accelerating how fast you can genuinely understand something, and then using that knowledge to create value for others.*

---

## How to Use

**Use the live site:**
👉 [vb-1405.github.io/aws-ccp-guide](https://vb-1405.github.io/aws-ccp-guide/)

**Run locally:**
```bash
git clone https://github.com/VB-1405/aws-ccp-guide.git
cd aws-ccp-guide
open index.html   # macOS
# or drag index.html into any browser
```

**Works offline** — the entire site (notes + exams) is self-contained in one HTML file.

---

## Repo Structure

```
aws-ccp-guide/
├── index.html      # The entire site — notes, exams, navigation
├── README.md       # This file
└── Resume.pdf      # Vrishabh's resume (optional download)
```

No dependencies. No npm install. No build step. Just open `index.html`.

---

## Adding New Cert Guides (For Reference)

When a new cert guide is ready, it gets added to `index.html` as a new section following the same pattern:

1. New cert card on the landing page
2. New sidebar section with domain links
3. Study notes pages with subtabs
4. Practice exam question bank
5. Next buttons connecting all sections

The landing page automatically shows all available guides.

---

## Official Resources

- [AWS Cert Overview](https://aws.amazon.com/certification/certified-cloud-practitioner/)
- [CLF-C02 Exam Guide PDF](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)
- [AWS Skill Builder (Free)](https://explore.skillbuilder.aws/learn/course/134/play/93785/aws-cloud-practitioner-essentials)
- [Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)
- [Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/)
- [AWS Pricing Overview Whitepaper](https://d0.awsstatic.com/whitepapers/aws_pricing_overview.pdf)
- [AWS Support Plans](https://aws.amazon.com/premiumsupport/plans/)
- [AWS Pricing Calculator](https://calculator.aws/)

---

## Contributing

Found an error, outdated info, or want to add questions?

1. Fork the repo
2. Make changes in `index.html`
3. Open a pull request with a clear description

All contributions welcome — especially corrections to explanations and new scenario-based questions.

---

## License

MIT — free to use, share, fork, and modify.

If this helped you pass, a ⭐ on the repo goes a long way and helps others find it.

---

*Built by [Vrishabh Bhavsar](https://vb-1405.github.io/Portfolio_VB/) · Cybersecurity MS @ CSUDH · [LinkedIn](https://www.linkedin.com/in/cyberrookie/) · [Verify AWS CCP](https://www.credly.com/badges/144c27ac-3106-4c8d-a9da-8aa5f3d3064a)*
