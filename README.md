# YT Screen Overlay

A customizable desktop overlay tool for YouTube livestreamers, built for OBS and other browser-source compatible streaming software.

> ⚠️ YT Screen Overlay is currently in **Alpha**.  
> Features may change and bugs are expected.

## Current Version

**v0.1.0-alpha.1**

Windows 10/11 x64

## Features

- Google / YouTube authentication
- YouTube livestream detection
- Multi-stream support
- Subscriber alerts
- Live comment widgets
- Custom alert messages
- Custom alert duration
- Per-widget sound configuration
- Clear/reset individual widgets
- OBS Browser Source integration
- Local WebSocket communication
- Desktop application powered by Electron

## OBS Integration

YT Screen Overlay provides a local browser overlay that can be added to OBS as a Browser Source.

1. Start YT Screen Overlay.
2. Sign in with Google.
3. Connect your YouTube channel.
4. Select your livestream.
5. Copy the overlay URL from the application.
6. Open OBS.
7. Add a **Browser Source**.
8. Paste the overlay URL.
9. Adjust the Browser Source dimensions as required.

Keep YT Screen Overlay running while using the overlay.

## Installation

Download the latest Windows installer from the **Releases** section.

Run:

`YT-Screen-Overlay-0.1.0-alpha.1-Setup.exe`

No Node.js, npm, Firebase CLI, or development environment should be required.

### Windows Security Notice

Early Alpha builds may not yet be digitally signed.

Windows SmartScreen may therefore display a warning when launching the installer.

Only download YT Screen Overlay from the official GitHub repository/release page.

## Alpha Testing

This release is intended for testing.

If you encounter a problem, please create a GitHub Issue and include:

- YT Screen Overlay version
- Windows version
- OBS version
- What you were doing
- What you expected
- What actually happened

Do NOT post OAuth tokens, credentials, or other sensitive information.

## Known Limitations

This is an early Alpha release.

Some cloud account/trial functionality is still under development.

YouTube API functionality may also be affected by API quota limitations during testing.

## Privacy

YT Screen Overlay requires Google/YouTube authorization for features that interact with your YouTube channel.

The application should request only the permissions required for its functionality.

Never share your Google OAuth tokens or application diagnostic files publicly without reviewing them for sensitive information.

## Development Status

Current status:

**Alpha / Active Development**

Planned work includes:

- Cloud-based account and entitlement persistence
- YouTube API quota optimization
- Development simulation mode
- Additional alert widgets
- Improved diagnostics
- Code signing
- Automatic update support

## Bug Reports & Feature Requests

Please use GitHub Issues for:

- Bug reports
- Feature requests
- Installation problems
- OBS integration problems

## Disclaimer

YT Screen Overlay is an independent project and is not affiliated with or endorsed by YouTube, Google, or OBS.

YouTube is a trademark of Google LLC.
OBS is a trademark of its respective owner.
