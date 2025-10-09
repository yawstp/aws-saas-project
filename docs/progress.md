<<<<<<< HEAD
\# Project Progress Log (Source of Truth)



\## Current State (TL;DR)

\- Milestone: Week 1 — Foundations

\- Status: in\_progress

\- Next 3 Actions:

&nbsp; 1) Create S3 state bucket + DynamoDB lock table; add Terraform backend/providers; run `terraform init`

&nbsp; 2) Deploy static “Hello World” via S3 + CloudFront + WAF

&nbsp; 3) Verify CloudTrail and GuardDuty alerts in CloudWatch + Security Hub

\- Risks/Blockers: None noted yet

\- Last Updated: 2025-10-08



---



\## Milestones (plan)

\- Week 1: Foundations

\- Week 2: Auth \& Core API

\- Week 3: Async \& Flags

\- Week 4: Analytics \& Billing

\- Week 5: CI/CD \& Observability

\- Week 6: Security, DR, Hardening



---



\## Week 1 — Foundations (Checklist)

\- \[x] Install Git

\- \[x] Install Python

\- \[x] Install Terraform

\- \[x] Install AWS CLI

\- \[x] Create GitHub repository and push basic project structure

\- \[x] Create free AWS account

\- \[x] Create `/docs/` directory

\- \[x] Create `/infra/terraform/` directory

\- \[x] Set $10 Budget alert in AWS Billing

\- \[x] Enable CloudTrail (all regions) and GuardDuty

\- \[ ] Configure Terraform remote state: S3 bucket + DynamoDB lock table

\- \[ ] Add Terraform backend/provider files and run `terraform init`

\- \[ ] Deploy static “Hello World” via S3 + CloudFront + WAF



---



\## JSON Snapshots



```json

{

&nbsp; "date": "2025-10-08",

&nbsp; "milestone": "Week 1 — Foundations",

&nbsp; "status": "in\_progress",

&nbsp; "completed": \[

&nbsp;   "Installed Git",

&nbsp;   "Installed Python",

&nbsp;   "Installed Terraform",

&nbsp;   "Installed AWS CLI",

&nbsp;   "Created GitHub repository and pushed basic project structure",

&nbsp;   "Created free AWS account",

&nbsp;   "Created /docs and /infra/terraform directories",

&nbsp;   "Set $10 Budget alert in AWS Billing",

&nbsp;   "Enabled CloudTrail (all regions) and GuardDuty"

&nbsp; ],

&nbsp; "next\_actions": \[

&nbsp;   "Create S3 state bucket and DynamoDB lock table; add Terraform backend/providers; run terraform init",

&nbsp;   "Deploy static Hello World via S3 + CloudFront + WAF",

&nbsp;   "Verify CloudTrail and GuardDuty alerts in CloudWatch + Security Hub"

&nbsp; ],

&nbsp; "evidence": {

&nbsp;   "repo\_url": "<https://github.com/<you>/aws-saas-project>",

&nbsp;   "screenshots": \[],

&nbsp;   "ids": {

&nbsp;     "budget\_id": "<your\_budget\_id>",

&nbsp;     "cloudtrail\_trail\_name": "<trail\_name>",

&nbsp;     "guardduty\_detector\_id": "<detector\_id>"

&nbsp;   }

&nbsp; },

&nbsp; "decisions": \[

&nbsp;   {"topic": "runtime", "choice": "<Node.js or Python>"},

&nbsp;   {"topic": "region", "choice": "us-east-1"},

&nbsp;   {"topic": "account\_plan", "choice": "single-account to start"}

&nbsp; ],

&nbsp; "risks": \[

&nbsp;   "None noted yet"

&nbsp; ]

}



=======
# Project Progress Log (Source of Truth)

## Current State (TL;DR)
- Milestone: Week 1 — Foundations
- Status: in_progress
- Next 3 Actions:
  1) Create a $10/month AWS Budget alert (email notifications)
  2) Enable CloudTrail (all regions) and GuardDuty
  3) Create S3 state bucket + DynamoDB lock table; add Terraform backend/providers; run `terraform init`
- Risks/Blockers: None noted yet
- Last Updated: 2025-10-06

---

## Milestones (plan)
- Week 1: Foundations
- Week 2: Auth & Core API
- Week 3: Async & Flags
- Week 4: Analytics & Billing
- Week 5: CI/CD & Observability
- Week 6: Security, DR, Hardening

---

## Week 1 — Foundations (Checklist)
- [x] Install Git
- [x] Install Python
- [x] Install Terraform
- [x] Install AWS CLI
- [x] Create GitHub repository and push basic project structure
- [x] Create free AWS account
- [x] Create `/docs/` directory
- [x] Create `/infra/terraform/` directory
- [X] Set $10 Budget alert in AWS Billing
- [ ] Enable CloudTrail (all regions) and GuardDuty
- [ ] Configure Terraform remote state: S3 bucket + DynamoDB lock table
- [ ] Add Terraform backend/provider files and run `terraform init`
- [ ] Deploy static “Hello World” via S3 + CloudFront + WAF

---

## JSON Snapshots

```json
{
  "date": "2025-10-06",
  "milestone": "Week 1 — Foundations",
  "status": "in_progress",
  "completed": [
    "Installed Git",
    "Installed Python",
    "Installed Terraform",
    "Installed AWS CLI",
    "Created GitHub repository and pushed basic project structure",
    "Created free AWS account",
    "Created /docs and /infra/terraform directories"
  ],
  "next_actions": [
    "Create a $10/month AWS Budget with email alerts",
    "Enable CloudTrail (all regions) and GuardDuty",
    "Create S3 state bucket and DynamoDB lock table; add Terraform backend/providers; run terraform init"
  ],
  "evidence": {
    "repo_url": "<https://github.com/<you>/aws-saas-project>",
    "screenshots": [],
    "ids": {
      "budget_id": "",
      "cloudtrail_trail_name": "",
      "guardduty_detector_id": ""
    }
  },
  "decisions": [
    {"topic": "runtime", "choice": "<Node.js or Python>"},
    {"topic": "region", "choice": "us-east-1"},
    {"topic": "account_plan", "choice": "single-account to start"}
  ],
  "risks": [
    "None noted yet"
  ]
}
>>>>>>> 26c16d769c1468c3f520ecdbd2da463a75a20ab5
