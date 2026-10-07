# ZebraPuma Claude Code plugins

The [Claude Code](https://code.claude.com) plugin marketplace of [ZebraPuma Services](https://zebrapuma.be): pragmatic tooling for data, delivery and project management.

## Add the marketplace

```bash
claude plugin marketplace add zebrapuma/claude-plugins
```

Then install any plugin below with `claude plugin install <plugin>@zebrapuma`.

## Plugins

| Plugin | What it does | Install |
|---|---|---|
| [`zps-pareto`](https://github.com/zebrapuma/zps-pareto-github-issues) | Never lose a request: every request becomes a GitHub issue, scored with the 80/20 rule, so you always work on the vital few first. Works on one repository or across a portfolio of repositories. | `claude plugin install zps-pareto@zebrapuma` |

All ZebraPuma plugins share the `zps-` prefix, so they group together when you type `/zps` in Claude Code.

## Updates

Each plugin entry is pinned to a released tag (`<plugin>--vX.Y.Z`): a new version reaches users only once its `ref` is moved here. Third-party marketplaces do not update automatically, so users run:

```bash
claude plugin marketplace update zebrapuma
claude plugin update <plugin>@zebrapuma
```

or turn on auto-update for `zebrapuma` in `/plugin`, **Marketplaces**.

## Issues

Report bugs and feature requests in each plugin's own repository.

## About

Curated by [Régis Scyeur](https://regis.scyeur.net/en/), Slasher / Digital Architect / Coach, at [ZebraPuma Services](https://zebrapuma.be). Everything open from the workshop lives at [github.com/zebrapuma](https://github.com/zebrapuma).

## License

[MIT](LICENSE) © ZebraPuma Services
