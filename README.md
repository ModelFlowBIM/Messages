# Send a ModelFlow announcement

1. Open [message.json](message.json) and click the pencil to edit it.
2. Set a new unique `id`, then write the `title` and `message`. Leave `expires_utc` empty or use a UTC date such as `2027-01-31T23:59:59Z`.
3. Click **Commit changes**. The apps check approximately every 15 minutes and display each ID once when a model or family is open.
4. To stop displaying an announcement, clear `id` or `message` and commit again.

Example:

```json
{
  "id": "announcement-001",
  "title": "ModelFlow news",
  "message": "Your message goes here.",
  "expires_utc": ""
}
```

This repository is public; do not include confidential information.
