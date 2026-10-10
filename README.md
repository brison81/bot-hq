# Bot HQ

Brian's Bot HQ is a static virtual office. Open the site to see each bot at a desk, in the meeting room, or on a break. The page loads `status.json` from the same folder and refreshes it every 60 seconds.

Statuses are light, non-sensitive summaries (name, project, room, and a short activity line). They do not include chat transcripts, credentials, or other private data.

`bot-hq.html` is the same office in one file, with a copy of the summary embedded so it still renders if `status.json` cannot be loaded.
