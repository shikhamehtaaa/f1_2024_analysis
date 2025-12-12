F1 2024 Driver Performance Analysis

This project explores Formula 1 driver performance during the 2024 season using open data from the Jolpica–Ergast API. The goal is to understand what actually separates elite drivers from their teammates once you account for car performance, race conditions, and circuit context. Rather than comparing drivers by championship points alone, this project uses contextual, within-team analysis to evaluate: qualifying pace and racecraft (positions gained) in the context of wet-weather performance, street vs. permanent circuit performance, and low vs. high overtaking conditions. 

The analysis includes extensive data cleaning, missing value exploration, facet-based visualization, and an interpretable logistic model predicting which teammate finishes ahead. Results are compared to actual 2024 season outcomes, and Shapley values are used to assess feature importance.

Key Findings:

Drivers who outperform teammates consistently qualify better, so qualifying pace is the strongest predictor of finishing ahead. Racecraft varies widely in that some drivers gain positions reliably, others lose them even from strong grid starts. Wet conditions compress the field and reveal pure driver skill; some teams dramatically rise or fall in the rain. Street circuits favor drivers with adaptable, low-speed car control. The interpretable logistic regression model correctly predicts almost all intra-team finishing orders, demonstrating that these contextual features explain much of driver performance.

Acknowledgments:

Thank you to the maintainers of Ergast and Jolpica for providing accessible Formula 1 data, and to the STATGR5702 teaching team for project guidance!
