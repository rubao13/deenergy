# DE Renewable Signal (80339)

This project is a simple static HTML page that shows the current renewable share of electricity and the corresponding traffic-light signal for Germany (postal code **80339**) using the public API from [energy-charts.info](https://energy-charts.info).

The page:
- Loads live data directly from the API in your browser.
- Filters **today’s** data between **08:00 and 23:00 CET**.
- Displays a table with:
  - Time (CET)
  - Renewable Share (%)
  - Signal (Red / Yellow / Green)
  - Signal Description
- Colors rows based on the signal:
  - Red – grid congestion or low renewable share  
  - Yellow – average renewable share  
  - Green – high renewable share

## How to use

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-user>/<your-repo>.git
   cd <your-repo>
