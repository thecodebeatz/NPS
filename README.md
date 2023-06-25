# NPS Margin of Error

This iPython notebook complements my blog post on https://codebeats.ml/blogpost/nps-score-quality-over-quantity. Here, I aim to demonstrate that NPS tracking can be reasonably reliable, even with a sample size as small as 40 respondents. This holds especially true when the sample standard deviation is lower.

In this notebook, I explore how NPS Error varies with changes in sample size and standard deviation. An interesting insight to highlight is that the margin of error (MoE) for a 100-respondent survey can be as significant as the MoE for a 30-respondent survey if the NPS ratings provided by customers exhibit high sample variance.

In other words, having 100 respondents for your NPS survey does not guarantee accurate results. If there is a high variance in the respondents' answers, the NPS score can be misleading and unreliable.

![NPS Error vs Sample Size and Variance](https://github.com/thecodebeatz/NPS/assets/46902643/0958fab6-f28e-4206-ad9d-646733b8bd16)
