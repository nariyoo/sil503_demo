# sil503_demo

Demo applications for the SIL 503 activity.

## Group 3: Listing Call Desk

`listing-call-desk/index.html` is a tool for housing caseworkers. It does two jobs:

- **Is it still open?** Search the shared listing database and see each listing's status (open, pending, closed or unconfirmed), when it was last confirmed and the call history. Listings not confirmed in the last 7 days are flagged for a call.
- **After-call summary.** Paste rough notes from a landlord call. Claude writes the summary, reads whether the unit is still available and suggests next steps and a follow-up date. The caseworker reviews the fields and saves them, which updates the listing for the whole team.

Live artifact: https://claude.ai/artifact/Mqh2vjSvLAfmNF7npcah1g (it uses the artifact `db` and `sample` capabilities, so it only runs inside Claude).
