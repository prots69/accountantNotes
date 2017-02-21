---
layout: post_prof
title:  "Impairment of financial assets - overview"
date:   2015-12-15 11:39:52
categories: [accounting, overview]
tags: [financial_instruments]
---

Impairment reviews are only required in respect of financial assets that are classified as amortised cost – for example, loans, debt securities and trade receivables under IAS 39.

### Incurred loss approach ###

IAS 39 states that a financial asset is impaired and impairment losses are incurred only if a loss event has occurred and this loss event had a reliably measurable impact on the future cash flows. This is often called the 'incurred loss' approach. This approach has led to overstatement of both assets and profits.

### Expected loss approach (Expected Credit Loss, ECL) ###

The IASB has proposed a model where credit losses on financial assets are no longer recognised when incurred but rather, are recognised on the basis of [expected credit losses]({% post_url 2015-11-11-impairment-fa-detailed %}). This is often called the 'expected loss' approach.

- This approach was adopted by the current Exposure Draft (ED) issued by the IASB in March 2013. 
It applies to:
+ financial assets measured at amortised cost and at FVTOCI (fair value through other comprehensive income), this includes debt instruments such as loans, debt securities and trade receivables;
+ irrevocable loan commitments
+ financial guarantee contracts that are not accounted for at FVTPL (fair value through profit or loss) under IFRS 9
+ lease receivables

> Expected credit losses are the present value of the expected cash flow shortfalls over the remaining life of the asset. It is the weighted average credit losses with the probability of default as the weighting.

The estimation of expected credit losses should consider past events, current conditions and reasonable and supportable forecasts. It is however open to the criticism that allowing the judgment of what future losses might be incurred it will allow some companies to engage in profit smoothing.

 Example: Consider the example from our other post [Financial instrument]({% post_url 2015-12-18-financial-instrument %}/#impairment) and calculate ECL on a life time basis. 

- ECL over lifetime means the PV of the shortfalls over the remaining life of the asset. In our previous example - shortfall of £5000 a year and effective rate of return is 8%. The discount rate used should be between the risk-free rate and the effective rate of the asset. 

In the absence of further information, the effective rate of 8% has been used in the calculations below:

	
|        	| shortfall         	| rate of ret 8%         	| PV                	|
|--------	|-------------------	|------------------------	|-------------------	|
| Y1     	|            5,000  	|                 0.926  	|            4,630  	|
| Y2     	|            5,000  	|                 0.857  	|            4,285  	|
| total: 	|                   	|                        	|            8,915      |


Thus, the expected credit loss is £8926. This is recognised as the impairment loss thus creating an expense to be charged to profit or loss and offset against the carrying value of the financial asset on the statement of financial position.

### 2 stage approach review to credit losses (ECL over 12 months / lifetime) ###

- Review of credit losses:
+ on initial recognition of a FA an impairment loss is based on the 12-months' expected credit losses,
+ on subsequent reviews:
	- for FA where credit quality has not changed since initial recognition - on 12 months basis,
	("investment grade" investments are low risks would be in that category)
	- for FA where credit quality has deteriorated - ECL would be estimated over lifetime (resumption - if contractual cashflows are 30 days overdue).
	If credit quality subsequently improves, then ECL could revert to 12 month period.

#### Subsequent reviews of credit risks: ####
 
- At each reporting date - assessment on ECL to be made:
if risk - low or no significant increase - 

### Simplified approach for trade receivables ###

No credit loss allowance is recognised on initial recognition. 
The subsequent impairment loss will be the present value of the expected cash flow shortfalls over the remaining life of the receivables.

Check out the more detailed info on [ECL on lifetime basis][impairment-ACCA].

[impairment-ACCA]:  http://www.accaglobal.com/vn/en/student/exam-support-resources/professional-exams-study-resources/p2/technical-articles/impairment-of-financial-assets.html
