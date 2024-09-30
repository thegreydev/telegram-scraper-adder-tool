# telegram-scraper-adder-tool
a tool that scrapes and add telegram users into groups and channels

developer: https://t.me/pysmart

![FE6C72B9-AD3B-4836-A1C3-309E80AF1E39](https://github.com/user-attachments/assets/c902e148-f5e8-43fe-bf39-fcd596569ee0)

# ANALYSIS
- The script reads the users.txt file containing the users scraped from the previous script.
- It attempts to add those users to the specified group or channel. It handles common errors like privacy restrictions and rate limits (FloodWaitError).
- It uses the InviteToChannelRequest to add users to the group.

developer: https://t.me/pysmart

# NOTES:
- Rate Limits: Telegram imposes restrictions on how many users you can add in a short period. If you encounter a FloodWaitError, you must respect the wait time or slow down your script.
- Privacy Settings: If a user has privacy restrictions (e.g., only allowing friends to add them to groups), the script will not be able to add them, and it will skip to the next user.
- Usernames: The script only attempts to add users with valid usernames, as Telegram primarily uses usernames for user interactions outside of contacts.

developer: https://t.me/pysmart
 
