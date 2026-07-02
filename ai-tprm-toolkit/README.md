# AI-TPRM Toolkit

**Open-source AI-Aware Third-Party Risk Management Toolkit**

A practical, framework-aligned toolkit for organisations managing third-party and AI supply chain risk. Covers vendor assessment questionnaires, risk scoring models, governance checklists, and policy templates aligned with ISO/IEC 27001, ISO/IEC 42001, EU AI Act, NIS2, and DORA.

---

## Who This Is For

- **GRC and compliance professionals** building or improving TPRM programmes
- **AI governance practitioners** assessing AI systems in their supply chain
- **Energy sector operators** managing NIS2 Article 21 supply chain obligations
- **Financial sector organisations** meeting DORA ICT third-party requirements
- **Security teams** needing structured vendor assessment tooling

---

## What Is Included

```
ai-tprm-toolkit/
├── README.md
├── questionnaires/
│   ├── standard_vendor_questionnaire.md        # General TPRM — all tiers
│   ├── ai_vendor_questionnaire.md              # AI-specific — ISO 42001 aligned
│   ├── ot_vendor_questionnaire.md              # OT/ICS vendor — IEC 62443 aligned
│   └── financial_vendor_questionnaire.md       # DORA-aligned ICT third-party
├── checklists/
│   ├── vendor_onboarding_checklist.md          # Full onboarding workflow
│   ├── nis2_article21_checklist.md             # NIS2 supply chain compliance
│   ├── eu_ai_act_supplier_checklist.md         # EU AI Act Annex III supplier check
│   ├── dora_ict_tprm_checklist.md              # DORA Article 28-44 checklist
│   └── vendor_offboarding_checklist.md         # Secure offboarding procedure
├── scoring/
│   ├── vendor_risk_scoring_model.md            # RAG scoring methodology
│   ├── ai_system_risk_calculator.md            # EU AI Act risk classification tool
│   └── tprm_kpi_dashboard_template.md          # KPI definitions and targets
├── governance/
│   ├── tprm_policy_template.md                 # Complete TPRM policy
│   ├── vendor_risk_tier_model.md               # Critical/High/Medium/Low model
│   ├── ai_supply_chain_policy.md               # AI-specific supply chain policy
│   └── dpa_review_checklist.md                 # GDPR Article 28 DPA review
└── templates/
    ├── vendor_assessment_report.md             # Assessment report template
    ├── risk_register_template.md               # Vendor risk register
    ├── remediation_plan_template.md            # Gap remediation tracker
    └── management_briefing_template.md         # Executive dashboard template
```

---

## Framework Alignment

| Framework | Coverage in this toolkit |
|-----------|--------------------------|
| ISO/IEC 27001:2022 | Annex A 5.19–5.22 supplier controls, Clause 6 risk assessment |
| ISO/IEC 42001:2023 | Clause 4.5 AI supply chain obligations, Annex A.10 third-party AI |
| EU AI Act (2024) | Annex III high-risk classification, Article 9 risk management |
| NIS2 Directive (2022/2555) | Article 21(2) ten measures, Article 21(3) supply chain |
| DORA (2022/2554) | Article 28–44 ICT third-party risk management |
| GDPR (2016/679) | Article 28 Data Processing Agreements |
| IEC 62443 | OT/ICS vendor security levels |
| NIST CSF 2.0 | GOVERN and IDENTIFY functions |

---

## How to Use

1. **Start with the vendor risk tier model** (`governance/vendor_risk_tier_model.md`) to classify your vendors
2. **Select the appropriate questionnaire** based on vendor type
3. **Score responses** using the scoring model (`scoring/vendor_risk_scoring_model.md`)
4. **Complete the onboarding checklist** before approving any vendor
5. **Track ongoing risk** using the KPI dashboard template

---

## Licence

Creative Commons Attribution 4.0 International (CC BY 4.0)

You are free to use, adapt, and redistribute this toolkit with attribution.

**Attribution:** Aderonke Thompson — AI-TPRM Toolkit — github.com/aderonkethoms/ai-tprm-toolkit

---

## Author

**Prof. A. F. Thompson, PhD**
ISO 27001 Lead Implementer / Lead Auditor | ISO 42001 AI Management Systems Practitioner
ERCIM Postdoctoral Fellow, VTT Technical Research Centre of Finland (2022–2024)

[ORCID: 0000-0003-2182-1505](https://orcid.org/0000-0003-2182-1505) | [LinkedIn](https://linkedin.com/in/aderonke-thompson)

---

## Contributing

Contributions welcome. Please open an issue or pull request.
Focus areas: additional sector questionnaires, translations, automation scripts.

---

*This toolkit is provided for educational and professional use. It does not constitute legal advice. Always consult qualified legal and compliance professionals for your specific regulatory obligations.*
