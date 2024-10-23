# Changelog

## Build 0.2.11

Release Date: Oct 23, 2024

- Added ADB and SSH client adapter.
- Added detailed adapter information.
- Added simulated preload data converter in CLI.
- Increase BDEM memory size from 2KB to 4KB.
- Increase frame rate (FPS) value resolution.
- Optimize `window-width` using `idle-duration` for faster event plot.

## Build 0.2.10

Release Date: Aug 07, 2024

- Fixed command mode issue.

## Build 0.2.9

Release Date: Aug 06, 2024

- Fixed data graph bde sync frame capture issue.
- Disable data graph window width as default settings.
- Reset memory dump content before new reading.

## Build 0.2.8

Release Date: Aug 05, 2024

- Fixed auto range control issue.

## Build 0.2.7

Release Date: Aug 05, 2024

- Improve frame table rendering speed when capturing.

## Build 0.2.6

Release Date: Aug 03, 2024

- Improve startup speed by delaying auto update check.

## Build 0.2.5

Release Date: Aug 03, 2024

- Auto remove captured data log outisde window width.

## Build 0.2.4

Release Date: Aug 02, 2024

- Added duration limit for graph data selection to improve its performance.

## Build 0.2.3

Release Date: Aug 02, 2024

- Improve data graph rendering performance.
- Use opengl as default event plot rendering engine.

## Build 0.2.2

Release Date: Jul 31, 2024

- Synchronize BDEM command (0xC0 -> 0xE8) to synchronize with specification.

## Build 0.2.1

Release Date: Jul 30, 2024

- Added BDE footer validation to handle corrupted BDE packet.
- Fixed application setting value endianess issue with SenseTrix device.

## Build 0.2.0

Release Date: Jul 30, 2024

- Added splashscreen image to improve user experience on startup.
- Fixed command feature transfer bug.
- Fixed auto load undefined memory symbol reference.

## Build 0.1.0

Release Date: Jul 28, 2024

- Initial release

## Build 0.0.0
