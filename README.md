# Merchant Scout Discovery

Public discovery metadata for the Merchant Scout paper-only Agent Purchase Guard.

This repository exists solely to provide a small public discovery surface for registries without exposing the private Merchant Scout / Epistemic Wanderer source repository.

## Live service

Base API:

https://merchant-scout-paper-demand.malcolmscott73.workers.dev

OpenAPI specification:

https://merchant-scout-paper-demand.malcolmscott73.workers.dev/openapi.json

Machine-readable discovery manifest:

https://merchant-scout-discovery.malcolmscott73.workers.dev/.well-known/agents.json

## Protocol

The live service exposes a REST/OpenAPI interface.

This repository does **not** claim that the service implements the A2A JSON-RPC task lifecycle or A2A `message/send`, task management, streaming, push notifications, or other A2A RPC operations.

`agent-card.json` is provided as public discovery metadata for registry import.

## Safety

The live trial is paper-only.

No wallet, live payment, signing, blockchain transaction, facilitator call, credentials, or live commerce functionality is enabled or accepted.

This public repository contains no application source code, secrets, credentials, private-repository content, or payment infrastructure.

The repository is a discovery surface only and does not modify the live trial configuration or behaviour.
