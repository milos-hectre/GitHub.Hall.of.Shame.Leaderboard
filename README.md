# GitHub Leaderboard

A client-side web application that generates a leaderboard for any GitHub organization based on stale open unmerged branches and pull requests.

## Usage

1. Open `index.html` in a web browser.

2. Enter the GitHub organization name and your GitHub Personal Access Token in the input fields.

3. Click "Load Leaderboard" to generate the leaderboard.

The application will fetch data from the specified organization's repositories and display a ranked list of contributors based on their stale open branches and pull requests.

## Scoring

- Each open branch older than 2 weeks: 1 point
- Each open pull request older than 2 weeks: 2 points

## Features

- Real-time progress updates during data fetching
- Expandable rows to view individual branches and PRs
- Dark theme UI
- Automatic exclusion of archived repositories and branches associated with pull requests
- Responsive design

## Requirements

- A modern web browser with JavaScript enabled
- A GitHub Personal Access Token with `repo` scope for private repositories (or `public_repo` for public access)

## Privacy

The application runs entirely in your browser. Your GitHub token is only used for API requests and is not stored or transmitted anywhere else.
