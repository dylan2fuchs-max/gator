# Gator 🐊

Gator is a robust command-line RSS feed aggregator built in Go. It enables users to register, manage accounts, follow/unfollow RSS feeds, continuously scrape updates in the background, and browse the latest posts right from the terminal, all backed by a PostgreSQL database.

## Prerequisites

To run Gator, make sure you have the following installed on your machine:
- **Go** (version 1.22 or newer)
- **PostgreSQL** (running locally or accessible via a connection string)

## Installation

You can install Gator directly using `go install`:

```bash
go install [github.com/YOUR_GITHUB_USERNAME/gator@latest](https://github.com/YOUR_GITHUB_USERNAME/gator@latest)