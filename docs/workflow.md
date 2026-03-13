# Operating Workflow

## 1) Gather

- Pull candidate signals from pre-defined source feeds.
- Normalize into event cards: `{topic, claim, artifact_link, date, actors, confidence}`.

## 2) Filter

- Score each card on consequence, novelty, evidence quality, and reader value.
- Drop low-evidence or duplicate narrative items.

## 3) Synthesize

- Cluster cards by storyline.
- Identify where disagreements are substantive vs semantic.
- Draft neutral summary with explicit fact/interpretation separation.

## 4) Construct issue

- Set title + one-sentence abstract.
- Choose modules based on top clusters.
- Add “Why It Matters” and “Open Questions” only when warranted by evidence.

## 5) Verify

- Link-check all primary references.
- Confirm no claim depends solely on Tier 3 commentary.
- Run style pass for neutrality and cliché removal.

## 6) Publish + archive

- Publish Dispatch issue.
- Archive issue metadata for future timelines, dashboards, and explainers.

## Suggested future automation

- Source ingestion scripts for repos and mailing lists
- Change-detection alerts for watched PRs/BIPs/releases
- Internal signal scoring dashboard
- Structured archive for searchable historical context
