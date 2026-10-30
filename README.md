# ILL Email Stats

ILL Email Stats is a command line tool to extract data from emails for interlibrary loan reports.

## Development Environment
This section provides guidance on setting up a NJT development environment on a local workstation.

### Prerequisites
The following instructions assume that "uv" is installed to enable the setup of an isolated Python environment.

See the following for setup instructions:
* https://docs.astral.sh/uv/getting-started/installation/

## Setup

Clone NJT from GitHub

```bash
git clone git@github.com:timkanke/ill-email-stats
cd ill-email-stats
uv venv
source .venv/bin/activate
```

To run program:
```bash
uv run ./src/ill-email-stats.py <path-to-file>
```