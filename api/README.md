# LuxCux Registry API

REST API for agent registration and discovery.

## Base URL
https://api.luxcux.com/v1

## Endpoints

| Method | Path | Description |
|--------|------|-------------|
| POST | `/agents/register` | Register a new agent |
| GET | `/agents/:id` | Get agent by ID |
| GET | `/agents/search?q=` | Search agents by capability |
| PATCH | `/agents/:id` | Update agent manifest |
| DELETE | `/agents/:id` | Deregister agent |

## Status
Under active development. Join the waitlist at [luxcux.com](https://luxcux.com) for API access.
