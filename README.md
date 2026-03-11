# NSA Storage — Data Science Take-Home Challenge

## Background

NSA Storage operates self-storage facilities across the United States. Our data science team is exploring whether local weather patterns can help us make better demand forecasting and pricing decisions.

You've been given internal facility-level data for 14 storage locations across 8 U.S. markets. The data covers daily operations at the unit group level (small, medium, and large units) from January 2024 through December 2025.

## The Data

Three CSV files are provided in the `data/` directory:

- **sites.csv** — Facility-level attributes (location, city, year opened)
- **unit_groups.csv** — Unit group attributes per site (unit size, count, square footage)
- **statements.csv** — Daily operational data per unit group (occupancy, move-ins, move-outs, street rate, and other fields)

Weather data is **not included**. Part of the challenge is sourcing and integrating external weather data for the markets represented in the dataset.

## The Ask

Using the provided data and any external data sources you find useful, explore the relationship between weather and storage demand. There is no single right answer — we want to understand how you think about and work with data.

Specifically:

1. **Explore the data.** Walk us through your EDA process. What did you find? What's interesting, surprising, or worth flagging?

2. **Source and integrate weather data.** Bring in external weather data for the markets in the dataset. Explain your source, any transformations, and how you joined it with the facility data.

3. **Build something.** Develop a model, feature set, or analytical framework that demonstrates whether (and how) weather impacts storage demand. Explain your choices — what you tried, what worked, what didn't.

4. **Think ahead.** If we wanted to operationalize your work — use it to actually inform pricing or demand forecasting decisions — what would need to happen? What additional data would you want? What are the limitations of your approach?

## Evaluation

We care more about your process than your results. We're looking at:

- How you explore and understand data before jumping into modeling
- How you handle messy or missing data and the decisions you make
- Whether your analysis reflects an understanding of the business context
- How clearly you communicate your thinking and findings
- Code quality and organization

## Submission

Please clone this repository into your own **private** GitHub repository. Commit all files used for the assessment (notebooks, scripts, documentation). When you're finished, invite the following collaborators to your private repo:

- `[REVIEWER_1_GITHUB]`
- `[REVIEWER_2_GITHUB]`

## Time

There is no strict deadline. We recommend spending a weekend on this — we respect your time and are not looking for a production-grade system. Focus on showing us how you think.

Good luck, and have fun with it!
