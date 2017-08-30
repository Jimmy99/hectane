## Hectane

> **Note:** this version of Hectane is still in development and _should not_ be used in production.

### Features

Hectane is designed to do it all. The list of planned features includes:

- Webmail client with simple and modern UI
- Send and receive emails via SMTP
- Full access to account via IMAP

### Building

To build Hectane, you must have the following tools installed:

- GNU Make (or equivalent)
- Docker

The binary is built using a group of Docker containers, so there is no need to worry about build dependencies such as the Go toolchain or NPM. The command to build the binary is as simple as:

    make

This will produce a binary in `dist/` named `hectane`. This is a standalone binary with no dependencies and can be used as-is.
