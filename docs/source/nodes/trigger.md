# Trigger Nodes

Trigger nodes initiate workflows with four types:

- **Message**: Triggered when a WhatsApp user sends a message (text or media) to the business. After execution, the global variable `${{context}}` provides the sender’s phone number with `.sender`, and `prev.output` gives access to the user’s text or media, with `prev.meta.media_type` indicating the media type.
- **Webhook**: Executes a workflow via an HTTP call. `prev.output` contains the response data, and `prev.meta` includes event or other webhook-related details.
- **Manual**: Runs the workflow on demand.
- **Schedule**: Schedules execution using a crontab-like configuration.
