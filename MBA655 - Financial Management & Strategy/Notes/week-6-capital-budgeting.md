# Week 6

Capital budgeting is fundamental element of the strategic process of the firm, as it is concerned with long-term (i.e. capital) investments the firm should make to increase value (i.e NPV).

Capital budgeting involves three steps:

1. Identifying potential investments
2. Analyzing the set of investment opportunities, isolating those that will create shareholder value, and prioritizing them if necessary
3. Implementing and monitoring the investment projects selected

The most critical elements of capital budgeting are:

- What are the cash flows relevant to the decision being made?
- HOw to systematically analyze those cash flows to determine which cash flow stream would best contribute to the fundamental goal of shareholder wealth maximization?

## Textbook: *"Chapter 7: Capital Budgeting Processes and Techniques"*

To understand what investments to undertake, managers need an analytical tool that:

- easy to apply and easy to explain to non-financial people
- focuses on cash flow (not profit)
- accounts for TVM
- adjusts for differences in risks across projects
- leads to higher firm value in any company (and higher stock prices in public firms)

### Payback Methods

**payback period**: amount of time it takes for a given project's cumulative net cash inflows to recoup the initial investment

- Firms using the payback approach define a maximum acceptable payback period and only accept projects if they are less than the maximum. *Project should pay for itself within a certain period of time.*
  - If more than one investment meets this criteria, they then prioritize those that pay back more quickly.

#### Pros/Cons of Payback

- Pros
  - Simple
  - Intuitive approach according to TVM that quicker cash flows are more valuable than distant.
    - Forecast errors also tend to crop up the longer the payback period.
  - Financing constraints can force firms to focus on repaying debt, etc. Payback is eeasy way to approach.
- Cons
  - Payback period is arbitrary with little connection to maximizing shareholder value.
  - Cash flows before cutoff are discounted at 0%, meaning they have equal weight (which does not account for TVM)
  - Cash flows past cutoff value carry no weight in decision.
  - Rejects risky projects that would carry higher rewards because of a longer payback period.

**discounted payback**: similar to payback approach, but in calculating the payback period, managers first discount the cash flow

- Has similar pros and cons to ordinary payback approach
- Does correct issue of 0% discount rate to all cash flows before cutoff point.

### Net Present Value

**net present value (NPV)**: the sum of a project's cash inflows and outflows, discounted at a rate consistent with the project's risk

<img src="https://render.githubusercontent.com/render/math?math=NPV=CF_0%2b\frac{CF_1}{(1%2br)^1}%2b\frac{CF_2}{(1%2br)^2}%2b\frac{CF_3}{(1%2br)^3}%2b...%2b\frac{CF_N}{(1%2br)^N}">

- CF = cash flow in year t
- r = discount rate
- N = life of project
- CF0 is negative number representing the outlay necessary to get the project started.
- **Invest in the project when the NPV exceeds zero.**

#### NPV and Bonds/Stocks

- Bond prices will always adjust to an equilibrium such that NPV is equal to zero.
- When NPV raises for a stock (i.e the dividend expected is higher than the rate of return), the stock price increases and vice versa.
  - (NPV / number of stocks outstanding) represent the increase in stock price

#### Pros/Cons of NPV

- Pros
  - Solves all issues related to payback and discounted payback
    - Focuses on cash flow
    - Makes appropriate adjustments for TVM
    - The calculation of NPV is less arbitrary than payback cutoff
    - Can account for riskier projects by discounting at higher rates (instead of infinite discounting)
    - Incorporates all cash flows over a project's life (not just early years)
    - Gives an estimate of change in shareholder wealth for a given investment
- Cons
  - Not as intuitive as payback
  - Slightly more difficult to calculate
  - Does not account for "managerial flexibility" to exploit the value of an investment and increase, by expanding it if it goes well and scaling back if it does not reach anticipated cash flow.

**economic value added (EVA)**: variant of NPV, also known as shareholder value added (SVA), based on the idea of *economic profit*

**economic profit**: the amount of profit earns relative to a competitive rate of return

- If a firm earns zero economic profit, accounting profits are positive and is sufficient to satisfy returns by firm's investors.
- If a firm earns positive economic profits, stock price will rise because it is out-earning its cost of capital and investor expectations.
- A firm can have a positive accounting profit but negative economic profit, meaning its not covering the firm's cost of capital.

### Internal Rate of Return

**internal rate of return (IRR)**: analogous to a bond's yield to maturity (YTM); essentially it is the discount rate that causes the net present value of all cash flows to equal zero

To find IRR, one must:

- Specify project's cash flows.
- Use a calculator, spreadsheet, or trial and error to find discount rate that equates NPV to zero.
- Invest only if IRR is greater than *hurdle rate*.

**hurdle rate**: should be set at a level that reflects market returns on investments that are just as risky as the project under consideration

- market-based instead of arbitrary like payback methods
- hurdle rate should be used in NPV analysis

#### Pros/Cons with IRR

- Pros
  - Makes appropriate adjustment for TVM
  - Hurdle rate is determined by the market
  - The result is rate of return, which is easy to grasp by financial and non-financial people
  - Focuses on cash flow
- Cons
  - Has trouble with *mutually exclusive projects* (projects that offer similar IRR in excess of hurdle rate but firm can only invest in one)
    - Highest IRR is not always the right decision.
  - Lending-versus-borrowing problem
    - If project has initial cash outflows and subsequent cash inflows (loan), invest when the project IRR exceeds the hurdle rate.
    - If project has initial cash inflows and subsequent cash outflows (borrowing), invest when the project IRR falls below the hurdle rate
  - If project has a mixture of negative and positive cash flows, there can be more than one solution to IRR equation. One needs to use NPV to make a decision on whether to invest.
    - Maximum number of IRRS can have equals the number of sign changes in the cash flow stream.
  - Doesn't account for scale. Highest IRR does not mean greater creation of wealth.
    - If promise to loan your friend \$1 today in return for \$2 tomorrow, that is 100% IRR.
    - If you promise to loan your friend \$100 today in return for \$150 tomorrow, that is 50% IRR.
    - The second investment is the better decision because it results in the greater monetary payoff.
    - To address the scale problem, use the *incremental project* approach.
      - Calculate the IRR for a hypothetical project with cash flows equal to the difference in cash flows between the large-scale and smaller-scale project. *Essentially breaking the large-scale project into two: smaller-scale and incremental project.
      - If incremental project IRR also exceeds hurdle rate, larger-scale project should be taken.
  - Timing Problem
    - One project can have a higher IRR than another because its payoffs occur earlier in the project than another. The latter project can still have a higher NPV.
    - Use NPV when evaluating projects with very different cash flow patterns.
    - Can also use incremental project approach.
  - Scale and timing problems only exist for mutually exclusive projects. Otherwise invest in both.

### Profitability Index

**profitability index (PI)**: present value of a project's cash inflows divided by the initial cash outflow

<img src="https://render.githubusercontent.com/render/math?math=PI=\frac{\frac{CF_1}{(1%2br)^1}%2b\frac{CF_2}{(1%2br)^2}%2b...%2b\frac{CF_N}{(1%2br)^N}}{CF_0}">

- Invest when PI is greater than 1.0 (NPV of cash inflows exceeds initial cash outflow).
  - If PI > 1, NPV > 0.
- Suffers from the scale problem similar to IRR
  - Can also be solved by the incremental project approach.

**capital rationing**: given a set of attractive investment opportunities, managers must choose a combination of projects that maximizes shareholder wealth

- By ranking projects by PI and investing down the line until all available capital has been exhausted, one will, on aggregate, select a portfolio that generates a higher NPV than any other combination of projects.
