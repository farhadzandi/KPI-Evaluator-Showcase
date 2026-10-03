# Synthetic Sample Evaluation

This example uses fictional data only.

## Evaluation context

| Field | Example |
|---|---|
| Contractor | Demo Mobility Systems |
| Project | Fleet Monitoring Pilot |
| Evaluator | Demo Evaluator |
| Status | Submitted |
| Passing threshold | 75 / 100 |

## Example KPI results

| Section | KPI | Weight | Score | Mandatory | Result |
|---|---|---:|---:|---|---|
| Technical | Functional compliance | 20 | 88 | Yes | Pass |
| Technical | Integration readiness | 15 | 80 | Yes | Pass |
| Delivery | Schedule adherence | 15 | 72 | No | Below target |
| Support | Incident response | 10 | 90 | No | Pass |
| Security | Access-control compliance | 20 | 95 | Yes | Pass |
| Documentation | Technical documentation | 10 | 82 | No | Pass |
| Training | User training | 10 | 78 | No | Pass |

## Example interpretation

The overall score may exceed the configured threshold while individual non-mandatory KPIs remain below target. Mandatory KPIs are evaluated independently and can block approval even when the aggregate score is acceptable.

This separation is important because a high total score should not compensate for failure in a critical requirement.
