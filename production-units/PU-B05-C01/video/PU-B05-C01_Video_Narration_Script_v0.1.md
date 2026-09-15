# Video Narration Script — MLOps Foundations

**Production unit:** PU-B05-C01  
**Target duration:** 18–22 minutes  
**Presenter tone:** calm, authoritative and practical  
**Visual identity:** navy field, cyan systems lines, gold control gates

## Opening — A model is not yet a system (0:00–1:20)

Welcome to MLOps Foundations. A model can achieve a strong metric and still be unsafe, irreproducible or impossible to operate. MLOps addresses that gap. It connects data, code, configuration, infrastructure, evaluation, monitoring and accountable decisions into one controlled lifecycle. In this lesson we will build evidence for a release candidate, but we will not confuse technical completion with authorization.

## The governed lifecycle (1:20–4:00)

Show the lifecycle as an operating loop: frame the decision, accept data, reproduce the environment, train and evaluate, package immutable artifacts, test contracts, review gates, deploy under authority, monitor, and either continue or roll back. Emphasize that ownership and evidence travel with every transition. The loop is not finished at deployment; production feedback changes the next decision.

## Evidence and lineage (4:00–6:30)

Open the notebook run record. Point to the fixed seed, configuration, data digest, model digest and split summary. Explain that a digest does not prove quality. It proves identity. Quality comes from acceptance tests and evaluation. Together, identity and quality allow another reviewer to reconstruct what was assessed.

## Evaluation beyond one metric (6:30–9:20)

Display ROC AUC, recall and the regional slice chart. A single aggregate metric can conceal uneven behavior. Slice evaluation asks where the model fails, for whom, and under what conditions. The notebook uses synthetic agricultural risk as a concrete example, but the same discipline applies to education support, health triage and habitat or housing services.

## Gates, approval and segregation of duties (9:20–12:20)

Walk through the release gates. Technical checks can pass while the release remains blocked. That is intentional. The builder supplies evidence; a suitably authorized reviewer accepts risk. This separation prevents a developer from silently converting successful execution into institutional approval.

## Monitoring and rollback (12:20–15:10)

Show the rainfall drift graphic and rollback record. Monitoring must connect a signal to an owner, threshold, response and evidence record. A rollback plan is not a sentence saying “revert if needed.” It identifies the prior approved artifact, trigger, authority, method and verification steps.

## Four sectors, one discipline (15:10–18:10)

For agriculture, monitor seasonal and regional shifts before operational use. For education, protect learners from opaque placement or intervention decisions. For health, demand clinical governance and human escalation. For habitat and housing, test geographic and demographic disparities and preserve appeal routes. The controls remain consistent, while risk tolerances and accountable authorities differ.

## Close — Evidence before promotion (18:10–19:30)

The central principle is simple: no artifact advances merely because it exists. Promotion requires reproducible evidence, explicit gates and accountable authority. Run the notebook, inspect the evidence inventory, challenge the gates, and document what would be required before this candidate could move beyond a controlled learning environment.

## End card

SRAI Book 5 · Lesson 1 · MLOps Foundations  
Evidence before promotion. Authority before release.
