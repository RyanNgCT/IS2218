### Forecast
- Platforms
- Basic Marketing
## A. Future Values and Compound Interest
- Suppose it costs one $500,000 to open new restaurant in Orchard in one year
- From Year 2 to 6, we gain $125,000 per year
	- In total, we gain $5 \times 125,000 = 625,000$
- Is it a good investment or not? How to answer this question?

- We compare this to putting the $500,000 sum in the bank or a fixed deposit
	- need to evaluate **whether this a a good investment** (return for restaurant versus return of safer options)
		- versus opportunity cost of higher or lower gains, depending on where we put the money (usually elsewhere)
	- Formula for calculation is usually: $500,000 \times (1 + \text{Interest Rate})^{5 \text{ years}}$
	- Have to ensure that these investments are made at the **same time** $\implies$ not an apples to apples comparison
		- have to apply the current financial context to the future rate (need to convert future cash flows from the initial investment to today's money or value for an accurate comparison)
		- can only compare stuff at the same point in time (since the valuation fluctuates)

> **Future Value** is the amount to which an investment will grow after earning interest
- money which we get at a future point in time.

> **Compound Interest** is interest earned on top of interest
- potential exponential growth
- is what the world works on (generally follows this principle, even the course is compound interest unless stated otherwise)

- *Formula:* $\text{Interest Earned per year} = \textbf{Prior Year Balance} \times 0.06$
	- the interest values actually (and usually) increases as time passes
- is the "eighth wonder of the world"
	- whatever the outcome (or value) of compounding has almost **no reflection of or relation to the original amount** or value invested
	- ETFs are accumulative in nature: the dividend for the shareholder is "put back"
	- the amount of interest in a sense *depends on the previous time period* as well, usually has no relation to the original amount, unlike in simple interest

> **Simple interest** is the interest earned on the (original) principal amount
- has linear growth (in nature)
- interest is a constant number

### Future Values
$FV = 100 \times (1 + r)^t$
- $r$ has to correspond to $t$ (should be the same instance where we compute the value $\implies$ same scale and same unit)
- rate $r$ or percentage per annum $\leftrightarrow$ time $t$ is in years  (if convert to month, need to change accordingly)

In terms of Present Value, it is given by the formula:
$$
FV = PV(1 + r)^t
$$
**Slide 7**
- the red line of the graph is the baseline principal sum

**Slide 8**
$$
\begin{aligned}
18 \text{ months} &= 1.5 \text{ years} \\
2x &= x(1 + r)^{1.5} \\
x &\to 0.59 \text{ or 59\%} (2,250)\\\
2,250(1 + g)^{45} &= 7.2 \times 10^9 \\\\
\textbf{Solve for g.} \\
(1 + g)^{45} &= 3.2 \times 10^6 \\
\ln (1 + g)^{45} &= \ln 3.2 \times 10^6 \\
\ln (1 + g) &= \frac{\ln 3.2 \times 10^6}{45} \\
e^{\ln (1 + g)} &= e^{\frac{\ln 3.2 \times 10^6}{45}} \\
1 + g &\approx 1.394950 \\
\therefore g &= 0.395 \qquad\text{ (to 3 d.p.), or 39.5\%}
\end{aligned}
$$

## B. Present Values
> **Present Value** is the value today of a *future cash flow*
- allows us to compare future cash flows (just need to divide by the factor of $(1+r)^t$)

> The **Discount Rate** is the interest rate that is used to compute the present values of future cash flows
- Interest Rate and Discount Rate are **interchangeable**
- allows us to "discount" and compute the present value of the investment

$$
\begin{aligned}
PV &= \frac{\text{Future Value after \(t\) periods}}{(1+ r)^t} \qquad \text{ refer to the above formula.} \\\\

\textbf{Example:} \\
&\text{Given Time } t = 5 \\
\text{PV} &=\frac{125,000}{(1+ r)^1} + \frac{125,000}{(1+ r)^2} + \ldots + \frac{125,000}{(1+ r)^5}
\end{aligned}
$$
**Homework: Dividend Discount Model**
- idea of share and market price
- if we hold a stock of a company, we expect some pay outs in the future through the stock
	- stock price is the value of all the dividends up to infinity, but *converted to today's cash flow*

- enables us to predict the price of a company's stock based on the theory that current price $= \sum$ all future dividend payments when adjusted with respect to present value

- contrast the fact that market value $\leftarrow$ future expectations

### Discounted Cash Flows
1. Discounted Cash Flow: method of computing present value discounting future cash flows

> The **Discount Factor** is the present value of a $1 future payment

2. Discount Factor: have a **present value of $1**, used to compute current present value of any cash flow
	- people used to have a $DF$ table to computing based on various rates $r$ and length of time $t$, when computers were not prevalent.
	- is quite irrelevant in today's world.
$$
\begin{aligned}
DF &= \frac{\text{1}}{(1+ r)^t}
\end{aligned}
$$

- ⚠️ *Terminology Note:* "same as cash", "zero interest instalment", "free credit"$\implies$ we can pay a few years or some time down the line

**Example on Slide 13**
- if the time period is not given, assume that the interest is per annum.
- $t$ is $2$ years, unless stated for perpetuity whereby it usually starts at the $1$ year mark.
$$
\text{PV} = \frac{3,000}{(1 + 0.08)^2}
$$

**Tips for the example questions**
- see how much we have $x$ years down the line (at each of the point) $\implies$ use $PV$ formula
##### Kangaroo Autos is offering free credit on a $20,000 car. You pay $8,000 up front and then the balance at the end of 2 years. Turtle Motors next door does not offer free credit but will give you $1,000 off the list price. If the interest rate is 10%, which company is offering the better deal?
- convert percentage to a decimal before working out.
$$
\begin{aligned}
A: (20,000 - 8,000) &= 12,000 \\ 
\frac{12,000}{(1.1)^2} &\approx 9917 \\
9,917 + 8,000 &= 17,917 \\\\
B: (20,000 - 1,000) \times (1 + 0.1)^2 &= 22,990
\end{aligned}
$$

##### How many times have you heard of an investment adviser who promises to double your money? Is this really an amazing feat? That depends on how long it will take for your money to double. With enough patience, your funds eventually will double even if they earn only a very modest interest rate. Suppose your investment adviser promises to double your money in 8 years. What interest rate is implicitly being promised?

## C. Multiple Cash Flows
- how long has the set amount of cash spent in the bank so far
- need to convert the money obtain at different periods in time to the same period, so that it is measurable and we can do any comparisons as necessary

## D. Level Cash Flows: Perpetuities & Annuities
- Suppose not, that is Vivek is not opening a Holland Village restaurant.
- In both Perpetuities & Annuities, we assume that they payment is $1$ year down the line.

> **Perpetuities** is a stream of level cash payments that *never ends*
- series of cash payments that never stops
- also known as "till infinity"
- $[0, \infty)$
- is known as a geometric progression (assume $r \geq 0$ by default)
$$
\begin{aligned}
PV &= \frac{c}{(1+ r)^t} \\\\
PV_{\text{Perpetuity}} &= \frac{C}{r} \qquad \text{ where r } \geq 0
\end{aligned}
$$

> **Annuity** is the level stream of cash flows at regular intervals with a finite maturity
- is *limited*, for $n$ number of years (or months or days etc.)
- a fixed sum of money is being received or paid each year
- $[0, n], n \in \mathbb{R}$
- is basically for financial planning
$$
\begin{aligned}
P_2 - P_1 = PV_{\text{Annuity}} &= \frac{C}{r} - \frac{\frac{C}{r}}{(1 + r)^t} \\
&= \frac{C}{r} \left(1 - \frac{1}{(1 + r)^t}\right) \qquad \text{where } t = t(P_2) - t(P_1)
\end{aligned}
$$
#### Present Value Annuity Factor
- present value of $1 a year for each of $t$ years.

**Slide 35 Example**
Method 1
- discount each cash flow to today's currency
- add it up

Method 2
- apply annuity formula
