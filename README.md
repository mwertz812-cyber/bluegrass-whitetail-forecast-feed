# Bluegrass Whitetail Forecast Feed

Public, read-only forecast data for BluegrassWhitetail.com.

- `current.json`: current five-region Kentucky whitetail forecast
- `counties.json`: verified county-to-region lookup used by Wix
- `regional-forecast-1.3.0.schema.json`: Wix-facing JSON contract

Forecast URL:

```text
https://raw.githubusercontent.com/mwertz812-cyber/bluegrass-whitetail-forecast-feed/main/current.json
```

Consumers should display a stale-data warning after the forecast's `valid_until` timestamp. The calculation engine and its implementation remain in a separate private repository.
