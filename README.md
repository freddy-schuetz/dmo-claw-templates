# dmo-claw Templates

MCP template catalog for [dmo-claw](https://github.com/freddy-schuetz/dmo-claw) — tourism-specific tools for DMO agents.

## Available Templates

| Template | Category | Description | API Key |
|---|---|---|---|
| `weather-alpine` | weather | Alpine weather, snow depth, freezing level, 7-day forecast | No (free) |
| `google-reviews` | reviews | Query locally cached Google Reviews, rating summaries, unanswered alerts | Google Places API Key |
| `instagram-post` | social | Create & schedule Instagram posts via Graph API | Instagram Token + Account ID |

## Usage

Ask your dmo-claw agent:

> "What templates are available?"
> "Install weather-alpine"

The Library Manager fetches templates from this catalog, imports the workflows, and registers the MCP server automatically.

## Creating Templates

See [n8n-claw-templates](https://github.com/freddy-schuetz/n8n-claw-templates) for the template format specification and examples.
