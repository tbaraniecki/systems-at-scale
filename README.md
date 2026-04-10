# Systems at Scale

Work-in-progress repository where I document real-world case studies of systems I’ve worked on under production load.

## Scope

This repo focuses on problems I’ve actually run into:

- Asynchronous ingestion pipelines with backpressure
- Handling peak ingestion and uneven traffic
- Distributed system failure modes
- Search infrastructure evolution (e.g. Elasticsearch upgrades)
- Production incident analysis

## Approach

Each case study follows roughly the same structure:

- Context
- Problem
- Constraints
- Options considered
- Decision
- Tradeoffs
- Implementation
- Failure modes
- Outcome
- Retrospective

The focus is on **decision-making under constraints**, not just implementation details.

## Status

I’m adding case studies incrementally.

Planned:

- ingestion-backpressure
- elasticsearch-read-projection-write-architecture
- elasticsearch-migration-es5-to-es7

## Notes

This is not a tutorial repo.

It’s a collection of situations where systems were under real pressure — where things slowed down, broke, or behaved in unexpected ways — and how those problems were approached and resolved.
