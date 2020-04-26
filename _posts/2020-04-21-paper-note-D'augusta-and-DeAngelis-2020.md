---
layout: post
title: "Paper note: D'Augusta and DeAngelis 2020 CAR"
date: 2020-04-22
---

This paper hypothesizes and finds evidence that accounting conservatism constrains upward tone management (UTM) in the MD&A. This constraining effect is stronger in situations where managers have higher incentives to manipulate tone upwards (1. just meeting/beating analyst consensus forecast 2. M&A and SEO 3. option grants). The authors conclude that accounting conservatism improves disclosure narratives.

<h5>Theory</h5>
<b>Quantitative (numerical) and Qualitative (narrative) disclosure</b>

In broader sense, this paper intends to analyze the relationship or interaction between properties of quantitative (conditional conservatism) and qualitative (abnormal tone) disclosure. But there is a fundamental problem: under reasonable circumstances, these two types of disclosure should be simultaneously chosen by firms. Whether these two types of disclosure themselves are correlated with each other, and how in case that there is correlation, are not obvious. Do they complement or substitute each other? Do they converge or diverge in contents? There is no consensus in extant literature, and therefore it remains an interesting and open research question. 

This paper differs from my current working project in that my research question focuses solely on one property of narrative disclosure, which is its responsiveness to good v.s. bad news, i.e. whether narrative disclosure <i>per se</i> is conservative or not, and I do not intend to get into the interaction between quantitative and qualitative disclosure, for the moment.  

<b>Mechanism</b>

The theoretical argument of how conservatism constrains UTM is not strong. I could imagine a situation in which a manager choose to be conditionally conservative in numerical disclosure, i.e. requiring higher verification for good news to be recognized in financial statements, and it is likely that she will also requiring higher verification for good news to be talked about in narrative disclosure, because of consistency. Therefore, there could exists an association between high level of conservatism and low level of UTM. But, in this situation, we cannot claim that it is conservatism that reduces UTM because it is the managerial discretion in reporting policy that simultaneously determines the two. However, I cannot think about a pathway through which conditional conservatism <i>per se </i> affects UTM.

The authors indeed provide some explanation about mechanisms, which are quite vague, as they wrote:

"<i>We hypothesize that conservatism makes it harder for managers to opportunistically downplay bad news and magnify good news when discussing current performance.</i>"

"<i>LaFond and Watts (2008) suggest that conservative earnings provide a hard benchmark for other, 'softer' sources of information, such as qualitative disclosure, which increases the credibility and usefulness of these alternative disclosure channels and improves the information environment.</i>"

Just because that conditional conservatism is a good corporate governance mechanism that improves information channels does not make it an effective tool for constraining UTM automatically. The good thing is that the authors were aware of this potential endogeneity and tried some remedies to empirically address the endogeneity concerns. I note down their endogeneity tests in empirics section.  

<h5>Empirics</h5>

<b>Main model</b>

The following model is deployed to access the constraining effect of conservatism on UTM:

(1) ABTONE = &alpha;<sub>0</sub> + &alpha;<sub>1</sub>CONS + &alpha;<sub>2</sub>LEV + &alpha;<sub>3</sub>SPREAD + &alpha;<sub>4</sub>FOLLOW + &alpha;<sub>5</sub>LITRISK +&alpha;<sub>6</sub>INSTOWN + &epsilon;

This model may lead to incorrect inferences because ABTONE is residuals obtained from a first-step regression that has low R-square (17% - 19%), according to Chen, Hribar and Melessa (2018). Several corrections can be applied to obtain an unbiased estimate, and one of them is to include all first-step regressors into second-step regression as controls. 

<b>Endogeneity tests</b>

The authors applied four tests to address endogeneity concerns:

First, controlling for past and future performance proxies and various managerial and corporate governance characteristics, mitigating omitted variable concerns.

Second, using firm-specific or the industry-average lagged value of conservatism and measuring conservatism using accruals as in Dutta, Patatoukas and Wang (2019), suggesting that results are not due to anomalous events in the treatment year or managers' simultaneous choice of conservatism and UTM levels (Garcia Lara et al., 2016). In addition, they performed a time-series analysis between conservatism and UTM and proves Grainger-causality from conservatism to UTM. 

Third, replicating the Basu (1997) asymmetric timeliness model and find similar results.

Finally, and quite interestingly, they use an exogenous shock (passing of SFAS 142) in conservatism (Cedergren et al., 2015) to gauge causality.

<b>Sample</b>

In contrast to prior literature of textual analysis, which usually contains a section about parsing the text document, this paper did not mention any technical details about parsing. And from my experience, extracting 10-K MD&A section from EDGAR raw filings is not an easy task. It is another thing if they used the processed LM dataset (which does not separate MD&A from the rest of texts in 10-X) or WRDS SEC analytics (which provides clean MD&A), but it is unlikely the case since the authors did not mention the above sources. The authors could be more transparent about data collection process.


<h5>Reading list</h5>
This paper applies four proxies in extant literature to measure conditional conservatism:

1. Givoly and Hayn (2000)

2. Khan and Watts (2009) (have replicated in master thesis)

3. Callen, Segal and Hope (2010)

4. Dutta, Patatoukas and Wang (2019) (based on accruals)

Also, it mentions a method to classify forward-looking and backward-looking statements  (Bonsall et al., 2014) and an exogenous shock in conservatism (Cedergren et al., 2015). 


<h5>References</h5>
<li>
<a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/1911-3846.12598">D'Augusta, C., & DeAngelis, D. M. (2020). Does accounting conservatism discipline qualitative disclosure? Evidence from tone management in the MD&A. Contemporary Accounting Research, forthcoming.<a>
<li>
<a href="https://www.aaajournals.org/doi/abs/10.2308/accr.2008.83.2.447">LaFond, R., & Watts, R. L. (2008). The information role of conservatism. The Accounting Review, 83(2), 447-478.<a>
<li>
<a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/1475-679X.12195">Chen, W., Hribar, P., & Melessa, S. (2018). Incorrect inferences when using residuals as dependent variables. Journal of Accounting Research, 56(3), 751-796.<a>
<li>
<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3279895">Dutta, S., Patatoukas, P. N., & Wang, A. Y. (2017). Identifying the Roles of Accounting Accruals in Corporate Financial Reporting. Working paper.<a>
<li>
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0165410197000141">Basu, S. (1997). The conservatism principle and the asymmetric timeliness of earnings1. Journal of accounting and economics, 24(1), 3-37.<a>
<li>
<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2695055">Cedergren, M. C., Lev, B., & Zarowin, P. (2015). SFAS 142, conditional conservatism, and acquisition profitability and risk. Working paper.<a>
<li>
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0165410100000240">Givoly, D., & Hayn, C. (2000). The changing time-series properties of earnings, cash flows and accruals: Has financial reporting become more conservative?. Journal of accounting and economics, 29(3), 287-320.<a>
<li>
<a href="https://www.sciencedirect.com/science/article/abs/pii/S0165410109000445">Khan, M., & Watts, R. L. (2009). Estimation and empirical properties of a firm-year measure of accounting conservatism. Journal of accounting and Economics, 48(2-3), 132-150.<a>
<li>
<a href="https://link.springer.com/article/10.1007/s11142-009-9087-6">Callen, J. L., Segal, D., & Hope, O. K. (2010). The pricing of conservative accounting and the measurement of conservatism at the firm-year level. Review of Accounting Studies, 15(1), 145-178.<a>
<li>
<a href="#">Bonsall, S. B., Bozanic, Z., & Merkley, K. J. (2014). What Do Forward and Backward-Looking Narratives Add to the Informativeness of Earnings Press Releases?. Working paper.<a>
