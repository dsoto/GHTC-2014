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
TODO: finish expected returns section
TODO: outline discussion
TODO: create charts comparing payment and available expenditures
TODO: outline conclusion
TODO: first draft of discussion
TODO: first draft of conclusion
TODO: check for citations
TODO: fix table output to work with two column files (try ctable?)
https://github.com/jgm/pandoc/issues/1023
TODO: reference for charging costs
TODO: how do we express the variability of lantern cost, kerosene cost, and kerosene displacement?
TODO: can we create a contour graph of IRR for initial cost and avoided cost?
TODO: make a regime plot with financing options both microfinance and in-house finance
TODO: infer terms of MKOPA dlight offering
TODO: create displaced kerosene calculation
TODO: is there a published relationship between lumen output and ml avoided kerosene?
TODO: what levels of income is this true for?
TODO: be sure that no content is clipped because of latex.  will
probably want to change the preprint template to fix this.
TODO: use marked custom preprocessor?
-->

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

<!-- end introduction here? -->


# Solar Lantern Results

## Solar Lantern Initial Cost

The cost of the solar lantern device is the most important part of a
financial decision for most customers.  For the devices available, price
varies depending on the amount of energy available each day, the
features of the device, and the quality of the product.  Prices can
range from as little as 10 USD for a small solar lantern to hundreds of
USD for a photovoltaic solar home system with battery storage.  To
evaluate if a product is affordable, a consumer will compare this
purchase price against their current energy expenditures and overall
income levels.

We can estimate the cost of these devices based on the costs of their
components.  Assuming solar panel costs, storage cost, transportation
costs, and the solar resource, we can estimate the purchase price.
While we can find prices of these products online and in advertising
literature, it is useful to look at the component costs and trends.

Lighting Global compiles data on lantern cost in their effort to create
uniform standards for solar lantern products.  Using prices from
Lighting Global [[@LightingGlobal2013]()],

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

It is important to keep in mind, that the most inexpensive solar
lanterns may not satisfy all of an individual's energy needs.  It is
important then to look at the energy expenditures, and energy avoided by
the lantern in the decision process.

## Overall Energy Expenditures

<!-- todo: reference fuelwood or phone charging literature?-->

To determine the amount of available capital in a household for a clean
energy purchase, we start by measuring the amount currently spent on
energy that could be avoided by the device.
Energy expenditures can take several monetary forms such as kerosene,
candles, batteries, and phone charging as well as time lost in travel or
adverse health effects.

There is some data on energy related expenditures related to
electricity from the Millennium Villages project.
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
Values are in USD per year.  These data are taken from multiple villages
participating in the project.

These values give us some guidance for the likely expenditures in
off-grid locations.  However, as the variability indicates, it is
necessary to evaluate the spending in a location where a pilot is being
conducted.
Data on phone charging expenditures and time spent by household would be
a valuable addition to these estimates.
For the rest of this analysis, we will only consider the displacement
of fuel-based lighting.  Larger devices will need to consider other
avoided costs.
While the total energy spending by a customer is a good basis for
estimations, it is important to quantify how much of this spending an
energy device can replace.


## Solar Lantern Expected Returns

The consumer will want to get an estimate of how much income the device
can bring to the household or what expenses the device can replace.  We
usually compare this to the purchase price of the asset to see how
quickly the purchase will pay for itself in energy savings.  These
returns may be in terms of kerosene or candles that now do not need to
be purchased.  They may also be revenues such as income from charging a
neighbor for cell phone charging.  Once these expected returns are
estimated, the customer determines what the available financing is and
thus the monthly payment.

The light provided from solar lanterns replace the light generated from
purchased kerosene, lowering household energy costs.  Lighting Global
has published data on the kerosene displaced by solar lanterns as well
as the prices paid for kerosene [[@CostOfKerosene]()].
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

|  Avoided Kerosene (liter/day)  |  Avoided Cost (USD/day)  |  Avoided Cost (USD/month)  |  Initial Cost (USD)  |
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
A harder to measure but plausible return could be increased business at
a shop because customers are attracted by the higher quality of light.
This benefit would likely disappear as more vendors buy improved
lighting.
Based on the length of time before the investment is paid back by the
avoided kerosene costs, these investments are very attractive.  However,
not all consumers have the available cash to purchase them.  We have to
look at available financing options to bridge this gap.

## Solar Lantern Available Finance

<!-- TODO: finish this section -->

What are the available finance options available to a customer?
Microfinance is a common option, but is best in areas that have a
population density and social structure that supports it.  Another form
of finance gaining popularity is financing from the solar lantern
provider.  This can be either a loan or a pay-as-you-go technology.

Finance allows the consumer to spread the payments for a power device
over time in smaller amounts.  The consumer will want to know, can these
payments be smaller than my existing energy payments.  For many
customers, the available finance will result in higher payments.

Assuming the customer has no ability to save to purchase the device up
front, the consumer must look for the available financing for the
purchase.  If suitable financing cannot be found, the device may be out
of reach.  Common sources of funding are microfinance institutions, and
in-house financing products provided by the companies themselves.  Some
of these are lease to own and pay-as-you-go financing schemes.

[[@ARCInHouse]()]
[[@ARCPayAsYouGo]()]

M-KOPA provides financing of solar lantern products where the daily
payment is approximately 0.50 USD per day over one year after a deposit.
Assuming the product is sold for 200 USD, this is an effective finance
rate of 49%.  This financing rate may appear unusually high to many
readers, but reflects the transaction costs and difficulty of financing
in these areas.

It is more important to focus on the difference between the resulting
daily or monthly payment and the cost of other energy services.
This 0.50 USD/day payment is approximately 15 USD/month, well above the
monthly spending observed in any of the villages.  This product is
enjoying great success but the monthly cost will have to be lowered to
be affordable to households with lower incomes.

One problem then in the scaling of adoption is this difference in cost.
This can be addressed by lowering the price of lanterns or by improving
the access to short and cheap loans to consumers.

Microfinance providers allow loans at rates of about 35%.  Some lantern
companies offer finance to consumers in the form of installment
payments.

We can see that for many persons, the monthly payments can be less, but
for others with lower existing expenditures, a lantern can mean an
increase in expenses.

<!-- how do we unify daily payments and monthly payments? -->
<!-- graph of expected cost and expected avoided cost -->


# Discussion

<!-- does this work provide any testable hypothesis? -->
<!-- has anyone looked at uptake and price signals for lanterns  -->
<!-- study of price points and financing points monthly payment vs cost
avoided -->

<!-- lower transaction costs -->
<!-- reduce perceived risk of investment -->

<!--
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
-->

## Lowering initial cost

Given that solar panels, batteries, and LED lights are approaching
maturity, we will see further improvements in price.  However,
reductions of 50% seem unlikely over the next few years.  We can
extrapolate the learning curves of each of the components to gain a
prediction of unit cost.  If we do not believe that these cost
reductions alone will make units more affordable, we must look for other
solutions.  Changing the terms of financing is one attractive area for
investigation.


## Longer Loan Terms

<!-- terms are over one year but battery is likely a 3 year asset -->

For the consumer, it makes sense for the length of the loan to match the
time over which the solar lantern provides positive benefits to the
consumer.

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


We can assemble these estimates of cost and benefit for each type of
device and compare to the available finance.
We can plot these by their payback and then see where finance needs to
be extended in order to encourage adoption.

The longer the terms of the loan or financing, the lower the monthly
payments.  However, there are many good reasons why the shorter terms
and higher interest rates are charged.  There are many transaction costs
and losses in the finances that require these rates.  (Engineers may
choose to think of the system as lossy.)

Another way to think of this is to notice that for longer loan terms and
lower interest rates, the payment is reduced.

![Monthly payment for a 100 USD solar lantern.  Low interest rates and
long loan terms are necessary to bring the payment into the range of
current energy expenditures in rural communities.](monthly-payment.pdf)


## Higher initial costs could lead to lower recurring costs

Most engineering focus is on lowering the initial price as much as
possible.  It is plausible that creating a product that is more
expensive but can be used longer, could reduce the monthly price and
risk for a consumer.

<!-- - Longer more expensive batteries also have this feature -->
<!-- - cite soto ghtc 2012 -->


We can plot the observed cost per daily watt hour for several models.
This allows us to estimate the cost and benefit for these projects.

Integrate the different devices into some sort of explanation of overall
affordability.

## Perceived risk

Consumers, businesses, and investors are discouraged by risk in this
space.  Humanitarian engineers can address this risk through creating
physically robust products as well as electronic transactions
technologies that can reduce payment risks.  There has already been good
progress in pay-as-you-go technologies.  The community can make a
contribution here as well.

<!-- cite lumeter, angaza, etc... -->

# Conclusion
- Products should be designed simultaneously with business models
- Can we include financial engineering in our designs?
- Future work: extend this analysis to other products and interventions
- Business in a box
- Charging services
- Future work: study the uptake of devices with longer finance terms
- study the willingness of people to enter long contracts

# Bibliography

<!--
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

