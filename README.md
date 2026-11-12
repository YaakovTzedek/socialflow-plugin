# SocialFlow for Cursor and Grok Bot

Connect the Facebook Pages and Instagram Business accounts you manage. List posts and comments, run automations, and publish approved posts from your AI assistant.

This plugin points Cursor at the hosted SocialFlow MCP server and lets the client run the ordinary OAuth redirect. No API keys belong in this repository.

- Website: https://isocialflow.com
- Docs: https://isocialflow.com/mcp (a dedicated docs page must be restored in production; do not ship a homepage redirect)
- Privacy: https://isocialflow.com/privacy
- Terms: https://isocialflow.com/terms
- Support: Currently listed only as gkobzafrani@gmail.com on the privacy page. Replace with a product mailbox (recommended: support@isocialflow.com) before store review.

## Install (Cursor / Grok Bot)

1. Install this plugin from the Cursor marketplace once it is listed, or add the MCP URL below as a custom remote server.
2. When prompted, sign in with your SocialFlow account (OAuth 2.1, PKCE). Approve the requested scopes.
3. Ask one of the example prompts in a new chat.

Remote MCP URL (Streamable HTTP): `https://isocialflow.com/api/mcp`


## Example prompts

- List the Facebook Pages and Instagram accounts connected to my SocialFlow account.
- Show recent posts on my main page and the latest comments on the most recent post.
- List my automations and explain what the first one does.
- Draft a reply-automation for comments that ask about pricing, but do not publish anything yet.
- Show this week’s insights and activity log.

## License

MIT. See LICENSE.

## Maintainer

Yaakov Tzedek. This repository is only the plugin wrapper (manifest + MCP pointer + logo). It does not contain account credentials.
