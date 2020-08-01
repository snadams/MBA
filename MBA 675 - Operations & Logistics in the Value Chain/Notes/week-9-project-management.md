# Week 9

## Chapter 7: Project Management

**project**: an interrelated set of activities with a definite starting and ending point, which results in a unique outcome for a specific allocation of resources

**project management**: a systemized, phased approach to defining, organizing, planning, monitoring, and controlling projects

* While projects may have been done several times before, differences can arise with each replication.
* Projects are temporary to be completed within a specific time, then the team is disbanded.

**program**: an interdependent set of projects that have a common strategic purpose

### Defining and Organizing Projects

1. Define the scope and objectives of a project.
   * Create a *project objective statement* that states scope, time frame, and allocated resources essential to managing the project.
   * Changes to scope increase costs and delay completion.
   * Be as specific as possible.
2. Select the project manager and team.
   * Roles that a project manager must take on:
     * *Facilitator*. Resolve conflicts to ensure the job has the appropriate resources to complete project.
     * *Communicator*. Report project progress and requests for additional resources. Keep in contact with project team to get best performance.
     * *Decision maker*. Sensitive to the way the team performs best and be ready to make tough decisions.
   * Several characteristics should be considered when selecting the project team.
     * Technical competence
     * Sensitivity
     * Dedication
3. Recognize organizational structure.
   * Each type of organizational infrastructure has different implications for project management.
     * *Functional*.
       * Project is based in a specific functional area (department) presumably the one with the most interest in it.
       * Assistance from personnel in other functional areas must be negotiated by PM.
     * *Pure Project*.
       * Team members work exclusively for the project manager on a particular project.
       * Simple lines of authority, effective for large projects that consist of work for each team member to work full time.
     * *Matrix*.
       * Compromise between functional and pure project structures.
       * Project managers all report to a program manager who coordinates resource and technological needs across functional boundaries.
       * Two bosses, PM and department manager.

### Constructing Project Networks

**work breakdown structure (WBS)**: a statement of work that has to be completed

**activity**: the smallest unit of work effort consuming both time and resources that the project manager can schedule and control

* Care must be taken to include all important activities to avoid project delays.
* Activity ownership avoids confusion in the execution of activities and assigns responsibility for timely completion.

**network diagram**: a visual display, designed to depict the relationships between activities, that consists of nodes (circles) and arcs (arrows)

* Two network planning methods were developed in the 1950s.
  * **program evaluation and review technique (PERT)**: a network planning method for the U.S. Navy's Polaris missile project, which involved 3,000 separate contractors and suppliers
  * **critical path method (CPM)**: a network planning method developed as a means of scheduling maintenance shutdowns at chemical-processing plants
* Often referred to as PERT/CM collectively.
* They offer several benefits to PMs.
  * Considering projects as networks forces project teams to identify and organize the data required and identify the interrelationships between activities.
  * Networks enable project managers to estimate the completion time of projects.
  * Reports based on project networks highlight the activities that are crucial to completing projects on schedule.
  * Network methods enable project managers to analyze the time and cost implications of resource trade-offs.
* **precedence relationship**: a relationship that determines a sequence for undertaking activities, it specifies that one activity cannot start until a preceding activity has been completed
* Estimating activity times become more certain the more times the activity is done.
  * Can also factor in learning curve models if activity times improve with repetition.

### Developing the Project Schedule

**path**: the sequence of activities between a project's start and finish

**critical path**: the sequence of activities between a project's start and finish that takes the longest time to complete

* Determine the completion time of the project
* **earliest finish time (EF)**: an activity's earliest start time plus its estimated duration, t, or EF = ES + t
* **earliest start time (ES)**: the earliest finish time of the immediately preceding activity
* **latest finish time (LF)**: the latest start time of the activity that immediately follows
* **latest start time (LS)**: the latest finish time minus its estimated duration, t, or LS = LF - t
* **activity slack**: the maximum length of time that an activity can be delayed without delaying the entire project, S = LS-ES or S=LF-EF
  * Activities on th critical path have *zero* slack.
* **Gantt chart**: a project schedule, usually created by the PM using computer software, that superimposes project activities, with their precedence relationships and estimated duration time lines, on a time line

### Analyzing Cost-Time Trade-offs

* Always cost-time trade-offs.
  * Hire more workers or run extra shifts to complete earlier.
  * These actions could be advantageous if savings or additional revenues accrue from completing the project early.
* *Total project costs* are the sum of direct costs, indirect costs, and penalty costs.
  * *Direct costs* include labor, materials, and any other costs directly related to project activities.
  * *Indirect costs* include administration, depreciation, financial, and other variable overhead costs that can be avoided by reducing total project time.
  * *Penalty costs* are costs that incurred if project extends beyond some specific date, where as an *incentive* may be provided for early completion.
* The PM may consider *crashing* or expediting some activities to reduce overall project completion time and total project costs.

**normal time (NT)**: the time necessary to complete an activity under normal conditions

**normal cost (NC)**: the activity cost associated with the normal time

**crash time (CT)**: the shortest possible time to complete an activity

**crash cost (CC)**: the activity cost associated with the crash time

<img src="https://render.githubusercontent.com/render/math?math=Cost\ to\ crash\ per\ period=\frac{CC-NC}{NT-CT}">

**minimum-cost schedule**: a schedule determined by starting with the normal time schedule and crashing activities along the critical path, in such a way that the costs of crashing do not exceed the savings in indirect and penalty costs

* The procedure involves the following steps.
  1. Determine the project's critical path(s).
  2. Find the activity or activities on the critical path(s) with the lowest cost of crashing per week.
  3. Reduce the time for this activity until (a) it cannot be further reduced, (b) another path becomes critical, or (c) the increase in direct costs exceed the indirect and penalty cost savings that result from shortening the project. If more than one path is critical, the time for an activity on each path may have to be reduced simultaneously.
  4. Repeat this procedure until the increase in direct costs is larger than the savings generated by shortening the project.

### Assessing and Analyzing Risks

**risk-management plan**: a plan that identifies the key risks to a project's success and prescribes way to circumvent them

* Can be assessed by examining four categories
  * *Strategic fit*.
  * *Service/product attributes*.
    * Could be market, technological, or legal risk if development of new service or product.
  * *Project team capability*.
  * *Operations*.

**optimistic time (a)**: the shortest time in which an activity can be completed, if all goes exceptionally well

**most likely time (m)**: the probable time required to perform an activity

**pessimistic time (p)**: the longest time required to perform an activity

Expected time for each activity

<img src="https://render.githubusercontent.com/render/math?math=t_e=\frac{a%2b4m%2bb}{6}">

Variance of beta distribution for each activity

<img src="https://render.githubusercontent.com/render/math?math=\sigma^2=(\frac{b-a}{6})^2">

Sum of the variances on time distribution

<img src="https://render.githubusercontent.com/render/math?math=(\sigma_p)^2=\sum(Variances\ of\ activities\ on\ the\ critical\ path)">

To analyze probabilities of completing a project by a certain date using the normal distribution, focus on the critical path and use the z-transformation formula:

<img src="https://render.githubusercontent.com/render/math?math=z=\frac{T-T_e}{\sigma_p}">

T = due date for the project

### Monitoring and Controlling Projects

A good tracking system will help the team project accomplish its project goals by collecting information on three topics.

* Open Issues
* Risks
* Schedule Stratus

Project managers can alleviate resource problems with several options.

* *Resource leveling*. The attempt to reduce the peaks and valleys in resources needs by shifting the schedules of conflicting activities within their earliest and latest start dates.
* *Resource allocation*. Assignment of resources to the most important activities.
* *Resource acquisition*. The addition of more of an overloaded resource to main the schedule of an activity.

**closeout**: an activity that includes writing final reports, completing remaining deliverables, and compiling the team's recommendations for improving the project process

## Chapter 15: Supply Chain Sustainability

**sustainability**: a characteristic of processes that are meeting humanity's needs without harming future generations

* It is not easy to achieve sustainability through supply chain. It requires cross-functional and inter-firm cooperation to address challenges such as:
  * *Environmental protection*.
    * Monitoring processes to improve waste elimination methods, reduce pollutions and increase efforts at ecological stewardship.
  * *Productivity improvement*.
    * Increase material conservation, energy efficiency and convert waste into useful by-products.
  * *Risk minimization*.
    * Ensuring that services and products do not pose health or safety hazards to customers.
  * *Innovation*.
    * Supporting their financial, environmental, and social responsibilities while serving the needs of customers with new products.

### The Three Elements of Supply Chain Sustainability

**financial responsibility**: an element of sustainability that addresses the financial needs of the shareholders, employees, customers, business partners, financial institutions, and any other entity that supplies the capital for the production of services or products or relies on the firm for wages or reimbursement

**environmental sustainability**: an element of sustainability that addresses the ecological needs of the planet and the firm's stewardship of the natural resources used in the production of services and products

* Leave as small of an environmental footprint so that future generations can make use of abundant natural resources

**social responsibility**: an element of sustainability that addresses the moral, ethical, and philanthropic expectations that society has of an organization

* **humanitarian logistics**: the process of planning, implementing, and controlling the efficient, cost-effective flow and storage of goods and materials, as well as related information, from the point of origin to the point of consumption for the purpose of alleviating the suffering of vulnerable people

### Reverse Logistics

**reverse logistics**: The process of planning, implementing, and controlling the efficient, cost effective flow of products, materials, and information from the point of consumption back to the point of origin for returns, repair, remanufacture, or recycling

**closed-loop supply chain**: a supply chain that integrates forward logistics with reverse logistics, thereby focusing on the complete chain of operations from the birth to the death of a product

* Firm must establish convenient collection points to receive used goods from the final customer
  * Transport those goods to a returns processor (either done by the manufacturer or outsourced to a supplier)
  * Could be cleaned and refurbished for direct use
  * Could be disassembled and the usable parts and materials, cleaned, tested, and returned to production process

### Energy Efficiency

**carbon footprint**: the total amount of greenhouse gasses produced to support operations, usually expressed in equivalent tons of carbon dioxide

* Managers use three levers to increase the energy efficiency of their operations.
  * *Transportation distance*.
    * Can simply decrease the amount of energy consumed by reducing the distance traveled in moving materials or supplying services.
    * **route planning**: an activity that seeks to find the shortest route to deliver a service or product
      * **shortest route problem**: a problem whose objective is to find the shortest distance between two cities in a network or map
        * Largely solved my GPS systems, Google Maps
      * **traveling salesman problem**: a problem whose objective is to find the shortest possible route that visits each city exactly once and returns to the starting city.
        * Solved with the **nearest neighbor (NN) heuristic**, a technique that creates a route by deciding the next city to visit on the basis of its proximity
          1. Start with the city that is designated as the central location (start city). Place all other cities in an unvisited set.
          2. Choose the city in the unvisited set that is closest to the start city. Remove that city from the unvisited set.
          3. Repeat the procedure with the latest visited city as the start city.
          4. Conclude when all other cities have been visited, and return back to the central location.
          5. Compute the total distance traveled along the selected route.
        * Does not always find the optimal solution but is fast and provides reasonable solutions.
  * *Freight density*.
    * By reducing the volume that product displaces while staying within the weight limits of the conveyance, a firm can use fewer trucks, containers, or rail cars to ship the same number of units

      <img src="https://render.githubusercontent.com/render/math?math=x=\frac{BD}{C}">

      * x = break-even weight
      * A = lower weight bracket
      * B = next highest level weight bracket
      * C = freight rate relative to A
      * D = freight rate relative to B

  * *Transportation mode*.
    * Four major modes of transportation are:
      * Air freight
      * Trucking
      * Shipping by water
      * Rail
    * From an energy perspective, air freight and trucking are less efficient than shipping or rail.
    * Trucks are more flexible and can make deliveries right to the customer's door.
    * **intermodal shipments**: mixing the modes of transportation for a given shipment, such as moving shipping containers or truck trailers on rail cars

### Disaster Relief Supply Chains

**disaster** a serious disruption of the functioning of society, causing widespread human, material, or environmental losses which exceed the ability of the affected people cope using only its own resources

* Disasters can be:
  * Human-related (Epidemic, arson, terrorism)
  * Natural (Earthquake, tsunami, flood)
* Humanitarian supply chains have three main operations related to disaster relief.
  * *Preparation*.
    * Since most disasters happen with little to no warning, it is beneficial for relief agencies to do advance planning to reduce response time.
    * Communication protocols and IT infrastructure can be prepared.
    * Kits of standardized, nonperishable items can be preassembled and stocked, and placed in strategic hubs to reduce the delivery time when the need arises.
  * *Response*.
    * Resources are mobilized and sent to the disaster location as soon as possible.
  * *Recovery*.
    * As time progresses, crisis mode of response gives way to a focus on building the information and logistical infrastructure and rehabilitating the affected population.
* The unpredictability and severity of disasters pose unique challenges to supply chain managers.
  * *Design implications*. Many disaster relief supply chains exist for only short times, which require a new design from scratch that prioritizes speed and agility over everything.
  * *Command and control*. UN usually has leadership in major international disasters. National and local governments must also be recognized and included.
    * They may not allow access to certain agencies based on security or political reasons.
  * *Cargo security*.
    * Can experience theft or extra delays due to numerous police checks/weight checks.
  * *Donor independence*.
    * Each agency sends what they thing is needed which can lead to confusion, congestion, overstocking of some items, and understocking of others.
  * *Change in work flow*.
    * Actual needs should dictate the required volume of supplies (pull-flow). Usually push-flow is how most disasters supply chains start.
  * *Local infrastructure*.
    * Damage to roads, railways, airports can reduce logistical movement of needed supplies.
  * *High employee turnover*.
  * *Poor communication*.
    * Telephone lines disrupted, cell service limited, Internet unreliable.

### Supply Chain Ethics

#### Buyer-Supplier Relationships

**SA8000:2014**: a list of standards covering nine dimensions of ethical workforce management

1. *Child labor*. Employ no underage workers.
2. *Forced or compulsory labor*. Includes prison or debt bondage labor.
3. *Healthy and safety*. Provide a safe and healthy work environment.
4. *Freedom of association and right to collective bargaining*.
5. *Discrimination*.
6. *Disciplinary practices*. No corporal punishment, mental or physical coercion, or verbal abuse.
7. *Working hours*. Require no more than 48 hours per week with at least 1 day off for every 7-day period.
8. *Remuneration*.
9. *Management systems*.

Other unethical activities include:

* Revealing confidential bids and allow certain suppliers to rebid
* Making reciprocal arrangements whereby the firm purchases from a supplier who in turn purchases from the firm
* Exaggerating situations to get better deals
* Using company resources for personal gain