# Code review checklist — UOWBigData

> University big data project — AIR4T Sovereign Fleet member

## 1. Security
- [ ] No secrets, API keys, or credentials in code or git history
- [ ] No PII or sensitive data in logs
- [ ] Input validation on all external-facing interfaces

## 2. Quality
- [ ] Code compiles/runs without errors
- [ ] Tests pass (if configured)
- [ ] Dependencies documented and pinned

## 3. Sovereign fleet governance
- [ ] No raw user content to Ledger (G-01)
- [ ] AU data residency (ap-southeast-2) default (G-04)
- [ ] No force-push to main (G-05)
- [ ] Serverless by default — no NAT/VPC/EC2 without approval (G-11)

If any item fails, fix or get explicit approval before merge.
