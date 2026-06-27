##### Hypothesis Test Notes

###### Business Objective

The objective of this A/B test is to determine whether the new onboarding and activation campaign significantly improves user activation compared to the existing onboarding experience. The result will help decide whether the treatment should be rolled out to all users.

\---

###### Metric Being Tested

**Primary Metric:** Onboarding Completion Rate (User Activation Rate)

###### Reason for Choosing This Metric

User Activation Rate is the North Star metric for this experiment because it directly measures whether users successfully complete the onboarding process. Users who complete onboarding are more likely to engage with the product, convert to paid subscriptions, and remain active over time.

\---

##### Hypotheses

###### Null Hypothesis (H₀)

There is no significant improvement in the onboarding completion rate for users exposed to the new onboarding campaign.

\[
 Null Hypothesis: Null Hypothesis (H₀): Hypothesized mean difference between control group \& treatment group is Zero Ho: μ\_control 
]

###### Alternative Hypothesis (H₁)

The new onboarding campaign significantly improves the onboarding completion rate.

\[

Alternative Hypothesis (H₁): Mean difference between two groups is not Zero Ha: μ\_control ≠ μ\_Treatment
Ha: p\_{Treatment} > p\_{Control}
]

\---

###### Test Type

**One-tailed Two-Proportion Z-Test**

A one-tailed test was selected because the business question is whether the new onboarding experience performs **better** than the existing experience, not merely whether it is different.

\---

###### Significance Level

* **α = 0.05 (5%)**

Decision Rule:

* If **p-value < 0.05**, reject the null hypothesis.
* If **p-value ≥ 0.05**, fail to reject the null hypothesis.

\---

###### Summary of Test Inputs

|Metric|Control|Treatment|
|-|-:|-:|
|Total Users|690|710|
|Completed Onboarding|108|150|
|Onboarding Completion Rate|15.65%|21.13%|

Difference in activation rate:

**21.13% − 15.65% = 5.48 percentage points**

\---

###### Test Output

**Statistical Test:** Two-Proportion Z-Test

**P-value:** < 0.05

###### Decision

Since the p-value is below the 5% significance level, the null hypothesis is rejected.

\---

###### Business Interpretation

The treatment group achieved a significantly higher onboarding completion rate than the control group. This indicates that the new onboarding campaign is more effective at activating users.

Supporting metrics also improved:

* Higher Landing Page Visit Rate
* Higher Trial Start Rate
* Higher Paid Conversion Rate
* Higher Engagement Score
* Faster Average Days to Convert

However, the treatment also showed:

* Higher Support Ticket Rate
* Slightly Higher Refund Rate
* Lower Average Revenue per Converted User

These guardrail metrics should continue to be monitored after rollout.

\---

###### Recommendation

Based on the statistical evidence, the treatment demonstrates a meaningful improvement in the primary business metric (User Activation Rate). The null hypothesis is rejected, indicating that the new onboarding campaign performs significantly better than the existing experience.

**Recommendation:** Proceed with a phased rollout of the treatment while closely monitoring support tickets, refund rates, and revenue per converted user to ensure that the improvements in activation translate into sustainable long-term business growth.

