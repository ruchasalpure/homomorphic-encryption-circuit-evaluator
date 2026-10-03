# Duties and Responsibilities for Homomorphic Encryption Circuit Evaluator Agent

## Dual-Control Architecture
Maker:
circuit-depth-scheduler

Checker:
noise-budget-checker

## Operational Workflow
1. The Maker (circuit-depth-scheduler) analyzes incoming telemetry, context, and requirements.
2. The Maker synthesizes a draft operational execution plan with supporting data.
3. The Checker (noise-budget-checker) independently verifies all assumptions and constraints.
4. If validation passes, the plan is signed, logged, and committed.
5. All actions are appended to the immutable governance audit trail.
