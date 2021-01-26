---
title: What is the Student Loan Interest Deduction?
description: Details, caveats, and limitations on the student loan interest deduction
weight: 4
---

Quick Summary
---

- You can deduct up to $2,500 when filing taxes if you paid interest to a qualified student loan, alongside other criteria
- You cannot use the deduction if you are filing as: married, filing separately, make over certain income thresholds, or are claimed as a dependent on someone else's tax return
- The $2,500 amount you can deduct also gradually decreases if you hit a certain phase-out MAGI threshold

--------

Do I Qualify?
---
Honestly, you really should refer to the [IRS\'s own student loan interest helper here.(https://www.irs.gov/help/ita/can-i-claim-a-deduction-for-student-loan-interest) But if you want a high level list of qualifications, they are:

- You actually paid interest on a qualified student loan (most of your higher level education loans are qualified)
- You are filing as 'Single' or 'Married, Filing Jointly'. **Married, Filing Separately** does not allow the SLI deduction. I know, weird.
- You or your spouse are not claimed as a dependent on anyone else's tax return
- Your Modified Adjusted Gross Income (MAGI) is less than a certain amount (see below)

If you check the boxes here, it's very likely you qualify to deduct your student loan interest paid.

--------

So.... how much can I deduct?
---

{{<table "table table-striped table-bordered" >}}
  Filing Status | Max You Can Deduct | MAGI Phaseout Threshold | MAGI Phaseout Limit 
  ------------- | ------------- | ------------- | -------------
 Single | $2,500 | $70,000 | $85,000
 Married, Filing Separately | You cannot claim this deduction | You cannot claim this deduction | You cannot claim this deduction
 Married, Filing Jointly | $2,500 | $140,000 | $170,000
{{</table>}}

Put simply, how much you can deduct depends on 3 things:

- How much student loan interest you actually paid
- What your Modified Adjusted Gross Income (MAGI) is
- What your tax filing status is

So let's walk through each individually

How much student loan interest did you pay?
----
This should be obvious, but you cannot deduct more than you paid. So barring all of the caveats above, if you only paid $500 in student loan interest, you would only be able to deduct, at max, $500. Your student loan provider should send out a 1098-E tax form at the start of every tax season to help you with this number.

What is your MAGI?
----
MAGI is one of those acronyms in the tax code that you don't hear about often. This is because the MAGI is rarely used as it's often very similar to your AGI, and really only used for specific corner cases such as how much of your student loan interest you can deduct! Calculating MAGI can be a bit confusing, but that our **[AMT calculator does all the work for you!](/amt-calculator/)**

For the vast majority of people, you can get your MAGI, or get a good rough estimate of your MAGI simply by taking your total income and subtracting **contributions to your traditional 401k** and **HSA Contributions**. If you are self employed, there are a few extra things you can take off as well.

What is your filing status?
----
Your filing status determines the various phaseout thresholds mentioned above in the table. I'll go over the calculations down below. 

The most important thing to note here is - and I am repeating myself a bit - if you are filing as **Married, Filing Separately**, you cannot take the student loan interest deduction! Isn't that crazy? I have no idea why. Ask Uncle Sam.

In addition, the maximum you can deduct on any single tax return is $2,500. That means it doesn't matter if you're filing as single or if you're married, filing jointly and both of you have student loan interest paid, the max you can put down is $2,500.

----

The Calculations
----
To calculate the Student Loan Interest Deduction, follow 3 rules (and refer to the above table):

- If you make below the 'MAGI Phaseout Threshold', you can deduct up to the full $2,500
- If you make above the 'MAGI Phaseout Limit', you cannot deduct anything
- If you make between the MAGI phaseout threshold and the limit, follow the below steps:

1. Subtract the phaseout threshold from your MAGI
2. Divide that number by $15,000 if you are filing as single, and by $30,000 if filing as married. 
3. You should end up with a 'multiplier' between 0 - 1, rounded to **3 digits (i.e. 0.621)**
4. Take the amount you actually paid (up to $2,500) and multiply it by the multiplier calculated
5. Subtract the number you got in step 4 from amount you actually paid (up to $2,500).

Confused? Let's walk through some examples


Example 1: Single, but Over the Phaseout Limit
----
Bob is projected to pay $750 in student loan interest this year. His total income is $120,000. He is a single filer and contributed the max to both his HSA ($3,600) and Traditional 401k ($19,500). That means his MAGI is $96,900. Because his MAGI is above the Phaseout Limit of $85,000 as a single filer, he cannot deduct any of his student loan interest.

Example 2: Married, and Under the Phaseout Threshold
----
Joe and Jane are projected to pay $3,000 in student loan interest this year. Joe is still in school but Jane is in her first year of work and has a total income of $140,000. They are married and are planning to filing jointly. Jane is not offered an HSA at work but she did max out her contributions to her Traditional 401k ($19,500). Joe, being a full time student with no part time job, is not contributing to either a 401k or HSA.

That means their joint MAGI is $120,500. Because their MAGI is below the Phaseout Limit of $140,000 for 'married, filing jointly', they can deduct the max amount! But even though they paid $3,000 in interest, since the cap is at $2,500, they would only enter $2,500 when filing their taxes.

Example 3: Single, and in between Phaseout Threshold and Limit
----
Karen is single and ready to mingle, and is projected to pay $1,000 in student loan interest for the year. She has a total income of $85,000. She's decided to contribute to a Roth 401k instead of a Traditional 401k but does have a High Deductible Health Plan through work which offers a HSA that she maxed out for the year ($3,600). That means her MAGI comes out to $81,400.

Because she is between the Phaseout threshold ($70,000) and limit ($85,000), she has to do some  math to determine how much of the $1,000 that she paid in interest she can actually deduct. Per our steps outlined above, here's how to do the math:

{{<table "table table-striped table-bordered" >}}
  Step by Step | Value
  ------------- | -------------
 Subtract phaseout threshold from her MAGI | 81,450 - 75,000 = 6,450
 Divide that number by 15,000 (as a single filer) to get her multipler | 6,450 / 15,000 = 0.43
 Multiply the interest actually paid by the multiplier determined | 1,000 * 0.43 = 430
 Subtract that number from the interest she actually paid | 1000 - 430 = 570
{{</table>}}

That means when Karen is filing out her tax form, or when her program is calculating it for her, she would only deduct $570!

------------------------------

If you don't want to deal with all of this, and you'd rather have an easy, automated calculator that just factors in your student loan interest when calculating your AMT, **[you can use our handy dandy tool here.](/amt-calculator)**