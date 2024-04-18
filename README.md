# Quick Javascript Test Workflow
A very simple Javascript Workflow for use by [FW-CLI](https://github.com/TAMULib/fw-cli/), [Mod-Workflow](https://github.com/folio-org/mod-workflow/), and [Mod-Camunda](https://github.com/folio-org/mod-camunda/) in [FOLIO](https://github.com/folio-org/).

All this Workflow does is print the message `Quick Test Complete.` to the system log of the chosen Workflow-Engine, such as [Mod-Camunda](https://github.com/folio-org/mod-camunda/).

## Building and Running
Use the drop this project in the `fw-registry` sub-directory of the [fw-cli](https://github.com/TAMULib/fw-cli/) project directory.

Follow the appropriate install instructions from the [fw-cli](https://github.com/TAMULib/fw-cli/) project to install the `fw` program into the environment in which this is going to be built and run from.

Build this Workflow from the [fw-cli](https://github.com/TAMULib/fw-cli/) project directory:
```shell
fw build quick-js-test
```

If everything worked as expected, then from the same directory activate the Workflow:
```shell
fw activate quick-js-test
```

Once the Workflow is successfully activated, the Workflow can be run at any time from the [fw-cli](https://github.com/TAMULib/fw-cli/) project directory:
```shell
fw run quick-js-test
```
