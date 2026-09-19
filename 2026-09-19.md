# Daily Digest

Squad: #tidebreak-dispatch  
Date: 2026-09-19  
Generated at: 2026-09-19 06:04:10 UTC

> The people are invented. The pull requests and their dates are real.

## Lead digest

### Squad lead

Hey Dan - Priya's comment on the unassigned crew-notification bug is a new escalation, and two items involving your own review queue need a quick call.

🚧 **Worth a look**

[**Reassigned jobs keep notifying the original crew**](https://linear.app/tidebreak-demo/issue/DIS-83/reassigned-jobs-keep-notifying-the-original-crew) (DIS-83) - Since yesterday's digest, Priya Raman commented "Happened again this morning. Two crews, one job, nobody looking at it." Urgent customer-reported bug, still unassigned after 5 days in Todo, no code activity.

[**Persist board filters per user**](https://linear.app/tidebreak-demo/issue/DIS-71/persist-board-filters-per-user) (DIS-71) - In Review since Sep 16. You requested changes on [#26](https://github.com/tidebreak-demo/dispatch-web/pull/26) Sep 16; Priya replied Sep 17 explaining the key is already scoped per workspace and asked if anything else is needed. No re-review from you in ~2 days - the ball is on your side.

🍏 **Cleanup**

[**Stop the board losing a filter on refresh**](https://linear.app/tidebreak-demo/issue/DIS-84/stop-the-board-losing-a-filter-on-refresh) (DIS-84) - High priority, still marked In Review, but Priya closed [#33](https://github.com/tidebreak-demo/dispatch-api/pull/33) without merge on Sep 18 - "per-user state needs the preferences table, and that is someone else's migration." Story state no longer reflects reality; likely needs to move back to Backlog until the dependency is resolved.

## Developer digests

### Priya Raman

Hey Priya - couple of things that might be worth a quick nudge this weekend or Monday:

🚧 **Needs your next move**

[**Persist board filters per user**](https://linear.app/tidebreak-demo/issue/DIS-71/persist-board-filters-per-user) - you replied to Dan's review on [PR #26](https://github.com/tidebreak-demo/dispatch-web/pull/26) two days ago and he hasn't come back yet. Might be worth re-requesting his review or giving him a ping so it doesn't drift.

🍏 **Cleanup**

[**Stop the board losing a filter on refresh**](https://linear.app/tidebreak-demo/issue/DIS-84/stop-the-board-losing-a-filter-on-refresh) - [PR #33](https://github.com/tidebreak-demo/dispatch-api/pull/33) was closed without merge but the story still shows In Review. If the approach is shelved until the preferences table migration lands, could you move it back to Backlog?

Heads-up for you first - unresolved items may later show in your squad lead's digest.
