# Fixing the Lead Scoring Math: Unblocking the B2B Marketing Funnel

**Summary:** I led an end-to-end analysis to understand why Marketing Qualified Leads (MQLs) were declining. The answer wasn’t only fewer leads; it was a structural flaw in the lead scoring model that made it nearly impossible for engaged buyers to qualify through multiple interactions. The work resulted in a targeted plan to rebalance scoring weights and fix operational gaps so high-intent buyers could reach Sales.

**My role:** I owned the analysis from start to finish: defining the methodology, extracting and combining CRM and marketing automation data, building custom funnel metrics, and presenting recommendations to Marketing Operations and business stakeholders.

**Project status:** Analysis delivered; recommendations incorporated into a revised lead scoring model.

**Public evidence:** Documentation only. All examples are fictionalized.

## The Problem
Qualified lead volume had been slipping for several quarters, and the pressure was building to “just get more leads to Sales.” The quickest-looking fix was obvious: lower the bar for what counts as qualified.

But lowering the bar without understanding the cause risked sending weaker leads to Sales while leaving the real problem untouched. Marketing Operations needed to know what was actually happening underneath the number. Was this a scoring problem, a demand problem, or a budget problem? Where were leads getting stuck, and which changes would increase qualification without sacrificing quality?

Success meant giving the team a clear, evidence-based answer about what was broken and which fixes were worth making first.

## My Approach and Key Decisions
* **Separating volume from efficiency:** Before questioning the scoring model, I checked whether conversion rates had actually changed. They hadn’t. Most of the decline came from fewer leads entering the funnel, in line with reduced marketing spend. That kept the investigation honest: any case against the scoring model had to stand on its own evidence, not borrow the whole decline as proof.
* **Distinguishing instant qualifiers from leads that build up points:** I separated leads that qualified immediately through a single high-intent action from those that qualified by accumulating engagement over time. Nearly all qualified leads fell into the first group, which meant the nurture side of the funnel was contributing very little. Looking only at totals would have hidden this completely.
* **Analyzing journeys, not just scores:** I mapped the sequence of actions each lead took and the time between them. This tested the core assumption behind any points-based model: that buyers engage repeatedly. Most didn’t.
* **Accounting for score decay:** The system resets scores after a period of inactivity, so I focused the score analysis on recently active leads and removed records inflated by duplicate merges. Without this step, the picture of where leads stall would have been misleading.
* **Testing the quick fix before recommending an alternative:** Rather than arguing against lowering the threshold in principle, I modeled it. That turned an open debate into a settled question.

## Findings
* Multi-touch journeys were rare. Most prospects engaged with a single campaign and then went quiet. The funnel was built for repeated engagement that rarely happened.
* The threshold wasn’t the bottleneck. Lowering it would have added only a marginal number of qualified leads, so relaxing the standard would not solve the problem.
* Engaged buyers were structurally blocked. The most common entry points awarded so few points that even a motivated buyer completing several follow-up actions would still fall short. The model was keeping genuinely interested buyers away from Sales.
* Timing worked against the model. When buyers did return, they often came back after their score had already reset, erasing the engagement they had built.

## Business Implication
The answer was not to lower the standard, but to fix what fed into it. I recommended that the team:
1. Give more weight to meaningful follow-up actions so engaged buyers can qualify naturally.
2. Remove penalties that block explicit high-intent requests.
3. Refresh nurture content with low-friction, hands-on next steps.
4. Recalibrate point values systematically, using predictive modeling or attribution data rather than intuition.
5. Add monitoring for data-quality issues affecting both reporting and field teams.

## Validation and Limitations
I applied consistent exclusions across every view, documented filters so results could be reproduced, and confirmed my interpretation of scoring rules with the system owner. Along the way, I surfaced data hygiene issues that were creating false alarms for field teams, and included fixes in the recommendations.

Some behavioral signals weren’t available in the data, so the picture of buyer engagement was incomplete. Because journeys were so short, the proposed scoring changes were a reasoned starting point rather than a proven optimum, which is why I recommended a systematic recalibration rather than presenting fixed values.

## Outcome
* **What I delivered:** A diagnostic of the scoring model, a tested assessment of the threshold proposal, and a prioritized set of recommendations.
* **What stakeholders adopted:** The recommendations were consolidated into a revised scoring model, including updated point weights, a longer decay window, and improved data enrichment.
* **What was measured:** The analysis showed that lowering the threshold would produce only a marginal gain, redirecting effort toward fixing the scoring inputs.
* **What remains unknown:** The impact of the revised model on lead volume and pipeline has not yet been measured.

## What I learned
The turning point came from looking at sequences instead of scores. I expected to find leads stuck midway through long journeys. Instead, most had no journey at all. That changed the question from “which actions deserve more points?” to “does this model fit how our buyers actually behave?”

It also reinforced a habit I rely on: when someone proposes a quick fix, model it first. A single clear number ended a debate that a methodological argument would not have.

Next time, I would secure all behavioral data sources up front and agree on a measurement plan alongside the recommendations, so the impact can be evaluated against a clean baseline.

## Keywords / Tools / Systems
Lead scoring | MQL qualification | Funnel diagnostics | Lead lifecycle | Behavioral and demographic scoring | Score decay | Nurture strategy | Journey analysis | Multi-touch attribution | Data quality | B2B marketing analytics | Tableau | Marketo | Salesforce | Snowflake | SQL

## Confidentiality
Internal company records, proprietary scoring models, system configurations, data structures, and raw data assets have been withheld or anonymized to protect company confidentiality. Any examples shown are fictional.
