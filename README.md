# 4 phases to build an evidence-based organization using experiments

## Phase 1 - Buy-in & core team (first 3-6 months):
- Secure buy-in from execs & senior leadership
- Build core team with mix of engineers & data-scientists
- Invite 1-2 starting teams as first customers
- Run a few experiments with manual processes if needed
- Research available 3rd-party tools
- Study research papers (Kohavi, Tang, Dmitriev, Xu, Deng, Bosch, Fabijan, Holmström Olsson...)

## Phase 2 - MVP platform & initial culture shift (~6 months)
- Buy vs build consideration (important to get this right)
- First MVP platform (cohorting + population filters + automated evaluation)
- Power analysis tool
- Help teams define standardized reusable metrics
- Drive culture shift for psychological safety
- Advocate for quick-win low-effort experiments (quantity over quality at this time)
- Publicly celebrate any completed experiments
- Offer metrics & experiment design support (hypothesis, cohorts, primary metrics, outlier handling)
- Create reusable experiment templates

## Phase 3 - Validated learnings (year 2-3)

[Data]
- Evolve high-quality & standardized data-pipelines (e.g. offline metric store)
- Collect 4 types of metrics: success, guardrail, data quality & debug metrics
- Handle late-arriving & incomplete data
- All product teams should define their standardized list of predefined metrics
- Build LTV metrics
- Pipeline for qualitative user insights to generate experiment hypotheses

[QA & releases]
- Ensure instant product deployments, fast releases & extensive monitoring
- Work with QA to prevent product combinatorics problem

[Tooling]
- Democratise decision-making of experimentation methodology
- Statistical framework: colliding experiments, carry-over effects, A/A, novelty effects, salted randomization, Bonferroni, SRM, ...
- User attribution targeting
- Consider product holdout groups
- Ensure consistent user experience across devices
- Experiment group exposure logging
- Built-in security/compliance/GDPR checks
- Pre-experiment & post-experiment automated checklists
- Regression-driven experimentation (gradual rollouts, canaries...)
- Alert & automatic stop of harmful experiments
- Global guardrail metrics
- Experiment reporting with p-value & confidence intervals
- Prevent peeking problem
- Slice & dice of experiment results
- Institutional memory of past experiments
- Enable data-scientist auditing
- Visualise ROI + cost

[Culture]
- Survey state of experimentation in different teams
- Company-wide education: Workshops, demos, onboarding, checklists, problem-solving guides, how-tos
- Teach Twyman’s Law (too good to be true = not true), statistical foundations, common pitfalls etc.
- Advanced progress reporting: blogging, highlighted experiments, exec reports
- Teach feature-slicing mentality, build-measure-learn blocks
- Embed experiment experts into teams
- Define clear decision-making frameworks
- Forced wrap-up of expired experiments with decision reasoning & qualitative learnings
- Sharing of all experiment results with global peer-review process

### Phase 4 - Operational Excellence (year 3+)
- Experiment specific holdout groups to monitor long-term effects
- Tie experiments to long-term business objectives
- Reverse & negative experiments
- Experiments everywhere: Notifications, emails, landing pages, marketing etc
- Experiments for all: finance, marketing, leadership etc
- Less pre-planned backlogs, engineers work freely to explore ideas to move metrics
- Purposefully hire autonomous engineers with experimentation mindset
- Rewards & performance review process based on validated metrics movement
- Metric trees & tiers, use experiment results to prove causality

### Sources
