# `sqlcl` OCR Repository

## Overview

`database/sqlcl` is the Oracle Container Registry repository for Oracle SQL Command Line (SQLcl). Oracle lists this repository in the OCR Database business area and publishes both a latest pull command and a tags table for selecting concrete image versions.

## Repository Snapshot

- **Registry path:** `container-registry.oracle.com/database/sqlcl`
- **OCR short description:** Oracle SQL Command Line (SQLcl)
- **Latest pull command shown on OCR:** `docker pull container-registry.oracle.com/database/sqlcl:latest`
- **License note on OCR:** OCR states that the software in this repository is licensed under the Oracle Free Use Terms and Conditions provided in the container image.

## What Oracle Documents Here

- The OCR readme documents this repository as the Oracle SQLcl Docker image and describes SQLcl as a free command line interface for Oracle Database.
- The page says the image contains the latest SQLcl release available and can be used anywhere Docker can run.
- OCR also documents running SQLcl interactively, passing standard SQLcl options on the `docker run` command line, and mounting `/opt/oracle/sql_scripts` for local script access.

## Oracle Version Notes (19c vs 26ai)

The OCR detail page tracks SQLcl image releases instead of a 19c-versus-26ai database matrix. The page itself is titled as SQLcl 25.4.2 Docker image documentation, so use the repository tags table to pin the release you want.

## Sources

- https://container-registry.oracle.com/ords/ocr/ba/database/sqlcl
- https://www.oracle.com/database/technologies/appdev/sqlcl.html
- https://www.oracle.com/downloads/licenses/oracle-free-license.html
