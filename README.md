# Jarvis

Farsi-first Telegram group management bot built on top of Alita.

## Overview

Jarvis is a self-hosted Telegram group management bot focused on moderation,
admin tools, automation, and clean extensibility.

The project is being adapted with a Persian-first user experience in mind,
while keeping the codebase ready for additional languages later.

## Goals

- Persian-first moderation experience
- Clean and maintainable codebase
- Multi-language support
- Self-hosted deployment
- Extensible feature modules

## Planned Core Features

- Admin and moderation commands
- Warn, mute, ban, and anti-spam tools
- Welcome and goodbye messages
- Filters and notes
- Lock and blacklist systems
- Reports, purge tools, and announcements
- Persian language support first, more locales later

## Tech Stack

- Go
- PostgreSQL
- Redis
- Docker

## Project Status

Initial branding and setup phase.

## Local Development

```bash
cp sample.env .env
# edit .env with your real values
docker-compose up -d
Localization Plan

Jarvis will launch with Persian as the main product language.
English will remain available as a fallback/development language.
Additional languages can be added later through the locale system.

Credits

This project is based on Alita_Robot by Divkix and is being customized and
extended under its original license terms.

License

This repository keeps the original license from the upstream project.
See the LICENSE file for details.
