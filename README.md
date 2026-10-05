# Script-Controlled Access Control in ServiceNow

A ServiceNow platform security project documenting script-controlled access to institution records in the custom `u_institution_details` table. The report covers user and role setup, table creation, ACL configuration for read, create, write, and delete operations, security verification, and project assessment.

## Project overview

| Component | Details |
| --- | --- |
| Platform | ServiceNow Platform Security, Global scope |
| Custom table | `u_institution_details` (Institution Details) |
| Access controls | Script-controlled table ACLs for read, create, write, and delete |
| Project documentation | Seven milestones, 35 operational steps, and a six-case security verification matrix, as reported in the project report |

## Status

| Area | Status | Reference |
| --- | --- | --- |
| Project report | Complete | [PDF report](ServiceNow_ACL_Project_Report_Updated.pdf) |
| Editable report | Available | [DOCX report](ServiceNow_ACL_Project_Report_Updated.docx) |
| Milestone index | Documented | [Milestones](milestones/README.md) |
| Evidence index | Available | [Evidence](evidence/README.md) |

The report records the implementation steps and verification outcomes. See the report for the full configuration walkthrough and test matrix.

## Access-control workflow

```text
User / role context
        |
        v
ServiceNow evaluates the table ACL and its script conditions
        |
        v
Read, create, write, or delete access decision
        |
        v
Institution Details records
```

## Repository structure

```
.
├── README.md
├── ServiceNow_ACL_Project_Report_Updated.docx
├── ServiceNow_ACL_Project_Report_Updated.pdf
├── evidence/
│   └── README.md
└── milestones/
    └── README.md
```

## Team

This project was completed by a five-member team. The roster and team identifier are included in the project report.

## Evidence

The report includes the configuration walkthrough, screenshots, and security verification matrix. A project demonstration video is linked from the [evidence index](evidence/README.md).
