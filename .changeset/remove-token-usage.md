---
"@ai-hero/sandcastle": patch
---

Remove TokenUsage feature from all providers and orchestrator. The TokenUsage interface, extractUsage helper, formatUsageRows function, and usage summary display have been deleted. ParsedStreamEvent's result variant no longer carries a usage field.
