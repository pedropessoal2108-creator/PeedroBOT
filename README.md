# Peedro

Peedro is a Discord ticket bot focused on simplicity, performance, and reliability.

## Features

* Ticket creation via slash commands and a persistent interaction panel (select menus + modals)
* Automatic channel and thread management
* Staff assignment and ticket status tracking
* Persistent storage with PostgreSQL
* Fast caching and temporary state handling with Redis

## Required Permissions

Peedro requests only the permissions necessary to operate a ticket system:

* **View Channels** – Access ticket channels
* **Send Messages** – Respond inside tickets
* **Read Message History** – Load previous ticket context
* **Manage Channels** – Create, edit, and configure ticket-related channels
* **Manage Threads** – Required, as tickets are handled using threads

No administrative permissions are required.

## Data Storage

* PostgreSQL is used for persistent ticket data
* Redis is used for caching and temporary state

Peedro does not share data with third parties.

## Invite

Invite Peedro to your server using the official link:  
https://discord.com/oauth2/authorize?client_id=1450687898046304297&scope=bot%20applications.commands&permissions=252334537501712

## Support

Join the official support server:  
https://discord.gg/aZPARCW7K6

## Legal

* [Privacy Policy](PRIVACY.md)
* [Terms of Service](TERMS.md)
