# Daily Digest

Squad: #tidebreak-dispatch  
Date: 2026-10-03  
Generated at: 2026-10-03 06:03:23 UTC

> The people are invented. The pull requests and their dates are real.

## Lead digest

### Squad lead

Hey Dan - the webhook change is still stalled, and a closed PR has left its issue in the wrong review state.

🚧 **Worth a look**

Sitting with Tom Lindqvist for 4 working days: [**Retry failed dispatch webhooks with backoff**](https://linear.app/tidebreak-demo/issue/DIS-89/retry-failed-dispatch-webhooks-with-backoff) (DIS-89) - High priority, In Progress since Sep 27 (~5.5 days), with no substantive code movement since Tom's Sep 25 commits; [#41](https://github.com/tidebreak-demo/dispatch-api/pull/41) has no human review, and the five-minute idempotency question remains unanswered.

🍏 **Cleanup**

This one is Maya Ortiz's: [**Move crew certification checks into the assignment path**](https://linear.app/tidebreak-demo/issue/DIS-91/move-crew-certification-checks-into-the-assignment-path) (DIS-91) - In Review since Sep 30 (~2.5 days), though [#44](https://github.com/tidebreak-demo/dispatch-api/pull/44) was closed unmerged on Oct 1; Maya's comment says assignment-time enforcement breaks bulk import before certifications sync.

:rocket: **What's done since last digest**  
:white_check_mark: [DIS-82 Badge jobs that still have unsent changes](https://linear.app/tidebreak-demo/issue/DIS-82/badge-jobs-that-still-have-unsent-changes)

## Developer digests

### Tom Lindqvist

Hey Tom - a couple of things you can probably unblock:

🚧 **Needs your next move**

[**Depot handover report for the morning briefing**](https://linear.app/tidebreak-demo/issue/DIS-92/depot-handover-report-for-the-morning-briefing) - the Oct 2 due date has passed without a reviewable code path; if this is still active, open a PR, or update the story if plans changed.

[**Retry failed dispatch webhooks with backoff**](https://linear.app/tidebreak-demo/issue/DIS-89/retry-failed-dispatch-webhooks-with-backoff) - still no code movement since Sep 25; could you settle the five-minute idempotency question on [**PR #41**](https://github.com/tidebreak-demo/dispatch-api/pull/41) and ask Dan for review when ready?

Heads-up for you first - unresolved items may later show in your squad lead's digest.

## How ShakaFlow decides

A pull request counts as waiting for review after about two working days in the reviewer's own time zone, a story in active development with no code after about three, an urgent bug with no activity after about a day. Days off are not counted, a gap that is merely around the line stays silent, and pull requests are followed through the tracker story they belong to. A quiet day is the normal case. Each developer hears about their own items first; the squad lead sees only what stayed stuck, with the follow-up drafted.
