# Jackie Wang

**Email:** [jaw039@ucsd.edu](mailto:jaw039@ucsd.edu)  

**Section:** B25
**Mentor:** Akash Shah, Lisa Li, Bor-Chau Juang, Pratyush Panda, Victor Calderon 

---

## Quarter 2 Project Brainstorm

**What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic this quarter has been forecasting operational demand in real business environments, specifically within Intuit’s call-center ecosystem. I found it fascinating how forecasting integrates seasonality, calendar effects, and service-level constraints to drive staffing and business decisions. Understanding how forecasting quality translates into real operational outcomes (e.g., agent coverage, cost efficiency, customer experience) made the problem feel both technically and practically meaningful.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For my Quarter 2 Project, I would like to explore ways to better model call center handle times by incorporating richer engineered features (e.g., abandonment rates, rolling statistics, agent group characteristics, or event-driven features like tax season or product launches). I’m particularly interested in evaluating whether modeling call volume and handle time jointly rather than separately improves downstream workload forecasting and agent scheduling accuracy. I’d also like to examine time-varying effects — for example, whether certain patterns only surface during peak periods.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
One change I would make to the current Q1 approach is improving our feature-generation and validation procedures. For example, I would enforce stricter chronological validation (e.g., walk-forward splits) and incorporate more systematic feature selection. Additionally, I would refine how we handle missing timestamps and outlier durations to create a more reliable signal, which could improve model training stability and performance.

**What other techniques would you be interested in using in your project?**  
I am interested in experimenting with more advanced time-series models such as gradient boosting (e.g., XGBoost, LightGBM), hierarchical forecasting, or hybrid approaches that combine statistical baselines with machine learning models. I would also like to explore probabilistic forecasting to better quantify uncertainty in call volume and handle-time predictions. Finally, I’m curious about operational optimization techniques that translate forecasts directly into staffing recommendations aligned with SLAs.