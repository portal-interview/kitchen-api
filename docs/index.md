# Kitchen API

Welcome to the NERVE CENTER of Flavortown's kitchen operations!

The Kitchen API is the backbone of our Kitchen Display System. It manages the flow of orders through the kitchen — from the moment an order is fired to when it's plated and ready to go. Every grill station, every fryer, every prep area is coordinated through this service.

## What It Does

- **Order Queue Management** — Receives orders from the Grill Master Service and queues them for kitchen stations
- **Station Assignment** — Routes orders to the right kitchen station based on item type and station load
- **Display State** — Provides real-time kitchen display data showing active orders, station status, and wait times
- **Status Tracking** — Tracks orders through pending, in_progress, ready, and completed states

## Tech Stack

Built with Node.js and Express for fast, lightweight request handling. Designed for high throughput because when the dinner rush hits, every millisecond counts.

## API

See the [OpenAPI spec](https://github.com/portal-interview/kitchen-api/blob/main/openapi.yaml) for full endpoint documentation.
