---
layout: post_prof
title: "Financial instruments"
date: 2015-12-18 11:39:52
categories: [accounting, overview] 
tags: [financial_instruments]
---

Financial instrument is  a contract that gives rise to a financial asset of one entity and a financial liability or equity instrument of an other entity. Examples: sale of goods, raising finance by issuing shares, issuing debentures.

In accounting terms financial instruments are:

- financial assets (investments in shares, bonds and receivables),
- financial liabilities (trade payables and long-term loans),
- equity instruments
- derivatives 

### Equity ###

The distinction between equity and liabilities is important. In an example with a raising finance, one party (who lends money) would account an investment in shares/bonds and the other - in liabilities or equity? If there is an obligation to repay, it's a debt, an interest in the assets of an entity would indicate an equity. The distinction would affect calculation of a gearing ratio and interest paid on debt would come out as an expense in profit and loss, while dividends on shares are appropriation of profit.  Some financial instruments contain both equity and debt elements, such as convertible bonds (see an example below).

Equity instrument - example: 

- The entity has raised finance (received cash) by issuing shares. The entity has no obligation to repay the monies received; rather it has increased the ownership interest in its net assets.As such, the issue of ordinary share capital creates equity instruments. The issue costs are written off against share premium. Nominal value of the shares would be in a share capital account with excess of consideration over a nominal value would go to a share premium account. 

### Financial liabilities ###

 Financial liabilities are measured at amortised cost or at FV (fair value).  

1. Financial liabilities **at cost**:
- effective rate of interest is charged as a finance cost to the statement of profit or loss (not the interest paid in cash) and no revaluation at the reporting date). Each year the liability will increase with the finance cost charged to the statement of profit or loss and decrease by the cash repaid.   

2. Financial liabilities **at FVTPL (fair value through profit & loss)** if they are for trading purposes or the entity chooses so (to reduce/eliminate mismatch where all financial assets and related liabilities are valued at the same base, FVTPL - see IFRS-9):
 - the value is calculated as above, but is then revalued at each reporting date with any gains and losses immediately recognised in the statement of profit or loss. The measurement of the new fair value at the year end will be its market value or, if not known, the present value of the future cash flows, using the current market interest rates. The interest rate used subsequently to calculate the finance cost will be this new current rate until the next revaluation. 

*Example*: 

- 3 year 5% $30,000 loans notes were issued 1/1/14 at nominal value when the effective rate of interest is also 5%. The loan notes will be redeemed at par. The liability is classified at FVTPL. At the end of the first accounting period market interest rates have risen to 6%. What is financial liability at the end of the 1st year? 
- Solution: Financial liability at FV would be PV (present value) of the remaining two years (see the table). 

**FV of liability is total PV of its cashflows for the remaining years**: 

|           	| cashflow  	    | discount fact. 6% 		|  PV      	    |
|-----------	|:----------------:	|-------------------------:	|--------------	|
| Y1        	|  1,500     		| 0.943                		|  	1,415	  	|
| Y2        	| 31,500    		| 0.890                		|  28,035     	|
|           	|          		    |                      		|           	|
| PV at Y0 		|          		    |                      		|  29,450 	    |


Notes:

- in the Y1 is due only interest (£30,000 @5%);
- discount factor at 6% is 0.943 ($${ 1 \over (1+0.06)^1 }$$); 
- in the final 2nd year a principal (£30,000) and an interest (£1,500) is due, PV of it is multiple of 0.89 ($${ 1 \over (1+0.06)^2 }$$);  
- PV as of now, in Y0, is the sum of PV for the two remaining years, which is £29,450. This will be a revalued loan at the year end of 31/12/14 at FV;
- gain of £550 (from the table below) is to P&L.

**Revaluation of loan at FV at y/e**:

|     gain/loss    	|     loan b/f     	|       fin charge  | int pmt          	| loan c/f   | loan at FV   |
|------------------	|-------------------|-------------------|------------------ |------------|--------------|
| Y0	 			|          30,000  	|                  	|                  	|          30,000        	|          29,450  	|             550  	|
| Y1         	|          29,450  	|           1,767  	| -         1,500  	|          29,717        	|          30,288  	| -          571   	|
| Y2         	|          30,288  	|           1,212  	| -       31,500   	|                   -    	|                  	|                  	|

Notes:

- in the Y0 the carrying value of the loan at FV (£29,450) is calculated using discounted factor 6% (market interest rates);
- in Y1 the finance charge at 6% is £1,767 (£29,450 x 6%);
- interest payments (£30,000 x 5%) are at the coupon rate which is 5%;
- at y/e Y1 the carrying value of loan (£29,717) is compared with the value at FV (£30,288). Assuming that the interest rates have fallen to 4%, the loan at FV at y/e Y1 is calculated as £30,288 ($${ £31,500 \over (1+0.04)^1 }$$);
- this has resulted in a loss of £571 taken to P&L


#### Accounting for financial liability: ####

![Financial instruments]({{ site.baseurl }}/assets/images/fin_instr2.gif) 

### Financial assets ###

- As with financial liabilites, financial assets will be accounted for at amortised cost if they meet 2 criteria of business model and cashflow (the same as above). These two tests are designed to ensure that fair value is irrelevant, even if interest rates change, as the primary goal is to passively hold a financial asset to receive an interest and a capital, and not to be sold on.

- however, even if the FA meets criteria as a debt, there is an option to designate to value it at FVTPL. It is done to eliminate an "accounting mismatch" that arises from measuring assets or liabilities and recognising gains or losses on them on different bases (example - financial asset as a debt with a fixed rate interest is then hedged with an interest rate swap).    

#### Accounting for financial assets: ####

![Financial instruments2]({{ site.baseurl }}/assets/images/fin_instr3.gif)


### Impairment ###

 - Impairment reviews are done only on financial assets measured at amortised cost with further proposals of reviewing of expected credit loss (ECL). The entity determines and account for ECL when the asset is originated or acquired rather than waiting for actual default. 

Example:
 
- portfolio of investments in debt instruments £100,000 with coupon 8% and effective rate of return 8%. Over the time it is expected that some loans would fail to result of rate of return would be 3%.
Carrying forward value of the loan would be £100k (do table below/above) with interest income of £8k. Under old rules, incurred loss model, no imparment would be recognised. Under ECL model, the expected credit loss adjustment of £5k (£8k - £3k expected return) would reduce interest income to £3k and carrying loan value to £95k.  

More for impairment - look at [Impairment of financial assets]({% post_url 2015-12-15-impairment-of-financial-assets %})

For more details look at ACCA articles [Financial instruments - part 1 by ACCA] and [Financial instruments - part 2 by ACCA]

[Financial instruments - part 1 by ACCA]: http://www.accaglobal.com/vn/en/student/exam-support-resources/fundamentals-exams-study-resources/f7/technical-articles/what-financial-instrument.html
[Financial instruments - part 2 by ACCA]: http://www.accaglobal.com/vn/en/student/exam-support-resources/fundamentals-exams-study-resources/f7/technical-articles/financial-instrument-part2.html
