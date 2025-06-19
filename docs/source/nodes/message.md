# Message Nodes

Message nodes send WhatsApp messages in various formats:

- If a message node is followed by a variable, it waits for a response; otherwise, it continues the flow (except for interactive types, which always require a user response).
- **Text**: Sends text with properties `to` (e.g., `${{context.sender}}`) and `text`.
- **Media**: Sends media (video, document, audio, image) with properties `to` and `content` (uploaded file).
- **Interactive**: Sends interactive messages with buttons, using properties `caption`, `buttons`, `buttonType`, and `content`.
