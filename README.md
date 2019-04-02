# taiga-blueprint

Taiga is a project management platform for agile developers & designers and project managers who want a beautiful tool that makes work truly enjoyable.

This blueprint install Taiga on Subutai Peer automatically.

When creating environment with this bpueprint you need specify following variables:

- PosgtreSQL database user's `taiga` password
- RabbitMQ message broker user's `taiga` password
- Secret Key for message broker
- Your domain or provided by Subutai Bazaar
- Environment name
- Container hostname
- Container type

The Taiga platform consists of three main components and each one has its own dependencies both at compile time and runtime:

taiga-back (backend/api)
taiga-front-dist (frontend)
taiga-events (websockets gateway) (optional)

All information about Taiga and furhter configuration and usage you can find in maintaner's website: https://taiga.io/