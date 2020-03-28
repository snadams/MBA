# Week 3

## Textbook: *"Chapter 3: The Time Value of Money"*

*future value* - value of an investment made today will be worth at a specific future date

*present value* - value today of a cash flow to be received at a specific date in the future

*time value of money* - how to compute the future value of a lump sum invested today of a cash flow to be received in the future

- assumes investors can earn the same returns as on investments of equal risk

### Future Value of a Lump Sum Received Today

- Found by either applying simple interest (*interest only paid on principal*) or compound interest (*interest paid on both principal and interest in previous periods*)
- Done through financial calculator or spreadsheet

    <img src="https://render.githubusercontent.com/render/math?math=FV=PV\times(1%2br)^n">
  
  - FV = future value of an investment
  - PV = present value of an investment (the lump sum)
  - r = interest rate per period (typically 1 year)
  - n = number of periods (typically years) that the lump sum is invested

### Present Value of a Lump Sum

*discounting* - helps determine the present value of a future amount, assuming an opportunity to earn a given return (r) on the money

<img src="https://render.githubusercontent.com/render/math?math=PV=FV\times\frac{1}{(1%2br)^n}">

### Future Value of Cash Flow Streams

- Two types of cash flow streams possible:
  - *mixed stream* - series of unequal payments reflecting no particular pattern
  - *annuity* - a stream of equal periodic cash flows over a stated period of time
- Either can represent inflows of returns earned on investments or outflows of funds invested to earn future returns

    <img src="https://render.githubusercontent.com/render/math?math=FV=\sum_{t=1}^{n} CF_t\times(1%2br)^n">

  - CF = cash flow at end of year *t*
- Two types of annuities include:
  - **ordinary annuity**: an annuity for which the payments occur *at the end of the period*

    <img src="https://render.githubusercontent.com/render/math?math=FV=PMT\times\frac{(1%2br)^n-1}{r}">

  - **annuity due**: an annuity for which the payments occur *at the beginning of each period*

    <img src="https://render.githubusercontent.com/render/math?math=FV=PMT\times\frac{(1%2br)^n-1}{r}\times(1%2br)">

  - Future value of an annuity due is always greater than the future value of an otherwise identical ordinary annuity.
    - Because you receive first cash flow today, you get a longer time to earn interest

### Present Value of Cash Flow Streams

- Present value of a mixed stream

    <img src="https://render.githubusercontent.com/render/math?math=FV=\sum_{t=1}^{n} CF_t\times\frac{1}{(1%2br)^n}">

- Present value of an ordinary annuity

    <img src="https://render.githubusercontent.com/render/math?math=PV=\frac{PMT}{r}\times(1-\frac{1}{(1%2br)^n})">

- Present value of an annuity due

    <img src="https://render.githubusercontent.com/render/math?math=PV=\frac{PMT}{r}\times[1-\frac{1}{(1%2br)^n}]\times(1%2br)">

- **perpetuity**: an annuity with an infinite life, will pay the same amount at the end of every year forever

    <img src="https://render.githubusercontent.com/render/math?math=FV=PMT\times\sum_{t=1}^{\infty}\frac{1}{(1%2br)^t}=\frac{PMT}{r}">

- Present value of a growing perpetuity

    <img src="https://render.githubusercontent.com/render/math?math=PV=\frac{CF_1}{r-g} (r &gt; g)">

  - CF = first year's cash flow that occurs one year from today
  - g = constant annual rate of growth (from now until end of time)
    - Determine the cash flow for any specific future year (*t*) by using the following formula:

        <img src="https://render.githubusercontent.com/render/math?math=CF_t=CF_1\times(1%2bg)^{t-1}">

### Special Applications of Time Value

**semiannual compounding**: involves two compounding periods of interest within a year

**quarterly compounding**: involves four compounding periods of interest within a year

- The more frequently interest compounds, the greater the amount of money that accumulates.

    <img src="https://render.githubusercontent.com/render/math?math=FV=PV\times(1%2b\frac{r}{m})^{m \times n}">

  - m = number of times compounded (if 1, similar to this future value of a lump sum [equation](#future-value-of-a-lump-sum-received-today))

**continuous compounding**: interest compounded daily, hourly, or by second.

<img src="https://render.githubusercontent.com/render/math?math=FV=PV\times e^{r \times n}">

**stated annual rate**: contracted annual rate charged by a lender or promised by a borrower

- also known as annual percentage rate (APR)

**effective annual rate (EAR)**: annual rate of interest actually paid, or *true annual return*

- also known as annual percentage yield (APY)
- reflects the impact of compounding frequency

    <img src="https://render.githubusercontent.com/render/math?math=EAR=(1%2b\frac{r}{m})^m-1">

  - continuous frequency

    <img src="https://render.githubusercontent.com/render/math?math=EAR=e^r-1">

**loan amortization**: refers to a borrower making equal periodic payments over time to fully repay a loan
