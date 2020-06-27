# Week 4

## Chapter 4: Capacity Planning

**capacity**: the maximum rate of output of a process or system

* Managers are responsible for ensuring that a firm can meet current and future demand

### Planning Long-Term Capacity

Long-term capacity plans cover at least two years in to the future.

Capacity can be expressed in one of two ways:

* *Output measures of capacity*. Best used when applied to individual processes within the firm or when the firm provides a relatively small number of standardized services and products.
  * Car manufacturing plant - number of cars produced per day
  * As the amount of customization and variety in the product mix increases, output-based measures become less useful.
* *Input measures of capacity*. Generally used for low-volume, flexible processes.
  * Custom furniture maker - number of workstations, number of workers
  * Still typically needs to be expressed as an output rate. Demand for furniture gets converted into labor hours and number of employees needed to fill those hours.

**utilization**: the degree to which equipment, space, or the workforce is being used, and is measured as the ratio of average output rate to maximum capacity (expressed as a percent)

<img src="https://render.githubusercontent.com/render/math?math=Utilization=\frac{Average\ output\ rate}{Maximum\ capacity}\times100">

#### Economies of Scales

**economies of scale**: a concept that states that the average unit cost of a service or good can be reduced by increasing its output rate

The four principles that explain why economies of scale can drive costs down as outputs increase are:

1. Fixed costs are spread over more units.
2. Construction costs are reduced.
   * Certain construction expenses don't change whether a plant is large or small, like building permits and rental of building equipment.
3. Costs of purchased materials are cut.
   * Buying and selling in huge quantities usually give retailers a better bargaining position and receive quality discounts.
4. Process advantages are found.
   * May justify the expense of more efficient technology or specialized equipment that can handle larger quantity.

**diseconomies of scale**: occurs when the average cost per unit increases as the facility's size increases

* The point at which the size of the facility becomes a detriment due to complexity, loss of focus and inefficiencies

### Capacity Timing and Sizing Strategies

#### Sizing Capacity Cushions

**capacity cushion**: the amount of reserve capacity a process uses to handle sudden increases in demand or temporary losses of production capacity; it measures the amount by which the average utilization (in terms of total capacity) falls below 100 percent

* 100% - average utilization rate (%)
* It's better to keep a buffer to guard against any uncertainties (i.e. sudden increases in demand or temporary losses of production capacity).
* Cushion varies by industry. The more capital intensive the less of a cushion is preferred. For them, unused capacity costs money.

#### Timing and Sizing Expansion

When do firms adjust capacity levels and by how much?

* *Expansionist strategy* involves large, infrequent jumps in capacity.
  * Minimizes the chance of sales lost to insufficient capacity.
* *Wait-and-see strategy* involves smaller, more frequent jumps in capacity.
  * Lags behind demand. When met with shortfalls, it uses short-term options (i.e overtime, temp workers, contractors, etc.).
  * Reduces the risk of overexpansion based on optimistic forecasts.
  * Tends to maximize short-term profits but erodes market share over the long run.
* *Follow the leader strategy* is in the middle where you only expand when others do.
  * If they were right, so are you and there is no advantage. If you're wrong, it affects everyone.

### Tools for Capacity Planning

Capacity planning requires demand forecasts for an extended period of time, whose accuracy declines as the forecast horizon lengthens.

*Waiting-line models* use probability distributions to provide estimates of average customer wait time, average length of waiting lines, and utilization of the work center.

*Simulation* can identify process bottlenecks and appropriate capacity cushions with random demand patterns and predictable surges in demand during a typical day.

*Decision trees* are valuable for evaluating different capacity expansion alternatives when demand is uncertain and sequential decisions are involved.

## Supplement B: Waiting Lines

**waiting line**: one or more "customers" waiting for service

* Customers can be people or inanimate objects (i.e. machines requiring maintenance, sales orders waiting for shipping, etc.)
* They form because of the variability in demand or service rate.

### Structure of Waiting-Line Problems

1. An input, or **customer population*, that generates potential customers
   * If the potential number of new customers for a service system is affected by the number of customers already in the system, the input source is said to be *finite*.
     * If maintenance crew can only service 10 machines and 10 are being serviced, the waiting for the new machines increases which decreases the likelihood it will enter the system.
   * It is infinite if the number of customers does not affect the rate at which the population generates new customers.
2. A waiting line of customers
   * *Patient* customer enters the system and remains there until served.
   * *Impatient* customer either decides to not enter the system or leaves the system being served.
3. **service facility**: a person (or crew), a machine (or group of machines) or both, necessary to perform the service for the customer
4. **priority rule** a rule that selects the next customer to be served by the service facility
   * Typically first-come, first-served (FCFS)
   * Other include earliest promised due date (EDD) or shortest expected processing time (SPT)
   * **preemptive discipline**: a rule that allows a customer of higher priority to interrupt the service of another customer
     * Occurs in a hospital where life-threatening injuries receive treatment first, regardless of order of arrival

**service system**: the number of lines and the arrangement of the facilities

* Can be either a single line or multiple lines
* In terms of machines being serviced, it isn't a literal line but the order in which it gets serviced.
* **channel**: one or more facilities required to perform a given service
* **phase**: a single step in providing a service
* Types of systems include:
  * *Single-channel, single-phase* system are when all services demanded by a customer can be performed by a single-server facility
    * i.e. a drive-through car wash
  * *Single-channel, multiple-phase* arrangements are used when performed in sequence by more than one facility, yet customer volume or other constraints limit the design to one channel.
    * i.e. McDonald's drive-through (i.e. first facility takes order, second takes money, third provides food)
  * *Multiple-channel, single-phase* arrangements are used when demand is large enough to warrant providing the same service at more than one facility, or when services offered by the facilities are different.
    * Can be done in one or more lines
    * i.e. a bank lobby is one line of customers that can go to multiple stations while a bank drive-through has multiple lines for each station
  * *Multiple-channel, multiple-phase* arrangements occur when one of the first-phase facilities but then requires service from a second-phase facility, and so on.
    * i.e. a laundromat (first phase - washing, second phase - drying)
  * *Mixed* arrangements involve customers who have unique sequences of required services and cannot be described neatly in phases.

#### Arrival Distribution

Customers arrive at service facilities randomly. Can often be described by a Poisson distribution, which specifies the probability that n customers will arrive in T time periods.

<img src="https://render.githubusercontent.com/render/math?math=P_n=\frac{(\lambda\T)^n}{n!}e^{-\lambda\T}">

* P_n = probability of n arrivals in T time periods
* lambda = average number of customer arrivals per period
* e = 2.7183

**interarrival times**: the time between customer arrivals

#### Service Time Distribution

Exponential distribution describes the probability that the next customer will arrive, or that a service to a customer will conclude, in the next T time periods.

<img src="https://render.githubusercontent.com/render/math?math=P(t\le\T)=1-e^{-\mu\T}">

* mu = average number of customers completing service per period
* t = service time of the customer
* T = target service time

### Using Waiting-Line Models to Analyze Operations

Managers should be concerned about the following operating characteristics of a system when determining whether to increase the efficiency:

1. Line length
   * Short lines either mean good customer service or too much capacity.
   * Long lines means low server efficiency or need to increase capacity.
2. Number of customers in system
   * A large number of customers may cause congestion and lead to customer dissatisfaction.
3. Waiting time in line
   * WHen waiting time seems long, the quality of the service may be perceived as poor.
4. Total time in system
   * You don't want customers to spend too much time in the service system.
5. Service facility utilization
   * Management's goal is to usually maintain high utilization and profitability without adversely affecting the other operating characteristics.

#### Single-Server Model

* Otherwise known as *single-channel, single-phase*
* Makes the following assumptions:
  1. The customer population is infinite and all customers are patient.
  2. THe customers arrive according to a Poisson distribution, with a mean arrival rate of lambda.
  3. The service distribution is exponential, with a mean service rate of mu.
  4. The mean service rate exceeds the mean arrival rate.
  5. Customers are served on a first-come, first-served basis.
  6. The length of the waiting line is unlimited.

With these assumptions, we can apply the following formulas to describe the operating characteristics of the system:

##### Average utilization of the system

<img src="https://render.githubusercontent.com/render/math?math=\rho=\frac{\lambda}{\mu}">

##### Probability that *n* customers are in the system

<img src="https://render.githubusercontent.com/render/math?math=P_n=(1-\rho)\rho^n">

##### Probability that zero customers are in the system

<img src="https://render.githubusercontent.com/render/math?math=P_0=1-\rho">

##### Average number of customers in the service system

<img src="https://render.githubusercontent.com/render/math?math=L=\frac{\lambda}{\mu-\lambda}">

##### Average number of customers in the waiting line

<img src="https://render.githubusercontent.com/render/math?math=L_q=\rho\L">

##### Average time spent in the system, including service

<img src="https://render.githubusercontent.com/render/math?math=W=\frac{1}{\mu-\lambda}">

##### Average waiting time in line

<img src="https://render.githubusercontent.com/render/math?math=W_q=\rho\W">

**Little's Law**: relates the number of customers in a waiting-line system to the arrival rate and the waiting time of customers

* Relies on situations where customer population is infinite

  <img src="https://render.githubusercontent.com/render/math?math=L=\lambda\W\ or\ L_q=\lambda\W_q">

* If N is greater than 30 customers, the single-service model with the assumption of an infinite customer population is adequate. Otherwise, the finite-source model is the one to use.

Management can improve a service system by making changes in one or more of the following areas:

1. *Arrival rates*.
   * Can be done through advertising, special promotions, or differential pricing.
2. *Number of service facilities*. An easy way to increase system capacity.
3. *Number of phases*.
   * Management may decide that two sequential service facilities is more efficient than one.
   * Can increase the service rate of each facility.
4. *Number of servers per facility*.
5. *Server efficiency*.
   * Adjusting the capital-to-labor ratio, devising improved work methods, or instituting incentive programs to increase efficiency of servers assigned to a service facility.
6. *Priority rule*.
7. *Line arrangement*.
   * One line or multiple lines?

## Chapter 5: Constraint Management

**constraint**: any factor that limits the performance of a system and restricts its output. In linear programming, a limitation that restricts the permissible choices for the decision variables.

* Usually fit under the following:
  * physical - labor, machine, workstation capacity, or material shortages
  * market - demand is less than capacity
  * managerial - policy, metrics, or mindsets that create constraints that impede work flow

**bottleneck**: a capacity constraint resource (CCR) whose available capacity limits the organization's ability to mee the product volume, product mix, or demand fluctuation required by the marketplace

* A system at least has one constraint or bottleneck. Otherwise, it would only be limited by market demand.
* Relieving a bottleneck in one part of an organization might not have the desired effect unless another bottleneck is also addressed.

### The Theory of Constraints

**theory of constraints (TOC)**: a systematic management approach that focuses on actively managing those constraints that impede a firms progress toward its goal

* TOC methods increase firm's profits more effectively by focusing on making materials flow rapidly through the entire system.
* The chief concept behind TOC is that bottlenecks should be scheduled to maximize their throughput of services or products while adhering to promised completion dates.
* Practical application of TOC involves the following steps:
  1. Identify the system bottleneck(s).
  2. Exploit the bottleneck(s).
      * Create schedules that maximize the throughput of the bottleneck(s).
      * Make sure that only good quality parts are passed on to the bottleneck.
  3. Subordinate all other decisions to Step 2.
      * Non-bottleneck resources should be scheduled to support the schedule of the bottleneck and not produce more than the bottleneck can handle.
  4. Elevate the bottleneck(s).
      * After scheduling improvements in steps 1 through 3 have been exhausted, management should consider increasing capacity of bottleneck.
      * Add a shift or another machine.
  5. Do not let inertia set in.
      * Actions in steps 3 and 4 will cause circumstances to change and may alter loads on other processes, causing constraints to shift. Repeat steps 1-4 to identify and manage new set of constraints.

#### Seven Key Principles of the Theory of Constraints

1. The focus should be on balancing flow, not on balancing capacity.
2. Maximizing the output and efficiency of every resource may not maximize the throughput of the entire system.
3. An hour lost at a bottleneck or a constrained source is an hour lost for the whole system. In contrast, an hour saved at a non-bottleneck resource is a mirage, because it does not make the whole system more productive.
4. Inventory is needed only in front of the bottlenecks to prevent them from sitting idle and in front of assembly and shipping points to protect customer schedules. Building inventories should be avoided.
5. Work should be released into the system only as frequently as the bottlenecks need it. Bottleneck flows should be equal to the market demand. Pacing everything to the slowest resource minimizes inventory and operating expenses.
6. Activating a non-bottleneck resource (using it for the improved efficiency that does not increase throughput) is not the same as utilizing a bottleneck resource (that does lead to increased throughput). Activation of non-bottleneck resources cannot increase throughput, nor promote better performance on financial measures.
7. Every capital investment must be viewed from the perspective of its global impact on overall throughput, inventory and operating expense.

### Managing Bottlenecks in Service Processes

**throughput time**: total elapsed time from the start to the finish of a job or a customer being processed at one or more work centers

* A bottleneck can be identified in a given service or manufacturing process by either:
  * Having the highest total time per unit processed
  * Highest average utilization and total workload
* Variability in workload creates *floating bottlenecks* where the bottleneck changes day to day or hour to hour.
  * Management typically favors lower utilization rates, for greater slack to absorb unexpected surges in demand.
