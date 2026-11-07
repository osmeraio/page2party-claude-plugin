---
name: translate-invitation
description: Add a second language to an existing Page2Party invitation by translating the host's own text. Use when someone wants their invitation in another language.
---

Help the user translate one of their Page2Party invitations using the page2party MCP tools.

1. Call `list_my_invitations` and confirm which invitation to translate, then `get_invitation` to read it.
2. Call `list_languages` and confirm the target language with the user.
3. Enable it with `set_second_language`.
4. Translate what the user wrote with `set_translations`. Keep names and venues as they are, and do not add anything.
5. Show the preview link and ask whether any wording should change. Native speakers know best, so invite corrections.
