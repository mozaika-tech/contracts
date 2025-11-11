# Contracts

Language-agnostic protobuf definitions for Mozaika, published to the Buf Schema Registry.

## Publishing

Push to the `master` branch to automatically publish to the Buf Schema Registry.

## Setup

Add the `BUF_TOKEN` secret to your GitHub repository settings:

1. Go to repository Settings → Secrets and variables → Actions
2. Create a new repository secret named `BUF_TOKEN`
3. Add your Buf API token as the value

## Consuming

Find published schemas at: https://buf.build/mozaika-tech/contracts

## Version Policy

This repository uses `v1alpha` versioning, which allows breaking changes. Stability guarantees will be introduced in future versions.
