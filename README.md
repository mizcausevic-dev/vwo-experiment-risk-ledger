# vwo-experiment-risk-ledger

Board-readable Kinetic Gain proof repo for **VWO** platform and company signal coverage.

## Product thesis

Experiment results become hard to trust when variants, holdouts, segments, and launch decisions are not governed together.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** Growth leaders, product marketers, experimentation teams, and revenue strategists
- **Signal domain:** Experimentation
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product maps each experiment to guardrails, decision owners, lift evidence, rollout risk, and buyer-safe narrative.
- **Value architecture:** Leaders can see which tests deserve rollout, rollback, more instrumentation, or a stronger evidence packet.

## What this repo proves

- **Normalize:** messy VWO operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: VWO experiments, variants, holdouts, conversion events, guardrails, and campaign decisions.

This is synthetic proof only. It does not connect to live VWO tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- VWO
- experiment governance
- conversion optimization
- A/B testing
- holdout evidence
