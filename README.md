# Tidebreak demo squad, Daily Digest

`tidebreak-demo` is ShakaCode's showroom organization for ShakaFlow (https://shakaflow.com), a Slack app for engineering leads. Every morning ShakaFlow reads the open pull requests of this GitHub organization and the demo squad's tracker, writes each developer a private heads-up about their own stuck items, and sends the lead only what stayed stuck, with the follow-up already drafted. Those messages are published here as plain markdown so anyone, including an AI assistant, can read them next to the source data.

- `latest.md`: this morning's digests.
- `YYYY-MM-DD.md`: one file per day.

The engineers in this organization are invented and the activity is generated. The pull requests, reviews and their timestamps are real GitHub data, so what the digest says can be checked against the organization's own pull-request lists.

## Verify it yourself

The digest watches four repositories. Every pull request it names should be open and in the state it describes; these lists are the source:

- dispatch-api: https://github.com/tidebreak-demo/dispatch-api/pulls
- dispatch-web: https://github.com/tidebreak-demo/dispatch-web/pulls
- crew-mobile: https://github.com/tidebreak-demo/crew-mobile/pulls
- infra: https://github.com/tidebreak-demo/infra/pulls

Tracker items in a digest point at a private Linear workspace and cannot be checked from here. The footer of each digest, "How ShakaFlow decides", states the thresholds, so a quiet day is a deliberate silence, not a miss.

Product: https://shakaflow.com
