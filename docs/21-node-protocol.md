# TIME-OS Unified Developer Specification
## Section 21 — Node Protocol (TNP)

### 21.1 Purpose of This Section
Defines the TIME-OS Node Protocol (TNP), the communication and synchronization protocol used by all nodes.

## 21.2 TNP Fundamentals
TNP ensures:
- Deterministic replay
- Ledger synchronization
- TMV consistency
- Pack state consistency

## 21.3 Node Message Types
Messages include:
- Ledger delta
- TMV update
- Pack update
- Routing directive
- Compliance alert

## 21.4 Node Sync Rules
Sync requires:
- Identical inputs
- Identical outputs
- Deterministic ordering
- Compliance validation

## 21.5 Node Failure Modes
Failures include:
- Sync divergence
- TMV mismatch
- Pack mismatch
- Routing mismatch

## End of Section 21 — Node Protocol
