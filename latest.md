# Daily Digest

Squad: #tidebreak-dispatch  
Date: 2026-10-05  
Generated at: 2026-10-05 06:05:58 UTC

> The people are invented. The pull requests and their dates are real.

## Lead digest

### Squad lead

Hey Dan - an unassigned customer bug and an overdue delivery path need a decision today.

🚧 **Worth a look**

[**Crews see yesterday's job list after crossing a timezone**](https://linear.app/tidebreak-demo/issue/DIS-93/crews-see-yesterdays-job-list-after-crossing-a-timezone) (DIS-93) - Urgent, Todo since Oct 1 (~3.5 days); three customer sites are affected this week, with no assignee or confirmed code path. [#47](https://github.com/tidebreak-demo/dispatch-api/pull/47) does not contain a timezone/job-list fix; no individual is assigned to take this.

Sitting with Tom Lindqvist for 4 working days: [**Depot handover report for the morning briefing**](https://linear.app/tidebreak-demo/issue/DIS-92/depot-handover-report-for-the-morning-briefing) (DIS-92) - In Progress since Sep 30 (~4.5 days), Urgent and 3 days past its Oct 2 due date; no confidently identified code path, and supervisors still rebuild the overnight report manually.

:rocket: **What's done since last digest**  
:white_check_mark: [DIS-72 Reassign a crew's day in one pass](https://linear.app/tidebreak-demo/issue/DIS-72/reassign-a-crews-day-in-one-pass)

## Developer digests

### Maya Ortiz

Hey Maya - a couple of things you can probably unblock:

🚧 **Needs your next move**

[**Move crew certification checks into the assignment path**](https://linear.app/tidebreak-demo/issue/DIS-91/move-crew-certification-checks-into-the-assignment-path) - still no replacement review path since Oct 2; [PR #44](https://github.com/tidebreak-demo/dispatch-api/pull/44) closed unmerged Oct 1. Could you propose the next implementation approach?

[**Flush the offline queue after reconnect**](https://linear.app/tidebreak-demo/issue/DIS-68/flush-the-offline-queue-after-reconnect) - [PR #26](https://github.com/tidebreak-demo/crew-mobile/pull/26) still needs capped retries and a surfaced failure state. Could you address those requests or suggest a smaller approach?

Heads-up for you first - unresolved items may later show in your squad lead's digest.

## How ShakaFlow decides

A pull request counts as waiting for review after about two working days in the reviewer's own time zone, a story in active development with no code after about three, an urgent bug with no activity after about a day. Days off are not counted, a gap that is merely around the line stays silent, and pull requests are followed through the tracker story they belong to. A quiet day is the normal case. Each developer hears about their own items first; the squad lead sees only what stayed stuck, with the follow-up drafted.
