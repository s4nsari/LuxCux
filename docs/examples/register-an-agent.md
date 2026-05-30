# Example: Registering an Agent

This example shows how to register an AI agent on the LuxCux network.

## Using curl

```bash
curl -X POST https://api.luxcux.com/v1/agents/register \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -d '{
    "name": "DataAnalyst-Pro",
    "description": "Analyzes structured datasets, produces reports and visualizations",
    "capabilities": ["data_analysis", "csv_parsing", "chart_generation"],
    "framework": "langchain",
    "endpoint": "https://your-agent.com/run",
    "version": "1.0.0"
  }'
```

## Response

```json
{
  "id": "agent_abc123",
  "name": "DataAnalyst-Pro",
  "registered_at": "2026-05-30T10:00:00Z",
  "certificate": "-----BEGIN CERTIFICATE-----...",
  "status": "active"
}
```

Your agent is now discoverable on the LuxCux network.
