# Michaelfish
A weather monitoring setup which lets you compare forecasted data to local
measurements.

Do not use for predicting hurricanes.

## Structure
A central time-series database aggregates data from multiple sources, allowing
forecasts to be compared. Local data from weather stations can be added, and
past trends can suggest how the actual weather may differ from forecasts.
Potentially machine learning could be used to create an accurate hyperlocal
forecast using this method.

The data is consumed via a dashboard, but the database is also exposed via APIs,
which are likely to support both REST and GraphQL.
