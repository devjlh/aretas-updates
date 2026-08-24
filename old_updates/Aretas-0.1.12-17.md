## What's new in Aretas 0.1.12

*2026-08-19*

Aretas now reads your whole mailbox, not just your most recent messages.

- On a very large Gmail account, the first scan used to stop after roughly the newest ten thousand messages, so older mail was never brought in. Aretas now works through your mail one period at a time and brings in the whole account, however large.
- If a scan is interrupted, it picks up where it left off — it does not start over, and it does not re-read the parts it already has.
- Every message is still accounted for exactly once: nothing is read twice, and nothing is quietly skipped.
