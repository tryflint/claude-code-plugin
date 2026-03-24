# Flint Plugin for Claude Code

Build and manage websites with [Flint](https://tryflint.com)'s AI website builder through natural conversation in Claude Code.

## Features

- **Run background agents** to modify your Flint sites — add pages, update content, redesign sections
- **Check agent progress** and get preview URLs when changes are ready
- **List your sites** across all connected organizations
- **Publish sites** to production when you're ready to go live

## Installation

Install from the Claude Code plugin marketplace:

```
/plugin install flint
```

After installing, authenticate with your Flint account:

```
/mcp
```

Select "Authenticate" for Flint and complete the browser login flow.

## Usage

Once authenticated, just ask Claude to work on your Flint site:

> "Add a pricing page with three tiers to my site"

> "Update the hero section to say 'Welcome to the Future'"

> "Publish my site"

You can also use the `/flint:edit-site` skill directly:

```
/flint:edit-site Add a contact form with name, email, and message fields
```

## Tips

- **Describe goals, not implementation** — Flint is an expert designer and produces better results when given creative freedom over layout, styling, and component structure
- **Pass through reference material** — if you have code snippets, embed scripts, or examples, include them and Flint will incorporate them
- **Be specific when you want to be** — requests like "make the header black" or "use a three-column grid" are honored directly

## Support

- Documentation: https://www.tryflint.com/docs/claude-code-plugin
- Email: support@tryflint.com

## Privacy Policy

https://www.tryflint.com/privacy-policy
