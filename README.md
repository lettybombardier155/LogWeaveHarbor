# LogWeaveHarbor

LogWeaveHarbor reads logs from multiple services and threads them into unified timelines based on correlation IDs or context keys.

## Features
- Multi-source log stitching via correlation ID.
- Customizable log parsing adapters.
- Outputs merged JSON or timeline reports.
- CLI tool or Python API usage.

## Usage
```bash
git clone https://github.com/your-org/LogWeaveHarbor.git
cd LogWeaveHarbor
python logweave/weaver.py logs/
