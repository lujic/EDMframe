# EDMFrame

EDMframe is an open source framework for efficient edge data management strategies. It consists of (1) a novel semi-automatic mechanism for recovery of incomplete time series, managing a recovery cycle that ensures detection and forecasting of each gap; (2) an edge storage management mechanism keeping only necessary amount of data for predictive analytics; (3) a mediator component that finds a trade-off between gap size and necessary range of historical data based on projection recovery maps. Preliminary results for (1) and (2) are shown in [1] and [2]. The current version includes new features such as the mediator process, showing a complete data path through the EDMFrame. 

The current EDMFrame is developed in R programming language and requires additional packages such as: readr, tseries, forecast, extrafont, readxl, pryrm, zoo.

DATA:
The proposed algorithms are evaluated on sensor-based time series data coming from real-world IoT systems, namely:
* Smart homes - it contains traces from the Smart* project (S. Barker, A. Mishra, D. Irwin, E. Cecchet, P. Shenoy, and J. Albrecht,
“Smart*: An open data set and tools for enabling research in sustainable homes,” SustKDD, August, vol. 111, p. 112, 2012.) for optimization of energy consumption smart homes design, obtained by UMass Trace Repository (http://traces.cs.umass.edu/).
* Smart buildings - it contains various measurements coming from the monitoring system of Austria’s largest Plus-Energy Office High-Rise Building.

ACKNOWLEDGMENTS 
The work described in this article has been funded through Rucon project (Runtime Control in Multi Clouds), FWF Y 904 START-Programm 2015 and supported with Ivan Lujic's netidee scholarship by the Internet Foundation Austria. The authors would like to thank staff at TU Wien's Plus-Energy Office High-Rise Building, especially to Thomas Bednar and Alexander David on valuable discussions and the Federal Real Estate Company (BIG) for providing data sources.

CITATION:
[1] I. Lujic, V. De Maio and I. Brandic, "Adaptive Recovery of Incomplete Datasets for Edge Analytics," 2018 IEEE 2nd International Conference on Fog and Edge Computing (ICFEC), Washington, DC, 2018, pp. 1-10.
[2] I. Lujic, V. D. Maio and I. Brandic, "Efficient Edge Storage Management Based on Near Real-Time Forecasts," 2017 IEEE 1st International Conference on Fog and Edge Computing (ICFEC), Madrid, 2017, pp. 21-30.
