---
title: How to Calculate the Alternative Minimum Tax
description: Detailed step by step guide on how to calculate the AMT
date: 2021-01-26
weight: 3
tags: ["alternative minimum tax"]
---

{{<disclaimer>}}
{{<direct_to_filing_taxes>}}

------

How to calculate the AMT
----
How the Alternative Minimum Tax is determined can be broken up into a few broad steps:

1. Figure out or estimate your **Total Income**
2. Subtract **total above-the-line deductions or adjustments** to get your **Adjusted Gross Income (AGI)**
3. Subtract **additional AMT eligible deductions**
4. Add in your total **ISO Exercise Spread** to get what we will call **'AMTI for Exemption'**
5. Subtract the **AMT exemption**, if eligible, to get your **Alternative Minimum Taxable Income (AMTI)**
6. Calculate your **Alternative Minimum Tax** based on the tax brackets.

-----------

Step 1: Figure out / Estimate your Total Income
----
If you're on this website in the midst of tax season and you have all of your financial statements ready, I invite you to pull out those statements and follow alongside me.

If, however, you are here to plan for any potential tax you may owe to Uncle Sam, or are here to [plan how many ISO stock options to exercise](/iso-tax-planner) and want to understand the meaning behind the numbers, you will need to do your best estimation of many of the below. I often find using the previous year's tax return can be helpful.

We'll start by assessing your total income, which includes not just your salary and wages, but also things such as capital gain/loss from stock or real estate investments, social security benefits, IRA distributions, pensions, etc. 

Also please note that in regards to capital gains, you will first need to determine if you have a net gain or loss, and if that is a short term or long term capital gain/loss. A net long term gain would be treated differently, and won't be covered here to avoid confusion.

For the purposes of this example, let's assume:

- You are filing as Single
- You have a salaried job that pays $140,000 a year
- And you have also dabbled around with the stock market, but due to an unforseen global pandemic, you've lost or are projected to lose a good $20,000 on the year in short term capital losses. 

You would end up with the below:

{{<table "table table-striped table-bordered" >}}
  Item | Value 
  ------------- | -------------
 Wages, Salaries, Tips | $140,000
 Net Capital Loss | -$20,000
 |
 Total Income | $120,000
{{</table>}}

------------

Step 2: Subtract Adjustments and get your Adjusted Gross Income (AGI)
----
There is a laundry list of possible adjustments or above-the-line deductions that can be found in your 1040 Schedule 1, so we will only use some of the most common.

Let's say you are a few years out of college in your late 20s so you:

- Maxed out your **Traditional 401k** through work
- Are in a High Deductible Health Plan and contributing to an **HSA**,
- Invested in a **Roth IRA**
- And you're still paying off those darn **student loans**

Your updated table might look like the following now:

{{<table "table table-striped table-bordered" >}}
 Item| Value 
  ------------- | -------------
 Total Income | $120,000
 |
 Adjustment: Traditional 401k | $19,500
 Adjustment: HSA | $3,550
 Adjustment: Traditional IRA | 0 (Remember, you're in a Roth IRA)
 Adjustment: Student Loan Interest | $500
 |
 Subtract Total Adjustments | -$23,550
 |
 Adjusted Gross Income (AGI) | $96,950
{{</table>}}
_*Important to note here is that if you contribute to, say, a Traditional 401k through your employer, the actual line item in your W2 for 'Wages, Salaries, Tips' will already reflect those contributions. So for example, if your salary is $140,000 and you are going to contribute the max amount to your 401k in 2021 (19,500), your W2 would report total wages as $120,500._

_For the purposes of this example, we will use your gross income (before 401k contributions)._

------------

Step 3: Subtract AMT eligible deductions
----
There are also quite a few AMT eligible deductions, most of which are not commonly used or known. These include drilling costs, biofuel producer credits, or most commonly, deductions on mortgage interest paid. If you're in a complex situation, I'd always advise consulting with a tax advisor, and for the purposes of this example we will presume that you own a home and you want to subtract your mortgage interest paid this year, which turns out to be $10,000.

As an aside, calculating this could be a pain if you have a jumbo loan, due to the restrictions placed by the Tax Cuts and Jobs act of 2017. You can read more about the [mortgage interest deduction here.](/articles/what-is-the-mortgage-interest-deduction)

{{<table "table table-striped table-bordered" >}}
 Item| Value 
  ------------- | -------------
 Adustable Gross Income (AGI) | $96,950
 |
 Subtract Deduction: Mortgage Interest Paid | -$5,000
 |
 Net | $91,950
{{</table>}}

------------

Step 4: Figure out and add in your ISO Exercise Spread
----
The short definition of the ISO Exercise Spread is the difference between your Strike Price and the Fair Market Value of your company's stock **at time of exercise.** You then take your spread and multiply it by the number of options exercised. You can think of this almost like the 'total discount' you 'received' when exercising your options. Do this for the totality of all grants you exercised from and add them up.

For this example, let's assume you exercised 1,500 options at a strike price of $1.00. At the time of exercising, your company has a Fair Market Value (FMV) of $5.00. And to keep the example simple, you did not sell any of these exercised options this year. Let's calculate the spread.

{{<table "table table-striped table-bordered" >}}
  Line Item | Value 
  ------------- | -------------
 Number of Options Exercised | 1,500
 Fair Market Value | $5.00
 Strike Price | $1.00
 Spread (per option) | $4.00
 |
 Total 'ISO Exercise Spread' | $6,000
 {{</table>}}

 Great! Now let's add that in to the net number you obtained from step 3. This will give us our 'AMTI for Exemption', or the base number we use to determine how much of an exmption we are eligible to take.

{{<table "table table-striped table-bordered" >}}
 Item| Value 
  ------------- | -------------
 Net value from Step 3 | $91,950
 |
 Add ISO Exercise Spread | +6,000
 |
 AMTI for Exemption | $97,950
{{</table>}}

------------

Step 5: (Almost there!) Figure out your AMT Exemption
----

The AMT Exemption is a special exemption you can take as part of the AMT tax system. It is a very straightforward calculation up until you start making in excess of around $523,600 as a single filer, or over around $1,047,200 as married, filing jointly. If you fall into this category, I would advise you to spend a minute or two reading up on the math behind the phaseout thresholds by understanding the [differences between the regular and AMT tax code.](/articles/amt-regular-tax-differences)

This is essentially a large chunk of money you can subtract before calculating the actual AMTI. Think of it like a special type of deduction, that almost everyone can take. The actual exemption in 2021 (filing in 2022) is:

- $73,600 for single filers
- $57,300 for Married, Filing Separately
- $114,600 for Married, Filing Jointly

In our case, because our **AMTI for Exemption** of 97,950 falls safely under that 523,600 phaseout number, we can take the full exemption! Let's calculate our AMTI

{{<table "table table-striped table-bordered" >}}
 Item| Value 
  ------------- | -------------
 'AMTI For Exemption' | $97,950
 |
 Subtract AMT Exemption | -73,600
 |
 Alternative Minimum Taxable Income (AMTI) | $24,350
{{</table>}}

------------

Step 6: Last step! Let's calculate our the Alternative Minimum Tax we (may) owe
----

The AMT tax bracket functions just like the regular income tax brackets, in that it is marginal tax, but much simpler. There are only 2 tax rates. Everything under a certain amount is taxed at one percentage, and everything over is at the other. 

{{<table "table table-striped table-bordered" >}}
  Alternative Minimum Tax Rate | Single Filing: | Married, Filing Separately: | Married, Filing 
  ------------- | ------------- |------------- | -------------
 26% | $0 | $0 | $0
 28% | $199,900 | $99,950 | $199,900
{{</table>}}

Looks like, with an AMTI of only 24,350, we will only need to pay a 26% flat tax on that. Let's summarize all we've done and calculate the final Alternative Minimum Tax.

{{<table "table table-striped table-bordered" >}}
  Line Item | Value 
  ------------- | -------------
 Wages, Salaries, Tips | $140,000
 Net Capital Loss | -$20,000
 |
 Total Income | $120,000
 Subtract Total Adjustments | -$23,550
 |
 Adjusted Gross Income (AGI) | $96,950
 Subtract Eligible Deductions (Mortgage Interest) | -$5,000
 Add in ISO Exercise Spread | +$6,000
 |
 'AMTI For Exemption' | $97,950
 Subtract AMT Exemption | -$73,600
 |
 Alternative Minimum Taxable Income (AMTI) | $24,350
 |
 Alternative Minimum Tax Owed (Taxed @ 26%) | $6,331
 {{</table>}}


-----------

But do you actually owe $6,331 in taxes?
----

As mentioned in our previous articles, in any given tax filing year, you would only pay the larger of either your Regular Federal Income Tax or the Alternative Minimum Tax.

Thus, in order to determine whether you actually need to cough up a few grand to Uncle Sam, you would also need to calculate your Regular Income Tax. We know it's a pain to do the math, so we have built an **[online AMT calculator](/amt-calculator)** so you don't have to!

And if you want to avoid paying AMT altogether, I would highly encourage you to check out our **[ISO tax calculator,](/iso-tax-planner)** which can save you thousands of dollars in tax

--------

<a href="/articles/what_is_the_amt_credit_carryover" class="next_up_link"><h4> >> Next Up: Did you know if you pay additional AMT this year, you may qualify for a tax credit next year? </h4></a>

<!--Step 3: Standard Deduction or Itemized Deduction?
----
The next step is to determine which deduction to take. If you can itemize a number of eligible deductions such that they all add up to more than the standard deduction, you should take the itemized deduction. If you are unsure which to take, that is fine. Our calculator and most tax programs will do the math for you. 

But as a guideline, here are some of the most common things to look out for that might make it more beneficial for you to itemize, each with articles of how they're calculated:

- A large amount of medical and dental expenses paid
- State and local real estate / property taxes (SALT Tax)
- Home Mortgage interest
- Large amounts of gifts to charity

For the purposes of this exercise, we'll assume you recently bought a home and have been paying your mortgage, with a large property tax bill coming up. In addition, you don't expect any huge medical or dental procedures this year.

{{<table "table table-striped table-bordered" >}}
  Deductions | Value 
  ------------- | -------------
 Home Mortgage Interest Paid | $8,000
 SALT (via property tax) | $2,500
 |
 Total Itemized Deduction | $10,500
 Standard Deduction | $12,400
 {{</table>}}

Based on these calculations above, this means you should just take the **standard deduction** to reduce your taxes!  

Step 4: Subtract your deduction from your AGI to get your Regular Taxable Income
----
Remember, this is the 'taxable income' you would use to calculate your Regular Income Tax
{{<table "table table-striped table-bordered" >}}
  Line Item | Value 
  ------------- | -------------
 Total Income | $120,000
 Subtract Total Adjustments | -$23,550
 |
 Adjusted Gross Income (AGI) | $96,950
 Subtract Standard Deduction | -$12,400
 |
 Regular Taxable Income | $84,550
 {{</table>}}

Step 5: Figure out your Alternative Minimum Taxable Income (AMTI)
----

Using the Regular Taxable Income we've determined as the starting point, we need to add in a few things to determine our AMTI. These are commonly **specific ineligible deductions** and your **ISO Exercise Spread**. 

For the first piece, the most common AMT specific ineligible deductions include the below. [You can read more about the differences here](/posts/amt-regular-tax-differences).

- Personal Exemptions (which are currently removed from the tax system altogether)
- The Standard Deduction, if you took it. Else, if you took the itemized deduction:
- Medical Expense Deductions
- State and local real estate / property taxes (SALT)

In our case we, we only took the standard deduction ($12,400) so we only need to worry about that.

The second piece is around your ISO Exercise Spread. The short definition of the ISO Exercise Spread is the difference between your Strike Price and the Fair Market Value of your company's stock at time of exercise. You then take your spread and multiply it by the number of options exercised. You can think of this almost like the 'total discount' you 'received' when exercising your options. -->

<!--There are many other caveats such as whether you sell any of your exercised options in the same calendar year. For more details, check out this article which explains everything in simple terms!-->

<!-- It is important to mention a not so well known fact here:

If you exercise options and sell them in the same **calendar year**, those options/stocks are not eliigble for AMT
----

In other words, you do not include them in the below calculation! But they would, by default, be included in your capital gains line item above (i.e. they would be included in your regular income tax calculation and classified as short term gains, so it's not like you're 'saving' money).

For this example, let's assume you exercised 1,500 options at a strike price of $1.00. At the time of exercising, your company has a Fair Market Value (FMV) of $5.00. And to keep the example simple, you did not sell any of these exercised options this year. Let's calculate the spread.

{{<table "table table-striped table-bordered" >}}
  Line Item | Value 
  ------------- | -------------
 Number of Options Exercised | 1,500
 Fair Market Value | $5.00
 Strike Price | $1.00
 Spread (per option) | $4.00
 |
 Total 'ISO Exercise Spread' | $6,000
 {{</table>}}

Now that we have our 2 additional components, let's calculate the AMTI

{{<table "table table-striped table-bordered" >}}
  Line Item | Value 
  ------------- | -------------
 Total Income | $120,000
 Subtract Total Adjustments | -$23,550
 |
 Adjusted Gross Income (AGI) | $96,950
 Subtract Standard Deduction | -$12,400
 |
 Regular Taxable Income | $84,550
 Add back in Ineligible Deductions (standard deduction, in our case)| +$12,400
 Add in your ISO Exercise Spread | +$6,000
 | 
 Alternative Minimum Taxable Income (AMTI) | $102,950
 {{</table>}}
 
Step 6: Subtract your AMT Exemption to get your Final AMTI
----
The AMT Exemption is a special exemption you can take as part of the AMT tax system. It is a very straightforward calculation up until you start making in excess of around $500,000 as a single filer, or over around $1 million dollars as married, filing jointly. If you fall into this category, I would advise you to spend a minute or two reading up on [the math behind the phaseout thresholds](/posts/amt-regular-tax-differences).

This is essentially a large chunk of money you can subtract from your AMTI before calculating the actual AMT you owe. Think of it like a special type of standard deduction, that almost everyone can take. The exemption is:

- $72,900 for single filers in 2020 and 
- $113,400 for Married, Filing Jointly in 2020
 
 {{<table "table table-striped table-bordered" >}}
  Line Item | Value 
  ------------- | -------------
 Total Income | $120,000
 Subtract Total Adjustments | -$23,550
 |
 Adjusted Gross Income (AGI) | $96,950
 Subtract Standard Deduction | -$12,400
 |
 Regular Taxable Income | $84,550
 Add back in Ineligible Deductions (standard deduction, in our case)| +$12,400
 Add in your ISO Exercise Spread | +$6,000
 | 
 Alternative Minimum Taxable Income (AMTI) | $102,950
 Subtract AMT Exemption | -$72,900
 |
 'Final Alternative Minimum Taxable Income (FAMTI)' | $30,050
 {{</table>}}

Step 7: Calculate your Alternative Minimum Tax
----
We're at the home stretch! All that's left is to calculate your AMT and Regular Income tax, and figure out which is larger.

The AMT tax bracket functions just like the regular income tax brackets, in that it is marginal tax, but much simpler. There are only 2 tax rates. Everything under a certain amount is taxed at one percentage, and everything over is at the other. 

Note, this is one of the few instances where being Married could increase the overall taxes you owe. See below and notice how the 28% tax rate threshold is the same regardless of if you're single or not.

{{<table "table table-striped table-bordered" >}}
  Alternative Minimum Tax Rate | Single Filing, Taxable Income Over | Married, Filing Jointly, Taxable Income Over
  ------------- | ------------- |-------------
 26% | $0 | $0
 28% | $197,900 | $197,900
{{</table>}}

In our case, luckily, our FAMTI of $30,050 is much lower than the thershold of $197,900. This means everything will be taxed at a 26% tax rate, which brings us to our final number - the AMT we actually owe!

{{<table "table table-striped table-bordered" >}}
  Line Item | Value 
  ------------- | -------------
 Total Income | $120,000
 Subtract Total Adjustments | -$23,550
 |
 Adjusted Gross Income (AGI) | $96,950
 Subtract Standard Deduction | -$12,400
 |
 Regular Taxable Income | $84,550
 Add back in Ineligible Deductions (standard deduction, in our case)| +$12,400
 Add in your ISO Exercise Spread | +$6,000
 | 
 Alternative Minimum Taxable Income (AMTI) | $102,950
 Subtract AMT Exemption | -$72,900
 |
 'Final Alternative Minimum Taxable Income (FAMTI)' | $30,050
 |
 Alternative Minimum Tax Owed (Taxed @ 26%) | $7,813
 {{</table>}}

 Step 8: Calculate your Regular Income Tax
----
But do you actually need to pay that **$7,813?**

It all depends if this number is greater than or less than your regular income tax! There are many websites that show you how to calculate the regular income tax you may owe, so I won't go into detail here. Using all the same parameters that we have used throughout this example:

Take my word for it, but your regular income tax would come out to: **$14,391**

 Step 9: So... what do I owe?
----
You would owe: $14,391

Because your AMT comes out to less than your Regular Income Tax, you wouldn't need to worry about your AMT at all! Just pay your regular income tax as you normally would, and you'll be good to go. 

In the event that your AMT is higher than your Regular income tax, your tax program may just register the net difference as an additional line item. For example, if your AMT came out to $12,000 and your Regular Income Tax came out to $10,000, you might just see a line item saying "$2,000 for AMT" such that your total tax owed comes out to $12,000. 

I should also mention that all of this is still within the realm of **FEDERAL** income taxes, including FICA (SSI and Medicare taxes). None of this takes into account state taxes, which is a whole 'nother ball game. Luckily, only a few states have AMT at the state level, and we'll have an article up soon detailing this.

This exercise is most useful if you want to plan for how much of your ISO to exercise this year, such that this exact scenario arises. This way, you could exercise the maximum amount of options early enough, but not exercise too many to trigger having to pay AMT. You could do the math yourself on Excel, but if you don't feel like doing it manually, [we've luckily built out a planning tool here](/iso-exercise-planner) -->

------
