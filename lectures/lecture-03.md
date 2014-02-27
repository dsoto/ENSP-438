## ENSP 438, Lecture 3
### Professor Daniel Soto, Sonoma State University
### Tuesday, 21 Jan 2014

## Topics
- Investment basics
- Example calculations

## Assigned
- Read REEPS2 Chapter 1, Tuesday 28 Jan 2014

<!--
the first section is review of material from 330
focus on the finance section
-->

## Due
- Luenberger reading

<!--
questions from reading?
simple interest
compound interest
effective interest rate
nominal rate
discounting
discount factor
don't worry about continuous compounding
equivalent streams
don't worry about IRR math, we will not solve the polynomial
net present value = present value of benefits and present value of the costs
IRR presumes multiple investment opportunities
depreciation
real interest rate corrects for inflation
-->

## Review

## Review
- equivalence, present value, future value
- discount rate, interest rate
- cash flows
- investment comparisons

<!--
- what did we talk about in the last class?
- why is it important?
- any questions?
-->

## Present Value

Single payment
$$ PV = \frac{C}{(1+i)^n} $$

Stream of payments
$$ PV = C_0 +
        \frac{C_1}{1+i} +
        \frac{C_2}{(1+i)^2} +
        \dots +
        \frac{C_N}{(1+i)^N}$$

Compact notation
$$ PV = \sum_{n=0}^{N} \frac{C_n}{(1+i)^n}$$


## Perpetuity
- What is the present value of an infinite series of payments?
- The present value is finite (pmt/interest rate)

<!--
guesses?
perpetuity is a type of annuity
it is finite
remember, in the limit of large N, the present value is zero
-->

## Loans

The present value calculation lets us calculate loan payments.

<!--
- take out your laptops and create a spreadsheet in the tool of your
  choice
-->

## Capital Recovery Factor

Suppose we make a loan.  We want to know what the yearly payment is so
that the present value of all payments is equal to the loan amount.

<!--
- Show how we arrive at the capital recovery factor
- (written notes)
- show the significance of the CRF
-->


## Capital Recovery Factor

$$CRF = \frac {i(1+i)^n}{(1+i)^n-1}$$


<!--
show that the formula for CRF matches an empirically derived CRF in a
spreadsheet
as a class exercise
-->


## Exercise
- What is the annual payment for a $10K loan with an interest rate of 5%
  paid over a period of 7 years?
- Solve on spreadsheet
- Solve using formula

## Solution
![](../figures/capital_recovery_factor.jpg)

<!--
calculate a car loan
does it match what you expect?
-->

## Spreadsheet functions
- NPV(rate, payments) net present value
- IRR(payments, guess) internal rate of return
- PMT(rate, number of payments, principal)


## Exercise
A 1kW solar panel costs $1000 and generates 2000 kWh of electricity per year.
If we can sell all of the electricity at $0.15/kWh for 20 years, what is
the net present value for the system?

## Solution


## Spreadsheet demonstration

<!--
set up cells for inputs
set up cash flow columns
show net present value manually
show sum function
show NPV function
-->

<!--
demo in spreadsheet
demo in ipython
solve this in a spreadsheet
solve this in a closed form equation
-->
