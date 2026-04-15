---
"@ai-hero/sandcastle": patch
---

Change agent provider `buildPrintCommand` and `buildInteractiveArgs` to accept an options object `{ prompt, dangerouslySkipPermissions }` instead of a bare prompt string. The `claudeCode()` factory now conditionally includes `--dangerously-skip-permissions` based on the boolean.
