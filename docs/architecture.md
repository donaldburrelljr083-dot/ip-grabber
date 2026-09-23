# Architecture Overview

## System Design

The decoy application operates as a lightweight service that:

### 1. Surface Layer
- Exposes simulated service banners and responses
- Mimics common vulnerability signatures to trigger automated scanning tools
- Uses randomized but realistic response patterns

### 2. Collection Layer
- Captures connection metadata (source IP, timestamps, payloads)
- Stores logs locally in structured JSON format
- Optionally forwards to external SIEM via syslog/API

### 3. Analysis Layer
- Parses collected logs for pattern recognition
- Generates IOC reports automatically
- Supports export to STIX/TAXII formats

## Data Flow

## Security Considerations

- All logs are stored locally by default
- No outbound connections from the decoy itself
- Designed to run in air-gapped or isolated environments
- Configuration files should never contain sensitive credentials in production
