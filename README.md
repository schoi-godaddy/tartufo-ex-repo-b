# tartufo-ex-repo-b

Repo B contains uncaught valid sample secrets.

## Key take aways

- Trust but verify potentially sensitive files.
  - Ex) Check [sample.env](./config/sample.env) and even [main.go](./main.go)
- Tartufo is **not a "security tool"**, it's just a tool that helps identifing potentially high entropy string(s).
