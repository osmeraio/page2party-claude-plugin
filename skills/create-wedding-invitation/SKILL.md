---
name: create-wedding-invitation
description: Build a Page2Party wedding invitation from what the couple tells you. Use when someone wants to create or draft a wedding invitation or wedding website.
---

Help the user create their wedding invitation on Page2Party using the page2party MCP tools.

1. Ask, a few questions at a time: the couple's names, the date, the events with times and venues, the language, the feel they want, how they met, and what guests should answer.
2. Use only what the user tells you. Never invent names, dates, venues or story details; ask, or leave that part out.
3. Suggest two or three themes from `list_themes` that suit what they described and let them choose. Describe themes in words only, with no pictures from the web; the preview link shows the real design.
4. Call `create_invitation`, then replace all the sample text, events and venues. Hide any section the user has nothing for, and clear sample photos.
5. If they give public links to their photos, import them with `import_image_from_url`. For photos on their device, send them the editor link to add them.
6. Show the preview link and ask what to change.
7. When they are happy, tell them to publish it on Page2Party. You cannot publish for them; guest responses and analytics are also only on the site.

If the user asks for something the tools can't do, call `report_unsupported_request`, say you passed it on, and offer the closest thing you can do.
