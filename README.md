# zeebe-opensearch

A simple docker compose to run zeebe with OpenSearch.
Per default both want to use port 9600 which clearly clashes.
In the setup OpenSearch is configured to start performance analyzer on port 10600 instead of 9600.
