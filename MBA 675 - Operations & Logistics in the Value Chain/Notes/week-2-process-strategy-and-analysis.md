# Week 2

## Chapter 2: Process Strategy and Analysis

### Process Improvement

**process improvement**: the systematic study of the activities and flows of each process to improve it

* Purpose is "learn the numbers", understand the process, and dig out the details. Only once a process is understood, can it be improved.

## Chapter 8: Forecasting

**forecast**: a prediction of future events used for planning purposes

* Forecasting demand requires uncovering the underlying patters from available information

**time series**: the repeated observations of demand for a service or product in their order of occurrence

* There are five basic patters of demand time series:
  1. *Horizontal*. Fluctuation of data around a constant mean.
  2. *Trend*. Systematic increase or decrease in the mean of the series over time.
  3. *Seasonal*. A repeatable pattern of increases or decreases in demand, depending on the day, week, month, or season.
  4. *Cyclical*. The less predictable gradual increases or decreases in demand over longer period of time (years or decades).
  5. *Random*. The unforecastable variation in demand.

* Random variation is the aspect of demand that makes every forecast ultimately inaccurate.

### Demand Management

**Demand management**: the process of changing demand patterns using one or more demand options

Here are the options that are used for managing demand:

* **complementary products**: services or products that have similar resource requirements but different demand cycles
  * Used to even out load on resources
  * i.e. a park can counterbalance seasonal staffing requirements by offering ice skating in the winter and basketball in the summer
* promotional pricing
  * rebates, price reductions for winter clothing in the summer, "two-for-one"
* pre-scheduled appointments
  * This allows demand to be leveled to not exceed supply.
  * Used by doctors, dentists, lawyers, and repair shops
* reservations
  * used when customer actually occupies or uses facilities associated with the service, i.e. hotel rooms, airline seats, concert seats
* **revenue management**: varying price at the right time for different customer segments to maximize revenues yielded by existing supply capacity
  * Works best if customers can be segmented
  * Airlines, hotels, cruise lines use this principle frequently.
* **backlog**: an accumulation of customer orders that a manufacturer has promised for delivery at some future date
  * Primarily used by firms who make customized products
  * Reduces the uncertainty of future production requirements and used to level demand
* **backorder**: a customer order that cannot be filled when promised or demanded but is filled later
  * Less than desired
  * Adds to the next period's demand requirement
* **stockout**: an order that cannot be satisfied, resulting in a loss of sale
  * Worst case scenario

### Key Decisions on Making Forecasts

**aggregation**: the act of clustering several similar services or products so that forecasts and plans can be made for whole families

* Typically done with service or product units instead of dollars. They can be then translated to dollars by multiplying them by unit price.

Two general types of forecasting techniques are:

* **judgment methods**: a forecasting method that translates the opinions of managers, expert opinions, consumer surveys, and salesforce estimates into quantitative estimates
* quantitative methods
  * **causal methods**: a quantitative forecasting method that uses historical data on independent variables, such as promotional campaigns, economic conditions, and other competitors actions
  * **time-series analysis**: a statistical approach that relies heavily on historical demand data to project the future size of demand and recognizes trends and seasonal patterns
  * **trend progression with regression**: a hybrid between time-series technique and the causal method

### Forecast Error

**forecast error**: the difference found by subtracting the forecast from actual demand for a given period

**cumulative sum of forecast errors (CFE)**: a measurement of the total forecast error that assesses the bias in a forecast

<img src="https://render.githubusercontent.com/render/math?math=\overline{E}=\frac{CFE}{n}">

#### Dispersion of Forecast Errors

The following are all measurements of the dispersion of forecast errors:

* mean squared error (MSE)

    <img src="https://render.githubusercontent.com/render/math?math=MSE=\sum E^2_t">

* standard deviation of the errors

    <img src="https://render.githubusercontent.com/render/math?math=\sigma = \frac{\sum (E_t-\overline{E})^2}{n-1}">

* mean absolute deviation (MAD)

    <img src="https://render.githubusercontent.com/render/math?math=MAD=\frac{\sum |E_t|}{n}">

#### Mean Absolute Percent Error

**mean absolute percent error (MAPE)**: a measurement that relates the forecast error to the level of demand is useful for putting forecast performance in the proper perspective

<img src="https://render.githubusercontent.com/render/math?math=MAPE=\frac{(\sum{|E_t|}/D_t)(100)}{n}">

* best error measurement to use when making comparisons between time series for different SKUs

### Judgment Methods

* Forecasts from quantitative methods are only useful when there is adequate historical data (i.e. history file)
* Some may have a history file but may be less useful with the type of rollout or special product
* Can be used to modify forecasts that are generated by quantitative methods by forecasters with contextual knowledge (knowledge gained through experience)
* Four of the more successful judgment methods are:
  * **salesforce estimates**: forecasts that are compiled from estimates of future demands made periodically by members of a company's salesforce
  * **executive opinion**: method in which the opinions, experience, and technical knowledge of one or more managers that are summarized to arrive at a single forecast
  * **technological forecasting**: an application of executive opinion to keep abreast of the latest advances in technology
  * **market research**: a systematic approach to determine external consumer interest in a service or product by creating and testing hypotheses through data-gathering surveys
  * **Delphi method**: a process of gaining consensus from a group of experts while maintaining their anonymity

### Causal Methods: Linear Regression

Causal methods are used when historical data are available and the relationship between the factor to be forecasted and other external or internal factors can be identified

**linear regression**: a causal method in which one variable (dependent) is related to one or more independent variables by a linear equation

* **dependent variable**: the variable that one wants to forecast
  * i.e. demand for a door hinge
* **independent variable**: variables that are assumed to affect the dependent variable and thereby "cause" the results observed in the past
  * i.e. advertising expenditures, new housing starts

### Time-Series Methods

**naive forecast**: a time-series method whereby the forecast for the next period equals the demand for the current period

* i.e. Demand on Wednesday is 35 customers, forecast for Thursday is 35 customers.
* Useful when horizontal, trend, or seasonal patterns are stable and random variation is small

**simple moving average method**: a time-series method used to estimate the average of a demand time series by averaging the demand for the *n* most recent time periods

**weighted moving average method**: a time-series method in which each historical demand in the average can have its own weight; the sum of the weights equal 1.0

**exponential smoothing method**: a weighted moving average method that calculates the time series by implicitly giving recent demands more weight than earlier demands

* only requires last period's forecast, actual demand for this period, and a smoothing parameter, alpha, between 0 and 1.0

    <img src="https://render.githubusercontent.com/render/math?math=F_{t%2b1}=\alpha D_t%2b(1-\alpha)F_t">

**multiplicative seasonal method**: a method where seasonal factors are multiplied by an estimate of average demand to arrive at a seasonal forecast

**additive seasonal method**: a method in which seasonal forecasts are generated by adding or subtracting a constant to the estimate of average demand per season

#### Criteria for Selecting Time-Series Method

How does one choose a time-series forecasting methods?

* Using statistical criteria
* **holdout sample**: actual demands from the more recent time periods in the time series that are set aside to test different models developed from the earlier time periods
* **tracking signal**: a measure that indicates whether a method of forecasting is accurately predicting actual changes in demand

### Insights into Effective Demand Forecasting

**big data**: data sets that are so large or complex that traditional data processing applications are inadequate to deal with them, characterized by volume, variety, and velocity

**combination forecasts**: forecasts that are produced by averaging independent forecasts based on different methods, different sources, or different data

**focus forecasting**: a method of forecasting that selects the best forecast from a group forecasts generated by individual techniques

**collaborative planning, forecasting, and replenishment (CPFR)**: a process for supply chain integration that allows a supplier and its customers to collaborate on making the forecast by using the Internet

## Chapter 13: Supply Chain Logistic Networks

**facility location**: the process of determining geographic sites for a firm's operations

**distribution center**: a warehouse or stocking point where goods are stored for subsequent distribution to manufacturers, wholesalers, retailers, and customers

### Factors Affecting Location Decisions

1. The factor must be sensitive to location. If a factor is uniform in all locations, it should not be considered.
2. The factor must have high impact on the company's ability to meet its goals.

Can be separated into dominant and secondary factors.

#### Factors in Manufacturing

* Favorable labor climate
  * function of wage rates, training requirements, attitudes toward work, worker productivity, and union strength
* Proximity to markets
  * Often cheaper to manufacture offshore near the market than to make it at home and ship it abroad
* Impact on environment
* **Quality of life**: a factor that considers the availability of good schools, recreational activities, cultural events, and an attractive lifestyle
* Proximity to suppliers and resources
* Proximity to the parent company's facilities
  * Communication and coordination can become more difficult as distance increases
* Utilities, taxes, and real estate costs
* Secondary factors include room for expansion, construction costs, competition from other firms for the workforce

#### Factors in Services

* Proximity to customers
  * Few people will travel to a service provider if another is more convenient
* Transportation costs and proximity to markets
* Location of competitors
  * Sometimes it pays off to avoid areas where competitors are well-established
  * Some industries, like car sales and fast food restaurants prefer to be near others, to create a *critical mass* (i.e. a situation whereby several competing firms clustered in one location attractor more customers than the total number who would shop at the same stores at scattered location)
* Site-specific factors like retail activity, residential density and traffic flow for retailers

### Load-Distance Method

**load-distance method**: a mathematical model used to evaluate locations based on proximity factors

* Assumes that:
  * There is only one facility to be located
  * Must serve a predetermined set of nodes (customer, suppliers) in a a logistic network
  * Independent of any other facility that may be in the network
* The purpose is to select a location that minimizes the sum of the loads from the facility to each node.
* Distance can be measured be in euclidean distance or rectilinear distance.
  * **euclidean distance**: the straight-line distance, or shortest possible path, between two points
    * x_i, y_i represent coordinates of customer i
    * x^\*, y^\* represent coordinates of proposed facility
    * d_i represents the distance between customer i and the proposed facility

    <img src="https://render.githubusercontent.com/render/math?math=d_i=\sqrt{(x_i-x^*)^2%2b(y_i-y^*)^2}">}

  * **rectilinear distance**: the distance between two points with a series of 90-degree turns, as along city blocks

    <img src="https://render.githubusercontent.com/render/math?math=d_i=|x_i-x^*|%2b|y_i-y^*|">

* To calculate the load-distance score, one must simply multiple the distance by the load (i.e shipments from suppliers, between plants or to customers, or to customers traveling to and from facility)

  <img src="https://render.githubusercontent.com/render/math?math=ld=\sum{l_id_i}">

* **center of gravity**: a good starting point to evaluate locations in the target area using the load-distance model

  <img src="https://render.githubusercontent.com/render/math?math=x^*=\frac{\sum{l_ix_i}}{\sum{l_i}}\ and\ y^*=\frac{\sum{l_iy_i}}{\sum{l_i}}">

### Transportation Method

When a firm with a network of existing facilities plans a new facility one of two conditions exist:

* The facilities operate independently (i.e. a chain of restaurants, health clinics, or banks)
* The facilities interact by moving materials or products to each other or share in the servicing of particular customers (i.e. component manufacturing plants, assembly plants, or warehouses)

**transportation method for location problems**: a quantitative approach that can help solve multiple-facility location problems

* used to determine the allocation patter that minimizes the cost of shipping products from two or more plants (*or sources of supply*) to two or more warehouses (*or destinations*)

### Geographical Information Systems

**geographical information systems**: a system of computer software, hardware, and data that the firm's personnel can use to manipulate, analyze, and present information relevant to a location decision

* Can be used to:
  * store databases
  * display maps
  * create models that information from existing datasets, apply analytic functions and write results into newly derived datasets
* Useful because it can help companies makes decisions that have a geographical aspect
* The frame work used locate multiple facilities with the use of GIS is:
  1. Map the data for existing customers and facilities in the GIS.
  2. Visually split the entire operating area in the number of parts or subregions that equal the number of facilities to be located.
  3. Assign a facility location for each region based on the visual density of customer concentration or other factors. Alternately, determine the center of gravity for each part identified in step 2 as the starting location point for the facility in that subregion.
  4. Search for alternate sites around the center of gravity to to pick a feasible location that meets management's criteria such as environmental issues, availability to major metropolitan areas, or proximity to highways.
  5. Compute total load-distance scores and perform capacity checks before finalizing the locations for each region.

### Inventory Placement

**centralized placement**: keeping all the inventory of a product at a single location such as at a firm's manufacturing plant or a warehouse and shipping directly to each of its customers

* Lowers the inventory pooling because demands are consolidated to one location.
  * **inventory pooling**: a reduction in inventory and safety stock because of the merging of variable demands from customers

**forward placement**: locating stock closer to customers at a warehouse, distribution center, wholesaler, or retailer
