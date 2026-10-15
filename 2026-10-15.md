# Daily Digest

Squad: #tidebreak-dispatch  
Date: 2026-10-15  
Generated at: 2026-10-15 06:03:37 UTC

> The people are invented. The pull requests and their dates are real.

## Lead digest

### Squad lead

Hey Dan - an overdue urgent report, an unowned customer bug, and unresolved review choices need your attention today.

🚧 **Worth a look**

[**Depot handover report for the morning briefing**](https://linear.app/tidebreak-demo/issue/DIS-92/depot-handover-report-for-the-morning-briefing) (DIS-92) - In Progress since Sep 25 (~~19 days), due Oct 2 (~~13 days overdue); no linked or correlated delivery path and no confirmed code activity.

[**Crews see yesterday's job list after crossing a timezone**](https://linear.app/tidebreak-demo/issue/DIS-93/crews-see-yesterdays-job-list-after-crossing-a-timezone) (DIS-93) - Urgent customer bug, Todo since Oct 1 (~13 days); crews at three sites can see yesterday's schedule after an offset change, with no owner, linked PR, or confirmed code activity.

[**Cache crew availability on the board**](https://linear.app/tidebreak-demo/issue/DIS-95) (DIS-95) - In Review since Oct 8 (~6 days); [#42](https://github.com/tidebreak-demo/dispatch-web/pull/42) has no approval. Dan raised the risk of showing assigned crews as free on Oct 9; Tom described the invalidation approach on Oct 10, and Maya proposed socket updates on Oct 12. The design choice remains unresolved.

Sitting with Maya for 10 working days: [**Flush the offline queue after reconnect**](https://linear.app/tidebreak-demo/issue/DIS-68/flush-the-offline-queue-after-reconnect) (DIS-68) - In Review since Oct 1 (~13 days); [#26](https://github.com/tidebreak-demo/crew-mobile/pull/26) has had no author reply or substantive commits since Dan requested retry limits and failure handling on Oct 2.

Sitting with Priya for 1 working day: [**Record every partner webhook attempt**](https://linear.app/tidebreak-demo/issue/DIS-78/record-every-partner-webhook-attempt) (DIS-78) - In Review since Oct 11 (~3.5 days); [#51](https://github.com/tidebreak-demo/dispatch-api/pull/51) has no human review from requested reviewer Dan. Priya's Oct 13 comment only bumped the PR; no substantive code movement since Oct 11.

## Developer digests

### Priya Raman

Hey Priya - one review you can probably unblock:

🚧 **Needs your next move**

[**Record every partner webhook attempt**](https://linear.app/tidebreak-demo/issue/DIS-78/record-every-partner-webhook-attempt) - [PR #51](https://github.com/tidebreak-demo/dispatch-api/pull/51) still has no human review. Could you chase Dan or reroute the review?

Heads-up for you first - unresolved items may later show in your squad lead's digest.

## How ShakaFlow decides

A pull request counts as waiting for review after about two working days in the reviewer's own time zone, a story in active development with no code after about three, an urgent bug with no activity after about a day. Days off are not counted, a gap that is merely around the line stays silent, and pull requests are followed through the tracker story they belong to. A quiet day is the normal case. Each developer hears about their own items first; the squad lead sees only what stayed stuck, with the follow-up drafted.
