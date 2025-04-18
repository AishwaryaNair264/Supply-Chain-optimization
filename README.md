

<p align="center">
  <img align="center" src="https://miro.medium.com/max/1400/1*ygvI_dS3-aJ59DGAfplXnA.png">
</p>

### Objective
To build a simple methodology of Supply Chain Network Design that is considering the fluctuation of the demand.

### Introduction
Supply chain optimization makes the best use of data analytics to find an optimal combination of factories and distribution centres to meet the demand of your customers.

In many software and solutions in the market, the core structure behind is a Linear Programming Model.
Some of these models find the right allocation of factories to meet the demand and minimize the costs assuming a constant demand.

#### Demand
Demand from customers in 5 different markets (Brazil, USA, Germany, India and Japan).
<p align="center">
  <img align="center" src="https://miro.medium.com/max/900/1*kaitTBi4zOqq2nUarEa9Bg.png">
</p>

#### Supply Capacity
Factories in the five markets. There is a choice between low and high-capacity facilities.

#### Objective: minimize the total cost of production and shipment
The objective is to design  a new transportation plan to increase the average size of trucks by delivering more stores per route.
<p align="center">
  <img align="center" src="https://miro.medium.com/max/1400/1*QvlfMEtHPS9aq5lCLfc1bQ.png">
</p>
                                                                                               
#### Demand Fluctuation
We consider a fluctuating demand (Normal Distribution) per market.
<p align="center">
  <img align="center" src="https://miro.medium.com/max/1400/1*w6RHuzcgKzRFUicusEPgLg.png">
</p>

#### Methodology
We'll run 50 scenarios and run a solver to find the optimal network.
<p align="center">
  <img align="center" src="https://miro.medium.com/max/1400/1*2cmp3ZRNHwMarV_2a0He1g.png">
</p>
