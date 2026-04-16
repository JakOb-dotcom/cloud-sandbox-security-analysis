# Cloud Sandbox Security Analysis

## Abstract
This repository contains a technical case study on environment variable exfiltration within an algorithmic trading competition platform. The research demonstrates a critical lack of sandbox isolation, allowing for the unauthorized access and extraction of sensitive cloud credentials (AWS Access Keys) via standard output streams.

## Key Findings
- **Vulnerability:** Insufficient process isolation within the execution sandbox.
- **Exfiltration Vector:** Direct access to environment variables with subsequent transmission via `stdout`.
- **Risk Level:** Critical (Full infrastructure secret disclosure).

## Status
- **Responsible Disclosure:** The vendor was notified of the findings prior to this publication. 
- **Current State:** Research documentation and Proof of Concept.
