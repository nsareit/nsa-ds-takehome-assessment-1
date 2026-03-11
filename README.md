# NSA Storage - Data Science Take-Home Challenge

## Background

NSA Storage operates self-storage facilities across the United States. Our data science team wants to better understand what drives storage demand across our diverse markets. We operate in cities with very different climates and seasonal patterns - and we're curious what signals are hiding in the data.

You've been given synthetic facility-level data for 14 storage locations across 8 U.S. markets. The data is entirely simulated and does not represent actual NSA Storage operations or performance. It covers daily operations at the unit group level (small, medium, and large units) from January 2024 through December 2025.

## The Data

Three CSV files are provided in the `data/` directory:

- **sites.csv** - Facility-level attributes (location, city, year opened)
- **unit_groups.csv** - Unit group attributes per site (unit size, count, square footage)
- **statements.csv** - Daily operational data per unit group (occupancy, move-ins, move-outs, street rate, and other fields)

Weather data is not included. These facilities are spread across cities with very different climates - sourcing and integrating local weather data is part of the challenge.

## The Ask

Dig into the data and help us understand what's going on with storage demand across these markets. There's no single right answer here - we want to see how you think about and work with data.

Specifically:

1. **Explore the data.** Walk us through your EDA process. What patterns do you see? What's driving demand up or down across markets and over time? What's interesting, surprising, or worth flagging?

2. **Bring in weather data.** Source and integrate historical weather data for the markets in the dataset. Explain your source, any transformations you made, and how you joined it with the facility data. Beyond just raw weather, think about what weather features might actually matter for storage demand.

3. **Build something.** Develop a model, feature set, or analytical framework that helps us understand or predict storage demand. Explain your choices - what you tried, what worked, what didn't.

4. **Think ahead.** If we wanted to take your work and actually use it to inform business decisions - pricing, staffing, marketing, whatever makes sense - what would that look like? What additional data would you want? What are the limitations of your approach?

## Evaluation

We care more about your process than your results. We're looking at:

- How you explore and understand data before jumping into modeling
- How you handle messy or missing data and the decisions you make
- Whether your analysis reflects an understanding of the business context
- How clearly you communicate your thinking and findings
- Code quality and organization

## Submission

Please clone this repository into your own **private** GitHub repository. Commit all files used for the assessment (notebooks, scripts, documentation). When you're finished, invite the following collaborators to your private repo:

- `Bhansen@nsareit.net`
- `bnebeker@nsareit.net`

## Time

There is no strict deadline. We recommend spending a weekend on this - we respect your time and are not looking for a production-grade system. Focus on showing us how you think.

Good luck, and have fun with it!
