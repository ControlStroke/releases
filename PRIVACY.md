# Privacy Policy

Last updated: July 6, 2026

Control Stroke is a local-first Windows desktop application for compatible device control through Intiface Central.

This policy explains what data Control Stroke handles and what data is not collected by the app.

## Summary

- The free desktop app does not require an account.
- The app does not include telemetry.
- The app does not upload scripts, videos, screen capture, device data, or logs to Control Stroke servers.
- Patreon login, when enabled, is used only to verify Pro access and owner entitlement.

## Local Data

Control Stroke may process or store data locally on your computer:

- Intiface WebSocket URL and connection settings;
- local app preferences;
- selected `.funscript` or compatible JSON files;
- optional local video references;
- saved local script entries;
- local troubleshooting logs shown inside the app;
- Control Stroke license state after Patreon-backed unlock is implemented.

This data is intended to stay on your computer unless you choose to share it.

## Screen Capture

Screen Sync processes screen information locally to derive motion signals. Control Stroke does not upload screen capture data to Control Stroke servers.

Your operating system or runtime may ask for screen capture permission. You control that permission through your local system settings.

## Device Control

Control Stroke communicates with Intiface Central over a local WebSocket connection. Compatible devices are managed through Intiface/Buttplug.

Control Stroke does not collect device telemetry or send device usage history to Control Stroke servers.

## Patreon Login

Future Pro access may use Patreon as the payment and entitlement provider.

When Patreon login is enabled:

- Patreon handles account login and payment information;
- Control Stroke's backend may receive Patreon account and membership identifiers needed to verify Pro access;
- the desktop app should receive only Control Stroke license data, not raw Patreon OAuth tokens;
- Patreon data is used for entitlement verification, restore access, and abuse prevention.

Do not send Patreon secrets, access tokens, payment details, or private account data through GitHub Issues.

## GitHub Issues

If you report a bug publicly on GitHub, the information you post is public. Do not include private files, sensitive screenshots, explicit media, personal data, or secret tokens.

## Third-Party Services

Control Stroke may link to or integrate with:

- GitHub, for downloads, release notes, and public issue reports;
- Patreon, for future Pro access and project updates;
- Cloudflare Workers, for future Patreon entitlement verification;
- Intiface Central and the Buttplug ecosystem, for local compatible device control.

Each third-party service is governed by its own terms and privacy policy.

## Adult Users

Control Stroke is intended for adult users only. Public support requests and GitHub Issues must stay non-explicit and software-focused.

## Changes

This policy may be updated as the product, entitlement backend, or release process changes. The current version will be published in this repository.

## Contact

Use GitHub Issues for non-sensitive product questions and bug reports:

https://github.com/ControlStroke/releases/issues
