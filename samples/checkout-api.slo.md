# checkout-api

SLI: share of HTTP requests that return below 500 and finish in under 300ms, measured at the ingress.

SLO: 99.9% over a rolling 30 days.

Error budget: 0.1%, about 43 minutes of bad requests in those 30 days.

Page when 2% of that budget burns in one hour. A slow burn opens a ticket. It does not wake anyone up.
