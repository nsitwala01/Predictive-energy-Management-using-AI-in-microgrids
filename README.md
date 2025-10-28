# Predictive Energy Management Using AI in Microgrids.
This research project investigates the implementation and performance of a predictive,
AI-based Energy Management System (EMS) for a hybrid microgrid. The study aims
to address the limitations of traditional rule-based control systems, which often rely on
static thresholds and fail to optimise power flow under varying environmental and load
conditions. By integrating short-term forecasting with dynamic energy scheduling, the
predictive EMS seeks to enhance operational efficiency, minimise diesel generator usage,
and improve renewable energy utilisation.


The methodology involved developing a microgrid model in MATLAB/Simulink consisting
of photovoltaic (PV) generation, battery storage, and a diesel generator. Solar and load
forecasts were generated using Long Short-Term Memory (LSTM) neural networks to
provide day-ahead predictions, which were then used as inputs for the predictive EMS.
The system’s performance was evaluated across distinct scenarios and compared against
a conventional rule-based EMS.

The results demonstrated that the predictive EMS significantly outperformed the rulebased system across all cases. Diesel runtime was reduced by up to 70%, operational
costs decreased by over 40%, and renewable energy utilisation improved substantially.
Although the predictive approach increased battery cycling, it achieved a favourable
trade-off between cost savings and component lifespan. The findings confirm that AI-driven predictive control can provide a more intelligent, adaptable, and cost-effective
solution for microgrid energy management. The study also offers practical recommendations
for deploying such systems in low-resource environments, emphasising scalability, edge
computing, and local capacity building.
