# Beauty Birthday Loyalty — Desktop + Cloud Loyalty System

A desktop and cloud system built for a retail client to collect customer birthdays and automate birthday-promotion SMS workflows.

## What I built

I worked on the desktop application, local database, cloud synchronization layer, birthday-submission flow and automation logic.

## Tech stack

- Tauri 2
- React
- TypeScript
- SQLite
- Cloudflare Workers
- Cloudflare D1

## Core features

- Desktop customer-management interface
- Import and cleanup of thousands of customer records
- Secure tokenized birthday-submission links
- Cloud-hosted birthday form
- Consent collection
- Desktop/cloud synchronization
- Automated daily birthday-promotion workflow
- SMS-provider abstraction
- Validation, duplicate handling and audit-friendly flows

## Engineering challenges

The project combines a local desktop app with a lightweight cloud backend, so the main challenge was keeping data synchronization reliable while preserving a simple experience for store staff and customers.

## Source code

The production repository is private client software. Architecture and implementation details can be discussed during an interview where appropriate.

[Back to portfolio](./README.md)
