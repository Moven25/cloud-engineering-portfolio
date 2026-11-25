# Publishing a Lab — Checklist

Use this checklist before publishing each completed lab.

- [ ] I performed the steps myself in a lab environment.
- [ ] The objective and environment are accurately documented.
- [ ] Commands, results, and troubleshooting steps reflect what actually happened.
- [ ] Screenshots demonstrate the work and contain no secrets or personal data.
- [ ] I explained what I learned in my own words.
- [ ] I marked the exercise as guided or independent.
- [ ] I linked the lab report from the relevant category README.
- [ ] I updated [LAB-TRACKER.md](LAB-TRACKER.md) to the correct status.

**Suggested structure per lab**

```text
01-Hardware-and-Diagnostics/
  LAB-001-System-Information/
    README.md
    images/
      system-information.png
      task-manager.png
```

Do not upload operating-system license keys, personal email addresses, account tokens, or screenshots of unrelated private projects.

## Cloud and architecture additions
- [ ] Label diagrams as planned, deployed or illustrative; keep editable source (Mermaid or draw.io) where applicable.
- [ ] Record design decisions, alternatives, security and cost trade-offs in an ADR when relevant.
- [ ] Include reproducible commands, versions, tests, limitations and cleanup steps for cloud resources.
- [ ] Remove credentials, tokens, private identifiers, Terraform state, sensitive logs and personal information; never commit secrets or .env files.
- [ ] Distinguish AI-assisted documentation from work actually performed; verify every claim and do not publish copyrighted course transcripts or exam questions.
- [ ] Record failures honestly and mark completion only after evidence and explanation are reviewed.
