# Overview

This repository contains the necessary files to launch a Che-Theia workspace with the SmartCLIDE extensions and plugins:

- `devfile.yaml`: provides Che with the information needed to create the workspace
- `editor_meta.yaml`: references the Che-Theia image that includes the desired extensions
- `plugins_meta.yaml`: describes the list of built-in plugins to be provided with the workspace

# How To Use?

The table below matches each release with the included plugins and extensions. To create and open a workspace,
choose a release and click "Run in Che" in the last column of the corresponding row. In case you have not logged in to
Eclipse Che, you will be asked to authenticate.

| Release | Content | Launch |
|---------|---------|--------|
| [v0.0.13](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.13) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li> <li>[smartclide-perftestgen-theia v0.0.2](https://github.com/eclipse-opensmartclide/smartclide-perftestgen-theia/releases/tag/v0.0.2) (KairósDS)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/5c15766424432a2f43dd02f7289b5a77176fe604) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/commit/129b1cfa0d35fbe00aa2f5d7a9afa68c2d827ac5) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/ed144123d3246692548d869834361e589efc738b) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.13) |
| [v0.0.12](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.12) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li> <li>[smartclide-perftestgen-theia v0.0.2](https://github.com/eclipse-opensmartclide/smartclide-perftestgen-theia/releases/tag/v0.0.2) (KairósDS)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/6bec65135cb7f7d4b093f779f9cec567b4e6d4da) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/commit/129b1cfa0d35fbe00aa2f5d7a9afa68c2d827ac5) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/ed144123d3246692548d869834361e589efc738b) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.12) |
| [v0.0.11](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.11) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li> <li>[smartclide-perftestgen-theia v0.0.2](https://github.com/eclipse-opensmartclide/smartclide-perftestgen-theia/releases/tag/v0.0.2) (KairósDS)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/6bec65135cb7f7d4b093f779f9cec567b4e6d4da) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/commit/129b1cfa0d35fbe00aa2f5d7a9afa68c2d827ac5) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/0c872e1250c2ea4c5256188ef44d94b1407dc66c) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.11) |
| [v0.0.10](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.10) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li> <li>[smartclide-perftestgen-theia v0.0.2](https://github.com/eclipse-opensmartclide/smartclide-perftestgen-theia/releases/tag/v0.0.2) (KairósDS)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/a1416494aec8c1fc2c21749ac870042d1b63fe9e) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/releases/tag/v0.0.1) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/0c872e1250c2ea4c5256188ef44d94b1407dc66c) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.10) |
| [v0.0.9](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.9) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li> <li>[smartclide-perftestgen-theia v0.0.2](https://github.com/eclipse-opensmartclide/smartclide-perftestgen-theia/releases/tag/v0.0.2) (KairósDS)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/7417e293d0920580bc853380d2a50c3ee12f3902) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/releases/tag/v0.0.1) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/0c872e1250c2ea4c5256188ef44d94b1407dc66c) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.9) |
| [v0.0.8](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.8) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li> <li>[smartclide-perftestgen-theia v0.0.1](https://github.com/eclipse-opensmartclide/smartclide-perftestgen-theia/releases/tag/v0.0.1) (KairósDS)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/7417e293d0920580bc853380d2a50c3ee12f3902) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/releases/tag/v0.0.1) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/0c872e1250c2ea4c5256188ef44d94b1407dc66c) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.8) |
| [v0.0.7](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.7) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li> <li>[smartclide-perftestgen-theia v0.0.1](https://github.com/eclipse-opensmartclide/smartclide-perftestgen-theia/releases/tag/v0.0.1) (KairósDS)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/7417e293d0920580bc853380d2a50c3ee12f3902) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/releases/tag/v0.0.1) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/dbca3f453cc60fbaee7b891f1e338d12bdf3962b) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.7) |
| [v0.0.6](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.6) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li> <li>[smartclide-perftestgen-theia v0.0.1](https://github.com/eclipse-opensmartclide/smartclide-perftestgen-theia/releases/tag/v0.0.1) (KairósDS)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/7417e293d0920580bc853380d2a50c3ee12f3902) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/commit/13c07399891940b37b21e238870dd3901ca995c8) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/dbca3f453cc60fbaee7b891f1e338d12bdf3962b) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.6) |
| [v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.5) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/7417e293d0920580bc853380d2a50c3ee12f3902) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/commit/13c07399891940b37b21e238870dd3901ca995c8) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/dbca3f453cc60fbaee7b891f1e338d12bdf3962b) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.5) |
| [v0.0.4](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.4) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/2c0d2c0d16392ec61177dbe3fc4e07cfa241f841) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/commit/13c07399891940b37b21e238870dd3901ca995c8) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/dbca3f453cc60fbaee7b891f1e338d12bdf3962b) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.4) |
| [v0.0.3](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.3) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/b740418aa827b2981f4b6297d78cb81d1b5ae76f) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/commit/13c07399891940b37b21e238870dd3901ca995c8) (UoM)</li> <li>[smartclide-design-pattern-selection-theia](https://github.com/eclipse-opensmartclide/smartclide-design-pattern-selection-theia/commit/361b241d1314cb69357f57e413e52bced9c4cbb3) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.3) |
| [v0.0.2](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.2) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/a7d266d604365d505abcdcb2291af5c228e36297) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/commit/33834c27e2bfb3b13fb216a450e1e615322d8635) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.2) |
| [v0.0.1](https://github.com/eclipse-opensmartclide/smartclide-devfiles/releases/tag/v0.0.1) | Plugins: <ul><li>[smartclide-ide-front-end-theme v0.0.5](https://github.com/eclipse-opensmartclide/smartclide-ide-front-end-theme/releases/tag/v0.0.5) (UNP)</li></ul> Extensions: <ul><li>[smartclide-service-creation-theia](https://github.com/eclipse-opensmartclide/smartclide-service-creation-theia/commit/2794f827c95f03e5893ce027ab703fbf0b67213a) (UoM)</li> <li>[smartclide-td-reusability-theia](https://github.com/eclipse-opensmartclide/smartclide-td-reusability-theia/commit/33834c27e2bfb3b13fb216a450e1e615322d8635) (UoM)</li></ul> | [Run in Che](https://che-smartclide-che.che.smartclide.eu/f?url=https://github.com/eclipse-opensmartclide/smartclide-devfiles/tree/v0.0.1) |
