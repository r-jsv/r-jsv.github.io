> Hi, I'm Robin 👋 An experienced full-stack staff software engineer (and [published author](https://link.springer.com/chapter/10.1007/978-3-030-35333-9_37)) with experience in building in-house exp platforms & experimentation culture. Let's talk evidence-based decision making on [LinkedIn](https://www.linkedin.com/in/robin-sveningson-11005793/) or [email](robin@empiriska.se)

This is a practical guide on how to evolve your opinion-based organization to an organization that uses experimentation & validated learnings for decision making. This guide is based on practical experience, 25+ research papers and many decades of learnings published by big-tech like Facebook, Google, Netflix etc. From starting the first experiments to operational excellence - for many small- to mid-scale software organization this is the natural next step for growth. 

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

## Highlighted sources
* Online Controlled Experiments at Large Scale - Kohavi et al - [link](https://dl.acm.org/doi/10.1145/2487575.2488217)
* The Evolution of Continuous Experimentation in Software Product Development: From Data to a Data-Driven Organization at Scale - Fabijan et al - [link](https://exp-platform.com/Documents/2017-05%20ICSE2017_EvolutionOfExP.pdf)
* The Anatomy of a Large-Scale Experimentation Platform - Gupta et al - [link](https://www.researchgate.net/profile/Aleksander-Fabijan/publication/324889185_The_Anatomy_of_a_Large-Scale_Online_Experimentation_Platform/links/5ae96411a6fdcc03cd8fa431/The-Anatomy-of-a-Large-Scale-Online-Experimentation-Platform.pdf)
* Introducing Continuous Experimentation in Large Software-Intensive Product and Service Organisations - Yaman et al - [link](https://www.sciencedirect.com/science/article/abs/pii/S0164121217301474)

## All sources
* Leaky Abstraction In Online Experimentation Platforms: A Conceptual Framework To Categorize Common Challenges - Kluck, Vermeer - [link](https://www.researchgate.net/publication/320180177_Leaky_Abstraction_In_Online_Experimentation_Platforms_A_Conceptual_Framework_To_Categorize_Common_Challenges)
* Experiment reporting at AirBnb - AirBnb - [link](https://medium.com/airbnb-engineering/experiment-reporting-framework-4e3fcd29e6c0#.cbl72jip2)
* Democratizing online controlled experiments at Booking.com - Kaufman, Pitchfork, Vermeer - [link](https://www.researchgate.net/publication/320582817_Democratizing_online_controlled_experiments_at_Bookingcom)
* Engineering for a Science-Centric Experimentation Platform - Diamantopoulos et al - [link](https://research.chalmers.se/publication/519813/file/519813_Fulltext.pdf)
* How A/B Tests Could Go Wrong: Automatic Diagnosis of Invalid Online Experiments - Chen, Liu, Xu - [link](https://dl.acm.org/doi/10.1145/3289600.3291000)
* From Infrastructure to Culture: A/B Testing Challenges in Large Scale Social Networks - Xu et al - [link](https://dl.acm.org/doi/10.1145/2783258.2788602)
* It takes a Flywheel to Fly: Kickstarting and Keeping the A/B testing Momentum - Fabijan et al - [link](https://www.microsoft.com/en-us/research/articles/it-takes-a-flywheel-to-fly-kickstarting-and-keeping-the-a-b-testing-momentum/)
* Seven Rules of Thumb for Website Experimenters - Kohavi et al - [link](https://exp-platform.com/rules-of-thumb/)
* Pitfalls of Long-Term Online Controlled Experiments - Dmitriev et al - [link](https://www.exp-platform.com/Documents/2016%20IEEEBigDataLongRunningControlledExperiments.pdf)
* The Evolution of Continuous Experimentation in Software Product Development: From Data to a Data-Driven Organization at Scale - Fabijan et al - [link](https://exp-platform.com/Documents/2017-05%20ICSE2017_EvolutionOfExP.pdf)
* Introducing Continuous Experimentation in Large Software-Intensive Product and Service Organisations - Yaman et al - [link](https://www.sciencedirect.com/science/article/abs/pii/S0164121217301474)
* The Benefits of Controlled Experimentation at Scale - Fabijan et al - [link](https://exp-platform.com/Documents/2017-08%20BenefitsOfExPScaleSEAA.pdf)
* The Anatomy of a Large-Scale Experimentation Platform - Gupta et al - [link](https://www.researchgate.net/profile/Aleksander-Fabijan/publication/324889185_The_Anatomy_of_a_Large-Scale_Online_Experimentation_Platform/links/5ae96411a6fdcc03cd8fa431/The-Anatomy-of-a-Large-Scale-Online-Experimentation-Platform.pdf)
* Decision Making at Netflix - Netflix - [link](https://netflixtechblog.com/decision-making-at-netflix-33065fa06481)
* Exp platform at Zalando - Huang - [link](https://engineering.zalando.com/posts/2021/01/experimentation-platform-part1.html)
* How We Reimagined A/B Testing at Squarespace - Absher et al - [link](https://engineering.squarespace.com/blog/2021/how-we-reimagined-ab-testing-at-squarespace)
* Why we use experimentation quality as the main KPI for our experimentation platform - Perrin et al - [link](https://medium.com/booking-product/why-we-use-experimentation-quality-as-the-main-kpi-for-our-experimentation-platform-f4c1ce381b81)
* Online Controlled Experiments at Large Scale - Kohavi et al - [link](https://dl.acm.org/doi/10.1145/2487575.2488217)
* Designing and Deploying Online Field Experiments - Bakshy et al - [link](https://dl.acm.org/doi/10.1145/2566486.2567967)
* Overlapping Experiment Infrastructure: More, Better, Faster Experimentation - Tang et al - [link](https://static.googleusercontent.com/media/research.google.com/sv//pubs/archive/36500.pdf)
* Building Blocks for Continuous Experimentation - Fagerholm et al - [link](https://dl.acm.org/doi/10.1145/2593812.2593816)
* The RIGHT Model for Continuous Experimentation - Fagerholm et al - [link](https://www.sciencedirect.com/science/article/abs/pii/S0164121216300024)
* Transitioning Towards Continuous Experimentation in a Large Software Product and Service Development Organisation – A Case Study - Yaman et al - [link](https://www.researchgate.net/publication/307994703_Transitioning_Towards_Continuous_Experimentation_in_a_Large_Software_Product_and_Service_Development_Organisation_-_A_Case_Study)
* Success stories from a democratized exp platform - Forsell et al - [link](https://www.researchgate.net/publication/347515831_Success_Stories_from_a_Democratized_Experimentation_Platform)
* Using data to build better products - Bosch - [link](https://janbosch.com/blog/wp-content/uploads/2024/06/UsingDataToBuildBetterProducts-SemiFinal.pdf)
* Effective online controlled experiment analysis - Fabijan et al - [link](https://www.researchgate.net/publication/327350401_Effective_Online_Controlled_Experiment_Analysis_at_Large_Scale)

