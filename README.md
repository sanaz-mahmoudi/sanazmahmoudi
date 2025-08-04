# Jupyter Notebooks by Sanaz Mahmoudi
In this repository, a network (shown in the figure below) comprising three buses interconnected via 100 MW transmission lines is considered. A 250 MW thermal power plant with a marginal cost of £50/MWh is connected to bus 1. A 150 MW wind farm with zero marginal cost is connected to bus 2; it is paired with a 100 MW sulphur-flow battery that provides 24-hour backup capability (i.e., the battery can operate at its rated capacity for 24 hours). All domestic and commercial consumers, with a peak electricity demand of 100 MW in February under normal weather conditions, are connected to bus 3. The power factor at bus 3 is assumed to be unity. Hourly profiles for normalised electricity consumption and renewable generation in February 2025 are provided ([link](https://github.com/sanaz-mahmoudi/sanazmahmoudi/blob/main/Hourly%20Profiles.csv)).

It is expected that a Dunkelflaute event will occur during the second week of February 2025, resulting in a 40% increase in electricity consumption and a 60% reduction in maximum available renewable production compared to the original profiles. In this regard, this repository includes some Jupyter notebooks presenting:

1. Optimisation example under normal conditions ([link](https://github.com/sanaz-mahmoudi/sanazmahmoudi/blob/main/OperationUnderNormalConditions.ipynb))
2. Optimisation example under abnormal conditions ([link](https://github.com/sanaz-mahmoudi/sanazmahmoudi/blob/main/OperationUnderAbnormalConditions.ipynb))
3. Resiliency assessment in a planned and unplanned 24-hour outage of the thermal power plant during the Dunkelflaute event ([link](https://github.com/sanaz-mahmoudi/sanazmahmoudi/blob/main/OperationUnderAbnormalConditionsDuringanOutage.ipynb))

Note: For the sake of simplicity, the transport model is used instead of AC or DC power flow equations to ensure nodal power balance.

NO NEED TO INSTALL ANYTHING!! JUST CLICK ON THE LINK AND RUN IT ON COLAB USING YOUR GOOGLE ACCOUNT.


