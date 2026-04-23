<p align="center">
    <a href="https://github.com/" title="Go to GitHub homepage">
        <img src="https://img.shields.io/badge/GitHub-fafafa?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMiIgaGVpZ2h0PSIzMiIgdmlld0JveD0iMCAwIDMyIDMyIiBmaWxsPSJub25lIj4KICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMTYgMEM3LjE2IDAgMCA3LjE2IDAgMTZDMCAyMy4wOCA0LjU4IDI5LjA2IDEwLjk0IDMxLjE4QzExLjc0IDMxLjMyIDEyLjA0IDMwLjg0IDEyLjA0IDMwLjQyQzEyLjA0IDMwLjA0IDEyLjAyIDI4Ljc4IDEyLjAyIDI3LjQ0QzggMjguMTggNi45NiAyNi40NiA2LjY0IDI1LjU2QzYuNDYgMjUuMSA1LjY4IDIzLjY4IDUgMjMuM0M0LjQ0IDIzIDMuNjQgMjIuMjYgNC45OCAyMi4yNEM2LjI0IDIyLjIyIDcuMTQgMjMuNCA3LjQ0IDIzLjg4QzguODggMjYuMyAxMS4xOCAyNS42MiAxMi4xIDI1LjJDMTIuMjQgMjQuMTYgMTIuNjYgMjMuNDYgMTMuMTIgMjMuMDZDOS41NiAyMi42NiA1Ljg0IDIxLjI4IDUuODQgMTUuMTZDNS44NCAxMy40MiA2LjQ2IDExLjk4IDcuNDggMTAuODZDNy4zMiAxMC40NiA2Ljc2IDguODIgNy42NCA2LjYyQzcuNjQgNi42MiA4Ljk4IDYuMiAxMi4wNCA4LjI2QzEzLjMyIDcuOSAxNC42OCA3LjcyIDE2LjA0IDcuNzJDMTcuNCA3LjcyIDE4Ljc2IDcuOSAyMC4wNCA4LjI2QzIzLjEgNi4xOCAyNC40NCA2LjYyIDI0LjQ0IDYuNjJDMjUuMzIgOC44MiAyNC43NiAxMC40NiAyNC42IDEwLjg2QzI1LjYyIDExLjk4IDI2LjI0IDEzLjQgMjYuMjQgMTUuMTZDMjYuMjQgMjEuMyAyMi41IDIyLjY2IDE4Ljk0IDIzLjA2QzE5LjUyIDIzLjU2IDIwLjAyIDI0LjUyIDIwLjAyIDI2LjAyQzIwLjAyIDI4LjE2IDIwIDI5Ljg4IDIwIDMwLjQyQzIwIDMwLjg0IDIwLjMgMzEuMzQgMjEuMSAzMS4xOEMyNy40MiAyOS4wNiAzMiAyMy4wNiAzMiAxNkMzMiA3LjE2IDI0Ljg0IDAgMTYgMFYwWiIgZmlsbD0iIzI0MjkyRSIvPgo8L3N2Zz4=" alt="GitHub">
    </a>
</p>

<p align="center">
    <a href="https://github.com/ramonclaudio/github-stats-checker" title="Go to repo">
        <img src="https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=GitHub%20Stats%20Checker&query=version&url=https%3A%2F%2Fraw.githubusercontent.com%2FRamon Claudio%2Fgithub-stats-checker%2Fmain%2F.github%2Fversion.json" alt="GitHub Stats Checker">
    </a>
</p>

<p align="center">
    <a href=".github/CHANGELOG.md" title="Go to changelog"><img src="https://img.shields.io/badge/maintained-yes-2ea44f?style=for-the-badge" alt="maintained - yes"></a>
    <a href=".github/CONTRIBUTING.md" title="Go to contributions doc"><img src="https://img.shields.io/badge/contributions-welcome-2ea44f?style=for-the-badge" alt="contributions - welcome"></a>
</p>

<p align="center">
    <a href="/">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ramonclaudio/github-stats-checker/main/.github/github-logo-dark.png">
          <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ramonclaudio/github-stats-checker/main/.github/github-logo-light.png">
          <img alt="GitHub" width="250" src="https://raw.githubusercontent.com/ramonclaudio/github-stats-checker/main/.github/github-logo-dark.png">
        </picture>
    </a>
</p>

A Python tool for analyzing GitHub profiles and repository statistics. This tool allows you to fetch comprehensive statistics about any GitHub user's repositories, including stars, forks, watchers, and more.

## 🚀 Features

- 📊 **Profile Analytics**: Fetch comprehensive GitHub user profile information and statistics
- 📈 **Repository Stats**: Analyze stars, forks, watchers, and other metrics for repositories
- 🔒 **Private Repos**: Support for private repository access with proper authentication
- 🪶 **Lightweight Design**: Minimal dependencies for easy setup and deployment
- 🔒 **Robust Error Handling**: Comprehensive error catching and validation

## 📋 Table of Contents

- [Installation](#-installation)
- [Authentication](#-authentication-optional)
- [Configuration](#-configuration-optional)
- [Usage](#-usage)
- [Advanced Configuration](#%EF%B8%8F-advanced-configuration)
- [Error Handling and Safety](#-error-handling-and-safety)
- [Contributing](#-contributing)
- [Issues and Support](#-issues-and-support)
- [Feature Requests](#-feature-requests)
- [Versioning and Changelog](#-versioning-and-changelog)
- [Security](#-security)
- [License](#-license)

## 🛠 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ramonclaudio/github-stats-checker.git
   ```

2. Navigate to the repository folder:
   ```bash
   cd github-stats-checker
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🔒 Authentication (*Optional*)

In order to access private repositories, you must provide a personal access token with the `read:user` scope selected.

> [!IMPORTANT]  
> Without a personal access token, this tool will not be able to access private repositories.

## 🔑 Configuration (*Optional*)
1. Obtain an access token from [GitHub](https://github.com/settings/tokens).
2. You have three options for managing your access token:
   <details>
   <summary>Click here to view the access token configuration options</summary>
   
   - **Setting it as an environment variable on your device (recommended for everyday use)**
       - Navigate to your terminal.
       - Add your access token like so:
         ```shell
         export GITHUB_ACCESS_TOKEN=YOUR_GITHUB_ACCESS_TOKEN_HERE
         ```
       This method allows the access token to be loaded automatically when using the wrapper.
     
   - **Using an .env file (recommended for development):**
       - Install python-dotenv if you haven't already: `pip install python-dotenv`.
       - Create a .env file in the project's root directory or rename `example.env` to `.env`.
       - Add your access token to the .env file like so:
         ```makefile
         GITHUB_ACCESS_TOKEN=YOUR_GITHUB_ACCESS_TOKEN_HERE
         ```
       This method allows the access token to be loaded automatically when using the wrapper.
   </details>

## 💻 Usage

```python
import github

github.crawl()
```

## ⚙️ Advanced Configuration

*You can customize the behavior of the tool by modifying the `config.yaml` file in the root directory of the repository.*

| Option | Type | Description | Default |
|--------|------|-------------|---------|
| `repo_limit` | Integer | Maximum repositories to analyze | `100` |
| `include_private_repos` | Boolean | Include private repositories | `false` |
| `include_forks` | Boolean | Include forked repositories | `true` |
| `include_stars` | Boolean | Include repository stars | `true` |
| `include_watchers` | Boolean | Include repository watchers | `true` |
| `include_overall_totals` | Boolean | Show combined statistics | `true` |
| `include_individual_totals` | Boolean | Show per-repository stats | `true` |
| `timeout` | Integer | API request timeout (seconds) | `10` |

## 🔒 Error Handling and Safety

| Error Type | Description | Solution |
|------------|-------------|----------|
| `TokenError` | Invalid/missing token | Check token permissions |
| `ConfigError` | Configuration issues | Verify config.yaml |
| `RateLimitError` | API rate limiting | Wait or use authentication |
| `NetworkError` | Connection issues | Check internet connection |
| `ValidationError` | Invalid parameters | Verify input parameters |

## 🤝 Contributing
Contributions are welcome!

Please refer to [CONTRIBUTING.md](.github/CONTRIBUTING.md) for detailed guidelines on how to contribute to this project.

## 🐛 Issues and Support
Encountered a bug? We'd love to hear about it. Please follow these steps to report any issues:

1. Check if the issue has already been reported.
2. Use the [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md) template to create a detailed report.
3. Submit the report [here](https://github.com/ramonclaudio/github-stats-checker/issues).

Your report will help us make the project better for everyone.

## 💡 Feature Requests
Got an idea for a new feature? Feel free to suggest it. Here's how:

1. Check if the feature has already been suggested or implemented.
2. Use the [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md) template to create a detailed request.
3. Submit the request [here](https://github.com/ramonclaudio/github-stats-checker/issues).

Your suggestions for improvements are always welcome.

## 🔁 Versioning and Changelog
Stay up-to-date with the latest changes and improvements in each version:

- [CHANGELOG.md](.github/CHANGELOG.md) provides detailed descriptions of each release.

## 🔐 Security
Your security is important to us. If you discover a security vulnerability, please follow our responsible disclosure guidelines found in [SECURITY.md](.github/SECURITY.md). Please refrain from disclosing any vulnerabilities publicly until said vulnerability has been reported and addressed.

## 📄 License
Licensed under the MIT License. See [LICENSE](LICENSE) for details.