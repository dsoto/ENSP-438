## ENSP 438, Lecture 4
### Professor Daniel Soto, Sonoma State University
### Thursday, 23 Jan 2014

## Topics
- Computational Techniques
- Excel calculations
- Computer calculations

## Energy in the news
- [Google buys Nest](http://www.sfgate.com/technology/article/Google-buys-Nest-to-feather-its-data-trackers-5160286.php)
- [$200 Million in funds for energy efficiency](http://www.greentechmedia.com/articles/read/Energy-Efficiency-Is-About-to-Get-a-200M-Jolt-From-Wall-Street)
- [Energy Information Agency Today in Energy](http://www.eia.gov/todayinenergy/)

<!--
two companies created $100 million dollar funds for energy efficiency
they are betting that EE will give better returns than the market
solar city allows you to invest in solar projects at 4.8 percent yield
web stuff
energy gang podcast
today in energy EIA
greentech media
twitter
-->

## Administration
- Intership applications due today
- Friday is add drop deadline
- Feb 1 is Graduation Application deadline
- [Academic Calendar](http://www.sonoma.edu/academics/calendar.html)

## Assigned
- REEPS Chapter 1, Tuesday 28 Jan 2014

## Due Today
- Nothing

## Next time
- Generation Economics
- Levelized cost
- Load duration curves

## IRR
Finding the IRR is the equivalent of asking, here is a loan, what was
the interest rate you got?

- IRR exercise worksheet

<!--
chalkboard: show cash flow stream
if i change the interest rate, what changes?
-->

## IRR of investment and loan rate
- You are taking out a loan to pay for a generation source
- Point spread worksheet

<!--
to make money, which must be greater?  the IRR or the loan interest
rate?
the business opportunities are in the difference
-->

## Irregular cash flow streams
So far we have shown cash flows that have the same payment each period.
NPV and IRR can also be used for cash flows that are different each
period.

<!--
show scripting solutions
-->

<!--
- start with IRR exercise
- also do ipython or scripting demo
- sometimes you know how much the electricity costs and you figure out the
  IRR
- sometimes you know the terms of the loan and you figure out the cost
  of electricity
- explicitly show the cash flow resulting from taking out a loan to pay
  for an investment with a given IRR
- what is the payback of a solar lantern
- avoided kerosene cost
- initial purchase price
-->

## Exercise
A 1kW solar panel costs $1000 and generates 2000 kWh of electricity per year.
If we can sell all of the electricity at $0.15/kWh for 20 years.

- What is the internal rate of return for the system?
- What is the net present value at a discount rate of 10%?

<!--
can i show that the IRR shows the types of financing i can get
can i illustrate the basic point spread mathematics?
remember you are acting like a bank
-->

<!--
what is our strategy for solving this?
everyone try this on your laptops in small groups
-->



## Monthly
For a loan that has monthly payments, we divide the interest rate by the
number of months in a year and use the same formulas.

## Car loan exercise

A 2014 Civic Sedan has a manufacturer suggested retail price (MSRP) of
$18,390.  If you can get a 5 year, 5% loan, what is the monthly payment?


## Solution

$$CRF = \frac {i(1+i)^n}{(1+i)^n-1}$$

$$ CRF = 0.01887 $$

$$ payment = CRF * 18390 = 347.04 $$

## Home loan exercise
A $500K home has a 3% 30 year loan paid monthly.  What is the monthly
payment?

## Solution
We find the CRF for 3% and 30 years, being careful to divide the
interest rate by 12 and multiply the number of years by 12 to get the
correct number of payments.

$$CRF = \frac {i(1+i)^n}{(1+i)^n-1}$$

$$ CRF = 0.004216 $$

$$ pmt = CRF * 500000 = 2108.02 $$

## Announcements

## Next Time
- Generation Economics
- Levelized cost
- Load duration curves


