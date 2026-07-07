# Bitfocus Companion Module for Internet Clicker

This module allows you to control Internet Clicker (and Cliqer) presentations directly from Bitfocus Companion using the SignalR event code methodology.

## Configuration

When adding this module in Companion, you will need to provide the following details:

* **Host URL**: The base URL of the Internet Clicker or Cliqer receiver hub. (Default: `http://localhost:52722`)
* **API Key**: If required by your receiver setup.
* **Event Code**: The unique pairing code used for your presentation.

## Available Actions

* **Next Slide**: Advances the presentation to the next slide.
* **Previous Slide**: Goes back one slide.
* **Start Timer**: Starts the presentation timer.
* **Pause Timer**: Pauses the presentation timer.
* **Stop Timer**: Stops the presentation timer.

## Development

To build this module locally:

1. Install dependencies:
   ```bash
   npm install
   ```
2. Build the module:
   ```bash
   npm run build
   ```
3. To develop with auto-recompilation on changes:
   ```bash
   npm run dev
   ```

See the [Companion Connection Developers' Guide](https://github.com/bitfocus/companion/wiki/Module-Development) for more information on testing custom modules.
