# Reproduction for https://github.com/renovatebot/renovate/issues/21365

## Expected results

Renovate bot runs do not end up with an `external-host-error` as it encounters the `omnition/opentelemetry-collector-contrib:0.2.8` image in a `docker-compose.yml` file.

## Actual results

Renvoate bot fails with `external-host-error` without recovering in subsequent runs.
