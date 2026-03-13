# `rac_ru` OCR Repository

## Overview

`database/rac_ru` is the Oracle Container Registry repository for Oracle Real Application Cluster Release Update Container Images. Oracle lists this repository in the OCR Database business area and publishes both a latest pull command and a tags table for selecting concrete image versions.

## Repository Snapshot

- **Registry path:** `container-registry.oracle.com/database/rac_ru`
- **OCR short description:** Oracle Real Application Cluster Release Update Container Images
- **Latest pull command shown on OCR:** `docker pull container-registry.oracle.com/database/rac_ru:latest-19`
- **License note on OCR:** OCR states that you must accept the Oracle Container Registry Critical Patch Update (CPU) Repository Terms and Restrictions before downloading from this repository.

## What Oracle Documents Here

- The OCR readme describes `rac_ru` as the Release Update container-image line for Oracle RAC in Linux containers.
- The page says RAC on Podman is supported starting with 19c (19.16) and 21c (21.7) for this Release Update stream.
- OCR links the RAC installation guide for Podman on Oracle Linux and covers preparation, network planning, storage, and password management.

## Oracle Version Notes (19c vs 26ai)

The OCR detail page explicitly positions `rac_ru` as a Release Update image stream and documents support on Podman starting with 19c (19.16) and 21c (21.7). The latest OCR pull command currently uses `latest-19`.

## Sources

- https://container-registry.oracle.com/ords/ocr/ba/database/rac_ru
- https://docs.oracle.com/cd/F39414_01/racpd/oracle-real-application-clusters-installation-guide-podman-oracle-linux-x86-64.pdf
- https://docs.oracle.com/en/database/oracle/oracle-database/21/racpd/target-configuration-oracle-rac-podman.html#GUID-59138DF8-3781-4033-A38F-E0466884D008
