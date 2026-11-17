# Slack to Copilot

Connect Slack to Microsoft Copilot using [Slack's hosted MCP server](https://docs.slack.dev/ai/slack-mcp-server/#overview). No custom MCP server to build or host.

Set up a **custom federated connector in the Microsoft 365 admin center**, under **Copilot > Connectors**. This is **not** a Power Platform custom connector or a Copilot Studio setup.

A browser-based runbook for IT admins: follow the exact clicks, copy tenant-specific configuration, and verify that Copilot can retrieve and cite Slack messages.

**[Open the interactive guide](https://eriic-builds.github.io/slack-to-copilot/)**

## From setup to a cited answer

One path through Slack app creation, MCP access, user permissions, OAuth registration, and pilot rollout, including the easily missed **Enable Slack MCP access** step.

Read **Full reference** to understand the choices, or switch to **Guided setup** to work one task at a time. Copy buttons, progress checks, troubleshooting, and an exportable run summary support the whole pilot.

This is the guide, not the connector itself. You configure Slack and Microsoft through their official portals; the page makes no tenant changes.

## Run your first pilot

You'll need Microsoft admin access, an appropriately licensed Copilot user, and permission to create and install an internal Slack app.

1. Open the guide and select **Start guided setup**.
2. Enter your tenant, Slack workspace, and pilot-user values.
3. Follow the clicks, restrict rollout to the pilot, and confirm each result.
4. Retrieve a message in Copilot and open its original Slack citation.

Save progress in your browser or download a personalized HTML copy to resume later. For offline use, download `index.html` and open it in Edge or Chrome. No CLI or package installation is required.

## Before you roll out

- **Read-only baseline:** public channels only; no private-channel, DM, file, or write scopes. Public search can cover the authorized workspace, not just your test channel.
- **No credentials in the guide:** enter secrets only in the official portals. Setup values are not submitted to a server; review saved copies before sharing.
- **Expand deliberately:** [Slack's tools and OAuth scopes](https://docs.slack.dev/ai/slack-mcp-server/#oauth-scopes) describe additional capabilities that need separate review and reauthorization.

Independent community guide, not an official Microsoft or Slack product. Check current [Microsoft](https://learn.microsoft.com/en-us/microsoft-365/copilot/connectors/set-up-custom-federated-connectors) and [Slack](https://docs.slack.dev/ai/slack-mcp-server/) requirements before rollout.
