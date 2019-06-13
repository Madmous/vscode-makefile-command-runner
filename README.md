# VS Code Makefile Command Runner extension

[![](https://vsmarketplacebadge.apphb.com/version-short/madmous.makefile-command-runner.svg)](https://marketplace.visualstudio.com/items?itemName=madmous.makefile-command-runner)
[![Codeship Status for Madmous/vscode-makefile-command-runner](https://app.codeship.com/projects/78250da0-7003-0137-7b3f-22aa969a7ad9/status?branch=master)](https://app.codeship.com/projects/347821)
[![Licence](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/Madmous/vscode-makefile-command-runner/blob/master/LICENSE)

> Makefile Command Runner **empowers** the Makefile capabilities built into Visual Studio Code — **Run any command** from the sidebar, **run and watch tests** by right clicking either on a file or folder.

## Settings Options

This extension contributes the following variables to the settings:

- makefilePath: use this setting to set the file path of your Makefile, for example bin/local
- unitTestCommand: use this setting to set the unit test command, for exmample unit-test-all
- integrationTestCommand: use this setting to set the integration test command, for exmample integration-test
- unitTestWatchCommand: use this setting to set the unit test watch command, for exmample unit-test-all-watch
- integrationTestWatchCommand: use this setting to set the integration test watch command, for exmample integration-test-all-watch
- filePathEnv: use this setting to set the file path environment variable used to pass down to node scripts the file path, for example FILE_PATH