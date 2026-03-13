# `instantclient` OCR Repository

## Overview

`database/instantclient` is the Oracle Container Registry repository for Oracle Instant Client. Oracle lists this repository in the OCR Database business area and publishes both a latest pull command and a tags table for selecting concrete image versions.

## Repository Snapshot

- **Registry path:** `container-registry.oracle.com/database/instantclient`
- **OCR short description:** Oracle Instant Client
- **Latest pull command shown on OCR:** `docker pull container-registry.oracle.com/database/instantclient:latest`
- **License note on OCR:** OCR presents this as a standard Oracle repository. The detail page prompts you to sign in with an Oracle account to accept the repository license agreement before downloading the image.

## What Oracle Documents Here

- The OCR readme says this image contains the Oracle Instant Client Basic, SDK, and SQL*Plus packages.
- The page says you can extend the image to run OCI, OCCI, and JDBC applications, or scripting-language drivers that use OCI.
- The OCR detail page includes both `latest` and versioned tags for selecting a specific Instant Client release.

## Oracle Version Notes (19c vs 26ai)

The OCR detail page does not publish a dedicated 19c-versus-26ai matrix for `instantclient`. Use the OCR tags table to pick the client version that matches your target environment.

## Sources

- https://container-registry.oracle.com/ords/ocr/ba/database/instantclient
