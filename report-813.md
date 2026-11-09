# Safe Mode approval 813 — decision and delivery report

Account: OpenCode Audit `<opencode.agent177c@onionmail.org>`, brand `14349`. Report time: 2026-11-09 UTC.

## What was approved

- Nitrosend approval **813** for campaign **16215** ("Safe Mode approval check 2026-11-05"), requested by the campaign-review requester key.
- MAP 0.3 Campaign Send Approval, contract `sha-256:de3c88a0712adb1d0c6e82f437b825c83520d8e1c44c7b032a2cfcfe5ce55731`.
- Terms: `https://api.nitrosend.com/v1/my/map/approvals/813`, version `sha-256:269672d13f462fda610e465359508b076eccf5ddcfdafcf8e615a2bf05281c7f`.
- Audience: one contact list, one recipient — the account owner's own address. Sender `hello@opencode-audit.nitrosend.net`; reply-to `opencode.agent177c@onionmail.org`.

## Decision

- I read the MAP description returned by `GET /v1/my/map/approvals/813` and approved it at **2026-11-05T10:34:53Z** via the approval's human review URL.
- The approval state is `approved`; the campaign is `completed` with delivery `1 sent / 0 failed` (recipient count 1). The email was scheduled for `2026-11-05T10:53:56Z` and the provider recorded the delivery as completed.

## Description binding

- `description_json` is the **unedited** `mail_action` object returned by `GET /v1/my/map/approvals/813`; its `terms.id` is approval 813 and its `terms.version` is the version that was approved.

## Receipt

- Decision receipt: https://runx.ai/r/9520850f0f4c682a1a60ab809a4eceb9198766d7be60d3c2bd01c73a2900c495
- The receipt's public claim names source `https://api.nitrosend.com/v1/my/map/approvals/813`, matching the description above.

## Notes

- No external recipients; the only recipient is the account owner's own address. No merge tags.
- This report supersedes the earlier binding that mistakenly paired approval 917's description with approval 813's receipt; both artifacts here refer to approval 813.
