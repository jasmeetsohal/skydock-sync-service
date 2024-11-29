
# Sync Service

## Purpose
Synchronize file changes across devices.

## Tech Stack
- Nest.js
- Kafka
- Redis

## Features
- Detect file changes and send events
- Conflict resolution (e.g., using version history)
- Real-time file sync logic

## Directory Structure
```plaintext
/src
  /event-handlers   # Kafka or Redis event consumers
  /services         # Core business logic
  /models           # Data models and entities
  /utils            # Helper functions
