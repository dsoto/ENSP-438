## ENSP 438, Lecture 2
### Professor Daniel Soto, Sonoma State University
### Thursday, 16 Jan 2014

## Topic: Investment Basics
- from a business perspective, renewable energy is an investment
- this investment must be more appealing than other available
  investments

<!--
so why talk about investment?
-->

## Due Today
- Homework 0
- Read REEPS2 Appendix A

## Homework 0
- Turn in papers
- Spreadsheet

## Reading
- Any questions from reading?

## Upcoming Deadlines
- Read Luenberger Ch. 1, Due 21 Jan 2014


<!--
turn in homework
if you don't see your name in the list, ask someone you do see on the
list how they did it
don't share with sotod@sonoma.edu (even though this is totally
reasonable)
share with sotod@seawolf.sonoma.edu
don't send me a copy of the spreadsheet
-->

<!--
how do we determine what an appealing investment is?
- comparison principle
- ideal bank same interest rate for deposits and loans
- bear with me, i'm going to give you a sense of where we are going
without giving you lots of details
-->

<!--
need to begin with a conceptual introduction to the concept of the time
value of money that transitions into a quantitative treatment.  need to
come up with a way to make the equivalence of present value and future
value.
-->

## Real Banks
- Allow you to store money and then pay the account holder interest
- This money is then invested by the bank

## Current rates
- Checking accounts 0.5\%
- Car loan 1.5 - 4.3\%

## Ideal Bank
- Same interest rate for deposits and loans

## How do we arrive at interest rates?
<!--
pause for discussion
-->

## Equivalence principle
- Given a choice between money now and money later, most demand a larger
  value at a later date

## Informal poll
Would you rather have

- $1K now or $500 in a year?
- $1K now or $1K in a year?
- $1K now or $2K in a year?
- $1K now or $5K in a year?
- $1K now or $10K in a year?





<!--
questions for class
- why do you have these preferences
- how do we quantify these preferences?
-->

<!--
any questions from the reading?
-->

<!--
show time series of account balance?
-->

## Discount rate based on equivalence principle
- Banks have preferences that set their loan rates
- People have preferences that dictate their discount rate

## Conceptual calculation example

<!--
- show on board a preference repeated year after year
- based on a one year preference
- assume 10% discount rate
- based on an assumption that this preference is repeated
- show the value needed after two years
- show it isn't linear
- we can do linear superposition
-->

## Discount Rate and Net Present Value
$$\textrm{Present Value (USD)} =
\frac
{\textrm{Future Amount (USD)}}
{(1 + \textrm{Discount Rate})^{\textrm{number of years}} }$$

$$P = \frac {F} {(1 + i)^{n} }$$

<!--
- this basic equation holds for many financial objects
-->

## Cash flow
- We think of discrete events in time where cash is paid or recieved

<!--
- chalk board
-->

## How do we compare investment opportunities?

## Pure finance
- Simple Payback
- Net Present Value (NPV)
- Internal Rate of Return (IRR)

## Additional Metrics for Energy Projects
- Cost of conserved energy
- Cost of avoided carbon

## Energy Economics
![](../figures/econ_06.jpg)

## Exercise
- You will receive a series of payments over the next three years.
- Year 1, $100
- Year 2, $200
- Year 3, $300
- At a discount rate of 10%, what is the present value of these
  payments?

## Solution
Discount each payment by the number of years it is in the future

$$PV = \frac{\$100}{(1+0.1)^1} +
       \frac{\$200}{(1+0.1)^2} +
       \frac{\$300}{(1+0.1)^3}$$
$$ = \$90.91 + \$165.29 + \$225.39 $$
$$ = \$481.59 $$

## Real world computation
- Spreadsheet
- Scripting

<!--
filler
questions
news events
computation on spreadsheet
-->

