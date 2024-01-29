# customer-risk-ui-poc



## Phase 0: Data Modeling
- Develop a coprehensive query that contains all of the necessary info to power the UI for a single user id.
- Develop a comprehensive dbt model that aligns and structures the necessary data points for the UI.
- Define relationships, aggregations, and any transformations needed for effective querying.

## Phase 1: API Development
- Create an API that interfaces with the dbt models and underlying Redshift table.
- Implement endpoints to support the required data retrieval for UI testing.
- Utilize mock data initially to facilitate testing and UI development.
- Ensure the API can handle both historical data from dbt models and real-time data.

## Phase 2: Real-time Data Stream
- Explore and implement real-time data streaming solutions to supplement historical data.
- Integrate the real-time stream into the API, ensuring it aligns with UI requirements.
- Develop filtering mechanisms to support real-time and historical data queries.
- Test and validate the real-time capabilities in collaboration with UI development.
