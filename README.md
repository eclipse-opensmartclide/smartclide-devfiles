# Overview

This repository contains the necessary files to launch a Che-Theia workspace with the SmartCLIDE extensions and plugins:

- `devfile.yaml`: provides Che with the information needed to create the workspace
- `editor_meta.yaml`: references the Che-Theia image that includes the desired extensions
- `plugins.yaml`: describes the list of built-in plugins to be provided with the workspace

# How To Use?

The table below matches each release with the included plugins and extensions. To create and open a workspace,
choose a release and click "Run in Che" in the last column of the corresponding row.

| Release | Content | Launch |
|---------|---------|--------|
| [v0.0.1](https://github.com/eclipse-researchlabs/smartclide-devfiles/releases/tag/v0.0.1) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-researchlabs/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-researchlabs/smartclide-service-creation-theia/commit/2794f827c95f03e5893ce027ab703fbf0b67213a) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-researchlabs/smartclide-td-reusability-theia/commit/33834c27e2bfb3b13fb216a450e1e615322d8635) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-researchlabs/smartclide-devfiles/tree/v0.0.1) |
