# SDC Compliance Engine

**Specification-Driven Compliance** — Live Demo mit DSGVO & OPA Rego

🌐 **[Live Demo](https://waxxdu.github.io/sdc-compliance-demo/)**

---

## Was ist SDC?

Compliance-Anforderungen als **testbare, maschinenlesbare Specs** — nicht als PDFs.

Regulierungstext rein → OPA Rego Policy raus → Engine prüft live.

## Features

- ⚡ **Compliance Engine** — 5 DSGVO Policies (Art. 44, 5, 25, 30, 33) in echtem OPA Rego
- 🤖 **Spec Generator** — Claude AI konvertiert Regulierungstext → Rego Policy in Echtzeit
- 📋 **Policy Manager** — alle Policies sichtbar, toggle-bar, audit-ready
- 📊 **Audit Log** — vollständige Prüfhistorie

## Architektur

```
Regulierungstext
      ↓
  SDC Agent (Claude)
      ↓
  OPA Rego Policy (maschinenlesbar)
      ↓
  Compliance Engine (PASS/FAIL/WARN)
      ↓
  Audit Trail
```

---

*tumaki.de · Carsten Wittmann · AI Compliance Consulting*
