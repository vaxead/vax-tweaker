# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in VAX TWEAKER, please report it responsibly.
Do NOT open a public issue. Contact us via GitHub Security Advisories.

## Supported Versions

| Version | Supported |
|---------|-----------|
| 1.0.x   | Yes       |

## Safety Architecture

VAX TWEAKER is designed with multiple safety layers:

- User-mode only, no kernel drivers, no direct hardware access
- Automatic registry backup before every modification
- CRC32 integrity verification on backup files
- Atomic file writes to prevent data corruption
- Command injection prevention in process execution utilities
- Single-instance mutex to prevent concurrent execution conflicts
