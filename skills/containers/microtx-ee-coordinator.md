# `microtx-ee-coordinator` OCR Repository

## Overview

`database/microtx-ee-coordinator` is the Oracle Container Registry repository for Oracle Transaction Manager for Microservices (MicroTx) Enterprise Edition. Oracle lists this repository in the OCR Database business area and publishes both a latest pull command and a tags table for selecting concrete image versions.

## Repository Snapshot

- **Registry path:** `container-registry.oracle.com/database/microtx-ee-coordinator`
- **OCR short description:** Oracle Transaction Manager for Microservices (MicroTx) Enterprise Edition
- **Latest pull command shown on OCR:** `docker pull container-registry.oracle.com/database/microtx-ee-coordinator:latest`
- **License note on OCR:** OCR presents this as a standard Oracle repository. The detail page prompts you to sign in with an Oracle account to accept the repository license agreement before downloading the image.

## What Oracle Documents Here

- The OCR readme says MicroTx Enterprise Edition helps maintain transaction consistency across distributed microservices applications.
- The page explicitly lists XA, Saga based on Eclipse MicroProfile Long Running Action (LRA), and Try-Confirm/Cancel (TCC) as supported distributed-transaction protocols.
- OCR also says the Enterprise Edition adds features such as transaction promotion, metrics visualization, and use of the MicroTx console.

## Oracle Version Notes (19c vs 26ai)

The OCR detail page tracks MicroTx image releases rather than a 19c-versus-26ai database matrix. Use the repository tags table to choose the coordinator version you need.

## Sources

- https://container-registry.oracle.com/ords/ocr/ba/database/microtx-ee-coordinator
- https://docs.oracle.com/pls/topic/lookup?ctx=microtx-latest&id=TMMLI-GUID-97C20FE6-4DA2-4699-96EB-BB26472FCCBE
- https://docs.oracle.com/pls/topic/lookup?ctx=microtx-latest&id=TMMDG-GUID-F6ED47D2-97FE-481E-A41E-C320A3611C0B
