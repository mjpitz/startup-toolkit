# startup-toolkit

Starting a company or looking for some tooling to complement your existing applications?
Here are some tools I've used and how they've helped.

## The startup spectrum

The term "startup" often refers to a large range of companies.
A startup could be 1 or 2 people just starting to put an idea together seeking seed funding.
A startup could also be a 30 person company with the start of sales and engineering organizations.
As a result, this can cause ambiguity when referring to startups as a collective.

In starting this list, I wanted to keep this fact in mind.
Some tools might be more useful at different stages of a company's development.

## Table of Contents

- [Redash](#Redash)
- [Renovate](#Renovate)

[postgresql]: https://postgresql.org
[redis]: https://redislabs.com

### Redash

- Query across multiple data sources like databases, Google Analytics, and so much more.
- Easily provide read-only access to your production databases protected by SSO and 2FA.
- Build, store, and schedule queries to pull information from different data sources.
- Construct visualizations to better display query data.
- Create interactive dashboards from queries and visualizations.

|               |                                        |
| :------------ | :------------------------------------- |
| Availability  | Self-host or hosted service            |
| Documentation | http://redash.io/help                  |
| GitHub        | http://github.com/getredash/redash     |
| Deployment    | Service - Virtual Machine or Container |
| Dependencies  | [PostgreSQL][], [Redis][]              |

### Renovate

- Stay on top of dependency versions

|               |                                         |
| :------------ | :-------------------------------------- |
| Availability  | Self-host or hosted service             |
| Documentation | https://renovatebot.com/                |
| GitHub        | https://github.com/renovatebot/renovate |
| Deployment    | CronJob - Virtual Machine or Container  |
| Dependencies  | None                                    |
