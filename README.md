# iCloud Mail Bridge

Read-only iCloud Mail tools for existing Mail Bridge accounts. Apple credentials stay on your Windows computer. Requested mail travels through an authenticated gateway to ChatGPT; the gateway does not persist mailbox contents.

## Status

Version 0.1.0 is a developer preview. The gateway and local companion have passed an authenticated live mailbox read. OpenAI directory approval and an actual ChatGPT UI connection remain pending.

## Connect

Install the Windows companion from this repository's release assets on the computer with your existing Mail Bridge installation. Enable read-only MCP access in Mail Bridge, then run the companion's Connect command. Enter its temporary pairing code only in the gateway's OAuth consent page when connecting the plugin. Keep that computer online while using mail tools.

The plugin can list recent inbox headers, search headers, and read a selected message. It cannot send, delete, or purchase anything. No Apple password or API key belongs in a ChatGPT conversation.

## Privacy and support

[Privacy](https://icloud-mail-bridge-chatgpt.evangrant69420.workers.dev/privacy) · [Terms](https://icloud-mail-bridge-chatgpt.evangrant69420.workers.dev/terms) · [Support](https://github.com/hr6ddbgzjg-lgtm/icloud-mail-bridge-plugin/issues)

Please exclude private mail, credentials, and pairing codes from issue reports.
