# Statorium

Statorium is a sports data API provider delivering live scores, statistics, schedules, standings, and news across 6+ sports including Soccer, American Football, Basketball, Hockey, Volleyball, and Handball. The API provides JSON-format responses covering over 200 football leagues, NBA, NFL, and other major competitions with full coverage of live data, historical data, player stats, team stats, lineups, and predictions.

**Website:** [https://statorium.com/](https://statorium.com/)

**Documentation:** [https://statorium.com/stats-api-documentation](https://statorium.com/stats-api-documentation)

## APIs

### Football API
Comprehensive football/soccer data for over 200 leagues worldwide including live scores, match results, standings, fixtures, lineups, player and team statistics, head-to-head records, league logos, and translated names.

**Human URL:** [https://statorium.com/football-api](https://statorium.com/football-api)

#### Properties
- [Documentation](https://statorium.com/stats-api-documentation)
- [OpenAPI](openapi/statorium-football-api-openapi.yml)

### Basketball API
NBA and international basketball live scores, game results, standings, player statistics, and team information.

**Human URL:** [https://statorium.com/basketball-api](https://statorium.com/basketball-api)

#### Properties
- [Documentation](https://statorium.com/stats-api-documentation)
- [OpenAPI](openapi/statorium-basketball-api-openapi.yml)

### American Football API
NFL scores, schedules, player news, team statistics, standings, and daily news feeds linked to NFL players and teams.

**Human URL:** [https://statorium.com/american-football-nfl-api](https://statorium.com/american-football-nfl-api)

#### Properties
- [Documentation](https://statorium.com/stats-api-documentation)
- [OpenAPI](openapi/statorium-american-football-api-openapi.yml)

## Common Properties

- [Website](https://statorium.com/)
- [Documentation](https://statorium.com/stats-api-documentation)
- [Pricing](https://statorium.com/)

## Artifacts

### Spectral Rules
- [Statorium Rules](rules/statorium-rules.yml)

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [Sports Data](capabilities/sports-data.yaml) | Unified multi-sport data — Football, Basketball, and NFL (14 tools) |

**Shared Definitions:**
- [Football API](capabilities/shared/football-api.yaml)
- [Basketball API](capabilities/shared/basketball-api.yaml)
- [American Football API](capabilities/shared/american-football-api.yaml)

### JSON Schema
- [Match Schema](json-schema/statorium-match-schema.json)
- [Team Schema](json-schema/statorium-team-schema.json)
- [Player Schema](json-schema/statorium-player-schema.json)

### JSON Structure
- [Match Structure](json-structure/statorium-match-structure.json)
- [Team Structure](json-structure/statorium-team-structure.json)

### JSON-LD
- [Statorium Context](json-ld/statorium-context.jsonld)

### Examples
- [List Leagues](examples/statorium-list-leagues-example.json)
- [Get Match](examples/statorium-get-match-example.json)
- [Get Standings](examples/statorium-get-standings-example.json)

### Vocabulary
- [Statorium Vocabulary](vocabulary/statorium-vocabulary.yml)

## Authentication

All API requests require an `apikey` query parameter. API tokens are provided after purchasing a data subscription.

**Example:** `https://api.statorium.com/api/v1/leagues/?apikey=your_token`

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
