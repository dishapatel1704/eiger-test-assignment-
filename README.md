# Eiger Test Assignment – Network Intelligence

## Overview

This repository contains my completed **Eiger Test Assignment** for the evaluation process at **Network Intelligence**.

The assignment involved analyzing the provided environment, identifying security vulnerabilities, demonstrating the vulnerable behavior, implementing security hardening, and validating the effectiveness of the implemented controls.

## Objective

The primary objectives of the assignment were to:

* Set up and understand the provided environment.
* Identify and reproduce the relevant security vulnerabilities.
* Analyze the security impact of the identified issues.
* Implement appropriate security controls and hardening measures.
* Verify that the vulnerabilities were no longer exploitable after hardening.
* Validate the final implementation using the provided test and capstone workflow.

## Implementation Approach

The assignment was completed in the following stages:

### 1. Environment Setup

Configured and tested the provided environment using the required tooling and Docker-based setup.

During the setup process, Docker/TLS-related connectivity and timeout issues were investigated and resolved to establish a working environment for testing.

### 2. Vulnerability Assessment

The initial implementation was assessed to identify security weaknesses.

The vulnerable implementation demonstrated that:

* Sensitive secrets could be exposed.
* An attacker could ingest unauthorized policy content.
* Malicious policy content could subsequently be retrieved.

These behaviors were reproduced as part of the vulnerability assessment.

### 3. Security Hardening

Security controls were implemented to address the identified vulnerabilities.

The hardened implementation focused on:

* Preventing exposure of sensitive secrets.
* Restricting unauthorized policy ingestion.
* Preventing retrieval of malicious or unauthorized policy content.
* Validating that security controls were enforced consistently.

### 4. Vulnerability Validation

After implementing the security controls, the same relevant scenarios were tested again against the hardened environment.

The results confirmed that the previously demonstrated vulnerable behavior was mitigated.

## M9 Test Results

| Test                       | Vulnerable | Hardened        |
| -------------------------- | ---------- | --------------- |
| Secret exposed             | ❌ Yes      | ✅ No / Redacted |
| Attacker can ingest policy | ❌ Yes      | ✅ Rejected      |
| Malicious policy retrieved | ❌ Yes      | ✅ Prevented     |

The comparison demonstrates the difference between the original vulnerable implementation and the hardened implementation.

## Capstone Status

The **capstone task was performed and the hardened implementation was successfully validated**.

The final validation confirmed that the implemented security controls addressed the identified vulnerabilities.

**Status: Hardened and Validated ✅**

## Key Security Outcomes

The completed implementation demonstrated:

* Identification of security vulnerabilities.
* Controlled reproduction of vulnerable behavior.
* Protection of sensitive information.
* Enforcement of policy ingestion controls.
* Prevention of unauthorized or malicious policy retrieval.
* Successful security hardening.
* Validation of the hardened implementation through testing.

## Technologies and Tools

* Docker
* Docker Compose
* TLS / Secure Communication
* Git
* GitHub
* Command Line
* Security testing and validation tools

## Repository Structure

```text
.
├── README.md
├── report
```

> The actual repository structure may vary according to the files included with the assignment.

## Conclusion

The Eiger Test Assignment provided practical experience in vulnerability assessment, security hardening, secure configuration, and validation.

The vulnerable implementation was successfully analyzed and tested, the identified security issues were addressed through hardening, and the resulting implementation was successfully validated.

## Submission

**Assignment:** Eiger Test Assignment
**Organization:** Network Intelligence
**Status:** Hardened and Validated

**Assignment Walkthrough Video::**
*https://drive.google.com/drive/folders/1xoDPM3G0n86EY4k4iQvbnkigJpK3JJ-E?usp=sharing*
