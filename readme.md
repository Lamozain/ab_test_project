# Analyze A/B Test Results 
## by Amos Moses Omofaiye (UDACITY DAND SCHOLAR)


## Dataset

> A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these

>For this project, you will be working to understand the results of an A/B test run by an e-commerce website. Your goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

> This dataset has 294478 rows and 5 columns.

#### Research Question
> I  explored based on the folowing broad research question:
<ol> 
    <li>Should the new page be adopted?</li>
</ol>
> For the Regression part, the hypotheses were: 
>
> **$H_{0}$**: **$p_{new}$**  == **$p_{old}$**
>
>**$H_{1}$**: **$p_{new}$**  !=  **$p_{old}$** 
>
> Whereas, for the part II, the hypotheses are: 
>
> **$H_{0}$**: **$p_{new}$**  -  **$p_{old}$**  <=  0
>
>**$H_{1}$**: **$p_{new}$**  -  **$p_{old}$**  >  0
>
> Thus, the two p_values are supposed to be different since the nulls are different.


## Summary of Findings

> Conclusively, these tests have shown that we fail consistently to reject the null hypothesis. This also means that all our explanatory variables have parameters that are no significantly different than zero except the intercept. This trend is consistent for countries, and even the interactions. Moreover, the experiment was run for only 22 days.

> So, the old page should continue to be used pending the time that we sufficiently have enough evidence to the contrary.
