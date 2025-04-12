### Forecast
- Platforms
- Basic Marketing
## A. Future Values and Compound Interest
- Suppose it costs one $500,000 to open new restaurant in Orchard in one year
- From Year 2 to 6, we gain $125,000 per year
	- In total, we gain $5 \times 125,000 = 625,000$
- Is it a good investment or not? How to answer this question?

- Why do we need to measure value?
	- i.e. use a weighing scale to "measure" of quantify the effectiveness of a particular diet
	- need to measure for value (not good just to say how much we are getting, but when as well $\to$ determines the "value" of money as time goes on, which usually decreases)
	- time value of money equation provides a value of money in **different time periods**

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

- Key Idea: we need to convert the value to the same point in time, regardless of whether we discount or compound it
### Future Values
$FV = 100 \times (1 + r)^t$
- $r$ has to correspond to $t$ (should be the same instance where we compute the value $\implies$ same scale and same unit)
- rate $r$ or percentage per annum $\leftrightarrow$ time $t$ is in years  (if convert to month, need to change accordingly)

In terms of Present Value (a.k.a. Principal), it is given by the formula:
$$
FV = PV(1 + r)^t = \text{Principal Amount} \times (1 + r)^t
$$
![future-value-curve](../assets/future-value-curve.png)
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
- present value curve as below tells us how cash flows very distant into the future are almost meaningless in today's currency

> The **Discount Rate** is the interest rate that is used to compute the present values of future cash flows
- Interest Rate and Discount Rate are **interchangeable**
- allows us to "discount" and compute the present value of the investment

$$
\begin{aligned}
\text{PV} &= \frac{\text{Future Value after \(t\) periods}}{(1+ r)^t} \qquad \text{ refer to the above formula.} \\\\

\textbf{Example:} \\
&\text{Given Time } t = 5 \\
\text{PV} &=(\sum) \: \frac{125,000}{(1+ r)^1} + \frac{125,000}{(1+ r)^2} + \ldots + \frac{125,000}{(1+ r)^5}
\end{aligned}
$$
![present-value-curve](../assets/present-value-curve.png)

**Homework: Dividend Discount Model**
- idea of share and market price
- if we hold a stock of a company, we expect some pay outs in the future through the stock
	- stock price is the value of all the **dividends obtained by the shareholder up to infinity**, but *converted to today's cash flow*

- enables us to predict the price of a company's stock based on the theory that current price $= \sum$ all future dividend payments when adjusted with respect to present value

- contrast the fact that market value $\leftarrow$ future expectations

### Discounted Cash Flows
1. Discounted Cash Flow: method of computing present value discounting future cash flows

> The **Discount Factor** is the present value of a $1 future payment

2. Discount Factor*: have a **present value of $1**, used to compute current present value of **any (future) cash flow**
	- people used to have a $DF$ table to computing based on various rates $r$ and length of time $t$, when computers were not prevalent.
	- is quite irrelevant in today's world.
$$
\begin{aligned}
DF &= \frac{\text{1}}{(1+ r)^t}
\end{aligned}
$$

- ⚠️ *Terminology Note:* "same as cash", "zero interest instalment", "free credit"$\implies$ we can pay a few years or some time down the line
	- seller is willing to sell at the same price as the current value in the future

**Example on Slide 13**
- if the time period is not given, assume that the interest is per annum.
- $t$ is $2$ years, unless stated for perpetuity whereby it usually starts at the $1$ year mark.
- basically asking us for the present value.
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
B: (20,000 - 1,000) \times (1 + 0.1)^2 &= 22,990 \\\\
\therefore \:, \text{we choose option A.}
\end{aligned}
$$
##### How many times have you heard of an investment adviser who promises to double your money? Is this really an amazing feat? That depends on how long it will take for your money to double. With enough patience, your funds eventually will double even if they earn only a very modest interest rate. Suppose your investment adviser promises to double your money in 8 years. What interest rate is implicitly being promised?
$$
\begin{aligned}
&\textbf{Advisor promises a FV of \$2 for every \$1 invested today:} \\
&2 = 1 \times (1 + r)^8 \\
&\ln (1 + r)^8 = \ln 2 \\
&e^{\ln (1 + r)} = e^{\frac{\ln 2}{8}} \\
&(1 + r) \approx 1.09050 \\
&r = 0.0905 \quad \text{or 9.05\%}
\end{aligned}
$$
##### You are able to put $1,200 in the bank now, and another $1,400 in 1 year. If you earn an 8% rate of interest, how much will you be able to spend on a computer in 2 years?
- convert each of the investments to future currency ($2$ years down the road), then we add them up together
	- able to add these cash flows since they have been converted to the same time period
$$
\begin{aligned}
1,200 \times (1+0.08)^2 &= 1,399.68 \\
1,400 \times (1+0.08) &= 1,512 \\
1,399.68 + 1,512 &= \$ 2,911.68
\end{aligned}
$$
##### Your auto dealer gives you the choice to pay $15,500 cash now, or make three payments: $8,000 now and $4,000 at the end of the following two years. If your cost of money is 8%, which do you prefer?
$$
\begin{aligned}
PV_1 &= 8,000 \\\\
PV_2 &= \frac{4,000}{(1 + 0.08)^1} = 3,703.70 \quad \text{(to 2 d.p.)} \\\\
PV_3 &= \frac{4,000}{(1 + 0.08)^2} = 3,429.36 \quad \text{(to 2 d.p.)} \\\\
\sum PV &= 8,000 + 3,703.70 + 3,429.36 = \$ 15,133.06 \leq 15,500 \\\\
&\therefore, \: \text{ I will choose the installment payment scheme}
\end{aligned}
$$
##### In order to avoid estate taxes, your rich aunt Frederica will pay you $10,000 per year for 4 years, starting 1 year from now. What is the present value of your benefactor’s planned gifts? The interest rate is 7%. How much will you have 4 years from now if you invest each gift at 7%?
$$
\begin{aligned}
\text{PV} &= \frac{10,000}{(1 + 0.07)^1} + \frac{10,000}{(1 + 0.07)^2} + \frac{10,000}{(1 + 0.07)^3} + \frac{10,000}{(1 + 0.07)^4} \\\\
&= 33872.11 \quad \text{(to 2 d.p.)}\\\\
\text{FV} &= 10,000 \textit{ (stays the same)} + (10,000 \times 1.07^1) + (10,000 \times 1.07^2) + (10,000 \times 1.07^3) \\
&= \boxed{44399.43} \quad \text{(to 2 d.p.)} \\
&= 33872.11 \times (1.07)^4
\end{aligned}
$$
## C. Multiple Cash Flows
- how long has the set amount of cash spent in the bank so far
- need to convert the money obtain at different periods in time to the same period, so that it is measurable and we can do any comparisons as necessary
## D. Level Cash Flows: Perpetuities & Annuities
- Suppose not, that is Vivek is not opening a Holland Village restaurant.
- In both Perpetuities & Annuities, we assume that they payment is $1$ year down the line.

> **Perpetuities** is a stream of level cash payments that *never ends*
- series of cash payments that never stops (we get money perpetually) $\implies$ use the mimic frequent payments
- also known as "till infinity"
- $[0, \infty)$
- is known as a geometric progression (assume the rate $r \gt 0$ or is positive by default)
$$
\begin{aligned}
PV &= \frac{c}{(1+ r)^t} \\\\
PV_{\text{Perpetuity}} &= \frac{C}{r} \qquad \text{ where r } \gt 0 \quad \text{ and } \neq \frac{C}{1 + r} \text{ (Normal Present Value)}
\end{aligned}
$$
##### Example 1a: In order to create an endowment, which pays $100,000 per year forever, how much money must be set aside today in the rate of interest is 10%?
$$
\begin{aligned}
PV_{\text{Perpetuity}} &= \frac{100,000}{0.1} \\\\
&= \$ 1,000,000
\end{aligned}
$$
##### Example 1b) If the first perpetuity payment will not be received until four years from today, how much money needs to be set aside today?
- because we delay the perpetuity by $2$ years, we can save $\approx \$ 250,000$
$$
\begin{aligned}
\text{1 year} &\implies \text{N.A.}\\
\text{2 years} &\implies \text{N.A.}\\
\text{3 years} &\implies 1,000,000 \\
\text{4 years} &\implies 100,000 \\
\text{5 years} &\implies 100,000 \\
\ldots \\
PV_{\text{Perpetuity}} &= \frac{1,000,000}{(1 + 0.1)^3}  = \$ 751,314.80 \quad \text{(to 2 d.p.)}
\end{aligned}
$$

> **Annuity** is the level stream of cash flows at *regular intervals* with a finite maturity
- is *limited or finite*, for $n$ number of years (or months or days etc.)
- a **fixed sum of money** of the same sum is being *received or paid* each year (i.e. equal cash flows over a set time period $t$)
- $[0, n], n \in \mathbb{R}$
- is basically for financial planning
- has no definition of whereby we state when the equal cash flows begin
$$
\begin{aligned}
P_2 - P_1 = PV_{\text{Annuity}} &= \frac{C}{r} - \frac{\frac{C}{r}}{(1 + r)^t} \\\\
&= \frac{C}{r} \left(1 - \frac{1}{(1 + r)^t}\right) \quad \text{where } t = t(P_2) - t(P_1) \text{ and C is the original cash payment}
\end{aligned}
$$

- Note that $\frac{\frac{C}{r}}{(1 + r)^t}$ is known as a **delayed perpetuity**
#### Present Value Annuity Factor
- present value of $1 a year for each of $t$ years.
$$
\text{PVAF} = \left(\frac{1}{r} - \frac{1}{r(1+r)^t}\right) \quad \text{where C = 1 from } PV_{\text{Annuity}}
$$

##### Slide 35 Example: You are purchasing a car. You are scheduled to make 3 annual installments of $8,000 per year. Given a rate of interest of 10%, what is the price you are paying for the car (i.e., what is the PV)?
Method 1
- discount each cash flow to today's currency
- add it up
$$
\frac{8,000}{(1 + 0.1)^1} + \frac{8,000}{(1 + 0.1)^2} + \frac{8,000}{(1 + 0.1)^3} = 19,894.82
$$

Method 2
- apply annuity formula
$$
\begin{aligned}
\text{1 year} &\implies 8,000 \\
\text{2 years} &\implies 8,000\\
\text{3 years} &\implies 8,000 \\\\
PV_{\text{Annuity}} &= 8,000\times\left(\frac{1}{0.1} - \frac{1}{(1 + 0.1)^3}\right) \\
&= 19,894.82
\end{aligned}
$$