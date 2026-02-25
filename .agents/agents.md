# sample-react-project - Agent Guide

This is the agent-facing guide for working in this repository.

## Project Context
- Sample react project for frontend role-based question

## Setup
See [`agents.yaml`](./agents.yaml) for prerequisites, commands, and ports.

### Setup Hints
- `nvm` may not be loaded in your shell. If `nvm: command not found`, source it first.
- `yarn start` runs in the foreground — background it the same way.

## Running the App
- Clone the repo
- Install: `yarn install`
- Dev: `yarn start &`
- Access: `http://localhost:8000`

## Architecture
- React 16 with create-react-app
- Entry point: `src/index.js`

## Working Agreement
- Write modular code
- Keep testable
- Incremental validation
- Commit meaningful checkpoints
- Write tests
- Validate before handoff
