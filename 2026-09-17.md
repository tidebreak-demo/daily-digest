# Daily Digest

Squad: #tidebreak-dispatch  
Date: 2026-09-17  
Generated at: 2026-09-17 06:03:12 UTC

> The people are invented. The pull requests and their dates are real.

## Lead digest

### Squad lead

Hey Zakir - Tom's review queue looks jammed: three PRs with changes requested and no author response, one PR without a reviewer, one waiting on Dan's re-review, and one with a dismissed approval. Plus the depot filter story still needs closing out.

🚧 **Worth a look**

[**Retry the dispatch webhook when the carrier endpoint times out**](https://linear.app/tidebreak-demo/issue/DIS-59/retry-the-dispatch-webhook-when-the-carrier-endpoint-times-out) (DIS-59) - Sitting with Tom Lindqvist for 3 working days. Dan requested changes on [#22](https://github.com/tidebreak-demo/dispatch-api/pull/22), no author response.

[**Split the crew roster query so dispatch stops timing out**](https://linear.app/tidebreak-demo/issue/DIS-61/split-the-crew-roster-query-so-dispatch-stops-timing-out) (DIS-61) - Same pattern: Dan requested changes on [#24](https://github.com/tidebreak-demo/dispatch-api/pull/24), no author response. Sitting with Tom for 3 working days.

[**Reject job assignments that overlap an existing shift**](https://linear.app/tidebreak-demo/issue/DIS-63/reject-job-assignments-that-overlap-an-existing-shift) (DIS-63) - Same pattern: Dan requested changes on [#26](https://github.com/tidebreak-demo/dispatch-api/pull/26), no author response. Sitting with Tom for 3 working days.

[**Upgrade the scheduling engine's dependency set**](https://linear.app/tidebreak-demo/issue/DIS-62/upgrade-the-scheduling-engines-dependency-set) (DIS-62) - Sitting with Tom for 3 working days. [#25](https://github.com/tidebreak-demo/dispatch-api/pull/25) is out of draft with no reviewer requested; last real code authored Sep 4 (~13 days ago).

[**Show the depot timezone on every dispatch card**](https://linear.app/tidebreak-demo/issue/DIS-64/show-the-depot-timezone-on-every-dispatch-card) (DIS-64) - Sitting with Dan Whitfield and Tom Lindqvist for 3 working days. Tom addressed Dan's feedback on [#27](https://github.com/tidebreak-demo/dispatch-api/pull/27), but no re-review since.

[**Backfill the missing depot codes on legacy jobs**](https://linear.app/tidebreak-demo/issue/DIS-67/backfill-the-missing-depot-codes-on-legacy-jobs) (DIS-67) - Sitting with Tom Lindqvist and Dan Whitfield for 3 working days. Dan's approval on [#30](https://github.com/tidebreak-demo/dispatch-api/pull/30) was dismissed; no re-review requested or received.

🍏 **Cleanup**

[**Add a depot filter to the dispatch queue**](https://linear.app/tidebreak-demo/issue/DIS-49/add-a-depot-filter-to-the-dispatch-queue) (DIS-49) - Sitting with Tom Lindqvist for 8 working days. Work shipped via DIS-47, [#25](https://github.com/tidebreak-demo/dispatch-web/pull/25) merged Sep 16, your comments from Aug 27 confirm there is nothing left to do - story just needs moving to Done.

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
