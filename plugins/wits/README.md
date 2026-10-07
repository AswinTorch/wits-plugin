# wits

wits is a voice-first app for notes, lists, and reminders. This plugin connects
your wits account to Claude, so you can save and find the same notes, lists,
and reminders you capture on your iPhone, Apple Watch, or the web.

## Use it

Install the plugin, then connect the wits connector and sign in with your wits
account. You choose whether Claude can only read your library or can also make
changes. Then ask things like:

- "Save this packing list to wits."
- "Remind me to call the dentist Thursday at 3pm."
- "What did I capture about the kitchen renovation?"
- "Add oat milk and coffee beans to my shared groceries list."
- "What's on my wits agenda this week?"

Reminders you create here notify you on your phone like any other wits
reminder. Shared lists keep their existing members and permissions.

## Data

The plugin sends the requests Claude makes on your behalf, such as a search
query or the text of a new note, to your wits account through
`wits-plugin.vercel.app`. Claude sees only the items it searches for or opens.
Locked notes are never available to this connection. Besides the items you ask
it to save, wits keeps only what the connection needs to work: the connection
itself and short-lived receipts that stop a retried save from being stored
twice. You can disconnect at any time in wits under Settings, Connections.

- Privacy policy: https://witsnotes.com/privacy
- Terms: https://witsnotes.com/terms
- Support: hi@witsnotes.com

The wits name and logo are not covered by the license.
