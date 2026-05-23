# libbrotni

It provides a minimal, high-performance client for distributed systems to request AI execution context (routing, quotas, configuration) and safely execute decisions made by the Brotni control plane.

## Features

- Context API client for AI decision retrieval
- MQTT / HTTP / gRPC communication support
- Lightweight caching for edge resilience
- Offline-safe fallback execution helpers
- Telemetry reporting for usage and cost signals
- Cross-platform support (embedded, edge, server)

libbrotni does NOT make decisions — it enables systems to consume decisions from Brotni.
