# Daily Digest

Squad: #tidebreak-dispatch  
Date: 2026-10-06  
Generated at: 2026-10-06 06:06:12 UTC

> The people are invented. The pull requests and their dates are real.

## Lead digest

### Squad lead

Hey Dan - an unresolved implementation question and an unanswered review need a look today.

🚧 **Worth a look**

[**Retry failed dispatch webhooks with backoff**](https://linear.app/tidebreak-demo/issue/DIS-89/retry-failed-dispatch-webhooks-with-backoff) (DIS-89) - In Progress since Sep 27 (~9 days); [#41](https://github.com/tidebreak-demo/dispatch-api/pull/41) has no human reviews and no substantive code movement since Sep 25. The job-and-attempt-window idempotency key question remains unresolved, including whether it could block legitimate split-shift dispatches.

[**Move crew certification checks into the assignment path**](https://linear.app/tidebreak-demo/issue/DIS-91/move-crew-certification-checks-into-the-assignment-path) (DIS-91) - In Review since Sep 30 (~6 days); [#44](https://github.com/tidebreak-demo/dispatch-api/pull/44) closed unmerged Oct 1 without the core certification check, and no later code activity is shown.

[**Flush the offline queue after reconnect**](https://linear.app/tidebreak-demo/issue/DIS-68/flush-the-offline-queue-after-reconnect) (DIS-68) - In Review since Oct 1 (~5 days); [#26](https://github.com/tidebreak-demo/crew-mobile/pull/26) has no substantive commits after Oct 1, and the Oct 2 request for capped attempts and a failure state remains unanswered.

## Developer digests

No developer digests were delivered.

## How ShakaFlow decides

A pull request counts as waiting for review after about two working days in the reviewer's own time zone, a story in active development with no code after about three, an urgent bug with no activity after about a day. Days off are not counted, a gap that is merely around the line stays silent, and pull requests are followed through the tracker story they belong to. A quiet day is the normal case. Each developer hears about their own items first; the squad lead sees only what stayed stuck, with the follow-up drafted.
