# Peedro

Peedro is a Discord ticket bot focused on simplicity, performance, and reliability.

## Features

* Ticket creation via slash commands
* Automatic channel management
* Staff assignment and ticket status tracking
* Persistent storage with PostgreSQL
* Fast caching and queue handling with Redis

## Required Permissions

Peedro requests only the permissions necessary to operate a ticket system:

* **View Channels** – Access ticket channels
* **Send Messages** – Respond inside tickets
* **Read Message History** – Load previous ticket context
* **Manage Channels** – Create, edit, and close ticket channels
* **Manage Threads** (optional) – If tickets are handled using threads

No administrative permissions are required.

## Data Storage

* PostgreSQL is used for persistent ticket data
* Redis is used for caching and temporary state
  nPeedro does not share data with third parties.

## Invite

Invite Peedro to your server using the official link:
[https://discord.com/oauth2/authorize?client_id=1450687898046304297&permissions=252334537501720&integration_type=0&scope=bot+applications.commands](https://discord.com/oauth2/authorize?client_id=1450687898046304297&permissions=252334537501720&integration_type=0&scope=bot+applications.commands)

## Support

Join the official support server:
[https://discord.gg/aZPARCW7K6](https://discord.gg/aZPARCW7K6)

## Legal

* [Privacy Policy](PRIVACY.md)
* [Terms of Service](TERMS.md)
