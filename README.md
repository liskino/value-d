# AI ChatBot Backups

Automatic chat backups with recovery system.

## Structure

backups/
- username/
  - chat_id/
    - messages.jsonl
    - meta.json

backups_recovery/
- username_recovery/
  - chat_id_recovery/
    - messages_recovery.jsonl
    - meta_recovery.json

## How to restore

1. Open AI ChatBot Pro
2. Go to Chat tab
3. Select chat
4. Click Restore from backup
