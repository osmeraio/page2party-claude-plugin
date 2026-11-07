# Page2Party for Claude

Create and edit [Page2Party](https://page2.party) invitations by chatting with Claude. Tell Claude about your event and it builds the invitation for you: it picks a theme, fills in your names, dates, events and venues, writes the story, sets up RSVP questions, adds a second language, and gives you a preview link to check the result. Changes stay private until you publish the invitation yourself on Page2Party.

## What it includes

- **MCP server** (`page2party`): connects Claude to your Page2Party account at `https://page2.party/mcp/page2party`.
- **Skill `create-wedding-invitation`**: a short interview that builds a wedding invitation from what you tell Claude.
- **Skill `translate-invitation`**: adds a second language to an existing invitation by translating your own text.

## Install

```
/plugin marketplace add osmeraio/page2party-claude-plugin
/plugin install page2party@page2party
```

The first time Claude uses a Page2Party tool, it opens a sign-in page where you log in and approve access. You need a free Page2Party account.

## Usage

Ask in your own words, for example:

- "Help me create a wedding invitation."
- "Show me my invitations."
- "Change the ceremony time to 5 pm and show me the preview."
- "Add a Tamil version of my invitation."

## What Claude can and cannot do

Claude can create and edit invitations: basics, design, venues, people, events, story, gallery from public photo links, RSVP questions, settings and translations. It can undo its last change.

Claude cannot publish an invitation, read guest responses or see analytics. Those are only available on the Page2Party site, and Claude will send you the right link. If you ask for something that isn't supported, Claude passes the request to the Page2Party team and offers the closest alternative.

## Privacy and permissions

The plugin asks for two permissions: create and edit your invitations, and send feedback about features you request that aren't available yet. Anything you tell Claude to put on an invitation is stored in your Page2Party account.

- Privacy policy: https://page2.party/privacy-policy
- Terms: https://page2.party/terms

## Support

For help or to report a problem, visit https://page2.party or open an issue on this repository.
