# `enterprise` OCR Repository

## Overview

`database/enterprise` is the Oracle Container Registry repository for Oracle Database Enterprise Edition. Oracle lists this repository in the OCR Database business area and publishes both a latest pull command and a tags table for selecting concrete image versions.

## Repository Snapshot

- **Registry path:** `container-registry.oracle.com/database/enterprise`
- **OCR short description:** Oracle Database Enterprise Edition
- **Latest pull command shown on OCR:** `docker pull container-registry.oracle.com/database/enterprise:latest`
- **License note on OCR:** OCR presents this as a standard Oracle repository. The detail page prompts you to sign in with an Oracle account to accept the repository license agreement before downloading the image.

## What Oracle Documents Here

- The OCR readme documents this image as Oracle AI Database Server Release 26ai Enterprise Edition running on Oracle Linux 8.
- The page says the image contains a default database in a multitenant configuration with one pluggable database.
- The OCR documentation covers startup, connections, data-volume reuse, and SGA/PGA sizing with `INIT_SGA_SIZE` and `INIT_PGA_SIZE`.

## Oracle Version Notes (19c vs 26ai)

The OCR detail page explicitly documents `enterprise` as the 26ai Enterprise Edition server image. OCR publishes `enterprise_ru` separately for Release Update container images.

## Sources

- https://container-registry.oracle.com/ords/ocr/ba/database/enterprise
