# Investment-Appraisal-Simulation

This project aimed to evaluate the financial viability of investing in a cement mixer for hire, on behalf of a construction company, using Monte Carlo simulation and Net Present Value (NPV) analysis.

This investment involved purchasing a cement mixer for £33,000, hiring it out at £150/day over a two-year period, and selling it at the end of the two years. The objective was to determine whether the investment was expected to create value for the company and to quantify the associated financial risk.

Several uncertain variables existed and were modelled using discrete probability distributions based on estimates provided by management. These variables included:

* Number of hire days per year
* Maintenance costs in Year 1
* Maintenance costs in Year 2
* Resale value of the cement mixer

An NPV model was constructed using discounted cash flow techniques, with a discount rate of 15%. Cash inflows from hiring out the mixer and resale value, along with cash outflows from maintenance costs and initial purchase cost, were incorporated into the model.

A Monte Carlo simulation containing 15,000 independent iterations was carried out in Excel. Random sampling from uniform (0,1) distributions was used to generate outcomes for each uncertain variable according to their specific probability distributions (as provided by management). NPV was calculated for every iteration within the simulation to produce a distribution of possible investment outcomes.

Summary statistics including mean NPV, median NPV, probability of loss, and percentile measures were calculated to assess expected return and investment risk. A histogram of NPVs from the simulation was produced to visualise the distribution of outcomes.

The simulation results were compared with an analytical, expected-value approach to show the advantages of Monte Carlo simulation in modelling uncertainty, and quantifying downside risk and upside potential. The results were then used to provide an evidence-based recommendation on whether the company should proceed with the investment.

### Skills Demonstrated
* Monte Carlo Simulation
* Financial Modelling
* NPV Analysis
* Probability Distributions
* Microsoft Excel
* Data Visualisation
* Communication of Findings
