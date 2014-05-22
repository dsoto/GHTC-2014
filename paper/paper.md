---
title: A consumer-based analysis of solar lantern financing
author:
- name: Daniel Soto
  affiliation: Sonoma State University
- name: Collaborator
  affiliation: UCB
abstract: |
    1.3 Billion people will remain without electricity without significant
    investment in new energy services.  The IEA shows that about half of
    these services need to be distributed energy to reach those beyond the
    grid.  Current investment focuses on centralized power plants and grid
    expansion.  In the absence of public funding, the unelectrified rural
    populations must rely on private financing.  In this paper, I compare
    the financial returns from watt-scale consumer products for lighting and
    mobile phone charging and the available financing for consumers from
    microfinancing.  A comparison of the avoided cost in kerosene or phone
    charging and the monthly payment for a product shows that microfinance
    loan payments often exceed the avoided cost.  Many customers are not
    able to tolerate these higher recurring payments even though in the
    future they will have no payments.  In the developed world, innovators
    create instruments that eliminate upfront costs for energy services and
    immediately reduce consumer energy expenses.  Equivalent innovation in
    this space could speed adoption of these technologies in the developing
    world as well.
---

<!--
TODO: fix table output to work with two column files
TODO: reference for charging costs
TODO: how do we express the variability of lantern cost, kerosene cost, and kerosene displacement?
TODO: can we create a contour graph of IRR for initial cost and avoided cost?
TODO: revisit writing in the sciences lectures
TODO: make a table that compares different devices and affordability
TODO: make a regime plot with financing options both microfinance and
in-house finance
TODO: infer terms of MKOPA dlight offering
TODO: create displaced kerosene calculation
TODO: is there a published relationship between lumen output and ml avoided kerosene?
TODO: what levels of income is this true for?
TODO: be sure that no content is clipped because of latex.  will
probably want to change the preprint template to fix this.
-->


<!-- MAIN POINTS -->
<!-- current product availability will not reach all consumers -->

# Introduction

<!--
# outline
- private enterprise offers a credible way to challenge energy poverty
- in off-grid areas, renewable energy is the least-cost solution
- however, renewable energy requires upfront payments
- Assume customers have little ability to save
- customers need access to finance to acquire energy devices
- I assert that this financing must lower overall energy expenditures
- For many customers, this is not possible despite affordable products
  and available finance
-->

Private enterprise offers a credible way to challenge energy poverty by
offering energy solutions at a scale that donation or gift based
solutions cannot reach.
Renewable energy is the lowest-cost option for many areas that are far
from the existing grid.
Renewable energy, however, requires an initial purchase in order to gain
the benefit of near-zero recurring energy costs.
Since many of these customers have little ability to save, they require
financing to afford renewable energy products.
This financing allows these customers to pay a smaller recurring fee
instead of the larger purchase price.
If this recurring payment is smaller that the amount the customer
currently spends on energy services, the customer can finance the
purchase and end up with a lower overall energy cost.
Despite several technological and financial innovations, many customers
will not be able to lower their overall payments with the options
available to them.
It will require further development to create affordable solutions for
all income levels.


<!--
- With modest income and no savings existing expenditures must be
  redirected
- Some data is collected on energy expenditure data
- Energy expenditure data also available from the Millennium Village
  Project [@MVPEnergy]
- We can estimate the benefits of products using reports on avoided
  kerosene [@CostOfKerosene]
- Do products offset all kerosene costs?
- Some data on firewood suggest low displacement of existing energy
  sources so we must be cautious (cite Nathan Johnson)
- Literature probably needs more data
- This offset cost is the available income for clean energy products
- Compare expenditures to rates some companies charge.  Companies
  pursuing in house financing could offer more favorable terms
  [@ARCInHouse][@ARCPayAsYouGo]
- What is good citation for finance rates?  Grameen shakti?
- These data give us a good indication of an acceptable recurring cost
  for a clean energy product
-->


We consider the value of a clean energy product as an investment on the
part of the consumer.  The consumer is faced with a decision.  She may
purchase a device at several times her monthly energy expenditure that
allows her to avoid that monthly expenditure for a time period.
To make her decision, one criterion is whether the device will result in
a lower overall cost of energy for her household.  She must compare the
energy costs that will be removed by the device with the payment she
must make on the device.
The devices we will consider will be solar photovoltaic devices, often
with LED lighting and battery storage.  This framework is applicable
regardless of the technology.



## Energy expenditures

To determine the amount of available capital in a household for a clean
energy purchase, we start by measuring the amount currently spent on
energy that could be avoided by the device.

Data from the Millennium Villages project measures fuel expenses per
household in several Sub-Saharan villages.
[[@MVPEnergy]()]
The averages are reported.
These cover the expenditures related to lighting which are kerosene and
candles.

| location   |   kerosene |   candles |   yearly |   monthly |
|:-----------|-----------:|----------:|---------:|----------:|
| Bonasso    |      18.53 |     51.37 |    69.9  |   5.82    |
| Ikaram     |       1.9  |     48.81 |    50.71 |   4.22    |
| Mayange    |       1.69 |     11.66 |    13.35 |   1.11    |
| Mbola      |       0.35 |     33.1  |    33.45 |   2.78    |
| Mwandama   |       7.31 |     12.08 |    19.39 |   1.61    |
| Pampaida   |       0.48 |     48.62 |    49.1  |   4.09    |
| Ruhiira    |       2.44 |     15.1  |    17.54 |   1.46    |
| Tiby       |       1.16 |     55.8  |    56.96 |   4.74    |

Table: Millennium Village surveys of energy expenditures by household.
Values are in USD per year.

We combine this with the income brackets in the Lighting Global
literature.

These values give us some guidance for the likely expenditures in
off-grid locations.  However, as the variability indicates, it is
necessary to evaluate the spending in a location where a pilot is being
conducted.

## Initial cost

The initial cost of the device should be considered.

## Expected returns

The consumer will want to get an estimate of how much income the device
can bring to the household or what expenses the device can replace.  I
will estimate this for a few broad classes of devices.  We usually
compare this to the purchase price of the asset to see how quickly the
purchase will pay for itself in energy savings.

These returns may be in terms of kerosene or candles that now do not
need to be purchased.  They may also be revenues such as income from
charging a neighbor for cell phone charging.

Once these expected returns are estimated, the customer determines what
the available financing is and thus the monthly payment.


## Available finance

Assuming the customer has no ability to save to purchase the device up
front, the consumer must look for the available financing for the
purchase.  If suitable financing cannot be found, the device may be out
of reach.

I will compile some financing options that are available for reference.

Common sources of funding are microfinance institutions, and in-house
financing products provided by the companies themselves.  Some of these
are lease to own and pay-as-you-go financing schemes.


# Results

Having provided a general explanation of consumer expenditures, expected
returns for products, and the available finance, we look at a few
classes of products.


## Solar Lantern

### Initial cost

A solar lantern is a tiny solar power plant with battery storage for
nighttime lighting applications.


We can estimate the cost of these devices based on the costs of their
components.  Assuming solar panel costs, storage cost, transportation
costs, and the solar resource, we can estimate the purchase price.

While we can find prices of these products, it is useful to look at the
component costs and trends.

Using prices from Lighting Global Minimum Quality Standards Memo 2013,


| Component         | Value                   |
|:------------------|:------------------------|
| overall           | 10 USD per klm          |
| solar             | 5 USD per watt          |
| battery           | 0.3 USD per Wh capacity |
| balance of system | 2 USD per watt          |
| derate            | 70%                     |

Table: Parameters for solar lanterns from Lighting Global Minimum
Quality Standards.

The level of lighting that satisfied the survey participants is 25
lumens with a run time of approximately 5 hours.  This is from the
Lighting Global Standards Memo.

The cost of a minimally acceptable solar lantern is about 10 USD and are
one of the products most affordable to most consumers.

These prices are likely to continue to decline over time due to
improvements in LED and PV performance and cost.  We assume that the
component costs of a lantern and a business-in-a-box solution are
equivalent.

### Solar lantern expected returns

The light provided from solar lanterns replace the light generated from
purchased kerosene, lowering household energy costs.  Lighting Global
has published data on the kerosene displaced by solar lanterns as well
as the prices paid for kerosene.
These are from a small field sample and are not meant
to be representative of all households.

| Lantern Cost | Displaced Kerosene |
|--------------|--------------------|
| 20 USD       | 60 ml/day          |
| 40 USD       | 90 ml/day          |
| 80 USD       | 140 ml/day         |

Table: Lantern cost and displaced kerosene.  Data from the Lighting
Africa report, "The True Cost of Kerosene in Rural Africa".

For a given initial payment, these lamps can displace kerosene at the
rates shown in the table.  By using the cost of kerosene we can
calculate the avoided costs.

| Location | Kerosene Cost per liter |
|----------|-------------------------|
| Rural    | 1.30 USD/liter          |
| Urban    | 0.96 USD/liter          |

Table: Kerosene cost in rural and urban markets.  Data from Lighting
Africa.

With these we can estimate the avoided cost for a household based on a
lantern purchase.  It is this avoided cost that can be directed to loan
repayments.

|  Kerosene Displacement (liter/day)  |  Avoided Cost (USD/day)  |  Avoided Cost (USD/month)  |  Initial Cost (USD)  |
|:-----------------------------------:|:------------------------:|:--------------------------:|:--------------------:|
|                0.06                 |          0.078           |            2.34            |          20          |
|                0.09                 |          0.117           |            3.51            |          40          |
|                0.14                 |          0.182           |            5.46            |          80          |

Table: Avoided costs from displaced kerosene from lanterns.


These all have a payback time of less than a year, but all require the
customer to make an initial expenditure 10 times larger than their
monthly expenditure.
That is, the payback can also be thought of as the factor beyond the
monthly payment that the customer must provide initially.  It may be
more relevant to look at payback for the daily purchases, since this is
the granularity of budgeting for many households.


### Available Finance

The useful life of the product is set
by the battery lifetime at what is likely 3-5 years.  Over these 3-5
year lifetimes, almost all solar lanterns have a positive net present
value.  However, most consumers cannot afford to pay for these lanterns
upfront and need financing.

In these markets, it may not be practical to get loans as long as 3-5
years.  Customers will not make the decision based on a net present
value calculation but more likely on whether or not the product can save
expenditures on kerosene.  This means that the finance payment for the
loan must be less than the kerosene saved.  The most likely loan lengths
are one year or less.  At these loan lengths the finance charge exceeds
the avoided kerosene cost.

One problem then in the scaling of adoption is this difference in cost.
This can be addressed by lowering the price of lanterns or by improving
the access to short and cheap loans to consumers.

Microfinance providers allow loans at rates of about 35%.  Some lantern
companies offer finance to consumers in the form of installment
payments.


## Business in a box



Robust solutions for small-scale energy entrepreneurs are available for
purchase.  These are moderately priced ($150) devices that have a solar panel,
battery storage, multiple DC output ports, and charging intelligence to manage
the battery.

These systems are designed not to offset existing costs, but to earn
revenue from charging services.
An entrepreneur can buy this system, harvest solar energy, and sell electrical
energy through phone charging to area villagers.

Assuming there is enough demand for charging, this device can have a very
attractive return.  The entrepreneur does incur a business risk since a
competing phone charging solution in the same geographic area could sharply
reduce demand and thus the income from the system.


- Cost of device \$150
- cost of charge 0.20 USD
- frequency of charge 100 / month
- monthly revenue if charging 3 phones per day, \$20 per month
- monthly revenue if selling electricity at retail, 30 days * 0.050 kWh/day *
0.20 USD/kWh = $3

We can look at the return as a function of the time the asset is held and
compare to available finance rates.




### Business in a box initial cost
### Business in a box expected returns

If the electricity is sold in the form of a phone charge, the returns
can be very attractive.
If the electricity is sold at retail rates however, the returns are much
less compelling.  This is a problem facing many minigrid enterprises.


*need reference for cell phone charging numbers*

Phone charging devices allow the user to avoid the cost of charging
their own phone and can also generate revenue.

*how long does it take to charge a phone*
*what are technical limits of charging*
*what are economic limits of charging*

Customers report spending from 0.10 USD to 0.25 USD to charge the
battery on their cell phone.  This represents about 5 Wh of DC energy in
the battery, and likely 6-7 Wh of AC energy delivered to the charging
device.  Charging often involves travel but we do not attempt to price
that time here.

There are limits to the number of charges and therefore the revenue a
device generates.  The first is the solar energy harvested per day.  The
second is the level of phone ownership and spending power of the
surrounding community.  It may make more sense to consider charging
revenue per village shared among the charging device owners.  There is
also the time and power needed to charge multiple batteries.

|      | revenue per charge |
|------|--------------------|
| high | 0.25 USD           |
| low  | 0.10 USD           |

Table: Charging revenue in some markets


*what is the cost per minute of minutes vs the power to talk on phone*

Consider a device that charges a cell-phone during the day with a solar
panel and a small charge controller.  The cost of this device will be
mostly the panel cost since the battery is on the phone.  This device
assumes that customers are willing to travel during the day and leave
their phones to be charged during the day.

These costs could be lowered by removing the battery, with the
consequence that charging can only be performed during sunny periods.

Assume

- Phone battery capacity of 5 Wh
- 5 Watt panel
- cost of charge 0.20 USD
- frequency of charge 10 / month

The lifetime of the panel could be 10 - 20 years, the charge controller is
likely less than that.

We can look at the return as a function of the time the asset is held and
compare to available finance rates.


Assume that the charger panel, assembly, and electronics is available at \$2.0
per watt.  For a 5 watt, panel this is \$10.

A five watt panel in a 5 peak sun hour location can generate 25 Wh each day.
This is about 5 phones worth of electricity if delivered with 100% charging
efficiency.  The largest uncertainty in the revenue is how many phones can be
recharged and paid for.  The capacity of the device is 4-5 per day or 120-150
per month for a maximum revenue of \$24--\$30 per month.  This is likely
entirely too optimistic, since the surrounding area may not have that many
customers or charging demand.  If we instead assume a charge per day, we have
revenues of closer to \$6--\$12 per month.


Even at conservative estimates, the payback for this device can be within a
month or so.

### Business in a box available financing

Microfinance rates allow for a monthly payment about .


Note that the M-Kopa payment rates are approximately 15 USD per month,
which are higher than these expenditures.  Only upper quartile customers
are likely able to make these payments by purely displacing current
energy costs.

- type, initial cost, monthly displacement, months until payback
- solar lantern, \$20, \$1.8, 11
- phone charging, \$10, \$2.0, 5
- battery in a box, retail electricity, 150 USD/month, 1.5--7.5 kWh/month, \$2, 50
- battery in a box, phone charging 150 USD/month, 20 USD/month, 7.5 months
- 1 kWh per day per customer microgrid without transmission






# Discussion


## Available finance terms

While these devices have different forms and uses, we can classify them
by their financial characteristics.

We can plot these by their payback and then see where finance needs to
be extended in order to encourage adoption.

This plot refers to

![Several returns are plotted as a function of the time that the
  investment is held.  Microfinance is in the lower left corner.](general-returns.pdf)




The longer the terms of the loan or financing, the lower the monthly
payments.  However, there are many good reasons why the shorter terms
and higher interest rates are charged.  There are many transaction costs
and losses in the finances that require these rates.  (Engineers may
choose to think of the system as lossy.)

![Caption](monthly-payment.pdf)


## Higher initial costs could lead to lower recurring costs

Most engineering focus is on lowering the initial price as much as
possible.  It is plausible that creating a product that is more
expensive but can be used longer, could reduce the monthly price and
risk for a consumer.

<!-- - Longer more expensive batteries also have this feature -->
    <!-- - cite soto ghtc 2012 -->


We can plot the observed cost per daily watt hour for several models.
This allows us to estimate the cost and benefit for these projects.

|                |      |
|----------------|------|
| fenix readyset | blah |
| dlight         |      |
| barefoot       |      |
| BBOXX          |      |

Table: Incomplete


|                   |    |   |   |
|:------------------|---:|--:|--:|
| Battery Charger   | 40 | 5 | 0 |
| Solar Home System | 40 | 5 | 0 |
| Solar Lantern     | 40 | 5 | 0 |

Table: Summary of device types and benefits




We can quantify the value of these future avoided costs using the future
discounting of the payments according to the familiar formula

$$ PV = \frac{FV}{(1+i)^n} $$

The discount rate reflects the customers preference for access to money
now instead of money in the future.  Customers often have very high
discount rates reflecting the focus on immediate financial concerns.


The longer that an energy product continues to offset costs, the higher
the benefit which is often measured in the net present value of the
investment.  This increasing value saturates depending on the discount
rate or relative value of money in the future.



*what is npv of a lantern as a function of time create plot*
*can we measure willingness to enter a contract?  is there an aversion
to entering these agreements that must be considered?*

Anything that reduces the life of the product reduces the net present
value of the asset.




### Simple payback

This ratio is simply the payback time but it helps us think about and
compare various options.  In general, if you are replacing kerosene
short payback times are possible, if you are selling photovoltaic
electricity at grid rates, the payback times are very long.


![Caption](charging-returns.pdf)



Integrate the different devices into some sort of explanation of overall
affordability.

<!--
## Retail electricity rate of return

If instead of competing with retail phone charging rates, the entrepreneur
decides to compete with grid electricity by selling electricity on a per kWh
basis, the return of the device decreases drastically.

Assume:

- All electricity collected by solar panel can be sold
- Retail cost of electricity similar to grid (0.20 USD/kWh)

ReadySet

- Battery 12V, 9Ah, VRLA, 54 Wh useable energy
- Solar panel 5-75 W

The retail price for a ReadySet is about 100 USD.

If electricity is only sold at night, there is about 50 Wh available each day or
1.5 kWh per month, because of the battery capacity.

If instead electricity is also sold during the day, the electricity is
constrained by the solar panel.  In a sunny location with 5 peak sun hours per
day, we could harvest 250 Wh per day from a 50 W panel or about 7.5 kWh per
month.

At retail rates of 0.20 USD/kWh, the monthly revenue is 0.30-1.5 USD/month with
paybacks of 60-300 months.  This assumes every kWh generated is sold.

At phone charging rates, if we can sell every kWh, the battery may charge 10
phones per day at 0.20 USD and 2 USD per day or 60 USD per month, with 1-2
month payback periods.  Again, this may be an optimistic assumption.

This wide difference underscores the difference between revenue based on an
avoided cost in a distorted market and having to compete with the grid.

The IRR are well over what microfinance will use at very short time periods.
The avoided cost is favorable and the storage is already purchased in the
cellphone eliminating that cost.

However, since such a device is inexpensive, financing may not be necessary to
begin with.

The longer the terms of the loan, the lower the recurring cost of the
asset.  For the lowest cost of ownership, the financing should extend
over the life of the asset.


In order to achieve payments comparable to average spending, the terms
of the loan must be longer.  One limitation of loan length is the useful
life of the battery.


We estimate the avoided costs or revenues for a watt-scale investment.

For many possible investments, the available microfinance interest rates
are above the returns of the investment.  This requires an increase in
monthly expenditures for customers which may be either impossible or
undesirable.

Most microfinance loans are short, less than 10 months and at interest
rates above 35%.  This means that microfinance results in positive cash
flow only for investments in the upper left region of the graph.

If finance is available at the same terms but below the IRR, there is a
positive cash flow for our investor.

If finance is available at the same terms but above the IRR, the
customer will have to raise her monthly expenditures above her current
expenditures to pay for the investment.

If finance is available for shorter terms than desired, the loan
payments will be greater than the avoided costs.

The microfinance loan terms allow for the purchase of the \$20 lamp at
near breakeven.  If the loan length were extended to 20 months, the
consumer would see a net positive cash flow each month.

There is only a small region where one of the lamps intersects with the
available financing region.

Without a financing option available, lanterns must be financed out of
pocket.  Despite attractive paybacks, this will not be feasible for many
consumers.

For the range of terms where solar lanterns are attractive investments,
there are no loans available.

- Central point is that lowest initial cost is not always desirable
- These same issues come up in diesel mini-grids
- Lower tiers are possible through financing
- Upper tiers are more difficult
- For example refrigerators require large marginal benefit
- Companies are pursuing this pay-as-you-go model
- For highest affordability, financing should be extended over the life
  of the product
- How do we move to higher tiers of energy access while simultaneously
  making it available to more income levels
- MFI rates
- Mobile money rates and remittance transaction costs #africasupertax
- pay as you go or company finance could lead to better terms


## Need to incorporate this into design process
- How can reduction of transaction costs be incorporated into design
  process?
- Can companies take the place of microfinance at a benefit to both
  consumers and providers?
- Can technology or software lower transaction costs and thus the
  interest rate?

## Difficulty once avoided costs are gone
- Productive uses will need to create income streams rather than
  displace costs, making returns more uncertain

## Need for research to quantify assumptions
- There is a need to quantify and publish these costs and benefits


-->

# Conclusion
- Products should be designed simultaneously with business models
- Can we include financial engineering in our designs?



<!--
# Questions
- can you price the salvage value of the asset?  [@ARCPayAsYouGo]
  mentions Azuri systems being given to family members.
- what are the economics of energy vs time based accounting mechanisms?
- what is the value of consolidating business data into a public
  database?
- are we seeing a secondary market for these products after upgrade?
- is grammeen shakti able to service more of the market with its longer
  terms?
-->

<!--
## Impact
- How will this paper change our field?
    - by creating greater awareness of recurring cost issues
- How will this paper increase energy access?
- Who should read this to increase energy access?

## Introduction
- despite high growth rate, uneven access to poor
- lack of financial modeling of off-grid solutions
- IEA says 50% of power needs to be off grid
- large scale capital like power africa currently flowing to centralized
  solutions.  private sector will have to step in.
- these off grid solutions will require small financing

## Introduction explain NPV, payback time, IRR
- net income as fraction of total income

## Figures
- range of irr with lantern cost and kerosene displacements
- net present value of lantern investments as a function of discount
  rate?
- figure that demonstrates quartiles of income and purchasing power
- map space of available loan terms

## Discussion
- Financing is not available over the lifetime of the battery
- Per unit of service costs are very high compared to grid
- We should look for alternatives to consumer financing
- Transactions costs must be lowered
- We can think (as EEs) of these transaction costs as line losses or
  efficiency reductions

-->
