# Changelog

## November 13, 2026

- **This change requires Fabricate >= 5.0.0**
- Added new `DANGEROUS_FABRICATE_ALLOW_INTERNAL_IPS` env var, which allows Fabricate to connect to specific private subnets, IPs or domains. Connections to private IP addresses are blocked by default. No infrastructure changes are required.
- See full v5.0.0 changelog: https://www.tonic.ai/tonic-fabricate-release-notes/5-0-0

## November 11, 2026

- **This change requires Fabricate >= 4.41.0**
- Added new `FABRICATE_PDF_HOST` and `FABRICATE_PDF_PORT` env vars for the `pdf-sidecar` container. The `FABRICATE_PDF_SOCKET_PATH` env var is now deprecated but preserved for backward compatibility, so existing instances with an older `docker-compose.yml` can keep using it. All new instances should use `FABRICATE_PDF_HOST`, `FABRICATE_PDF_PORT` and the latest updated `docker-compose.yml`.
- It is highly encouraged to make a backup before upgrading.
- See full v4.41.0 changelog: https://www.tonic.ai/tonic-fabricate-release-notes/4-41-0

## October 22, 2026

- **This change requires Fabricate >= 4.39.0**
- Added `FABRICATE_GCP_IMPERSONATOR_*` env vars. No infrastructure changes are required.
- See full v4.39.0 changelog: https://www.tonic.ai/tonic-fabricate-release-notes/4-39-0

## October 1, 2026

- **This change requires Fabricate >= 4.32.0**
- Added `FABRICATE_OPENAI_*` env vars. No infrastructure changes are required.
- See full v4.32.0 changelog: https://www.tonic.ai/tonic-fabricate-release-notes/4-32-0

## September 21, 2026

- **This change requires Fabricate >= 4.30.0**
- Added `FABRICATE_CA_CERT_FILE` env var. No infrastructure changes are required.
- See full v4.30.0 changelog: https://www.tonic.ai/tonic-fabricate-release-notes/4-30-0

## May 26, 2026

- **This change requires Fabricate >= 4.1.0**
- Added env vars for Google Gemini Enterprise Agent Platform. No infrastructure changes are required.
- See full v4.1.0 changelog: https://www.tonic.ai/tonic-fabricate-release-notes/4-1-0

## May 12, 2026

- **This change requires Fabricate >= 4.1.0**
- Renamed env var to `FABRICATE_STORAGE_SERVICE`. No infrastructure changes are required.
- See full v4.1.0 changelog: https://www.tonic.ai/tonic-fabricate-release-notes/4-1-0

## May 5, 2026

- Initial release.
