# Approved AWS-first training strategy
Approved 2026-11-25. All work below is planned, not completed. Preserve 124 assignment IDs, 26 categories and four capstones.

## Direction and certification
AWS primary; Microsoft 365, Entra ID, AD, Intune and Azure fundamentals complementary. Linux, networking, PowerShell, Python, Terraform, Docker and Git remain core. Kubernetes later. A+, Network+, AZ-900 and Cloud Practitioner coursework only; Security+ first exam, AWS Solutions Architect Associate next, Terraform Associate recommended, CloudOps Engineer Associate conditional, FinOps Practitioner recommended, Solutions Architect Professional and AI credential later after experience. Recheck current exam objectives and costs before booking.

## Career gates
Review every 30 days; assess sooner when evidence supports it. Target spring/summer 2027, apply earlier if ready; no mandatory waiting period or Level 3 help desk prerequisite. Target Tier 2 competency, but consider Tier 1 or junior infrastructure roles with meaningful cloud exposure. After employment evaluate cloud readiness around six months, earlier if warranted; 6–12 months is an illustrative transition window, not a guarantee. Review 15–20 distinct relevant job descriptions every 60 days; separate required/preferred skills and experience, deduplicate and record dates. No applications or outreach without learner approval.

## Delivery
Two hours daily, flexible 30/60/15/15 minutes concepts/practice/assessment/documentation. Before first job suggested focus 65% IT foundations, 25% security, 10% cloud; after first job 15% foundations, 15% security, 50% cloud, 20% automation. Adjust to demonstrated gaps and work schedule.
Use fictional 15-person small business (M365, endpoints, security), 50-person logistics firm (AWS, databases, automation, AI), and existing 150-person enterprise (hybrid, governance, recovery). Synthetic data only. Use local simulations first; obtain approval for any paid resources. Physical hardware deferred, optional; ARM limitations may require alternate authorized environments.
Tools: Jira Service Management, Intune, M365 Admin Center, Wireshark, PowerShell, Sysinternals, Git, VS Code, AWS CLI, Terraform, Docker, GitHub Actions, Grafana, Cost Explorer. Label simulated versus actual tool use; do not claim licensed environments are provisioned.

## Help desk to cloud bridge
Map existing labs rather than duplicate IDs:
- LAB001–006, 022–030: Windows diagnostics, permissions, services, logs and scripts → EC2, IAM, CloudWatch and automation.
- LAB003–004, 040–047: DNS, DHCP, VPN, firewall and packet diagnostics → VPC, Route 53, security groups, routing.
- LAB031–039: ticket triage, escalation, communication and change control → cloud incident operations.
- LAB070–079: AWS compute, S3, IAM, private networking, load balancing, RDS, encryption, budgets, migration and recovery; use AWS Backup where appropriate.
- LAB080–091: Terraform, Docker, ECS/Fargate, EKS later, CI/CD, observability, rollback.
- LAB092–097, 117–124: AWS cost analysis, forecasts, unit economics and business value.
- LAB101–116: Bedrock, SageMaker AI or suitable open-source alternatives; quality, latency, security and cost.
Inject unfamiliar faults in isolated labs: DNS, permissions, services, VPN, certificates, failed deployment, unreachable EC2, unexpected bill, failed AI endpoint, slow database. Require diagnosis, safe resolution or escalation, verification, documentation and rollback. Never intentionally disrupt real systems.

## Consulting integration
Use existing capstones LAB098–100 and LAB017. Adapt to SMB modernization, secure migration, automation, FinOps and AI document processing with synthetic logistics data. Include discovery, requirements, alternatives (including no change), estimates, TCO/ROI, scope, risks, proposal, acceptance tests, executive presentation, project margin and realized versus potential benefits. No claims of actual client work or savings. Keep AI infrastructure a long-term specialization, not a first-job prerequisite.
