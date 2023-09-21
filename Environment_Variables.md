### Configuration Settings - Please Copy and Paste the Key and Enter the Desired Values. 

You can change it depending on platform settings or
within bot using setvar command

For Example setvar key = value


1. **[SESSION_ID](#SESSION_ID)** - Obtain this after a successful scan.

2. **[SUDO](#SUDO)** - Your primary number or another number to use with the bot. Example:
   - SUDO = 987654321, 911234567890

3. **[PREFIX](#PREFIX)** - Your preferred command prefix. Example:
   - PREFIX = !
   - PREFIX = bot
   - PREFIX = ^[.,!]
   - PREFIX = null

4. **[VPS](#VPS)** - Set it to true if using a local or virtual system. Example:
   - VPS = true
   - VPS = false

5. **[STICKER_PACKNAME](#STICKER_PACKNAME)** - Sticker pack name. Example:
   - STICKER_PACKNAME = Name, Author
   - STICKER_PACKNAME = Name
   - STICKER_PACKNAME = , Author
   - STICKER_PACKNAME = false

6. **[WARN_LIMIT](#WARN_LIMIT)** - Number of allowed warnings. Example:
   - WARN_LIMIT = 3

7. **[DIS_BOT](#DIS_BOT)** - Block bots. Example:
   - DIS_BOT = 5375039464603@g.us, 91987654321

8. **[ANTILINK_MSG](#ANTILINK_MSG)** - Message sent when an antilink is detected.
   - ANTILINK_MSG = Antilink Detected &mention kicked

9. **[ANTISPAM_MSG](#ANTISPAM_MSG)** - Message sent when antispam is detected.
   - ANTISPAM_MSG = Antispam Detected &mention kicked

10. **[ANTIWORDS_MSG](#ANTIWORDS_MSG)** - Message sent when antiword is detected.
    - ANTIWORDS_MSG = Antiword Detected &mention kicked

11. **[ANTIWORDS](#ANTIWORDS)** - List of disallowed words. Example:
    - ANTIWORDS = word1, word2, word3

12. **[SS_TOKEN](#SS_TOKEN)** - Token for SS API from [https://app.screenshotapi.net/dashboard](https://app.screenshotapi.net/dashboard). Example:
    - SS_TOKEN = token_from_api

13. **[REJECT_CALL](#REJECT_CALL)** - Automatically reject calls. Example:
    - REJECT_CALL = true
    - REJECT_CALL = false

14. **[AUTO_STATUS_VIEW](#AUTO_STATUS_VIEW)** - Automatically view status. Example:
    - AUTO_STATUS_VIEW = true (view all)
    - AUTO_STATUS_VIEW = false (off)
    - AUTO_STATUS_VIEW = no-dl (only view)
    - AUTO_STATUS_VIEW = expect-view jid, jid,... (don't view given jid status)
    - AUTO_STATUS_VIEW = only-view jid, jid,... (only view given jid status)

15. **[SEND_READ](#SEND_READ)** - Send a blue tick. Example:
    - SEND_READ = true
    - SEND_READ = false

16. **[BRAINSHOP](#BRAINSHOP)** - Lydia API key. Example from [https://brainshop.ai/](https://brainshop.ai/):
    - BRAINSHOP = 159501, 6pq8dPiYt7PdqHz3

17. **[RMBG_KEY](#RMBG_KEY)** - remove.bg API key. Example:
    - RMBG_KEY = key_from_api

18. **[MAX_UPLOAD](#MAX_UPLOAD)** - Maximum file size (in MB) that the bot can upload.
    - MAX_UPLOAD = 230

19. **[DATABASE_URL](#DATABASE_URL)** - Obtain it from [HERE](https://github.com/lyfe00011/whatsapp-bot-md/wiki/DATABASE_URL) or leave it empty, depending on the platform.

20. **[PORT](#PORT)** - Port for the server.
    - PORT = 3000

21. **[FORCE_LOGOUT](#FORCE_LOGOUT)** - Force logout from WhatsApp web. Change back to false after logout.
    - FORCE_LOGOUT = true

22. **[AJOIN](#AJOIN)** - Accept group join requests (Group Privacy).
    - AJOIN = true
    - AJOIN = false

23. **[APPROVE](#APPROVE)** - Set antifake (based on this, approve, reject, or do both).
    - APPROVE = reject
    - APPROVE = approve
    - APPROVE = all

24. **[TZ](#TZ)** - Timezone.
    - TZ = Asia/Kolkata

25. **[PERSONAL_MESSAGE](#PERSONAL_MESSAGE)** - Send a greeting on the first personal message.
    - PERSONAL_MESSAGE = This is a bot; my owner will message you back when online
    - PERSONAL_MESSAGE = null

26. **[ANTI_BOT](#ANTI_BOT)** - Remove bots from the group.
    - ANTI_BOT = true
    - ANTI_BOT = false

27. **[ANTI_BOT_MESSAGE](#ANTI_BOT_MESSAGE)** - Send an informational message upon removal.
    - ANTI_BOT_MESSAGE = &mention removed

28. **[ANTI_DELETE](#ANTI_DELETE)** - Send deleted Message
    - ANTI_DELETE = off (off sending deleted message)
    - ANTI_DELETE = p (send deleted message to your or first sudo chat)
    - ANTI_DELETE = g (send deleted message to the chat where it deleted)
    - ANTI_DELETE = jid (send deletd message to the jid)