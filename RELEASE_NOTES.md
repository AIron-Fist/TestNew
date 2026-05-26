# Release Notes

## v1.0.0 - 2026-05-26

Initial public release of the mock Node.js app.

### Highlights

- Added a small Node.js startup flow with dotenv configuration loading.
- Added a default `NODE_ENV` of `development` when no environment is configured.
- Added startup messages that report the resolved environment and safe key-loading status.
- Added automated tests for environment resolution and startup message output.
- Added basic README usage instructions for installing dependencies and starting the app.
- Cleaned up repository ignore rules for local cache and environment artifacts.

### Dependencies

- Added `dotenv` for environment variable loading.

### Verification

- Run `npm install`, then `npm test` to verify the app.
- Run `npm start` to start the application.

### Notes

- Package metadata remains at `1.0.0`.
- No production secrets are included in this release.
