# @sabbour/adaptive-ui-travel-data-pack

An [Adaptive UI](https://github.com/sabbour/adaptive-ui-framework) component pack for **travel planning data**. Provides weather forecasts, country information, currency conversion, packing checklists, and budget tracking — all using free public APIs.

## Components

| Component | Props | Description |
|-----------|-------|-------------|
| `weatherCard` | `location`, `units?` | Current weather conditions and 3-day forecast for a destination. |
| `countryInfoCard` | `country` | Country facts card showing capital, languages, currency, timezone, and driving side. |
| `currencyConverter` | `from`, `to`, `amount?` | Live currency conversion with current exchange rates. |
| `travelChecklist` | `items`, `bind?` | Interactive packing/preparation checklist with check-off functionality. |
| `budgetTracker` | `currency?`, `categories?`, `bind?` | Budget tracking widget for trip expense management by category. |

## Tools

| Tool | Description |
|------|-------------|
| `get_weather` | Current weather and 3-day forecast. Use to advise on packing and activities. |
| `get_exchange_rate` | Live currency exchange rates for budget calculations. |
| `get_country_info` | Country facts (capital, languages, currency, timezone, driving side). |
| `get_time_zone` | Current local time at a destination for jet lag advice and scheduling. |

## Installation

```bash
npm install @sabbour/adaptive-ui-travel-data-pack
```

```typescript
import { createTravelDataPack } from '@sabbour/adaptive-ui-travel-data-pack';

const travelPack = createTravelDataPack();
// Register with your AdaptiveApp
```

## Prerequisites

No API keys required — all tools use free public APIs.

## License

MIT
