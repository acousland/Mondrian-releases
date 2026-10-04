# Mondrian for macOS

Mondrian is a native macOS diagram renderer with a local drawing library and an MCP helper for AI clients.

Download the installer from [Releases](https://github.com/acousland/Mondrian-releases/releases/latest), open the DMG, and drag **Mondrian.app** into **Applications**.

When replacing an existing installation, quit the application and AI clients and remove only the previous application bundle. Keep your library folder and Application Support files. Mondrian discovers compatible saved library locations and leaves the library data in place. Choose **Settings → General → Open Existing Library…** if several locations are found or the saved location was removed.

Update your AI client's helper command to **Mondrian.app/Contents/MacOS/MondrianMCP** and restart the client. **Settings → AI Clients** contains full setup instructions.

Requires macOS 14 or newer on Apple silicon. Published installers are Developer ID signed and notarised by Apple. Mondrian verifies automatic updates against its own signing key.
