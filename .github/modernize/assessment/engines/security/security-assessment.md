# Security Assessment Report

**Generated:** 2026-09-16T02:36:00.0000000Z

## Summary

| Metric | Count |
|--------|-------|
| Total Findings | 2 |
| CVE Vulnerabilities | 0 |
| CWE Vulnerabilities | 2 |
| Total Rules Assessed | 59 |
| Rules Passed | 57 |

### By Severity

| Severity | Count |
|----------|-------|
| mandatory | 0 |
| optional | 2 |
| potential | 0 |

## CWE Findings (Code-Level Vulnerabilities)

### CWE-259: Use of Hard-coded Password
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** src/main/resources/application.yml:13

The RabbitMQ outbound connection password is hard-coded as `guest` in application.yml:13.

### CWE-798: Use of Hard-coded Credentials
- **Category:** Credentials & Secrets
- **Severity:** optional
- **Story Points:** 5
- **Files:** src/main/resources/application.yml:12, src/main/resources/application.yml:13

RabbitMQ credentials are hard-coded as `guest` for both username (application.yml:12) and password (application.yml:13).
