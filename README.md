# OpenAI Creative Assistant

An application for creating and exploring content with OpenAI. The goal is to
bring text generation, image creation, voice messages, and FAQ chat together in
one place.

> **Status:** Project concept. The features below describe the intended
> functionality; they are not necessarily implemented yet.

## Planned features

- **Text generation** — draft, rewrite, summarize, and brainstorm text from a
  user's prompt.
- **Image generation** — create images from text descriptions.
- **Voice messages** — generate spoken responses and, where supported, let
  users interact with the app using voice.
- **FAQ chat** — answer frequently asked questions in a conversational
  interface, using a configured set of FAQ content.

## Intended experience

Users will be able to choose the kind of help they need, provide a prompt or
question, and receive a generated response. The FAQ chat is intended for
questions about a specific product, service, or topic; its answers should be
grounded in the FAQ material configured for the application.

## Development status

This repository is at an early stage. The technology stack, installation
instructions, configuration, and feature-specific documentation will be added
as the application is implemented.

## API key safety

OpenAI API keys are secrets. Do not commit keys to this repository or expose
them in browser-side code. When API integration is added, keep credentials in
server-side configuration or environment variables, and provide a safe example
configuration file without real secrets.