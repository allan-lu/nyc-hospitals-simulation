# New York City Hospital Simulation Modeling 

New York City is currently at the epicenter of US COVID-19 pandemic. The purpose of this project is to model how well NYC hospitals can handle this crisis using a discrete event simulation method.

---

## References
1. Bae, Ki Hwan, et al. “Simulation Modelling of Patient Flow and Capacity Planning for Regional Long-Term Care Needs: A Case Study.” _Health Systems_, vol. 8, no. 1, Taylor & Francis, 2019, pp. 1–16, doi:10.1080/20476965.2017.1405873.

The authors of this paper developed a simulation model investigate the effects capacity and demand have on hospital performance. The focus was on the length of stay for long term care patients in various healthcare providers. Using a discrete event simulation, they projected demands and capacities through demographic data, and identified long term care service gaps in Kentucky. They used their results to invesitgate the impact of service improvements to long term care regarding patient wait time and resource allocation. The authors discovered a significant difference in length of stay between patients by gender and age. The DES was developed using _Simio_, a commercial software.

2. Cocchi, Duccio, et al. “Discrete Event Simulation-Based Approach for Hospital Services Development and Monitoring.” _IFMBE Proceedings_, vol. 57, 2016, pp. 688–93, doi:10.1007/978-3-319-32703-7.

This paper discribes a simulation model used to optimize lab analysis in hospitals. In this model the author uses a discrete event simulation approach to analyze hospital performances by modeling patient wait times, number of patients, number of resources, and how long it takes to complete the lab analysis. One problem they noted when implementing this model was making sure that the events and how much time passes between events are accurate to real life, which requires knowledge of the research topic. They validated their models using historical data related to patient wait times. Three senarios were ran, each with varying parameters to optimize the process. They concluded that hospital organization can be improved using a discrete event simulation approach.

3. Harper, P. R., and A. K. Shahani. “Modelling for the Planning and Management of Bed Capacities in Hospitals.” _Journal of the Operational Research Society_, vol. 53, no. 1, 2002, pp. 11–18, doi:10.1057/palgrave/jors/2601278.

Many things must happen for a hospital to function correctly. To model a hospital, assumptions have to be made to simplify the system. This article describes the planning that goes into hospital bed capacity modeling. Some key statements the authors made is that patient length of stay is highly variable, and the simulation must include both short and very long hospital stays. Also, the process of refusing a patient is more complicated than just denying them a bed. Patients can be moved around to accomodate for more room. This article is very thorough in describing the process for patient admissions. To accurately model bed capacity, one would need to create more events than simply admit and discharge. This is a very useful article, to further develop my DES modeling project.
