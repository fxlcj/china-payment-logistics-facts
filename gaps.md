# Known gaps and deliberate exclusions

This file is **not a dataset**. Nothing here is a verified fact and nothing here may be quoted as one. It records the figures we wanted to include but could not verify against an official source, together with entries we refused because the evidence did not hold. It exists so that a later maintainer does not quietly fill these holes with a guess.

| Missing or excluded | Why it is not in `facts.json` | Evidence |
|---|---|---|
| A nationwide figure for how often overseas cards are accepted at individual merchants | We could not verify an official page that publishes one. Acceptance depends on the merchant, so this repo lists the published limits and rules, not a success rate. | Repo scope, 2026-11-10. |
| An editorial filler sentence about National Bureau of Statistics data picked up by the 08:55 automated sync | Reverted on 2026-11-11: it carried no concrete figure and linked to a section landing page rather than an official deep link. | `CHANGELOG.md`, 2026-11-11 quality revert. |
| Provider-specific commercial terms that go beyond the published rules | Only the limits and rules stated on official pages are in scope here. Commercial terms set by an individual provider are not published as official rules. | Repo scope, 2026-11-10. |

If an official page becomes available, add the entry through the monthly maintenance task with its official source URL and check date, record the change in `CHANGELOG.md`, and remove the row above. The official page, not this file and not a third-party mirror, is always the authority.
