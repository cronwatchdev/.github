## CronWatch

Cron job monitoring that lives in your own app and database.

Wrap a job once, and CronWatch records every run in a database you already have. It tells you when a run is missed, fails, gets stuck, runs slow, goes over budget, or quietly does nothing. There's no server to run and no account to make. MIT licensed.

**[cronwatch.dev](https://cronwatch.dev)** · [Docs](https://cronwatch.dev/docs/) · [Changelog](https://github.com/cronwatchdev/cronwatch/blob/main/CHANGELOG.md)

### Install

| Language | Install |
|---|---|
| TypeScript and Node | `npm install @cronwatch/sdk` |
| Ruby and Rails | `bundle add cronwatch` |
| Python | `pip install cronwatch-sdk` |
| PHP | `composer require cronwatch/cronwatch` |
| Go | `go get cronwatch.dev/go` |
| Rust | `cargo add cronwatch` |
| Elixir | add [`:cronwatch`](https://hex.pm/packages/cronwatch) to `mix.exs` |
| Java | `dev.cronwatch:cronwatch` |
| .NET | `dotnet add package Cronwatch` |

There are also plugins for [WordPress](https://wordpress.org/plugins/cronwatch/), [Drupal](https://www.drupal.org/project/cronwatch), and [Craft CMS](https://plugins.craftcms.com/cronwatch), integrations for Laravel, Symfony, Django, Celery, Sidekiq, Oban, Spring, Quartz, Hangfire, and more, an [MCP server](https://cronwatch.dev/docs/mcp/) (`@cronwatch/mcp`), and an [agent skill](https://cronwatch.dev/docs/agent-skill/) (`npx skills add cronwatchdev/cronwatch`, [on skills.sh](https://www.skills.sh/cronwatchdev/cronwatch)).

### Repositories

- **[cronwatch](https://github.com/cronwatchdev/cronwatch)**: every package, the site, and the docs. Issues and pull requests go here.
- [cronwatch-php](https://github.com/cronwatchdev/cronwatch-php) and [cronwatch-craft](https://github.com/cronwatchdev/cronwatch-craft): read-only copies of the PHP package and the Craft plugin, for Packagist and the Craft Plugin Store.
