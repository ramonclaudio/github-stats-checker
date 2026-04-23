# github-stats-checker

I wanted one call that pulled a full GitHub profile breakdown: every repo, stars, forks, watchers, aggregated totals. The API has the data, `gh` CLI has pieces, but nothing rolled it up with filters for public/private/forks. So I built this.

Python tool for analyzing GitHub profiles and repository statistics.

## Install

```bash
git clone https://github.com/ramonclaudio/github-stats-checker.git
cd github-stats-checker
pip install -r requirements.txt
```

## Configuration

Optional: set a GitHub personal access token (with `read:user` scope) to include private repositories. Without one, public repos only.

```bash
export GITHUB_ACCESS_TOKEN=your_token_here
```

## Usage

```python
import github

github.crawl()
```

## Options

Edit `config.yaml`:

| Option | Type | Default | Description |
| --- | --- | --- | --- |
| `repo_limit` | int | `100` | Max repos to analyze |
| `include_private_repos` | bool | `false` | Include private repos |
| `include_forks` | bool | `true` | Include forks |
| `include_stars` | bool | `true` | Include star counts |
| `include_watchers` | bool | `true` | Include watcher counts |
| `include_overall_totals` | bool | `true` | Show aggregated totals |
| `include_individual_totals` | bool | `true` | Show per-repo breakdown |
| `timeout` | int | `10` | API timeout (seconds) |

## Errors

| Error | When |
| --- | --- |
| `TokenError` | Invalid or missing token |
| `ConfigError` | Bad `config.yaml` |
| `RateLimitError` | API rate limit hit |
| `NetworkError` | Connection issue |
| `ValidationError` | Bad input |

## License

MIT
