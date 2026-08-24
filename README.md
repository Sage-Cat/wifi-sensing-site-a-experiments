# Wi-Fi sensing data: site A

Sanitized raw measurements from three anonymized operational captures:

- `AC01`: one 2.4 GHz sensor, 24-hour natural-operation baseline;
- `AC02`: two 2.4 GHz sensors with raw controller and read-only AP context;
- `AC03`: two 2.4 GHz sensors plus one 5 GHz sensor, endurance capture.

Each directory under `datasets/` contains only captured data: chunked sensor
records in `serial/`, collector telemetry in `logs/`, controller/context event
streams when present, and one sanitized `metadata.json`. Files ending in
`.incomplete` are preserved partial raw chunks, not analysis products.

Network names, addresses, device identifiers, credentials, exact location, and
private control arguments were removed or replaced before publication. No
analysis, derived tables, validators, capture tooling, or private configuration
is included. Dataset limitations are recorded in each `metadata.json`.

Data and documentation reuse terms are in [LICENSE.md](LICENSE.md).
