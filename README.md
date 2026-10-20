# Hi, I'm Jack

I'm studying a Master of Data Science at UNSW in Sydney, graduating in July 2027, and aiming for data engineering roles. I'm most interested in how data gets collected, stored and moved, and in building the pipelines that make it usable.

## Projects

- **[vehicle-safety-pipeline](https://github.com/SipOfLatte/vehicle-safety-pipeline)**: loads US vehicle complaint and recall data from NHTSA into Snowflake every day, using S3, dbt and Airflow on an AWS EC2 Spot instance set up with Terraform. A public app on top has a RAG chatbot that cites the records it used and a text-to-SQL assistant that runs under a read-only role. [Live app](https://vehicle-safety-pipeline.streamlit.app)
- **[sydney-bus-reliability](https://github.com/SipOfLatte/sydney-bus-reliability)**: polls Transport for NSW's live GTFS-Realtime feed, rebuilds 7.5 million bus arrivals in Parquet and DuckDB, and reports on-time performance by route, stop and hour. [Dashboard](https://sydney-bus-reliability.streamlit.app)
- **[sydney-property-analysis](https://github.com/SipOfLatte/sydney-property-analysis)**: a repeat-sales growth index and hedonic model built from 881,664 cleaned NSW property sales. [Dashboard](https://sydney-property-analysis.streamlit.app)
- **[dbt-snowflake-airflow-pipeline](https://github.com/SipOfLatte/dbt-snowflake-airflow-pipeline)**: TPC-H order data modelled in dbt on Snowflake through staging, intermediate and mart layers with data tests, run daily by Airflow through Astronomer Cosmos in Docker.

## Tools

Python, SQL, Snowflake (including Cortex vector search), dbt, Airflow (Astronomer Cosmos), AWS (S3, EC2, SNS), Terraform, Docker, GitHub Actions, DuckDB, Parquet, Claude API, Streamlit, pandas, scikit-learn, Git

## Links

- Website: [haosun.dev](https://haosun.dev)
- LinkedIn: [linkedin.com/in/hao-s-1560212b2](https://www.linkedin.com/in/hao-s-1560212b2)
- Email: jacksunruo@hotmail.com

When I'm not coding I'm either on the golf course or deep in a League of Legends match, both involving more strategy than they look like from the outside.
