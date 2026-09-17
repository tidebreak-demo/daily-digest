# Daily Digest

Squad: #tidebreak-dispatch  
Date: 2026-09-17  
Generated at: 2026-09-17 10:00:59 UTC

> The people are invented. The pull requests and their dates are real.

## Lead digest

### Squad lead

Hey Dan - several of Tom's PRs are sitting without response to your review feedback, and a finished story still needs to be closed out.

🚧 **Worth a look**

[**Retry the dispatch webhook when the carrier endpoint times out**](https://linear.app/tidebreak-demo/issue/DIS-59/retry-the-dispatch-webhook-when-the-carrier-endpoint-times-out) (DIS-59) - your changes-requested review on [#22](https://github.com/tidebreak-demo/dispatch-api/pull/22) has had no response from Tom. Sitting with him for 3 working days.

[**Split the crew roster query so dispatch stops timing out**](https://linear.app/tidebreak-demo/issue/DIS-61/split-the-crew-roster-query-so-dispatch-stops-timing-out) (DIS-61) - same pattern: your changes-requested review on [#24](https://github.com/tidebreak-demo/dispatch-api/pull/24) with no response from Tom.

[**Reject job assignments that overlap an existing shift**](https://linear.app/tidebreak-demo/issue/DIS-63/reject-job-assignments-that-overlap-an-existing-shift) (DIS-63) - same pattern on [#26](https://github.com/tidebreak-demo/dispatch-api/pull/26), changes requested with no follow-up from Tom.

[**Upgrade the scheduling engine's dependency set**](https://linear.app/tidebreak-demo/issue/DIS-62/upgrade-the-scheduling-engines-dependency-set) (DIS-62) - [#25](https://github.com/tidebreak-demo/dispatch-api/pull/25) is out of draft with no reviewer requested; last real code authored Sep 4 (~13 days ago). Sitting with Tom for 3 working days.

🍏 **Cleanup**

[**Add a depot filter to the dispatch queue**](https://linear.app/tidebreak-demo/issue/DIS-49/add-a-depot-filter-to-the-dispatch-queue) (DIS-49) - In Progress since Aug 27 (~21 days), but the depot filter already shipped via DIS-47 on Aug 20. Comments from Zakir confirm no further work is needed - board state just needs to catch up.

## Developer digests

### Tom Lindqvist

Hey Tom - a few things that look like they could use a nudge from you:

🚧 **Needs your next move**

[**Retry the dispatch webhook when the carrier endpoint times out**](https://linear.app/tidebreak-demo/issue/DIS-59/retry-the-dispatch-webhook-when-the-carrier-endpoint-times-out) - Dan requested changes on PR #22 and hasn't heard back yet.

[**Split the crew roster query so dispatch stops timing out**](https://linear.app/tidebreak-demo/issue/DIS-61/split-the-crew-roster-query-so-dispatch-stops-timing-out) - same situation, Dan's changes-requested review on PR #24 is waiting on you.

[**Reject job assignments that overlap an existing shift**](https://linear.app/tidebreak-demo/issue/DIS-63/reject-job-assignments-that-overlap-an-existing-shift) - Dan requested changes on PR #26, also unanswered. If you've been working through these in a batch, pushing fixes or commenting on the three PRs above would unblock Dan's side.

[**Upgrade the scheduling engine's dependency set**](https://linear.app/tidebreak-demo/issue/DIS-62/upgrade-the-scheduling-engines-dependency-set) - PR #25 is out of draft but has no reviewer assigned. Last code push was Sep 4. If it's ready, requesting a review would keep it moving.

[**Show the depot timezone on every dispatch card**](https://linear.app/tidebreak-demo/issue/DIS-64/show-the-depot-timezone-on-every-dispatch-card) - you pushed fixes on PR #27 addressing Dan's feedback, but he hasn't re-reviewed yet. Might be worth pinging him if it's been a while.

[**Backfill the missing depot codes on legacy jobs**](https://linear.app/tidebreak-demo/issue/DIS-67/backfill-the-missing-depot-codes-on-legacy-jobs) - Dan's approval on PR #30 was dismissed and no re-review has been requested. Could you re-request his review so it doesn't slip through the cracks?

🍏 **Cleanup**

[**Add a depot filter to the dispatch queue**](https://linear.app/tidebreak-demo/issue/DIS-49/add-a-depot-filter-to-the-dispatch-queue) - still In Progress, but the depot filter shipped back in August and [PR #25](https://github.com/tidebreak-demo/dispatch-web/pull/25) merged yesterday. If the work is done, moving it to Done would tidy up the board.

Heads-up for you first - unresolved items may later show in your squad lead's digest.

### Dan Whitfield

Hey Dan - a couple of reviews that could use a second look from you:

🚧 **Needs your next move**

[**Show the depot timezone on every dispatch card**](https://linear.app/tidebreak-demo/issue/DIS-64/show-the-depot-timezone-on-every-dispatch-card) - Tom pushed fixes addressing your feedback on PR #27, but there's no re-review yet.

[**Backfill the missing depot codes on legacy jobs**](https://linear.app/tidebreak-demo/issue/DIS-67/backfill-the-missing-depot-codes-on-legacy-jobs) - your earlier approval on PR #30 was dismissed and it still needs a fresh review. If you have a few minutes, both PRs would benefit from a quick pass today.

Heads-up for you first - unresolved items may later show in your squad lead's digest.
