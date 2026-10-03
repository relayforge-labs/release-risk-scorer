# release-risk-scorer

Summarize release risk from change metadata and test evidence.

## Run

Requires Node.js 20+.

```sh
npm start
```

The tool reads its development gateway settings from `settings/dev.env`. Override those values in your deployment environment before production use. Review generated output before applying it to another system.

## Model

This example targets the `gpt-6-astra` frontier model through the configured OpenAI-compatible router.
