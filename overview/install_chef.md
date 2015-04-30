# Installing Fluentd Using Chef

This article explains how to install Fluentd using Chef.

## Before Installation

Please follow the [Preinstallation Guide](before-install) to configure your OS properly. This will prevent many unnecessary problems.

## Import Recipe

The chef recipe to install td-agent can be found [here](https://github.com/treasure-data/chef-td-agent). Please import the recipe, add it to run_list, and upload it to the Chef Server.

## Run chef-client

Please run chef-client to install td-agent across your machines.
