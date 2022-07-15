# AbuseIPDB-SO-Analyzer

## Description
Submit an IP address to AbuseIPDB for analysis.

## Configuration Requirements

``api_key`` - API key used for communication with the AbuseIPDB API


This value should be set in the ``sensoroni`` pillar, like so:

```
sensoroni:
  analyzers:
    abuseipdb:
      api_key: $yourapikey
```