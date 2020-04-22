---
layout: post
title: "Paper note: Huang, Teoh and Zhang 2014 TAR"
date: 2020-04-21
---

This paper investigates three questions.

<b>1. Do firms strategically manage the tone of words in earnings press release to influence investors' perception? </b>

Yes, as ABTONE is associated with worse future earnings and operating cash flows (Table 4, pp. 1096).

<b>2. If the upward tone management phenomenon is due to managerial incentives associated with agency problem, then tone management should be applied more frequently in circumstances where managers have stronger incentive to mislead the markets. Do the authors find more salient tone management under these situations?</b>

Generally yes. The authors studies the following 5 situations:

&nbsp;&nbsp;&nbsp;&nbsp;1) Just meeting/beating thresholds: tone management complements (is positively associated with) beating or meeting earnings benchmarks to affect investor perception. 

&nbsp;&nbsp;&nbsp;&nbsp;2) Future earnings restatements: tone management is positively associated with future earnings restatements.

&nbsp;&nbsp;&nbsp;&nbsp;3) Seasonal equity offerings: managers deploy tone management when announcing earnings prior to a stock issuance to incite greater excitement about the firm so as to obtain a better price for the newly issued shares.

&nbsp;&nbsp;&nbsp;&nbsp;4) M&A: one standard deviation increase in ABTONE is associated with an increase in the frequency of M&A of 10 percent. The results suggest that tone management often accompanies acquisition activities.

&nbsp;&nbsp;&nbsp;&nbsp;5) Stock option grants: managers strategically bias perceptions downward using tone in the earnings press release prior to an option grant to ensure a lower option strike price at the grant date. 

<b>3. Do investors detect/react to tone management?</b>

Market first reacts positively to tone management but reverses in subsequent 2-4 months.


<h5>Empirics</h5>
First, this paper develops the following model to assess normal and abnormal tone based on the tone determinants proposed by Li (2010): 

(1) TONE<sub>jt</sub> = &alpha; + &beta;<sub>0</sub>EARN<sub>jt</sub> + &beta;<sub>1</sub>RET<sub>jt</sub> + &beta;<sub>2</sub>SIZE<sub>jt</sub> + &beta;<sub>3</sub>BTM<sub>jt</sub> + &beta;<sub>4</sub>STD_RET<sub>jt</sub> +&beta;<sub>5</sub>STD_EARN<sub>jt</sub> + &beta;<sub>6</sub>AGE<sub>jt</sub> + &beta;<sub>7</sub>BUSSEG<sub>jt</sub> + &beta;<sub>8</sub>GEOSEG<sub>jt</sub> + &beta;<sub>9</sub>LOSS<sub>jt</sub> + &beta;<sub>10</sub>&Delta;EARN<sub>jt</sub> + &beta;<sub>11</sub>AFE<sub>jt</sub> + &beta;<sub>12</sub>AF<sub>jt</sub> + &epsilon;<sub>jt</sub>

<i>"Normal positive tone, NTONE, is the predicted value of Regression (3). ABTONE , abnormal positive tone, is the residual of Regression (3). By construction, ABTONE is therefore designed to be unrelated to firm fundamentals and business environment such as current market and financial performance, growth prospects, and firm operating risk and complexity."</i> (pp. 1091)

This model has a drawback that it gives very low R-square (4.41%), and according to Chen, Hribar and Melessa (2018), using residuals obtained from low-R-square regressions as dependent/independent variables can be statistically problematic and may lead to incorrect inferences.

Next, this paper deploys the following model to evaluate the relation between abnormal tone and future performance (in terms of future earnings and operating cash flows), which is "<i>crucial for distinguishing between whether abnormal positive tone informs or misinforms investors</i>" (pp. 1085).

(2) EARN<sub>jt+n</sub> = &alpha; + &beta;<sub>0</sub>ABTONE<sub>jt</sub> + &beta;<sub>1</sub>DA<sub>jt</sub> + &beta;<sub>2</sub>EARN<sub>jt</sub> + &beta;<sub>3</sub>SIZE<sub>jt</sub> + &beta;<sub>4</sub>BTM<sub>jt</sub> +&beta;<sub>5</sub>RET<sub>jt</sub> + &beta;<sub>6</sub>STD_RET<sub>jt</sub> + &beta;<sub>7</sub>STD_EARN<sub>jt</sub> + &epsilon;<sub>jt</sub>

(3) CFO<sub>jt+n</sub> = &alpha; + &beta;<sub>0</sub>ABTONE<sub>jt</sub> + &beta;<sub>1</sub>DA<sub>jt</sub> + &beta;<sub>2</sub>EARN<sub>jt</sub> + &beta;<sub>3</sub>SIZE<sub>jt</sub> + &beta;<sub>4</sub>BTM<sub>jt</sub> +&beta;<sub>5</sub>RET<sub>jt</sub> + &beta;<sub>6</sub>STD_RET<sub>jt</sub> + &beta;<sub>7</sub>STD_EARN<sub>jt</sub> + &epsilon;<sub>jt</sub>

I failed to replicate this negative results from model (2) and (3) with 10-Q data, but without controlling for discretionary accruals (DA).

<h5>Strengths</h5>
This paper develops a new model to measure abnormal tone, which is by construction unrelated to firm fundamentals and reflects managerial discretion in communication via earnings press releases. And this paper is quite well structured in terms of writing logic flow, with good transition paragraphs. 

<h5>References</h5>
<li>
<a href="https://www.aaajournals.org/doi/abs/10.2308/accr-50684">Huang, X., Teoh, S. H., & Zhang, Y. (2014). Tone management. The Accounting Review, 89(3), 1083-1113.<a>
<li>
<a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/1475-679X.12195">Chen, W., Hribar, P., & Melessa, S. (2018). Incorrect inferences when using residuals as dependent variables. Journal of Accounting Research, 56(3), 751-796.<a>
<li>
<a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1475-679X.2010.00382.x">Li, F. (2010). The information content of forward‐looking statements in corporate filings—A naïve Bayesian machine learning approach. Journal of Accounting Research, 48(5), 1049-1102.<a>
