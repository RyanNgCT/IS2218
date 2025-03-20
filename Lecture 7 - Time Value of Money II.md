## A. Perpetuities and Annuities
**Present Value of Annuity**
- gives us how much the cash flows are worth in today's dollars
$$
PV_{\text{Annuity}} = C \times \left(\frac{1}{r} - \frac{1}{r(1+r)^t}\right)
$$

**Future Value of Annuity Payment**
- find out how much value that we want to have at a certain point in time (i.e. at the point of retirement)
$$
\begin{aligned}
FV &= [C \times PVAF] \times (1 + r)^t \\\\
&= C \times \frac{(1 + r)^t -1}{r}
\end{aligned}
$$
- recall $PV$ is also given by: $C \times PVAF \implies$ total investments, when converted to present value
- we always assume that the saving is given **at the end of each year**
- *bottom formula equivalent:* if we make a contribution of $\$c$ every month or year, at rate of $r\%$, then we can derive the value of the money at some later time (i.e. retirement)

**Slide 39**
$$
3000 \times \left(\frac{1}{0.08} - \frac{1}{0.08(1+0.08)^4}\right)
$$
**Slide 41**
$$
10000 \times \left(\frac{1}{0.05} - \frac{1}{0.05(1 + 0.05)^{30}}\right) = 153724.51
$$
**Slide 43**
$$
\begin{aligned}
500,000 &= C \times \left(\frac{1}{0.1} - \frac{1}{0.1(1 + 0.1)^{50}}\right) \times (1 + 0.1)^{50} \\
C &= \$429.59 \quad \text{(to 2 d.p.)}
\end{aligned}
$$

## B. Annuities Due
> **Annuity Due** is a level stream of cash flows *starting immediately*
- the downpayment is the first payment
- suppose the instalment is $1,000 per year.
- however, seller want us to pay in advance (each payment is worth $1 + r$ more as it can be used to **generate interest**)
	- we need to invest or pay one year ahead instead
	- so $PV_{\text{new}} = PV_{\text{old}} \times (1+r)$ and $FV = FV \times (1 + r)$
$$
\begin{aligned}
FV &= (429.59 \times \frac{1}{0.1} - \frac{1}{0.1(1+0.1)^{50}}) \times (1+ 0.1)^{50} \times (1+ 0.1)\\
&= 550,000
\end{aligned}
$$

- time duration of loan (number of periods) will dramatically change if we have a change payment
	- pay less $=$ have to pay for a lot longer.
## C. Home Mortgages & Amortization
- Bank will also do simple annuity calculation by putting a rate of interest on the downpayment (downpayment is because unlikely for bank to make the full payment)

- Bank starts to charge interest and so when we pay off the loan, a portion of payment is use to write off the interest value
## D. Effective Interest Rates
- effective annual interest rate is the interest rate that is annualized using compound interest
- The Interest component keeps decreasing year on year
	- higher % of payment amount goes to reduce the principal amount rather than the interest amount

**Effective Annual Interest Rate**
- how we can convert interest rates to an annual rate
- we take into consideration the effect of compounding.
$$
EAR = (1 + MR)^{12} -1
$$
**Annual Percentage Rate** $\to$ lousy
- the interest rate that is annualized using **simple interest** (and not compound interest)
- is quite frankly useless in calculations, but good for understanding
$$
APR = MR \times 12
$$

- $EAR - APR$ provides us with the additional interest as an effect of compounding
## E. Relevant Spreadsheet Formulae
- each of the values are dependent on the four other values
- the brackets mean that the parameters are optional
	- if `type` not specified (defaults to `0`), means at the end of the year (regular annuity)
	- if `type = 1` $\implies$ start of period (annuity due)

- can use excel to do the assignment
	- need to note the formula with the relevant rows
	- can only used to be done without excel (by trail and error)

- if the sign inverts $\implies$ rate lies between $5$ and $10$%

- most of the formulas return a negative number
## F. Inflation
> **Inflation** is the rate at which prices as a whole are increasing
- inflation is done based on the usual things that people buy (the consumer price index)

> The **Nominal Interest Rate** is the rate at which money invested grows
- *"current"* and *nominal* are interchangeable, does not take into account inflation (i.e. "GDP at current")

> The **Real Interest Rate** is the rate at which the purchasing power of an investment increases
- "GDP at *constant* prices" $\implies$ price is fixed, see if GDP is increasing
$$
\begin{aligned}
\textbf{Accurate Formula:}\\

1 + \text{real interest rate} &= \frac{1 + \text{nominal interest rate}}{1 + \text{inflation rate}} \\\\

\textbf{Approximation Formula:} \\
\text{Real int. rate} &\approx \text{nominal int. rate} - \text{inflation rate}
\end{aligned}
$$
### Current vs Real Cash Flow
- for current dollar cash flows (not considering inflation) $\implies$ **nominal interest rate**
- for real dollar cash flows (considering inflation) $\implies$ **real interest rate**

- today's dollars $\iff$ today's prices

---
### Question
$$
\begin{aligned}
\text{a)} \\
PV &= 30,000 \times \left(\frac{1}{0.1} - \frac{1}{0.1(1+0.1)^{30}}\right) \\
&= 282807.43 \quad \text{ (to 2 d.p.)} \\\\
\text{b)} 
\end{aligned}
$$

Part e) we use the future value
Part f) Real is with inflation, nominal is not considering inflation