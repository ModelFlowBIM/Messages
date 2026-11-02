# Send ModelFlow announcements

1. Open [message.json](message.json) and click the pencil.
2. Add each message inside the square brackets, separated by commas. Give each a unique `id`.
3. Set `persistent` to `false` to show it once per user, or `true` to show it once every time Revit opens.
4. Commit changes. To stop a message, remove its entire entry and commit. Use `[]` for no messages.

```json
[
  { "id": "news-001", "title": "ModelFlow news", "message": "Your message here.", "persistent": false },
  { "id": "notice-002", "title": "Notice", "message": "A recurring notice.", "persistent": true }
]
```

Messages appear only with a model or family open. Checks run approximately every 15 minutes. This repository is public; never include confidential information.
