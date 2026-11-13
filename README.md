# Search Engine
A web search engine written in Go.

## Status

Early development. See [docs/roadmap.md](docs/roadmap.md) for planned
features and current progress.

## Architecture

[Crawler] → [Parser] → [Indexer] → [Storage]
↓
[Query] → [Search] → [Ranker] → [Results]


See [docs/architecture.md](docs/architecture.md) for details.

## Getting Started

```bash
# Prerequisites: Go 1.22+
make build
make run

# Or directly:
go run ./cmd/server

Server listens on :8080 by default.
